---
title: "Gemini CLI 오늘 종료 — 오픈소스의 배신, Antigravity 시대 개막"
date: 2026-06-18
lang: ko
categories: [news]
tags: [gemini-cli, antigravity, copilot, copilot-app, codex-cli, fable-5, kaggle]
excerpt: "Google이 6,000개 이상의 커뮤니티 PR을 받은 오픈소스 Gemini CLI를 오늘 폐쇄하고, 비공개 소스 Antigravity CLI로 전환을 강제했다."
---

오늘 2026년 6월 18일, Gemini CLI가 개인 사용자에게 서비스를 완전히 종료했다. 1년 가까이 Apache 2.0 라이선스로 운영되며 6,000개 이상의 외부 기여 PR을 받은 오픈소스 프로젝트가, 폐쇄형 바이너리 하나로 대체된 것이다.

## Gemini CLI: 오픈소스 신뢰의 종말

오늘부터 `gemini` 명령어가 개인 사용자에게 에러를 반환한다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). CI/CD 파이프라인, 셸 스크립트, cron 작업 등 `gemini` 명령어에 의존하던 모든 자동화가 오늘부터 작동을 멈추며, 유예 기간은 없다([AI Builder Club](https://www.aibuilderclub.com/blog/google-kills-gemini-cli-june-18-2026)). 대체제 Antigravity CLI(`agy`)는 Go 기반 비공개 소스로, 기존 무료 일간 1,000회 호출 대신 주간 컴퓨트 캡을 적용한다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)). Hacker News에서는 "오픈소스로 커뮤니티를 낚고 클로즈드로 전환한 끼워팔기"라는 비판이 쏟아졌다([HN](https://news.ycombinator.com/item?id=48196867)). Gemini Code Assist Standard/Enterprise 기업 고객만 계속 접근 가능하다.

## Copilot App GA: 데스크톱 에이전트의 시대

GitHub Copilot 데스크톱 앱이 macOS, Windows, Linux에서 정식 출시됐다([GitHub Blog](https://github.blog/changelog/2026-06-17-github-copilot-app-generally-available/)). 이슈나 PR에서 직접 에이전트 세션을 시작하고, 여러 저장소에서 병렬로 AI 코딩 세션을 실행할 수 있다. Canvases 기능으로 에이전트와 동일한 계획·PR·터미널·브라우저 세션에서 실시간 협업이 가능하다. 하지만 45주 연속 하락 속에서 과금 반발을 막기엔 역부족이라는 시각이 지배적이다.

## Codex CLI v0.140.0: Claude Code 마이그레이션 도구 탑재

Codex CLI가 v0.140.0 안정판을 출시했다([OpenAI Developers](https://developers.openai.com/codex/changelog)). `/import` 명령어로 Claude Code의 설정·프로젝트 구성·최근 채팅을 선택적으로 마이그레이션할 수 있으며, `/usage`로 일간/주간/누적 토큰 사용량을 확인하고, `codex delete`로 세션을 영구 삭제할 수 있다([Releasebot](https://releasebot.io/updates/openai/codex)). Amazon Bedrock 인증과 MCP OAuth 자격증명 암호화 저장도 추가됐다.

## Fable 5: 정지 6일째, 워싱턴 대면 협상

Claude Fable 5 정지가 6일째에 접어들었다([EisnerAmper](https://www.eisneramper.com/insights/artificial-intelligence-insights/fable-5-suspension-facts-and-timeline-0626/)). Anthropic은 Tom Brown과 Sarah Heck을 워싱턴에 파견해 상무부와 대면 협상을 진행 중이다([explainx.ai](https://explainx.ai/blog/when-will-fable-5-be-available-again-2026)). 복원 시점에 대한 공식 일정은 없으며, Anthropic은 "오해에 기반한 조치"라는 입장을 유지하고 있다. isfable5back.com에서는 여전히 "No"를 표시 중이다([isfable5back](https://isfable5back.com/)).

## Google & Kaggle AI Agents Intensive 4일차

Google과 Kaggle의 무료 5일간 AI 에이전트 집중 과정이 4일차에 들어섰다([Google Blog](https://blog.google/innovation-and-ai/technology/developers-tools/kaggle-genai-intensive-course-vibe-coding-june-2026/)). 자연어 워크플로우를 사용한 프로덕션급 AI 에이전트 구축을 가르치며, 올해는 바이브코딩이 핵심 주제다. 지난 11월 첫 과정에서 150만 명 이상이 수강했다([Kaggle](https://www.kaggle.com/competitions/5-day-ai-agents-intensive-vibecoding-course-with-google)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 안정적 정상 유지 |
| ChatGPT | 96 | — | 10억 MAU 돌파 후 안정 |
| Cursor | 96 | — | Origin 발표 후 플랫폼 전쟁 본격화 |
| Claude AI | 96 | — | Fable 5 정지 6일째 + 집단소송 |
| Codex CLI | 87 | — | v0.140.0 안정판, /import 기능 |
| Windsurf | 85 | — | $15 가격으로 Copilot 이탈 흡수 |
| Antigravity | 76 | ↑2 | Gemini CLI 종료일, 마이그레이션 대거 유입 |
| Aider | 68 | — | 오픈소스 코딩 에이전트 정체기 |
| Gemini CLI | 55 | ↓3 | 오늘 종료, 기업 전용 전환 완료 |
| Copilot | 38 | ↓1 | 45주 연속 하락, App GA 효과 불투명 |

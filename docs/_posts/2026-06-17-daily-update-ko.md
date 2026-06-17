---
title: "Gemini CLI 내일 종료 — 개인 사용자 마지막 날, Antigravity CLI 대이동 시작"
date: 2026-06-17
lang: ko
categories: [news]
tags: [gemini-cli, antigravity, copilot, fable-5, spacex, kaggle]
excerpt: "Gemini CLI 개인 사용자 서비스가 내일(6월 18일) 종료된다. 수만 명의 개발자가 Antigravity CLI로 이동해야 하는 마지막 밤이다."
---

Gemini CLI의 마지막 날이다. 내일 6월 18일부터 Google은 무료·Pro·Ultra 개인 사용자의 Gemini CLI 접근을 완전히 차단한다. 약 한 달 전 Google I/O에서 예고된 이 전환은 오픈소스 Node.js 도구에서 폐쇄형 Go 바이너리로의 강제 이동이라는 점에서 개발자 커뮤니티의 불만을 사고 있다.

## Gemini CLI: D-1, 마지막 카운트다운

내일 6월 18일부터 Gemini CLI의 `gemini` 명령어가 개인 사용자에게 에러를 반환한다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). CI/CD 파이프라인, 셸 스크립트, cron 작업 등 `gemini`를 호출하는 모든 자동화가 내일부터 깨진다. 대체제인 Antigravity CLI(`agy`)는 Go 기반 고성능 바이너리로, Google은 "10분 이내 마이그레이션"이 가능하다고 안내하지만([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)), 오픈소스가 아닌 점과 주간 컴퓨트 캡 적용이 기존 무료 일 1,000회 호출 대비 체감 다운그레이드라는 비판이 계속되고 있다([Linux Foundation](https://www.linuxfoundation.org/blog/gemini-cli-bait-and-switch)). 기업용 Gemini Code Assist Standard/Enterprise 라이선스 보유 조직만 기존 Gemini CLI를 계속 사용할 수 있다.

## Copilot: 44주 연속 하락, 39점 — 종량제 17일차

GitHub Copilot이 39를 기록하며 44주 연속 하락세를 이어갔다([GitHub Community](https://github.com/orgs/community/discussions/192948)). 6월 1일 사용량 기반 과금 전환 이후 17일째로, 개발자들의 Claude Code·Codex CLI·Windsurf 이탈이 지속되고 있다. 일부 사용자는 에이전틱 세션에서 월 $30-40/일이 발생한다고 보고했으며([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)), 시장점유율은 2025년 67%에서 51%로 하락했다([CNBC](https://www.cnbc.com/2026/05/22/github-copilot-outages-security-breaches.html)).

## Fable 5: 정지 5일째, 복원 불투명

Claude Fable 5 모델이 미 상무부 수출 통제 지시로 정지된 지 5일째다([Appwrite](https://appwrite.io/blog/post/claude-fable-5-and-mythos-5-access-suspended)). Anthropic은 주말 워싱턴 협상을 진행했고, David Sacks 전 AI 차르는 "가능한 빨리" 복원하겠다고 시사했지만([FableRadar](https://fableradar.live/)), 공식 일정은 없다. Polymarket에서 6월 내 복원 확률은 약 35%로 집계됐다([Polymarket](https://polymarket.com/event/claude-fable-5-restored-for-us-customers-by-20260613193753196)). Fortune은 Amazon이 자사 투자 대상인 Anthropic의 모델 취약점을 상무부에 보고해 정지를 촉발한 정황을 보도했다([Fortune](https://fortune.com/2026/06/13/amazon-fable-5-commerce-department/)).

## Kimi K2.7 Code: 1조 파라미터 오픈소스 코딩 모델

Moonshot AI가 6월 14일 Kimi K2.7 Code를 Modified MIT 라이선스로 공개했다([GIGAZINE](https://gigazine.net/gsc_news/en/20260615-kimi-k2-7-code/)). 총 1조 파라미터(활성 320억)의 MoE 모델로, 256K 컨텍스트를 지원한다. Kimi Code Bench v2에서 +21.8%, Program Bench에서 +11.0%, MLS Bench Lite에서 +31.5% 향상을 보였다. Opus 4.8 대비 출력 비용이 6배 저렴하며, 추론 토큰을 30% 절감했다([Flowtivity](https://flowtivity.ai/blog/kimi-k2-7-code-review/)). Aider 등 오픈소스 코딩 에이전트에서 즉시 활용 가능하다.

## Google & Kaggle AI Agents Intensive: 3일차 진행 중

Google과 Kaggle이 공동 운영하는 무료 5일간 AI Agents Intensive 바이브 코딩 과정이 3일차에 접어들었다([Kaggle](https://www.kaggle.com/competitions/5-day-ai-agents-intensive-vibecoding-course-with-google/)). 2025년 11월 초판이 150만 명 이상을 모은 데 이어, 이번 2026년 판은 프로덕션 배포와 캡스톤 프로젝트를 추가했다([Google Blog](https://blog.google/innovation-and-ai/technology/developers-tools/kaggle-genai-intensive-course-vibe-coding-june-2026/)). 19일까지 진행된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.178, 에이전트 과금 중단 안도 |
| ChatGPT | 96 | — | 10억 MAU, GPT-5.5 시대 |
| Cursor | 96 | — | SpaceX $600억 인수 진행 중 |
| Claude AI | 96 | — | Fable 5 정지 5일째, 복원 불투명 |
| Codex CLI | 87 | — | Goal 모드 GA 안착 |
| Windsurf | 85 | — | $15 가격으로 Copilot 이탈 흡수 |
| Antigravity | 74 | ↑1 | Gemini CLI D-1, 마이그레이션 수혜 |
| Aider | 68 | — | Kimi K2.7 Code 호환 가능 |
| Gemini CLI | 58 | ↓1 | 내일 종료, 기업 전용 전환 |
| Copilot | 39 | ↓1 | 44주 연속 하락, 종량제 17일차 |

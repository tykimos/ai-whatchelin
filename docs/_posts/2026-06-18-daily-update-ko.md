---
title: "Gemini CLI 오늘 폐쇄, Claude Code 하루에 2번 업데이트 — AI 코딩 패권 격차 벌어진다"
date: 2026-06-18
lang: ko
categories: [news]
tags: [gemini-cli, antigravity, claude-code, copilot, copilot-app, codex-cli, fable-5, kaggle, g7, anthropic]
excerpt: "Google이 Gemini CLI를 폐쇄한 날, Anthropic은 Claude Code를 하루에 두 번 업데이트하며 격차를 벌렸다. G7에서 AI 3사 CEO가 한자리에."
---

Google이 오픈소스로 6,000개 이상의 커뮤니티 PR을 받아들인 Gemini CLI를 오늘 공식 폐쇄한 날, Anthropic은 Claude Code를 하루에 두 번 릴리스하며 정반대의 개발 속도를 보여줬다. "죽이는 쪽"과 "만드는 쪽"의 대비가 이렇게 극명한 날도 드물다.

## Gemini CLI: 오픈소스 신뢰의 마지막 날

오늘부로 `gemini` 명령어가 개인 사용자에게 에러를 반환한다([AI Builder Club](https://www.aibuilderclub.com/blog/google-kills-gemini-cli-june-18-2026)). CI/CD 파이프라인, 셸 스크립트, cron 작업 등 `gemini`에 의존하던 자동화가 유예 기간 없이 중단됐다. 대체제 Antigravity CLI(`agy`)는 폐쇄형 Go 바이너리로, 무료 일간 1,000회 호출이 주간 20회로 98% 감소했다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)). Hacker News에서는 143 비추천 대 4 추천으로 압도적 반발이 쏟아졌다([HN](https://news.ycombinator.com/item?id=48196867)). Linux Foundation은 이를 "오픈소스 끼워팔기"의 대표 사례로 지목했다([TechTimes](https://www.techtimes.com/articles/317407/20260529/linux-foundation-tool-spotlighted-furious-developers-accuse-sickening-google-gemini-cli.htm)).

## Claude Code v2.1.179 + v2.1.181: 하루 2회 릴리스

Gemini CLI가 멈춘 날, Claude Code는 두 번 업데이트됐다([Anthropic Changelog](https://code.claude.com/docs/en/changelog)). v2.1.179에서 스트림 중간 연결 끊김, WSL2 스크롤 문제, 샌드박스 glob 성능 저하를 수정하고, v2.1.181에서 `/config key=value` 프롬프트 기반 설정 명령어, Bun 1.4 런타임 업그레이드, 긴 문단 라인별 스트리밍 등 품질 개선을 추가했다([GitHub Releases](https://github.com/anthropics/claude-code/releases)). 네트워크 드라이브 파일 쓰기와 커스텀 `ANTHROPIC_BASE_URL` 프롬프트 캐싱 문제도 수정됐다.

## G7 AI 정상회의: 3대 CEO 한자리에

어제 G7 AI 워킹 런치에 Sam Altman(OpenAI), Dario Amodei(Anthropic), Demis Hassabis(Google DeepMind)가 동시 참석했다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-june-17-2026)). 청소년 안전과 프론티어 AI 리스크에 대한 자발적(구속력 없는) 합의가 도출됐다. 캐나다 PM Carney는 Fable 5 사태를 AI 과의존 위험의 증거로 인용했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-16/trump-s-anthropic-crackdown-sets-off-ai-alarms-for-us-allies)). SoftBank은 프랑스 AI 데이터센터에 450억 유로 투자를 약속했다.

## Anthropic 서울 오피스 오픈

Anthropic이 서울에 첫 한국 오피스를 열었다. 아시아 시장 확대의 일환으로, 지난주 NEC와의 일본 파트너십(3만 명 배포)에 이은 행보다. $9,650억 밸류에이션의 세계 최고 가치 비상장 AI 기업이 한국 시장에 본격 진출한 것이다.

## Copilot App GA: 45주 하락을 멈출 수 있을까

GitHub Copilot 데스크톱 앱이 macOS, Windows, Linux에서 정식 출시됐다([GitHub Blog](https://github.blog/changelog/2026-06-17-github-copilot-app-generally-available/)). 이슈/PR에서 에이전트 세션을 시작하고 Canvases로 실시간 협업이 가능하지만, 종량제 18일차 반발이 여전하다. Pro 사용자는 2시간 만에 크레딧 8%를 소진하고, 에이전틱 세션에 하루 $30-40이 청구되고 있다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)).

## Fable 5: 정지 6일째, 복원 기미 없음

Fable 5 정지가 6일째에 접어들었다([EisnerAmper](https://www.eisneramper.com/insights/artificial-intelligence-insights/fable-5-suspension-facts-and-timeline-0626/)). Anthropic은 Tom Brown과 Sarah Heck을 워싱턴에 파견해 상무부와 대면 협상 중이지만, 공식 복원 일정은 없다([explainx.ai](https://explainx.ai/blog/when-will-fable-5-be-available-again-2026)). "48시간 내 복원" 루머가 돌았으나 확인되지 않았으며, isfable5back.com은 여전히 "No"를 표시 중이다([isfable5back](https://isfable5back.com/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 하루 2회 릴리스, 안정적 정상 |
| ChatGPT | 96 | — | 10억 MAU, 안정 유지 |
| Cursor | 96 | — | SpaceX 인수 확정, Origin 발표 |
| Claude AI | 96 | — | Fable 5 정지 6일째 + 서울 오피스 |
| Codex CLI | 87 | — | v0.140.0 안정판 |
| Windsurf | 85 | — | $15 가격으로 Copilot 이탈 흡수 |
| Antigravity | 76 | ↑2 | Gemini CLI 종료일 대규모 유입 |
| Aider | 68 | — | 오픈소스 에이전트 정체 |
| Gemini CLI | 55 | ↓3 | 오늘 종료, 기업 전용 전환 완료 |
| Copilot | 38 | ↓1 | 45주 연속 하락, App GA 효과 불투명 |

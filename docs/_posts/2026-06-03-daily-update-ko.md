---
title: "Build 2일차: Microsoft가 온디바이스 AI 모델을 꺼내들었다 — Copilot 이탈은 3일째 가속"
date: 2026-06-03
lang: ko
categories: [news]
tags: [microsoft-build, github-copilot, claude-code, windsurf, nvidia, gemini-cli, spacex]
excerpt: "Microsoft Build 2026 2일차에서 Aion 1.0 SLM과 MAI 모델 7종을 공개하며 온디바이스 AI 전략을 선보였다. 한편 Copilot 종량제 3일째, 개발자 이탈이 현실로 나타나고 있다."
---

Microsoft Build 2026이 2일차에 접어들며 하드웨어와 모델 양쪽에서 큰 발표가 쏟아졌다. 그러나 개발자들의 관심은 여전히 Copilot 종량제 과금 3일째의 청구서에 쏠려 있다. Windsurf가 Pro 요금을 $15로 인하하며 이탈 수요를 정조준하고 있다.

## Microsoft Build Day 2: 온디바이스 AI의 시대 선언

Microsoft가 Aion 1.0을 공개했다 — Windows에 기본 탑재되는 온디바이스 SLM 2종이다([NewsBytesApp](https://www.newsbytesapp.com/news/science/2-microsoft-aion-1-0-ai-models-revealed-at-build-2026/story)). Aion 1.0 Instruct는 경량 추론 모델이고, Aion 1.0 Plan은 14B 파라미터에 32K 컨텍스트를 지원하는 에이전틱 모델로 완전 로컬에서 도구 호출과 계획 수립이 가능하다. MAI 모델 7종도 함께 발표됐으며, MAI-Thinking-1(추론 특화)과 MAI-Code-1(GitHub/VS Code 특화)이 핵심이다([Tom's Guide](https://www.tomsguide.com/news/live/microsoft-build-2026)).

하드웨어 측에서는 Surface RTX Spark Dev Box가 공개됐다. NVIDIA RTX Spark 실리콘 기반으로 1페타플롭의 AI 연산과 128GB 통합 메모리를 갖추고, 120B 파라미터 모델을 로컬에서 구동할 수 있다([Visual Studio Blog](https://devblogs.microsoft.com/visualstudio/whats-coming-next-in-visual-studio-our-microsoft-build-2026-announcements/)).

## Copilot 종량제 3일차: 이탈이 현실이 되다

Copilot 사용량 기반 과금 3일째, 더 많은 개발자들이 실비용을 공유하며 충격이 확산되고 있다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Pro+($39/월) 사용자가 2시간 만에 월 크레딧의 ~8%를 소진했다는 보고, 단일 코드 변경에 $6 이상이 청구된 사례 등이 Reddit과 GitHub Discussions에서 공유되고 있다([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). Copilot 인기도는 30주 연속 하락해 53을 기록 — 추적 시작 이래 최저치를 또 경신했다.

인기 있는 우회 전략은 Copilot 크레딧을 먼저 소진한 뒤 OpenRouter(VS Code 동일 인터페이스, 크레딧 1년 이월)로 전환하는 하이브리드 방식이다([findskill.ai](https://findskill.ai/blog/github-copilot-too-expensive-alternatives-2026/)).

## Windsurf Pro $15 가격 인하 — Cursor 언더커팅

Cognition이 Windsurf Pro를 월 $20에서 $15로 인하했다([NxCode](https://www.nxcode.io/resources/news/cognition-windsurf-acquisition-swe-1-5-codemaps-2026)). Cursor Pro $20, Claude Code $20보다 저렴해진 것이다. SWE-1.5(Claude Sonnet 4.5 대비 13배 빠르다고 주장), 기본 내장된 Devin, 그리고 새로운 Codemaps 기능과 합쳐져 Copilot 이탈 수요를 직접 흡수하려는 전략이 명확하다.

## Claude 장애 원인 규명 — 서브에이전트 무한 루프

6월 2일 발생한 Claude 글로벌 장애의 원인이 밝혀졌다([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/claude-celebrates-anthropics-stock-market-float-with-blockbuster-outage/5250071)). Claude Code의 서브에이전트 시스템에서 에이전트가 기하급수적으로 증식하는 무한 루프 버그가 발생해 대량의 토큰을 소모했다. Pro·Max 구독자 다수가 수 분 만에 쿼터를 전부 소진했으며, Anthropic이 긴급 쿼터 리셋을 실시했다([The National](https://www.thenationalnews.com/future/technology/2026/06/02/anthropics-claude-hit-by-major-global-outage-due-to-unexpected-capacity-constraints/)). S-1 IPO 제출 직후 발생한 장애라 타이밍이 좋지 않았다.

## Gemini CLI 종료 D-15 — 마이그레이션 필수

Gemini CLI 서비스 종료까지 15일 남았다([AI Builder Club](https://www.aibuilderclub.com/blog/google-kills-gemini-cli-june-18-2026)). 6월 18일 이후 모든 비엔터프라이즈 요청은 HTTP 410(Gone)으로 응답된다. Antigravity CLI로의 전환 방법: `agy plugin import gemini`으로 확장 가져오기, `GEMINI.md`를 `AGENTS.md`로 리네임, `.gemini/skills/`를 `.agents/skills/`로 이동([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)).

## SpaceX IPO 로드쇼 D-1

SpaceX IPO 로드쇼가 내일(6월 4일) 시작된다([CNBC](https://www.cnbc.com/2026/05/20/spacex-ipo-live-updates.html)). $1.75조 목표 밸류에이션, $750억 조달 예정이며, 6월 11일 가격 확정, 6월 12일 나스닥(SPCX) 거래 개시다. S-1에서 Anthropic이 월 $12.5억의 Colossus 컴퓨트 비용을 지불하고 있음이 공개된 바 있다([InsiderFinance](https://www.insiderfinance.io/news/spacex-ipo-prospectus-nears-ahead-of-june-roadshow)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 안정적 1위, 장애 복구 완료 |
| ChatGPT | 96 | — | Build 영향 관망 |
| Cursor | 96 | — | Teams 개편 후 안정 |
| Claude AI | 95 | — | 장애 원인 규명, 쿼터 리셋 |
| Codex CLI | 87 | — | GPT-5.5 Bedrock GA |
| Windsurf | 82 | ↑1 | Pro $15 인하, Copilot 이탈 수요 흡수 |
| Gemini CLI | 72 | ↓1 | 종료 D-15, HTTP 410 카운트다운 |
| Aider | 68 | — | 오픈소스 안정세 |
| Antigravity | 63 | ↑1 | 롤백 위기 후 회복 9주차 |
| GH Copilot | 53 | ↓1 | 30주 연속 하락, 종량제 이탈 가속 |

Build 2일차의 온디바이스 AI 전략은 장기적으로 의미가 크지만, 오늘 개발자들이 체감하는 것은 Copilot 청구서다. Windsurf $15 인하가 이 타이밍에 나온 것은 우연이 아니다.

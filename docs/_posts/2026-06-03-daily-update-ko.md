---
title: "Build 2일차: Microsoft가 자체 코딩 모델을 꺼내들었다 — Copilot 이탈 3일째, Windsurf $15 역습"
date: 2026-06-03
lang: ko
categories: [news]
tags: [microsoft-build, github-copilot, claude-code, windsurf, nvidia, gemini-cli, spacex, codex-cli]
excerpt: "Microsoft Build 2026 2일차에서 MAI-Code-1-Flash와 Project Solara를 공개하며 OpenAI 의존도 탈피를 선언했다. Copilot 종량제 3일째 이탈은 가속화되고, Windsurf는 $15 가격 인하로 이탈 수요를 정조준하고 있다."
---

Microsoft Build 2026이 2일차에 접어들며 가장 중대한 발표가 나왔다 — Microsoft가 OpenAI 없이 자체 코딩 모델을 만들기 시작했다. 한편 Copilot 종량제 3일째, 개발자 이탈은 가속화되고 있으며 Windsurf가 Pro 요금을 $15로 낮추며 정면 승부에 나섰다.

## MAI-Code-1-Flash: Microsoft가 직접 만든 5B 코딩 모델

Microsoft Build 2일차의 핵심 발표는 **MAI-Code-1-Flash**다 — Microsoft가 프로덕션 Copilot 하네스와 라이선스 데이터로 처음부터 끝까지 자체 훈련한 5B 파라미터 코딩 모델이다([Microsoft AI](https://microsoft.ai/news/introducingmai-code-1-flash/)). OpenAI의 관여 없이 만들어진 이 모델은 적응형 사고(adaptive thinking)로 코딩 작업에서 토큰 60%를 절감하면서도 Claude Haiku 4.5를 벤치마크에서 능가한다([CNBC](https://www.cnbc.com/2026/06/02/microsoft-unveils-new-ai-models-lessen-reliance-on-openai-lower-costs.html)). VS Code 모델 피커에서 전 Copilot 플랜에 즉시 배포 중이다.

함께 발표된 MAI-Thinking-1은 중형 추론 모델이고, Aion 1.0은 Windows에 기본 탑재되는 온디바이스 SLM 2종(Instruct + 14B Plan)이다([Tom's Guide](https://www.tomsguide.com/news/live/microsoft-build-2026)). Surface RTX Spark Dev Box는 1페타플롭의 AI 연산과 128GB 통합 메모리로 120B 파라미터 모델을 로컬에서 구동한다([Visual Studio Blog](https://devblogs.microsoft.com/visualstudio/whats-coming-next-in-visual-studio-our-microsoft-build-2026-announcements/)).

## Project Solara: 앱에서 에이전트로의 전환

Microsoft가 Project Solara를 공개했다 — Android 기반 칩-투-클라우드 에이전트 퍼스트 디바이스 플랫폼이다([Engadget](https://www.engadget.com/2185941/microsoft-announces-project-solara-its-take-on-an-ai-agent-platform/)). 앱을 열지 않고 에이전트를 호출하는 "just-in-time UI" 개념이 핵심으로, 스마트 배지(5G/카메라/터치스크린)와 스마트 디스플레이 컨셉 하드웨어를 선보였다. Best Buy, CVS Health, Levi's, Target 등이 파일럿에 참여한다([TechRadar](https://www.techradar.com/pro/is-this-the-next-computer-microsofts-project-solara-looks-to-break-ai-out-of-the-pc-and-into-the-real-world)).

## Copilot 종량제 3일차: 이탈이 현실이 되다

종량제 전환 3일째, 더 많은 개발자들이 실비용을 공유하며 충격이 확산되고 있다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Pro+($39/월) 사용자가 2시간 만에 월 크레딧의 ~8%를 소진했고, 단일 코드 변경에 $6 이상이 청구된 사례도 나왔다([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). Reddit과 GitHub Discussions에서는 월 비용이 $29에서 $750, $50에서 $3,000까지 뛴다는 추산이 공유되고 있다. Copilot 인기도는 **30주 연속 하락해 53** — 추적 시작 이래 최저치를 또 경신했다.

## Windsurf Pro $15 — Cursor 언더커팅

Cognition이 Windsurf Pro를 월 $20에서 $15로 인하했다([Windsurf Blog](https://windsurf.com/blog/pricing-v2)). Cursor Pro $20, Claude Code $20보다 저렴해진 것이다. SWE-1.5(Claude Sonnet 4.5 대비 13배 빠르다고 주장), 기본 내장된 Devin, 새로운 Codemaps 기능과 합쳐져 Copilot 이탈 수요를 직접 흡수하려는 전략이 명확하다.

## Codex CLI v0.137.0 — Windows Computer Use 지원

Codex CLI가 v0.137.0-alpha.4를 출시하며 Windows Computer Use를 지원한다([OpenAI Codex Changelog](https://developers.openai.com/codex/changelog)). Codex가 이제 Windows 데스크톱 앱을 보고, 클릭하고, 타이핑할 수 있다. TUI에서 /archive로 세션 보관이 가능해졌고, ChatGPT iOS/Android에서 Windows 디바이스를 원격 제어할 수 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 안정적 1위, 장애 복구 완료 |
| ChatGPT | 96 | — | Build 영향 관망 |
| Cursor | 96 | — | Teams 개편 후 안정 |
| Claude AI | 95 | — | 장애 원인 규명, 쿼터 리셋 |
| Codex CLI | 87 | — | v0.137.0, Windows Computer Use |
| Windsurf | 82 | ↑1 | Pro $15 인하, Copilot 이탈 수요 흡수 |
| Gemini CLI | 72 | ↓1 | 종료 D-15, HTTP 410 카운트다운 |
| Aider | 68 | — | 오픈소스 안정세 |
| Antigravity | 63 | ↑1 | 롤백 위기 후 회복 9주차 |
| GH Copilot | 53 | ↓1 | 30주 연속 하락, 종량제 이탈 가속 |

Build 2일차 가장 중요한 메시지는 Microsoft가 OpenAI 없이 자체 코딩 모델을 만들기 시작했다는 것이다. MAI-Code-1-Flash가 Claude Haiku 4.5를 능가한다면, Copilot의 가격 논란도 "더 싼 모델로 충분하다"는 방향으로 전환될 수 있다.

---
title: "GPT-5.6 유출, Project Polaris 공개 임박 — Build 2026 전야의 AI 코딩 대전"
date: 2026-05-30
lang: ko
categories: [news]
tags: [openai, microsoft-build, copilot, claude, anthropic, mozilla, deepswe]
excerpt: "Codex 배포 로그에서 GPT-5.6 'iris-alpha'가 유출되고, Microsoft의 자체 코딩 모델 Project Polaris가 Build 2026 D-2에 앞서 드러났다. Copilot은 26주 연속 하락으로 57까지 떨어지며, DeepSWE 벤치마크는 SWE-Bench의 검증기 오류율 32%를 폭로했다."
---

Codex 배포 로그에서 'gpt-5.6' 문자열이 발견됐다 — 코드명 'iris-alpha', 1.5M 토큰 컨텍스트 윈도를 탑재한 것으로 추정되며 예측시장에서 6월 30일까지 공개 확률이 80-89%로 거래되고 있다([ChatForest](https://chatforest.com/reviews/openai-gpt-5-6-canary-leak-release-date-prediction-markets-2026/)). Build 2026 개막을 이틀 앞둔 시점에 Microsoft와 OpenAI 모두 차세대 카드를 내밀고 있는 형국이다.

## Microsoft Build D-2: Project Polaris 유출

Microsoft의 자체 코딩 모델 'Project Polaris'가 Build 2026 전에 유출됐다([Windows News](https://windowsnews.ai/article/microsoft-build-2026-homegrown-ai-models-to-power-github-copilot.420887)). MoE(Mixture-of-Experts) 아키텍처 기반으로 HumanEval과 MBPP에서 GPT-4 Turbo를 능가하며, 8월 GA 예정이다. IP 소송을 보상하는 'Code Content Guarantee'가 포함된다는 점이 엔터프라이즈 시장을 겨냥한 핵심 차별화다. Mustafa Suleyman 팀이 4월 OpenAI 훈련 제한에서 해방된 후 첫 결과물이다([The Information](https://www.theinformation.com/newsletters/ai-agenda/microsoft-release-new-coding-model-next-week-comeback-attempt)).

## Copilot: 26주 연속 하락, 사용량 과금 D-2

Copilot 인기도가 57까지 추락하며 역대 최저치를 다시 경신했다([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)). 6월 1일 사용량 기반 과금 전환까지 단 2일 — Pro는 $10, Pro+는 $39, Business는 $19/사용자, Enterprise는 $39/사용자의 AI 크레딧을 받는다. 코드 완성은 무료 유지되지만, 에이전트와 채팅은 크레딧을 소모한다. 26주 연속 하락의 바닥이 어디인지, Build 2026의 Project Polaris가 반전을 만들 수 있을지가 관건이다.

## DeepSWE: SWE-Bench 신뢰성에 근본적 의문

Datacurve가 오염 없는 113개 작업으로 구성된 DeepSWE 벤치마크를 발표했다([VentureBeat](https://venturebeat.com/technology/deepswe-blows-up-the-ai-coding-leaderboard-crowns-gpt-5-5-and-finds-claude-opus-exploiting-a-benchmark-loophole)). GPT-5.5가 70% 해결률로 1위를 차지하고 Claude Opus는 54%에 그쳤다. 더 충격적인 건 SWE-Bench Pro의 검증기 오류율이 ~32%로 밝혀진 것이다 — 기존 벤치마크 순위의 신뢰성 자체에 의문이 제기되는 대목이다.

## Mozilla: Claude Mythos로 Firefox 보안 10배 개선

Mozilla가 Claude Mythos Preview를 활용해 Firefox 취약점 271건을 수정했다 — 이전 Claude 모델 대비 10배 개선이다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-may-30-2026)). 수백만 줄의 레거시 코드에 대한 대규모 보안 스캐닝에서 에이전틱 AI의 실용적 가치를 입증한 사례다.

## TechCrunch: AI 없이 일하기를 거부하는 개발자들

METR 연구에 따르면 대부분의 개발자가 AI 없이는 작업을 거부하고 있어 역량 위축과 의존성에 대한 우려가 커지고 있다([TechCrunch](https://techcrunch.com/2026/05/29/coders-are-refusing-to-work-without-ai-and-that-could-come-back-to-bite-them/)). AI 어시스턴트 없이 코딩하는 것이 '팔을 잃는 것 같다'는 반응이 나오는 시점에서, 지난주 HN 1위를 기록한 "AI로 더 느리게 더 나은 코드 작성" 논의와 맞물려 AI 코딩 도구의 방향성에 대한 담론이 심화되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 + $965B, Mythos 임박 |
| ChatGPT | 96 | ↓1 | 장애 여파 지속, GPT-5.6 유출 |
| Cursor | 96 | — | Build 대기, xAI Colossus 2 |
| Claude AI | 95 | — | IPO 10월 목표, Big Four 표준화 |
| Codex CLI | 88 | — | GPT-5.6 기대감, Goal 모드 GA |
| Windsurf | 81 | — | Devin 통합 안정화 |
| Gemini CLI | 76 | ↓1 | 종료 D-19, 이탈 가속 |
| Antigravity | 59 | ↑1 | v2.0.0 패치 후 완만한 회복 |
| Aider | 68 | — | 오픈소스 기반 안정 |
| GH Copilot | 57 | ↓1 | 26주 최저, 과금 D-2 |

Build 2026 개막 이틀 전, GPT-5.6 유출과 Project Polaris 등 차세대 모델 떡밥이 쏟아지고 있다. 그러나 DeepSWE가 폭로한 벤치마크 신뢰성 문제는 — 점수 경쟁 자체의 의미를 다시 생각하게 만든다.

---

*출처: 각 문장에 인라인 표기*

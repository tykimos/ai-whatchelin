---
title: "SpaceX $1.75조 IPO 로드쇼 시작 — 월가 '적정가의 2배' 경고, Copilot 이탈 4일차"
date: 2026-06-04
lang: ko
categories: [news]
tags: [spacex-ipo, github-copilot, anthropic, claude-code, grok-build, gemini-cli, microsoft-build]
excerpt: "SpaceX가 역대 최대 $750억 IPO 로드쇼를 시작했지만 Morningstar는 적정가의 2배라 경고한다. Copilot 종량제 4일차 이탈이 가속되는 가운데, Anthropic의 6월 15일 에이전트 과금 전환까지 11일 남았다."
---

SpaceX가 역대 최대 규모의 IPO 로드쇼를 시작했다. 그러나 월가의 시선은 갈린다 — Morningstar는 적정가의 절반도 안 된다고 경고하고, ARK Invest는 오히려 저평가라 주장한다. AI 코딩 도구 시장에서는 Copilot 이탈 4일차, Anthropic 에이전트 과금 카운트다운, 그리고 Build 여파가 동시에 작동하고 있다.

## SpaceX IPO 로드쇼: $1.75조 vs Morningstar $780B

SpaceX IPO 로드쇼가 공식 시작됐다. 주당 $135, 5억 5,560만 주, ~$750억 조달 목표 — 역대 최대 IPO다([CNBC](https://www.cnbc.com/2026/06/03/spacex-ipo-stock-price-roadshow-musk.html)). $1.75조 밸류에이션은 Tesla(~$1.6조)를 넘어 미국 시가총액 7위에 해당한다. 그러나 Morningstar는 적정가를 $780B로 산정해 목표의 절반도 안 된다며 장기 투자자에게 상장 후 진입을 권유했다([TechTimes](https://www.techtimes.com/articles/317676/20260603/spacex-ipo-roadshow-begins-morningstar-calls-175t-valuation-nearly-twice-fair-value.htm)). 반면 ARK Invest의 Cathie Wood는 Starlink·Starship·Orbital AI 합산 시 2030년 $2.5조도 가능하다며 "현실적 궤도"라 평가했다.

AI 업계와의 연결고리는 명확하다. S-1에서 공개된 Anthropic의 월 $12.5억 Colossus 계약(총 $450억)이 SpaceX 매출의 상당 부분을 차지하며, AI 인프라 시장의 규모를 보여준다.

## Copilot 종량제 4일차: "분노한 개발자들이 이탈을 선언"

The Register가 "분노한 개발자들이 Copilot을 떠나겠다고 선언"이라는 제목의 기사를 내보냈다([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). 종량제 4일째, 실비용 데이터가 쌓이면서 상황은 악화되고 있다. Reddit에서 한 사용자는 월 $29에서 $750으로 뛸 것이라 추산했고, 또 다른 사용자는 단일 코드 변경에 $6 이상이 청구됐다고 보고했다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Copilot 인기도는 **31주 연속 하락해 52**를 기록했다.

이탈 대상은 주로 Claude Code, Codex CLI, 그리고 OpenRouter/RooCode/LM Studio 같은 서드파티 라우팅 서비스다.

## Anthropic 에이전트 과금 D-11: 6월 15일 청구 분리

Anthropic이 6월 15일부터 Claude Agent SDK, claude -p, Claude Code GitHub Actions, 서드파티 에이전트를 구독 한도에서 분리해 별도 월간 크레딧으로 전환한다([Codersera](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/)). Pro $20, Max 5x $100, Max 20x $200 크레딧이 배정되며 API 정가 기준으로 차감, 이월은 안 된다([DevToolPicks](https://devtoolpicks.com/blog/anthropic-splits-claude-subscriptions-agent-sdk-credit-june-2026)). 11일 앞으로 다가온 이 변경은 헤비 유저에게 영향을 줄 수 있어 사전 점검이 필요하다.

## Build 후폭풍: Microsoft의 OpenAI 탈피 전략 해석

CNBC는 "Microsoft가 자체 모델로 OpenAI 의존도를 줄인다"라는 분석 기사를 실었다([CNBC](https://www.cnbc.com/2026/06/01/microsoft-and-google-take-on-anthropic-and-openai-in-ai-coding-models.html)). MAI-Code-1-Flash가 Claude Haiku 4.5를 능가하고 Project Polaris가 8월 GPT-4 Turbo를 대체하면, Microsoft-OpenAI 관계의 역학이 근본적으로 바뀐다. Mordor Intelligence는 AI 코딩 도구 시장이 2026년 $93억에서 2031년 $300억으로 연 26% 성장할 것으로 전망했다.

## xAI Grok Composer 2.5 출시

xAI가 Grok Composer 2.5를 발표했다 — 장시간 작업과 복잡한 명령 수행에 특화된 새 모델이다([Releasebot](https://releasebot.io/updates/xai)). 입력 토큰 $0.50/M, 출력 $2.50/M으로 Grok Build 0.1 대비 입력 비용이 약 100% 저렴하다. 빠른 변형은 $3.00/$15.00/M이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 안정적 1위, v2.1.161 안정성 수정 |
| ChatGPT | 96 | — | Build 후폭풍 관망 |
| Cursor | 96 | — | SpaceX 인수 IPO 후 본격화 예상 |
| Claude AI | 95 | — | 6/2 장애 완전 복구 |
| Codex CLI | 87 | — | v0.137.0 Windows Computer Use |
| Windsurf | 83 | ↑1 | $15 인하 효과 + Copilot 이탈 흡수 |
| Gemini CLI | 71 | ↓1 | 종료 D-14, 기업 고객만 유지 |
| Aider | 68 | — | 오픈소스 안정세 |
| Antigravity | 64 | ↑1 | 롤백 위기 후 회복 10주차 |
| GH Copilot | 52 | ↓1 | 31주 연속 하락, 종량제 이탈 본격화 |

SpaceX IPO는 단순한 주식 시장 이벤트가 아니다. S-1이 공개한 Anthropic의 월 $12.5억 컴퓨팅 계약은 AI 코딩 도구의 성장이 어디에서 오는지를 보여준다 — 이 규모의 인프라 투자가 Claude Code의 가격과 성능을 지탱하고 있다.

---
title: "Windsurf가 Devin Desktop으로 — SpaceX $1.75조 IPO 로드쇼 첫날, Copilot 이탈 4일차"
date: 2026-06-04
lang: ko
categories: [news]
tags: [windsurf, devin-desktop, spacex-ipo, github-copilot, anthropic, claude-code, uber, cursor, grok-build]
excerpt: "Windsurf가 Devin Desktop으로 리브랜딩됐고, SpaceX는 역대 최대 IPO 로드쇼를 시작했다. Copilot 종량제 이탈이 4일차에 접어든 가운데 Uber는 AI 도구에 월 $1,500 상한을 걸었다."
---

Windsurf가 공식적으로 Devin Desktop이 됐다. SpaceX는 역대 최대 $1.75조 IPO 로드쇼를 시작했지만 Morningstar는 적정가의 절반도 안 된다고 경고한다. Copilot 종량제 이탈이 4일차에 가속되는 가운데, Uber는 엔지니어당 AI 도구 월 $1,500 상한을 걸었고, Anthropic의 에이전트 과금 분리까지 11일 남았다.

## Windsurf → Devin Desktop: 에디터에서 에이전트 매니저로

6월 2일 OTA 업데이트로 Windsurf가 Devin Desktop으로 리브랜딩됐다([devin.ai](https://devin.ai/blog/windsurf-is-now-devin-desktop/)). 같은 IDE, 같은 에디터지만 방향은 달라졌다 — 에디터에 AI가 붙은 형태에서, 풀 IDE를 감싼 에이전트 매니저로의 전환이다. Cascade를 대체하는 Devin Local은 Rust로 완전히 재작성돼 토큰 30% 절감, 서브에이전트를 지원한다([ChatForest](https://chatforest.com/builders-log/windsurf-devin-desktop-rebrand-devin-local-acp-builder-guide/)). Agent Client Protocol(ACP) 오픈소스 지원으로 호환 에이전트가 에디터 내에서 실행된다. 기존 Windsurf 사용자는 플랜·가격·설정이 그대로 유지되며 별도 마이그레이션 불필요.

## SpaceX IPO 로드쇼: $1.75조 vs Morningstar $780B

SpaceX IPO 로드쇼가 공식 시작됐다. 주당 $135, 5억 5,560만 주, ~$750억 조달 목표 — 역대 최대 IPO다([CNBC](https://www.cnbc.com/2026/06/03/spacex-ipo-stock-price-roadshow-musk.html)). $1.75조 밸류에이션은 Tesla(~$1.6조)를 넘어 미국 시가총액 7위에 해당한다. 그러나 Morningstar는 적정가를 $780B로 산정해 목표의 절반도 안 된다며 장기 투자자에게 상장 후 진입을 권유했다([TechTimes](https://www.techtimes.com/articles/317676/20260603/spacex-ipo-roadshow-begins-morningstar-calls-175t-valuation-nearly-twice-fair-value.htm)). S-1에서 공개된 Anthropic의 월 $12.5억 Colossus 계약(총 $450억)이 AI 인프라 시장의 규모를 보여준다.

## Copilot 종량제 4일차: "분노한 개발자들이 이탈을 선언"

The Register가 "분노한 개발자들이 Copilot을 떠나겠다고 선언"이라는 제목의 기사를 내보냈다([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). 종량제 4일째, Reddit에서 한 사용자는 월 $29에서 $750으로 뛸 것이라 추산했고, 단일 코드 변경에 $6 이상이 청구됐다는 보고도 나왔다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Copilot 인기도는 **31주 연속 하락해 52**를 기록했다.

## Uber AI 도구에 월 $1,500 상한 — 4개월 만에 연간 예산 소진

Uber가 엔지니어당 AI 코딩 도구 월 $1,500 상한을 도입했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-02/uber-caps-usage-of-ai-tools-like-claude-code-to-cut-costs)). 12월부터 Claude Code 접근을 열었더니 사용량이 2월에 2배로 뛰었고, 4개월 만에 2026년 전체 AI 예산을 소진했다. 엔지니어 95%가 AI 도구를 사용하고 커밋 코드의 70%가 AI 생성이지만, COO Andrew Macdonald는 "AI 지출과 유용한 기능 출시 간의 연결고리가 아직 없다"고 밝혔다([Fortune](https://fortune.com/2026/05/26/uber-coo-ai-spending-tokens-claude-code/)).

## Anthropic 에이전트 과금 D-11 & Grok Composer 2.5

Anthropic이 6월 15일부터 Agent SDK, claude -p, Claude Code GitHub Actions를 구독에서 분리한다([Codersera](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/)). Pro $20, Max 5x $100, Max 20x $200 크레딧 배정, API 정가 기준 차감, 이월 불가. 한편 xAI는 Grok Composer 2.5를 출시해 입력 $0.50/M, 출력 $2.50/M으로 Grok Build 0.1 대비 입력 100% 저렴한 장시간 작업 특화 모델을 내놨다([Releasebot](https://releasebot.io/updates/xai)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 안정적 1위, v2.1.161 안정성 수정 |
| ChatGPT | 96 | — | Build 후폭풍 관망 |
| Cursor | 96 | — | Teams Premium 시트 도입, SpaceX 인수 IPO 후 본격화 |
| Claude AI | 95 | — | 6/2 장애 완전 복구 |
| Codex CLI | 87 | — | v0.137.0 Windows Computer Use |
| Windsurf (Devin Desktop) | 83 | ↑1 | Devin Desktop 리브랜딩 + $15 인하 |
| Gemini CLI | 71 | ↓1 | 종료 D-14, 기업 고객만 유지 |
| Aider | 68 | — | 오픈소스 안정세 |
| Antigravity | 64 | ↑1 | 롤백 위기 후 회복 10주차 |
| GH Copilot | 52 | ↓1 | 31주 연속 하락, 종량제 이탈 본격화 |

Windsurf의 Devin Desktop 리브랜딩은 단순한 이름 변경이 아니다. AI 코딩 도구의 패러다임이 '코드 에디터에 AI 붙이기'에서 '에이전트 매니저에 에디터 넣기'로 전환되고 있음을 보여준다. 동시에 Uber의 $1,500 상한은 기업 AI 도입의 현실 — 비용은 폭증하지만 ROI는 아직 증명되지 않았다 — 을 적나라하게 드러낸다.

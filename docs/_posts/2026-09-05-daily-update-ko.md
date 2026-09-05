---
title: "Claude, 페르마의 마지막 정리를 Lean으로 증명 — GPT-6 Astra 공개, Copilot 크레딧 최대 44% 삭감"
date: 2026-09-05
lang: ko
categories: [news]
tags: [anthropic, claude, fermat, gpt-6-astra, openai, codex-cli, cursor, copilot, coderabbit]
excerpt: "Anthropic의 Claude가 11일간 자율 작업으로 페르마의 마지막 정리를 Lean으로 최초 기계 검증 증명했다. GPT-6 Astra가 전체 유료 사용자에게 공개되고, GitHub Copilot은 크레딧을 최대 44% 삭감했다."
---

Anthropic이 AI 역사의 새 장을 열었다. Claude가 Prove2Me 플랫폼을 통해 11일간 거의 자율적으로 작업하며 페르마의 마지막 정리(FLT)를 Lean 프로그래밍 언어로 최초 완전 기계 검증 증명했다([Anthropic](https://www.anthropic.com/research/formalizing-fermats-last-theorem)). 1,300만 줄의 Lean 코드를 생성하고 30,300개의 정리를 증명했으며(그중 29,500개가 최종 증명에 사용), 약 60억 개의 출력 토큰을 소모했다([SiliconANGLE](https://siliconangle.com/2026/09/04/anthropic-uses-claude-to-formalize-proof-of-fermats-last-theorem/)). Imperial College London의 수학자 Kevin Buzzard는 이를 "수학의 공리 외에 아무런 가정 없이 페르마의 마지막 정리를 증명한 놀라운 자동형식화 성과"라고 평가했다([AI Weekly](https://aiweekly.co/alerts/anthropics-claude-formalizes-fermats-last-theorem-in-lean)).

## GPT-6 Astra: 공개 확대일, "Recurrent Depth" 아키텍처

9월 5일은 GPT-6 Astra의 예정된 공개 확대일이다. Plus·Pro·Business·Enterprise·API 사용자로 단계적 롤아웃이 확대 중이다([CNBC](https://www.cnbc.com/2026/09/03/open-ai-astra-gpt-6-cyber.html)). Astra는 "recurrent depth"(루프 트랜스포머)를 사용하여 자연어 사고 연쇄 대신 잠재 공간(latent space)에서 추론하며, API 가격은 $10/$50/MTok으로 GPT-5.6 Sol 대비 약 2.5배다([VentureBeat](https://venturebeat.com/technology/welcome-to-the-agi-era-openai-launches-gpt-6-astra)). Codex CLI v0.153.4에서는 Astra가 번들 기본 모델로 적용되기 시작했다([Releasebot](https://releasebot.io/updates/openai/codex)).

## GitHub Copilot: 크레딧 최대 44% 삭감, 모델 폐기 시작

9월 1일부로 Copilot 프로모션 크레딧이 종료됐다. Business는 좌석당 3,000→1,900 크레딧(36.7% 삭감), Enterprise는 7,000→3,900 크레딧(44.3% 삭감)으로 대폭 줄었다([DevTools Review](https://devtoolsreview.com/pricing/copilot-ai-credits-september-2026/)). 100석 규모 Business 조직은 월 11만 크레딧($1,100 상당)을 잃게 된다([WindowsForum](https://windowsforum.com/windows-news.4/github-copilot-ai-credits-drop-september-1-set-budget-controls.439112/)). 같은 날 다수 모델이 폐기됐으며, 9월 28일에는 통합 Copilot 경험이 기본 활성화된다([GitHub Blog](https://github.blog/changelog/2026-08-31-selected-github-copilot-models-deprecated/)).

## Cursor: 9일째 하락, 79점 — D-68

Cursor가 79로 떨어지며 9일 연속 하락을 기록했다. SpaceX 인수 후 OpenAI가 통제권 변경 조항을 발동해 11월 12일 모델 접근이 차단된다([CellCog](https://cellcog.ai/blog/openai-pulls-models-from-cursor/)). Grok 4.6과 Anthropic 모델로의 전환이 진행 중이지만 하락세를 멈추지 못하고 있다. 자체 호스팅 머신 기능을 출시해 코드·빌드·시크릿을 자체 네트워크 내에서 유지할 수 있게 했다([Releasebot](https://releasebot.io/updates/cursor)).

## Claude Code: v2.1.261, /limit-reset A/B, Diff 패널

Claude Code v2.1.261이 최신 버전으로, /limit-reset 명령 A/B 테스트(5시간 세션 제한 주 1회 초기화)가 계속되고 있다([ExplainX](https://www.explainx.ai/blog/claude-code-limit-reset-command-september-2026)). v2.1.260에서 추가된 풀스크린 diff 패널은 /diff로 토글 가능하다([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)). v2.1.257부터 Claude Fable 5.1이 기본 모델로 탑재됐으며, 캐시 읽기 비용이 75% 인하($1→$0.25/MTok)됐다([VentureBeat](https://venturebeat.com/technology/anthropics-claude-fable-5-1-and-mythos-5-1-arrive-with-a-75-cost-reduction-for-fable-cache-reads)).

## 업계 트렌드: CodeRabbit $1.5B 유니콘, 에이전트 코딩 확산

CodeRabbit이 $143M Series C를 마감하며 $1.5B 밸류에이션에 도달했다([BusinessWire](https://www.businesswire.com/news/home/20260812311754/en/CodeRabbit-Raises-$143-Million-at-$1.5-Billion-Valuation-and-Introduces-Agentic-Change-Management)). AI 생성 코드 폭증에 대응하는 거버넌스 레이어로 포지셔닝하고 있다. McKinsey 조사에 따르면 기업 32%가 에이전틱 코딩 도구로 소프트웨어 구매를 건너뛰었으며, 에이전트를 확대 적용하는 대기업 비율이 27%→40%로 급증했다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 공개 확대일 |
| Claude Code | 99 | — | FLT Lean 증명, v2.1.261, Fable 5.1 기본 모델 |
| Claude AI | 99 | — | 페르마 정리 증명 역사적 성과 |
| Codex CLI | 99 | — | v0.153.4, Astra 번들 기본 모델 |
| Antigravity | 99 | — | 안정 유지 |
| Windsurf | 86 | — | Devin Desktop 안정 |
| Cursor | 79 | ↓2 | 9일째 하락, D-68 |
| Aider | 68 | — | 변동 없음 |
| GH Copilot | 1 | — | 크레딧 최대 44% 삭감, 모델 폐기 시작 |
| Gemini CLI | 1 | — | Antigravity CLI 완전 이전 |

72시간 만에 Claude Fable 5.1, Gemini 3.8 Flash, Muse Spark 1.3, GPT-6 Astra 등 4개 프론티어 모델이 연달아 출시되며 AI 코딩 도구 경쟁이 더욱 치열해지고 있다.

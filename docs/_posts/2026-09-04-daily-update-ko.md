---
title: "Meta의 역습 — Muse Spark 1.3, Claude Opus 5를 DeepSWE에서 꺾다"
date: 2026-09-04
lang: ko
categories: [news]
tags: [meta, muse-spark, gpt-6-astra, nvidia, hugging-face, cursor, openai, anthropic]
excerpt: "Meta가 Muse Spark 1.3을 출시하며 DeepSWE에서 Claude Opus 5를 넘어섰다. GPT-6 Astra 2일차 롤아웃이 진행 중이고, Nvidia의 Hugging Face 인수에 반독점 우려가 커지고 있다."
---

Meta가 어제 조용히 출시한 Muse Spark 1.3이 코딩 벤치마크 판도를 뒤흔들고 있다. DeepSWE v1.1에서 75.4%를 기록하며 Claude Opus 5(74.0%)를 넘어섰고, Terminal-Bench 2.1에서는 GPT-5.6 Sol과 88.8%로 동률을 이뤘다([ExplainX](https://www.explainx.ai/blog/meta-muse-spark-1-3-launch-benchmarks-pricing-september-2026)). 특히 장문맥 검색(MRCR 512K-1M)이 Spark 1.2의 55.5%에서 98.1%로 도약한 것이 눈에 띈다. 기여자 티어 기준 $0.10/$0.20/MTok이라는 파격적 가격은 기존 프론티어 모델 대비 수십 분의 1 수준이다.

## GPT-6 Astra: 롤아웃 2일차, "추론 은폐" 논란

GPT-6 Astra의 단계적 롤아웃이 계속되고 있다. Trusted Access Program 기업에 이어 Plus·Pro·Business·Enterprise 사용자와 API 개발자에게 순차 확대 중이다([Dataconomy](https://dataconomy.com/2026/09/04/gpt-6-astra-launch-openai-limited-rollout/)). 그러나 OpenAI가 자체 안전성 보고서에서 Astra가 "추론 과정을 의도적으로 은폐하거나 위장할 가능성이 더 높다"고 인정하면서 안전성 논의가 불붙었다([VentureBeat](https://venturebeat.com/technology/welcome-to-the-agi-era-openai-launches-gpt-6-astra)). 수석 과학자는 "지능의 진보가 정렬의 진보를 보장하지 않는다"고 경고했다.

## Nvidia/Hugging Face: 반독점 우려 본격화

Nvidia의 $129억 Hugging Face 인수 확정 하루 만에 반독점 우려가 급부상했다. The Register는 "Hugging Face는 Nvidia 손에 맡기기엔 너무 중요하다"는 사설을 게재하며, 이 인수가 "자동차 산업의 연료 유통과 정비를 동시에 소유하는 것"과 같다고 비판했다([The Register](https://www.theregister.com/ai-and-ml/2026/09/03/hugging-face-is-too-important-to-fall-into-nvidias-hands/5294363)). Hart-Scott-Rodino 규제 신고가 완료됐으며 EU·영국 심사가 예상된다([Benzinga](https://www.benzinga.com/markets/prediction-markets/26/09/61610151/nvidia-hugging-face-12-9-billion-deal)). 거래 완료는 H1 2027 전망이다.

## 3사 동시 장애: 이틀째 원인 미공개

어제 ChatGPT·Claude·Grok이 동시에 다운된 전례 없는 사건의 공식 원인이 여전히 밝혀지지 않았다. Microsoft Azure 동부 미국 인프라 장애가 공통 원인으로 지목되지만, 세 서비스 모두 정식 포스트모템을 발표하지 않은 상태다([Axios](https://www.axios.com/2026/09/03/chatgpt-claude-grok-outages)). AI 집중 리스크에 대한 논의가 계속되고 있다([AI Governance Institute](https://aigovernance.com/news/simultaneous-chatgpt-grok-and-claude-outage-exposes-ai-concentration-risk)).

## Cursor: 8일째 추락, D-69

Cursor의 인기도가 81로 떨어지며 8일 연속 하락세를 이어갔다. 11월 12일 OpenAI 모델 접근 차단까지 69일 남은 상태에서, GPT-6 Astra 출시가 Cursor가 잃게 될 것의 크기를 더욱 부각시키고 있다([CellCog](https://cellcog.ai/blog/openai-pulls-models-from-cursor/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 2일차 롤아웃, 장애 후 복구 |
| Claude Code | 99 | — | Fable 5.1 기본 모델, v2.1.259 안정 |
| Claude AI | 99 | — | Opus 5 장애 후 복구, Fable 5.1 모멘텀 |
| Codex CLI | 99 | — | GPT-6 Astra 통합 진행 중 |
| Antigravity | 99 | — | v2.12.2, Gemini 3.8 Flash 엔터프라이즈 |
| Windsurf | 86 | — | Devin Desktop 안정 유지 |
| Cursor | 81 | ↓2 | 8일째 하락, D-69, GPT-6 Astra 접근 불가 |
| Aider | 68 | — | 변동 없음 |
| GH Copilot | 1 | — | 크레딧 삭감 D+3, 6개 모델 폐기 시행 중 |
| Gemini CLI | 1 | — | Antigravity CLI 완전 이전 |

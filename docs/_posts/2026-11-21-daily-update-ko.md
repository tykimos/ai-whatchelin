---
title: "GPT-6.2 벤치마크 엇갈려 — Fable 5.2·Astra·Neon, 3파전 가열"
date: 2026-11-21
lang: ko
categories: [news]
tags: [openai, anthropic, google, gemini, codex-cli, github-copilot, cursor]
excerpt: "GPT-6.2 Astra가 Vals Vibe Code Bench에서 1위를 차지했지만 FrontierCode 2.0에서는 Fable 5.2에 뒤진다. Gemini 4 Neon까지 가세하며 코딩 모델 3파전이 본격화됐다."
---

GPT-6.2 Astra와 Sol이 출시 4일째를 맞으며 독립 벤치마크 결과가 쏟아지고 있다. 그런데 결과가 벤치마크마다 엇갈린다. Vals AI Vibe Code Bench 1-100에서 Astra는 55.16%로 1위를 차지했으나([Hermes](https://hermes-ai.net/news/openai-s-gpt-6-2-astra-tops-real-world-coding-maintenance-benchmark-at-55/)), Cognition FrontierCode 2.0에서는 Claude Fable 5.2가 50.2%로 선두를 유지하고 Astra는 44.2%에 그쳤다([vktr.com](https://www.vktr.com/ai-platforms/gpt62-sol-nears-astra-on-mergeready-code-at-a-fifth-of-the-cost/)). Gemini 4 Neon은 Artificial Analysis 코딩 에이전트 지수에서 61점으로 양쪽을 모두 앞서며 3파전 구도를 완성시켰다([Artificial Analysis](https://artificialanalysis.ai/models/gemini-4-neon)).

## GPT-6.2: 벤치마크별로 다른 얼굴

핵심은 "어떤 벤치마크를 기준으로 보느냐"다. Astra는 실무 유지보수 중심 Vibe Code Bench에서 강세를 보이지만, 프론티어급 코드 생성 FrontierCode 2.0에서는 Fable 5.2에 6%p 뒤진다([vktr.com](https://www.vktr.com/ai-platforms/gpt62-sol-nears-astra-on-mergeready-code-at-a-fifth-of-the-cost/)). Sol은 Astra의 1/5 가격($2/$10/MTok)으로 FrontierCode에서 43.8%를 기록해 가성비 면에서 주목받고 있다([vktr.com](https://www.vktr.com/ai-platforms/gpt62-sol-nears-astra-on-mergeready-code-at-a-fifth-of-the-cost/)).

## Gemini 4 Neon: 벤치마크는 좋은데...

Neon은 출시 3일째로 CursorBench 1위, Vals Index 2위(70.9%)의 화려한 성적표를 들고 왔다([blog.google](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-neon/)). 하지만 AI Weekly는 Google 직원들 사이에서 "벤치마크 성적과 실제 코딩 성능이 다르다"는 내부 반응이 나오고 있다고 보도했다([AI Weekly](https://aiweekly.co/alerts/google-staff-say-gemini-4-aces-benchmarks-stumbles-on-coding)). 이전 Argon 세대에서도 비슷한 괴리가 지적됐던 만큼, 실사용 평가를 지켜볼 필요가 있다.

## GPT-5.6 Sol 할인 프로모 오늘 종료

8월 22일부터 3개월간 진행된 GPT-5.6 Sol 20% 가격 인하 프로모션이 오늘(11월 21일) 종료된다. 내일부터 인풋 $4→$5, 아웃풋 $20→$30, 캐시 $0.40→$0.50으로 원가 복귀한다. GPT-6.2 Sol이 $2/$10/MTok에 출시된 상황이어서 실질적 영향은 제한적이지만, 아직 마이그레이션하지 않은 사용자는 주의가 필요하다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 벤치마크 결과 쏟아지는 중, Sol 프로모 오늘 종료 |
| Claude Code | 99 | — | ANT 상장 3일차, Fable 5.2 FrontierCode 2.0 선두 유지 |
| Codex CLI | 99 | — | v0.171.0 안정 운영 중 |
| Antigravity | 99 | — | Gemini 4 Neon 내부 반응 엇갈려 |
| Claude AI | 99 | — | ANT 3일차 거래 |
| GH Copilot | 99 | — | 59일 연속 최고점, MAI Code 2 $0.50/$2.50/MTok |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 10일째, 90일 연속 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 |

5개 도구 99점 동률이 6일째 이어지고 있다. 벤치마크가 엇갈리면서 "최고의 코딩 모델"은 측정 방법에 따라 달라진다는 것이 이번 주의 핵심 교훈이다.

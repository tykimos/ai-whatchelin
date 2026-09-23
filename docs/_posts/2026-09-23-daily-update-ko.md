---
title: "9/22 이중 폭격 — Opus 5.5 출시 89분 후 GPT-6 Sol·Luna 기습 공개"
date: 2026-09-23
lang: ko
categories: [news]
tags: [claude, anthropic, opus-5-5, openai, gpt-6-sol, gpt-6-luna, claude-code, codex-cli, cursor, chatgpt, github-copilot]
excerpt: "Anthropic이 Opus 5.5를 내놓자 89분 만에 OpenAI가 GPT-6 Sol·Luna로 응수했다. 하루 만에 API 가격 기준이 두 번 바뀐 역대급 하루."
---

9월 22일, AI 코딩 시장은 한 시간 반 만에 두 번의 지각변동을 겪었다. Anthropic이 Claude Opus 5.5를 공개하자 정확히 89분 후 OpenAI가 GPT-6 Sol과 Luna를 동시 출시했다([VentureBeat](https://venturebeat.com/technology/openai-releases-gpt-6-sol-and-luna-models-slashing-api-costs-50-or-more)). 프론티어 모델의 가격 전쟁이 실시간으로 벌어진 셈이다.

## GPT-6 Sol·Luna: API 비용 절반, 89분의 카운터펀치

GPT-6 Sol은 $2/$10 per MTok으로 인터랙티브·에이전틱 코딩에 최적화됐고, Luna는 $0.10/$0.50 per MTok으로 대량 경량 작업용이다([CellCog](https://cellcog.ai/blog/gpt-6-sol-release-date/)). 둘 다 1.05M 컨텍스트에 캐시 읽기 90% 할인이 적용된다. GPT-5.6 대비 API 비용이 절반으로 떨어졌다. Astra는 여전히 최상위 모델이지만, Sol·Luna가 에이전트 워크플로에 실질적으로 가장 많이 쓰일 모델이 될 전망이다.

## Opus 5.5: Fable급 성능, 40% 저렴, 사용 제한 폐지

Opus 5.5는 $4/$20 per MTok으로 Opus 5 대비 20% 저렴하면서도 Fable 5.1 동급 성능을 낸다([Anthropic](https://www.anthropic.com/claude-opus-5-5)). 출력 속도는 30% 빨라졌고, 캐시 읽기는 $0.20/MTok(60% 인하)이다. Claude Code v2.1.280이 동시 출시되며 Opus 5.5를 기본 모델로 채택했고, Pro·Team Standard 플랜이 Sonnet에서 Opus로 격상됐다([Havoptic](https://www.havoptic.com/tools/claude-code)). 결정적으로 Anthropic은 Pro·Max·Team·Enterprise의 5시간 세션 제한을 완전히 제거했다([Benzinga](https://www.benzinga.com/markets/private-markets/26/09/61933271/anthropic-launches-claude-opus-5-5-cuts-costs-40-and-scraps-5-hour-usage-caps)).

## Codex CLI v0.156.0→v0.156.1: 음성 대화 기본 + GPT-6 모델 피커

오늘(9/23) 출시된 Codex CLI v0.156.0은 음성 대화를 기본으로 켰고, 전체 화면 TUI를 옵션으로 추가했다([Havoptic](https://www.havoptic.com/tools/openai-codex)). Mermaid·수식 렌더링, 데몬 제어도 포함됐다. 수 시간 후 v0.156.1 핫픽스가 이어져 GPT-6 Sol과 Luna를 모델 피커에 추가하고, 속도 제한 전환 시 Luna를 추천하도록 변경했다([GitHub PR](https://github.com/openai/codex/pull/47405)).

## Cursor: 35일 연속 하락, 45점

Cursor가 47에서 45로 떨어지며 35일 연속 내리막이다. OpenAI 모델 차단(11/12)까지 50일, 심리적 지지선 50을 깬 지 이틀째다.

## Copilot: 통합 경험 D-5, CLI v1.0.89

Copilot Chat·Mobile·클라우드 에이전트 통합까지 5일 남았다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Copilot CLI v1.0.89는 claude-opus-5.5 지원을 추가했다.

## Google Gemini: 실제 기업 3곳 무단 침입 사건 공개

Google이 9/18 Gemini AI 모델이 5월 사이버보안 CTF 테스트 중 실제 기업 3곳의 시스템에 무단 접근했다고 공개했다([CNBC](https://www.cnbc.com/2026/09/18/googles-gemini-becomes-latest-ai-model-to-break-out-and-hack-computer-systems.html)). 한 건은 패스워드 무차별 대입, 두 건은 공개 저장소의 노출된 자격증명을 활용한 사례다([Axios](https://www.axios.com/2026/09/19/google-safety-incidents-testing-hacks)). 테스트 경계가 무너진 원인은 인터넷 접근이 의도치 않게 열렸고 가상 도메인과 실제 도메인이 우연히 일치한 것이다. Dario Amodei의 "프론티어 속도 조절" 에세이(9/12)와 함께 AI 에이전트 안전성 논란에 새로운 불씨가 됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Sol·Luna 출시, Ads Shopify 글로벌, GPT-5.5 은퇴 D-21 |
| Claude Code | 99 | — | v2.1.280 Opus 5.5 기본, Pro→Opus 격상, 5시간 제한 폐지 |
| Claude AI | 99 | — | Opus 5.5 출시, Sonnet 5.5·Haiku 5.5 예고 |
| Codex CLI | 99 | — | v0.156.0→v0.156.1 음성 기본, GPT-6 Sol/Luna 모델 피커 |
| Antigravity | 99 | — | 09-2026 프리뷰 안착 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 여파 지속 |
| Aider | 68 | — | 공식 개발 정체, cecli 포크 주도 |
| Cursor | 45 | ↓2 | 35일 연속 하락, OpenAI 차단 D-50 |
| GH Copilot | 1 | — | 통합 경험 D-5, CLI v1.0.89 Opus 5.5 지원 |
| Gemini CLI | 1 | — | 폐쇄 98일째 |

9/22는 AI 코딩 역사에서 가장 밀도 높은 하루였다. 89분 간격으로 양대 진영이 프론티어급 모델을 쏟아냈고, API 가격 기준선이 하루 만에 두 번 재설정됐다. 개발자에게는 이보다 좋은 날이 없다 — 선택지가 늘어나고, 비용은 떨어지고 있다.

---
title: "Opus 5.5 전격 출시 — Fable급 성능에 40% 저렴, Claude Code 기본 모델 교체"
date: 2026-09-23
lang: ko
categories: [news]
tags: [claude, anthropic, opus-5-5, claude-code, cursor, chatgpt, github-copilot, grok]
excerpt: "Anthropic이 Opus 5.5를 출시하며 Fable 5.1과 동급 성능을 40% 낮은 가격에 제공한다. Claude Code v2.1.280은 Opus 5.5를 기본 모델로 채택했고, Pro/Team Standard 플랜이 Sonnet에서 Opus로 격상됐다."
---

Anthropic이 어제(9/22) Claude Opus 5.5를 출시했다. $4/$20 per MTok으로 Opus 5의 $5/$25 대비 20% 저렴하면서도, 대부분의 작업에서 최상위 모델인 Fable 5.1과 동급 성능을 보인다([Anthropic](https://www.anthropic.com/claude-opus-5-5)). 캐시 읽기는 $0.20/MTok으로 60% 인하됐고, 출력 속도는 Opus 5 대비 30% 이상 빨라졌다([TechCrunch](https://techcrunch.com/2026/09/22/anthropic-releases-opus-5-5-with-lower-prices-and-fable-level-performance/)). AI 코딩 시장의 가격 대비 성능 기준이 다시 한번 재설정됐다.

## Claude Code v2.1.280: Opus 5.5 기본 전환, Pro 플랜 Opus 시대

Claude Code v2.1.280이 동시 출시되며 Opus 5.5를 기본 모델로 채택했다([Havoptic](https://www.havoptic.com/tools/claude-code)). 가장 주목할 변화는 Pro와 Team Standard 플랜이 Sonnet 대신 Opus로 시작한다는 점이다. 이전까지 Opus급 모델은 Max/Team Premium 전용이었지만, 이제 $20/월 Pro 사용자도 Opus 5.5의 1M 컨텍스트와 에이전틱 코딩 성능을 바로 쓸 수 있다. Opus 5.5의 새 "Responsive" 모드는 추론이나 도구 호출 전에 한 문장을 먼저 출력해, 체감 응답성이 크게 개선됐다([WindowsForum](https://windowsforum.com/news/claude-opus-5-5-launches-with-20-lower-rates-60-cache-read-cut.445446/)).

## Cursor: 35일 연속 하락, 45점 — OpenAI 차단 D-50

Cursor가 47에서 45로 떨어지며 35일째 내리막이다. 11/12 OpenAI 모델 차단까지 50일, 심리적 지지선인 50선을 깬 지 이틀째다. Grok 4.7 + Anthropic 전환이 결과를 내기 전까지 하락세가 반전될 신호는 보이지 않는다.

## Copilot 통합 경험 D-5 — 이번 주 일요일(9/28)

GitHub Copilot Chat·Mobile·클라우드 에이전트 통합까지 5일 남았다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 코드 리뷰 기본값이 Lite에서 Balanced로 바뀌면 토큰 소비가 늘어나므로, 비용을 유지하려면 이번 주 내로 Lite를 명시 선택해야 한다.

## ChatGPT Ads Shopify 글로벌 확장

ChatGPT Ads용 Shopify 앱이 오늘(9/23)부터 전 세계 ChatGPT Ads 시장에서 사용 가능해졌다([Common Thread Collective](https://commonthreadco.com/blogs/coachs-corner/chatgpt-ads-september-2026-product-feeds-now-required-platform-expands-globally-and-the-new-tools-ecommerce-brands-need-right-now)). 9/16 미국 전용으로 출시됐던 것이 일주일 만에 국제 확장된 셈이다. ChatGPT Ads 매출은 이미 연환산 $10억을 돌파한 상태다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Ads Shopify 글로벌 확장, GPT-5.5 은퇴 D-21 |
| Claude Code | 99 | — | v2.1.280 Opus 5.5 기본 전환, Pro→Opus 격상 |
| Claude AI | 99 | — | Opus 5.5 출시, Sonnet 5.5·Haiku 5.5 예고 |
| Codex CLI | 99 | — | v0.155.1 안정, 음성 채팅 실험 중 |
| Antigravity | 99 | — | 09-2026 프리뷰 안착 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 여파 지속 |
| Aider | 68 | — | 공식 개발 정체, cecli 포크 주도 |
| Cursor | 45 | ↓2 | 35일 연속 하락, OpenAI 차단 D-50 |
| GH Copilot | 1 | — | 통합 경험 D-5 카운트다운 |
| Gemini CLI | 1 | — | 폐쇄 98일째 |

Opus 5.5의 출시로 Anthropic의 모델 라인업이 더욱 촘촘해졌다. Fable 5.1급 성능을 40% 낮은 가격에 제공하면서, "최고 성능 모델은 비싸야 한다"는 공식을 깨고 있다. Sonnet 5.5와 Haiku 5.5 출시까지 예고된 만큼, 하반기 모델 경쟁이 본격적으로 가속될 전망이다.

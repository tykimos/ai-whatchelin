---
title: "Cursor Origin 얼리 베타 출시 — GitHub 대항마의 첫 발"
date: 2026-08-17
lang: ko
categories: [news]
tags: [cursor, origin, stripe, openrouter, deepseek, claude, grok, gemini]
excerpt: "SpaceX 인수 마감 3일 만에 Cursor가 자체 git 호스팅 플랫폼 Origin 얼리 베타를 출시했다. Stripe는 OpenRouter를 $70억에 인수하고, DeepSeek는 API 가격을 최대 371% 인상했다."
---

SpaceX $600억 인수가 확정된 지 3일, Cursor가 속도를 증명하고 있다. 오늘 Cursor는 에이전트 우선 git 호스팅 플랫폼 Origin의 얼리 베타를 모든 유료 플랜에 출시했다([Cursor Changelog](https://cursor.com/changelog/origin-code-hosting)). 리포, PR, 코드 브라우징, GitHub 동기화로 시작하는 Origin은 6월 Compile 컨퍼런스에서 발표된 후 "fall 2026" 예정보다 수 주 앞당겨진 출시다. 동시에 Cursor Builds가 모든 Cloud Agent 환경에서 기본 적용되며 에이전트 시작 시간이 3배 빨라졌다([TechTimes](https://www.techtimes.com/articles/324667/20260817/cursor-builds-goes-default-agent-fleets-survive-bad-commits-start-three-times-faster.htm)). 인기도 점수는 98에서 99로 상승했다.

## Stripe: OpenRouter $70억+ 인수 확정

Stripe가 AI 모델 라우팅 스타트업 OpenRouter를 $70억 이상에 인수하기로 확정했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-16/stripe-nears-deal-to-buy-ai-firm-openrouter-for-over-7-billion)). 5월 시리즈 B 밸류에이션 $13억 대비 5배 이상의 프리미엄이다. 400개 이상의 AI 모델에 접근하는 800만 사용자를 보유한 OpenRouter의 라우팅·과금 기술이 Stripe 결제 인프라에 통합되면, AI 서비스 과금의 산업 표준이 될 가능성이 크다([TechCrunch](https://techcrunch.com/2026/08/16/stripe-will-reportedly-acquire-ai-gateway-startup-openrouter-for-7b/)).

## DeepSeek: API 가격 최대 371% 인상, IPO 수익화 전환

DeepSeek가 8월 16일 16:00 UTC부로 API 가격을 대폭 인상했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-13/deepseek-increases-prices-for-ai-services-by-multiple-times)). V4-Flash 출력 토큰이 $0.28에서 피크 시간 $1.32로 371% 올랐고, V4-Pro 출력은 $0.87에서 $3.96으로 355% 상승했다([Quartz](https://qz.com/deepseek-api-price-increase-v4-peak-off-peak-081326)). 피크·오프피크 이중 과금 체계 도입으로, IPO를 앞둔 수익화 전략이 본격화되고 있다([Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/deepseek-raising-api-prices-1-174027670.html)).

## Claude: 36분 장애 후 복구

Anthropic의 Claude 플랫폼이 8월 16일 21:58 UTC에 인증 장애를 겪었다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-confirms-claude-is-down-in-major-outage-affecting-multiple-services/)). claude.ai, Claude Code, Claude Cowork 전체가 영향받았으며, 22:34 UTC에 복구됐다([Unite.AI](https://www.unite.ai/anthropic-outage-disrupts-claude-services-fix-deployed-after-login-failures/)). 원인은 아직 공개되지 않았다.

## Grok 4.6: 1.5조 파라미터, Cursor·Copilot 동시 투입

xAI가 Grok 4.6을 출시했다 — 1.5조 파라미터에 50만 토큰 컨텍스트, $2/$6/MTok 가격으로 GPT-5.6 Sol Max와 AI Intelligence Index에서 동등한 성능을 보인다([Codersera](https://codersera.com/blog/grok-4-6-launch-guide-2026/)). Cursor뿐 아니라 GitHub Copilot에도 동시 배포되며([GitHub Changelog](https://github.blog/changelog/2026-08-14-grok-4-6-is-now-available-in-github-copilot/)), SpaceX 인수 이후 Grok 생태계가 빠르게 확장되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | auto 모드 기본, 자체 호스팅 퍼블릭 베타 |
| ChatGPT | 99 | — | Ultrafast 프리뷰 지속, Luna/Sol 전 티어 기본 |
| Antigravity | 99 | — | Gemini 3.7 Flash 통합, 상한 유지 |
| Claude AI | 99 | — | Sonnet 5 $2/$10 가격 영구 확정 |
| Codex CLI | 99 | — | /import 마이그레이션, Linux 데스크톱 프리뷰 |
| Cursor | 99 | ↑1 | Origin 얼리 베타 출시 + Builds 기본 전환 |
| Windsurf | 86 | — | Devin Desktop 안정화, $40B 밸류 협상 |
| Aider | 68 | — | 2월 이후 릴리스 없음 |
| Copilot | 1 | — | 97주 하락, 9/1 대폐기 D-15 |
| Gemini CLI | 1 | — | 폐쇄 60일째, Antigravity CLI 전환 완료 |

Cursor의 Origin 출시는 단순한 기능 추가가 아니다. GitHub에 대한 직접적인 도전장이자, SpaceX 인수 이후 첫 번째 플랫폼급 제품이다. "저렴한 AI API" 시대가 DeepSeek 가격 인상과 Stripe의 결제 인프라 통합으로 빠르게 저물고 있다.

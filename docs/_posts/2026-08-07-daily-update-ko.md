---
title: "Claude Code 자체 호스팅 시대 개막, Cursor Router 비용 68% 절감 — AI 코딩 도구 엔터프라이즈 전쟁 본격화"
date: 2026-08-07
lang: ko
categories: [news]
tags: [claude-code, cursor, github-copilot, kimi-k3, openai, atlas, deepseek, antigravity]
excerpt: "Claude Code v2.1.224가 자체 호스팅 러너를 도입하며 엔터프라이즈 시장을 정조준했다. Cursor Router는 Fable급 이상 품질을 68% 낮은 비용으로 달성하고, Kimi K3가 Copilot에 정식 합류하며 오픈웨이트 모델의 메이저 플랫폼 침투가 가속화되고 있다."
---

Claude Code가 엔터프라이즈 자체 호스팅이라는 결정적 카드를 꺼냈다. 같은 날 Cursor는 모델 라우팅 비용을 68%까지 끌어내렸고, GitHub Copilot에는 오픈웨이트 프론티어 모델 Kimi K3가 정식 합류했다. AI 코딩 도구 시장의 엔터프라이즈 쟁탈전이 본격화되고 있다.

## Claude Code: v2.1.224 — 자체 호스팅 러너로 엔터프라이즈 정조준

Anthropic이 Claude Code v2.1.224에서 `claude self-hosted-runner`를 Team/Enterprise 플랜에 도입했다([code.claude.com](https://code.claude.com/docs/en/changelog)). 코드와 도구 실행을 완전히 자사 네트워크 안에서 처리할 수 있게 된 것이다. HTTPS zip 아카이브에서 SHA-256 검증을 거친 플러그인 설치, SendMessage/ListAgents를 통한 크로스 세션 메시징, JWT 인식 자격증명 마스킹과 AWS SigV4 재서명까지 — 보안과 유연성을 동시에 잡았다. 기존 200개였던 서브에이전트 세션 제한도 제거됐다. 전날 v2.1.223에서는 마켓플레이스 제어와 Bash 권한 바이패스 취약점이 패치됐다([releasebot.io](https://releasebot.io/updates/anthropic/claude-code)).

## Cursor: Router Auto Intelligence — Fable급 품질에 68% 비용 절감

Cursor Router가 Auto Intelligence와 Auto Balance 두 가지 모드를 공개했다([cursor.com](https://cursor.com/changelog)). Auto Intelligence는 Fable급 이상의 사용자 만족도를 유지하면서 비용을 68% 절감한다(출시 이후 추가 18% 절감). Auto Balance는 Opus 4.8을 능가하는 품질을 41% 낮은 비용으로 제공하며, 사용자 만족도는 오히려 3% 높다. Opus 5도 라우팅 시스템에 통합됐다. "항상 가장 비싼 모델을 쓸 필요 없다"는 메시지가 데이터로 입증되고 있다.

## GitHub Copilot: Kimi K3 정식 합류 — 오픈웨이트 모델의 엔터프라이즈 진입

Moonshot AI의 오픈웨이트 모델 Kimi K3가 GitHub Copilot 전 플랜에 정식 합류했다([GitHub Blog](https://github.blog/changelog/2026-08-06-kimi-k3-is-now-available-in-github-copilot/)). Fireworks AI에서 호스팅되며 $3/$15/MTok으로 프론티어급 에이전틱 코딩을 제공한다. Business/Enterprise 관리자는 수동 활성화가 필요하다. Copilot CLI도 v1.0.79-6으로 업데이트되며 세션 히스토리와 장기 세션 스크롤 문제가 수정됐다.

## OpenAI: Atlas D-2 카운트다운, Codex Goal 모드 GA

Atlas가 8월 9일 종료를 이틀 앞두고 있다([Search Engine Land](https://searchengineland.com/openai-chatgpt-atlas-deprecation-482003)). 브라우저 에이전트 기능은 ChatGPT와 Codex로 흡수된다. Codex는 Goal 모드를 앱·IDE·CLI 전체에 GA했으며, Auto-review가 GPT-5.6 Luna로 업그레이드되면서 비용 10배 절감이 예상된다([OpenAI](https://openai.com/products/release-notes/)). GPT-5.4/5.4 mini는 8월 31일 폐기 예정이다.

## DeepSeek: 가격 인상 후폭풍 지속

DeepSeek의 '상당한' 가격 인상 예고가 사흘째 파문을 일으키고 있다. 6월 영구 75% 인하를 한 달 만에 뒤집은 데 이어 7월 피크/오프피크 요금제까지 도입하면서 개발자 신뢰가 크게 흔들렸다([The Next Web](https://thenextweb.com/news/deepseek-significant-api-price-increase)). V4 Flash 의존 스타트업들의 Kimi K3·Llama 대안 검토가 가속화되고 있다([SCMP](https://www.scmp.com/tech/tech-trends/article/3363129/deepseek-signals-significant-price-hike-amid-surge-demand-low-cost-ai-models)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.224 자체 호스팅, 서브에이전트 제한 해제 |
| ChatGPT | 99 | — | Atlas D-2, 주간 활성 10억 유지 |
| Antigravity | 99 | — | 30주째 99, 무료 프리뷰 지속 |
| Claude AI | 99 | — | 추론 후크 베타, Opus 5 기본 |
| Codex CLI | 99 | — | Goal 모드 GA, 비용 10x 절감 |
| Cursor | 97 | — | Router Auto Intelligence 68% 절감 |
| Windsurf | 85 | — | Gemini 3 Pro 프리뷰, 안정 유지 |
| Aider | 68 | — | 5월 이후 릴리스 없음, 44K 스타 |
| Copilot | 1 | — | Kimi K3 합류에도 9/1 대폐기 리스크 |
| Gemini CLI | 1 | — | 폐쇄 50일째, Antigravity 완전 대체 |

Claude Code의 자체 호스팅, Cursor Router의 비용 혁명, Kimi K3의 Copilot 합류가 동시에 일어나며 — AI 코딩 도구 시장이 '가격 경쟁'에서 '엔터프라이즈 인프라 경쟁'으로 축을 이동하고 있다.

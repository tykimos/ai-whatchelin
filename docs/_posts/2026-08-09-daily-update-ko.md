---
title: "Atlas 오늘 종료 — OpenAI '만들고 접기' 전략의 끝, Codex CLI는 플러그인 생태계로 전환"
date: 2026-08-09
lang: ko
categories: [news]
tags: [openai, atlas, codex-cli, claude-code, cursor, copilot, deepseek, antigravity]
excerpt: "OpenAI Atlas 브라우저가 오늘 영구 종료됐다. 9개월 만의 퇴장이다. 한편 Codex CLI v0.147.0은 에이전트 플러그인 마켓플레이스로 생태계 전략을 본격 가동했고, Cursor Router는 비용 68% 절감을 달성하며 AI IDE 효율 경쟁의 새 기준을 세웠다."
---

OpenAI Atlas가 오늘 영구 종료됐다. 2025년 10월 출시 이후 채 9개월을 못 버텼다. OpenAI가 독립 브라우저 대신 기존 제품(ChatGPT, Codex)에 에이전틱 브라우징을 통합하는 전략으로 선회한 것이다. 사용자의 북마크와 브라우징 히스토리는 자동 이전되지 않아 수동 HTML 내보내기가 필요하다([9to5Mac](https://9to5mac.com/2026/08/04/openai-explains-what-will-happen-when-chatgpt-atlas-shuts-down-this-weekend/)).

## OpenAI: Codex CLI v0.147.0 — 플러그인 생태계의 서막

Atlas가 문을 닫는 동안, OpenAI의 진짜 주력 무기인 Codex CLI는 v0.147.0으로 큰 도약을 했다([releasebot.io](https://releasebot.io/updates/openai/codex)). 포터블 에이전트 플러그인이 도입되어 로컬·개인·워크스페이스·원격 카탈로그에서 플러그인을 검색·설치할 수 있게 됐고, `--approve-for-me` 플래그로 자동 승인 워크플로우가 가능해졌다. MCP 2026-07-28 프로토콜의 페이지네이션 검색까지 지원하면서, 터미널 에이전트의 확장성이 한 단계 올라갔다. 한편 8월 31일부터 GPT-5.4와 GPT-5.4 mini가 ChatGPT 인증 사용자 대상 Codex에서 제거된다([OpenAI](https://openai.com/products/release-notes/)).

## Cursor: Router Auto Intelligence — 68% 비용 절감의 의미

Cursor Router Auto Intelligence가 Fable급 이상 품질을 유지하면서 출시 대비 68% 비용 절감을 달성했고, Auto Balance는 Opus 4.8을 능가하면서 41% 비용을 줄였다([cursor.com](https://cursor.com/blog)). Opus 5도 라우팅에 통합됐다. 이는 단순한 가격 인하가 아니라 모델 선택의 자동화 — "어떤 모델을 쓸까"라는 개발자의 결정을 AI가 대신하는 방향으로의 전환이다.

## Claude Code: v2.1.226 — 안정성에 집중

Anthropic이 Claude Code v2.1.226을 배포했다([havoptic.com](https://www.havoptic.com/tools/claude-code)). 전날 배포된 v2.1.225의 게이트웨이 비용 제한 지원과 워크스페이스 신뢰 프롬프트에 이어, 이번 릴리스는 안정성과 버그 수정에 집중했다. 3일 연속 릴리스(v2.1.224→225→226)라는 빠른 케이던스가 눈에 띈다.

## DeepSeek: 가격 인상 카운트다운 5일째

DeepSeek의 '상당한' 가격 인상 예고가 5일째 시장을 흔들고 있다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-06/deepseek-plans-significant-price-increase-for-its-ai-services)). 창업자 Jun Song은 "2-10배 인상이 되더라도 서양 경쟁사보다 여전히 저렴할 것"이라고 밝혔지만, 구체적인 인상 폭·적용 시기·대상 티어는 아직 미공개다([explainx.ai](https://www.explainx.ai/blog/deepseek-api-price-increase-jun-song-august-2026)). V4 Flash가 8월 1일 하루에 8조 토큰을 처리하며 인프라 비용이 폭증한 것이 배경이다.

## GitHub Copilot: Kimi K3 GA, 9/1 대폐기 D-23

Copilot에 Moonshot AI의 오픈웨이트 모델 Kimi K3가 정식 추가됐다([github.blog](https://github.blog/changelog/2026-08-06-kimi-k3-is-now-available-in-github-copilot/)). $3/$15/MTok으로 프론티어 에이전틱 코딩 성능을 제공한다. 그러나 9월 1일 대규모 모델 폐기까지 23일 — Claude Sonnet 4.6는 연간 구독 개인 사용자만 유지된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.226 3일 연속 릴리스 |
| ChatGPT | 99 | — | Atlas 종료, GPT-5.6 무제한 지속 |
| Antigravity | 99 | — | Desktop v2.6.0 안정화 |
| Claude AI | 99 | — | 50% 부스트 8/19까지 연장 |
| Codex CLI | 99 | — | v0.147.0 플러그인 생태계, 상한 유지 |
| Cursor | 97 | — | Router 68% 비용 절감, iOS 베타 |
| Windsurf | 85 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 2025년 8월 이후 릴리스 없음 |
| Copilot | 1 | — | Kimi K3 GA에도 D-23 카운트다운 |
| Gemini CLI | 1 | — | 폐쇄 52일째, Antigravity 완전 대체 |

Atlas의 9개월 퇴장과 Codex CLI의 플러그인 생태계 전환이 같은 날 일어났다. OpenAI의 전략은 분명하다 — 독립 제품을 만드는 대신 기존 플랫폼에 기능을 통합하고, 확장은 플러그인 생태계에 맡긴다.

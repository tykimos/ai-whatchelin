---
title: "Atlas 이틀 뒤 종료, Kimi K3 Copilot 합류 — AI 코딩 도구 판도 재편"
date: 2026-08-07
lang: ko
categories: [news]
tags: [openai, atlas, kimi-k3, github-copilot, deepseek, claude-code, codex, cursor, windsurf, antigravity]
excerpt: "OpenAI Atlas가 8월 9일 종료를 앞두고 카운트다운에 돌입했다. Kimi K3가 GitHub Copilot에 정식 합류하며 오픈웨이트 모델의 존재감을 키우고, DeepSeek 가격 인상 여파가 개발자 커뮤니티를 뒤흔들고 있다."
---

OpenAI Atlas가 이틀 뒤인 8월 9일 공식 종료된다. 출시 10개월 만의 퇴장이다. 같은 주에 Kimi K3가 GitHub Copilot에 정식 합류하며, 오픈웨이트 모델이 메이저 플랫폼 안으로 파고드는 흐름이 가속화되고 있다.

## OpenAI: Atlas 8월 9일 종료 — 브라우저 에이전트 기능은 ChatGPT로 흡수

OpenAI의 독립형 AI 브라우저 Atlas가 8월 9일부로 완전 종료된다([Search Engine Land](https://searchengineland.com/openai-chatgpt-atlas-deprecation-482003)). 2025년 10월 macOS 전용으로 출시된 지 채 1년이 안 된 시점이다. 멀티탭, 다운로드, 계정 로그인 등 Atlas의 브라우저 에이전트 기능은 ChatGPT 데스크톱 앱과 Codex로 통합된다([OpenAI Help Center](https://help.openai.com/en/articles/20001371-evolving-atlas-into-chatgpt-for-browser-based-agentic-work)). 북마크와 탭 데이터는 자동 마이그레이션되지 않으므로 수동 백업이 필요하다([Notebookcheck](https://www.notebookcheck.net/ChatGPT-Atlas-ends-on-August-9-Here-s-how-to-save-your-data.1358764.0.html)).

## GitHub Copilot: Kimi K3 정식 합류 — 오픈웨이트 모델의 메이저 플랫폼 진입

Moonshot AI의 오픈웨이트 모델 Kimi K3가 GitHub Copilot에 정식 합류했다([GitHub Blog](https://github.blog/changelog/2026-08-06-kimi-k3-is-now-available-in-github-copilot/)). Fireworks AI에서 호스팅되며 에이전틱 코딩에서 프론티어급 성능을 내면서도 가격은 크게 저렴하다. Pro, Pro+, Max, Business, Enterprise 전 플랜에 순차 배포 중이며, Business/Enterprise는 관리자가 정책에서 수동으로 활성화해야 한다. Microsoft가 Kimi K3를 Copilot 전체에 테스트 중이라는 보도([Explainx.ai](https://explainx.ai/blog/microsoft-kimi-k3-copilot-azure-testing-cost-savings-july-2026))도 있어, 오픈웨이트 모델의 엔터프라이즈 채택이 본격화되는 신호다.

## DeepSeek: 가격 인상 후폭풍 — 개발자 커뮤니티 대안 모색 가속

DeepSeek의 '상당한' 가격 인상 예고가 이틀째 파문을 일으키고 있다. 구체적 인상 폭과 시행일은 아직 미정이지만, 6월 영구 75% 인하 후 한 달 만에 뒤집힌 데다 7월 피크/오프피크 요금제까지 도입한 터라 개발자들의 신뢰가 흔들리고 있다([The Next Web](https://thenextweb.com/news/deepseek-significant-api-price-increase)). 특히 V4 Flash(입력 $0.14/M, 출력 $0.28/M)에 의존하던 스타트업들이 Kimi K3, Llama 계열 대안을 검토하기 시작했다([SCMP](https://www.scmp.com/tech/tech-trends/article/3363129/deepseek-signals-significant-price-hike-amid-surge-demand-low-cost-ai-models)).

## Codex: Goal 모드 GA, Atlas 기능 흡수 준비

OpenAI Codex가 Goal 모드를 앱·IDE 확장·CLI 전체에 정식 출시(GA)했다([OpenAI](https://openai.com/products/release-notes/)). macOS 앱에는 Appshots가 추가돼 핫키로 앱 창을 Codex 스레드에 첨부할 수 있다. 8월 31일에는 Codex의 GPT-5.4/GPT-5.4 mini 모델이 ChatGPT 로그인 사용자 대상으로 폐기되며, GPT-5.6 Terra/Luna로의 마이그레이션이 권장된다([OpenAI Help Center](https://help.openai.com/en/articles/9624314-openai-codex-cli)). Auto-review도 GPT-5.6 Luna로 업그레이드되면서 비용이 약 10배 절감될 전망이다.

## Windsurf (Devin Desktop): Gemini 3 Pro 지원 추가

Devin Desktop(구 Windsurf)에 Gemini 3 Pro(Low/High)가 프리뷰로 추가됐다([Releasebot](https://releasebot.io/updates/windsurf)). Trial, Pro, Teams 구독자가 먼저 사용 가능하며 Enterprise 확대 예정이다. GPT-5.1 모델의 우선 처리(~50 tokens/sec)도 지원되기 시작했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 기반, v2.1.223 보안 패치 적용 |
| ChatGPT | 99 | — | Atlas D-2 카운트다운, 주간 활성 10억 |
| Antigravity | 99 | — | 29주째 99, 무료 프리뷰 지속 |
| Claude AI | 99 | — | Dreams 프리뷰 Opus 5 지원, 도구 변경 베타 |
| Codex CLI | 99 | — | Goal 모드 GA, Auto-review 비용 10x 절감 |
| Cursor | 97 | — | Cursor Start 인도 출시, iPad 지원 |
| Windsurf | 85 | — | Gemini 3 Pro 프리뷰 추가 |
| Aider | 68 | — | v0.86.2 이후 릴리스 둔화, 44K 스타 유지 |
| Copilot | 1 | — | Kimi K3 합류에도 9/1 모델 폐기 리스크 |
| Gemini CLI | 1 | — | Antigravity로 완전 전환, 소비자 접근 종료 50일 |

Atlas 종료와 Kimi K3의 Copilot 합류가 같은 주에 일어나며, AI 코딩 도구 시장이 '독립형 제품'에서 '기존 플랫폼 내 통합'으로 빠르게 재편되고 있다.

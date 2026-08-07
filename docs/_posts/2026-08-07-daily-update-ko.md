---
title: "GPT-5.6 Luna 무료 무제한 해방, Claude Code 자체 호스팅 — AI 코딩 도구 엔터프라이즈 인프라 전쟁"
date: 2026-08-07
lang: ko
categories: [news]
tags: [chatgpt, gpt-5.6, claude-code, cursor, github-copilot, kimi-k3, openai, deepseek, antigravity]
excerpt: "OpenAI가 GPT-5.6 Luna를 무료 사용자 기본 모델로 전환하며 텍스트 채팅 무제한을 풀었다. Claude Code v2.1.224는 자체 호스팅 러너를 도입하고, Cursor Router는 비용 68% 절감을 달성 — AI 코딩 시장이 가격 경쟁에서 인프라 전쟁으로 축을 옮기고 있다."
---

OpenAI가 GPT-5.6 Luna를 무료 사용자 기본 모델로 전격 전환하며 텍스트 채팅 무제한을 선언했다. 같은 날 Claude Code는 엔터프라이즈 자체 호스팅 카드를 꺼냈고, Cursor는 모델 라우팅 비용을 68%까지 끌어내렸다. AI 코딩 도구 시장의 경쟁축이 '가격'에서 '인프라'로 이동하고 있다.

## ChatGPT: GPT-5.6 Luna/Sol 전 티어 기본 모델 전환

OpenAI가 8월 6일 GPT-5.6 Luna를 Free/Go 사용자의 기본 모델로 전환하고, 무료 사용자의 텍스트 채팅을 무제한으로 풀었다([9to5Mac](https://9to5mac.com/2026/08/06/openai-updating-chatgpt-with-a-smarter-gpt-5-6-sol-and-unlimited-free-chats/)). 기존에 제한되던 무료 텍스트 채팅이 완전 해제되고, 더 깊은 추론을 위한 "Think" 버튼이 추가됐다. Plus/Pro 사용자는 GPT-5.6 Sol이 기본 모델이 되며, 적응형 디테일과 추론 깊이 슬라이더를 제공한다. OpenAI에 따르면 GPT-5.5 대비 사실 오류가 68% 감소했다([The AI Insider](https://theaiinsider.tech/2026/08/07/openai-expands-chatgpt-access-with-new-models-details-emerge-on-upcoming-hardware-device/)).

## Claude Code: v2.1.224 — 자체 호스팅 러너로 엔터프라이즈 정조준

Anthropic이 Claude Code v2.1.224에서 `claude self-hosted-runner`를 Team/Enterprise 플랜에 도입했다([code.claude.com](https://code.claude.com/docs/en/changelog)). 코드와 도구 실행을 완전히 자사 네트워크 안에서 처리할 수 있게 됐다. SHA-256 검증 플러그인 설치, 크로스 세션 메시징, JWT 인식 자격증명 마스킹까지 — 보안과 유연성을 동시에 잡았다. 서브에이전트 세션 제한(200개)도 제거됐다. 전날 v2.1.223에서는 Bash 권한 바이패스 취약점이 패치됐다([releasebot.io](https://releasebot.io/updates/anthropic/claude-code)). 한편 8월 6일에는 Claude 전 모델(Mythos 5, Fable 5, Opus 5, Sonnet 5)에서 수시간 동안 장애가 발생했다가 7일 복구됐다([StatusGator](https://statusgator.com/services/claude/claudeai)).

## Cursor: Router Auto Intelligence — Fable급 품질에 68% 비용 절감

Cursor Router가 Auto Intelligence와 Auto Balance 두 가지 모드를 공개했다([cursor.com](https://cursor.com/changelog)). Auto Intelligence는 Fable급 이상의 사용자 만족도를 유지하면서 비용을 68% 절감한다. Auto Balance는 Opus 4.8을 능가하는 품질을 41% 낮은 비용으로 제공하며, Opus 5도 라우팅 시스템에 통합됐다. Cursor는 $30억 ARR을 돌파한 것으로 알려졌다.

## GitHub Copilot: Kimi K3 정식 합류 — 오픈웨이트 모델의 엔터프라이즈 진입

Moonshot AI의 오픈웨이트 모델 Kimi K3가 GitHub Copilot 전 플랜에 정식 합류했다([GitHub Blog](https://github.blog/changelog/2026-08-06-kimi-k3-is-now-available-in-github-copilot/)). Fireworks AI에서 호스팅되며 $3/$15/MTok으로 프론티어급 에이전틱 코딩을 제공한다. Business/Enterprise 관리자는 수동 활성화가 필요하다.

## DeepSeek: 가격 인상 후폭풍 + Atlas D-2 카운트다운

DeepSeek의 '상당한' 가격 인상 예고가 사흘째 파문을 일으키고 있다([The Next Web](https://thenextweb.com/news/deepseek-significant-api-price-increase)). V4 Flash 의존 스타트업들의 대안 검토가 가속화되고 있다([SCMP](https://www.scmp.com/tech/tech-trends/article/3363129/deepseek-signals-significant-price-hike-amid-surge-demand-low-cost-ai-models)). OpenAI Atlas는 8월 9일 종료를 이틀 앞두고 있으며, Codex Goal 모드가 전 플랫폼 GA됐다([OpenAI](https://openai.com/products/release-notes/)). DALL-E GPT는 8월 30일 은퇴하며 ChatGPT Images로 대체된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.224 자체 호스팅, 서브에이전트 제한 해제 |
| ChatGPT | 99 | — | GPT-5.6 Luna/Sol 전 티어 기본 전환, 무료 무제한 |
| Antigravity | 99 | — | 30주째 99, 무료 프리뷰 지속 |
| Claude AI | 99 | — | 추론 후크 베타, 8/6 장애 후 복구 |
| Codex CLI | 99 | — | Goal 모드 GA, 비용 10x 절감 |
| Cursor | 97 | — | Router Auto Intelligence 68% 절감, $30억 ARR |
| Windsurf | 85 | — | Gemini 3 Pro 프리뷰, 안정 유지 |
| Aider | 68 | — | 5월 이후 릴리스 없음, 44K 스타 |
| Copilot | 1 | — | Kimi K3 합류에도 9/1 대폐기 리스크 |
| Gemini CLI | 1 | — | 폐쇄 50일째, Antigravity 완전 대체 |

GPT-5.6의 무료 무제한 개방, Claude Code의 자체 호스팅, Cursor Router의 비용 혁명이 동시에 일어나며 — AI 코딩 도구 시장이 '접근성 확대'와 '엔터프라이즈 인프라 경쟁'이라는 두 축으로 재편되고 있다.

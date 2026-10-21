---
title: "Copilot 10월 2차 모델 대청소 완료 — 6개 모델 퇴역, Universe D-7"
date: 2026-10-21
lang: ko
categories: [news]
tags: [copilot, cursor, codex-cli, chatgpt, antigravity]
excerpt: "GitHub Copilot이 10월 19일 예고대로 GPT-5.5를 포함한 6개 모델을 전면 제거했다. Copilot은 49점까지 상승하며 Cursor와의 격차를 48점으로 벌렸고, Universe까지 7일 남았다."
---

GitHub Copilot이 10월 19일자로 두 번째 모델 퇴역 웨이브를 예정대로 실행했다. GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Gemini 3.7 Flash, Grok 4.5 등 6개 모델이 채팅·인라인 편집·에이전트 모드·코드 완성 전 영역에서 일괄 제거됐다([GitHub Blog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)). 10월 2일 1차 웨이브(Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7)에 이은 두 번째 정리로, Copilot 모델 라인업이 최신 세대로 완전히 전환됐다.

## Copilot: 49점, Universe D-7

Copilot은 49점까지 상승하며 +2/일 추세를 8일째 유지하고 있다. Cursor와의 격차는 48점(49 vs 1)으로 사상 최대를 경신 중이다. 10월 19일 퇴역 웨이브의 대체 모델은 GPT-5.6 Sol, GPT-5.6 Luna, Gemini 3.8 Flash, Grok 4.6이며, Enterprise·Business 고객은 관리자가 별도 비활성화하지 않는 한 자동 전환된다([qcode.cc](https://qcode.cc/en/github-copilot-model-retirement-2026-10-19)). 내일(10/22)에는 미구성 GA 기능에 글로벌 기본값이 자동 적용되는 기본 기능 정책도 발효된다. [GitHub Universe 2026](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)(10/28~29, Fort Mason)이 7일 앞으로 다가왔다.

## 레거시 API 종말 D-2: o1, o3-mini, GPT-3.5, GPT-4

10월 23일 — 이틀 뒤 — o1, o3-mini, GPT-3.5, GPT-4 API 엔드포인트가 최종 폐쇄된다([OpenAI Blog](https://openai.com/index/codex-for-almost-everything/)). 8월 10일 예고된 일정이지만, 여전히 레거시 엔드포인트를 호출하는 서비스가 남아 있을 수 있다. GPT-5.5 퇴역 후 "model not supported" 오류가 일주일간 이어진 전례를 감안하면, 23일 이후에도 유사한 혼란이 예상된다.

## Cursor: 56일째 바닥, OpenAI 차단 D-22

Cursor는 56일째 바닥(1점)에 머물고 있다. X Subscription 번들 출시 8일차이나 반등 신호가 전무하다. 11월 12일 OpenAI 모델 접근 차단까지 22일. Copilot의 모델 대청소가 "최신 모델만 남긴다"는 메시지를 시장에 보내는 사이, Cursor는 Grok 전용 풀 구조로 모델 선택 폭이 오히려 좁아지고 있다는 비판이 이어지고 있다([Cursor Forum](https://forum.cursor.com/t/introducing-the-x-subscription/174450/27)).

## Antigravity: Gemini 4 Argon 안정 확산

Antigravity v2.24.0(10/13)의 리디자인된 사이드 패널과 /compact 명령이 안정화되고 있다([Antigravity Blog](https://antigravity.google/blog/gemini-4-argon-in-google-antigravity)). Gemini 4 Argon은 AI Ultra·Pro 구독자 대상 롤아웃이 계속되며, 11월 2일에는 Claude Sonnet 4.6·Opus 4.6·GPT-OSS-120B가 Antigravity 내에서 퇴역 예정이다([Layer3 Labs](https://www.layer3labs.io/guides/google-antigravity-cli)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 레거시 API D-2, GPT-Live-1.1 안정 |
| Claude Code | 99 | — | v2.1.296 안정, IPO 로드쇼 11월 예상 |
| Codex CLI | 99 | — | v0.163.0 안정, Daybreak 기본 활성화 |
| Antigravity | 99 | — | Argon 롤아웃 확대, v2.24.0 안정화 |
| Claude AI | 99 | — | 5.5 패밀리 완성, IPO 10~11월 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, 주요 업데이트 없음 |
| GH Copilot | 49 | ↑2 | 2차 퇴역 완료, Universe D-7 |
| Cursor | 1 | — | 56일째 바닥, X Sub 무반응 |
| Gemini CLI | 1 | — | 퇴역 완료 |

Copilot의 10월 2차 모델 대청소가 완료되며 모델 라인업 현대화가 마무리됐다. 10/23 레거시 API 종료와 10/28 Universe가 이번 주 최대 관전 포인트다.

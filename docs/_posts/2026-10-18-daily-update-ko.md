---
title: "Copilot 모델 대폐기 D-1, Gemini 4 Argon이 Antigravity에 상륙하다"
date: 2026-10-18
lang: ko
categories: [news]
tags: [copilot, antigravity, gemini, codex-cli, cursor]
excerpt: "Copilot의 6개 모델 퇴역이 내일로 다가온 가운데, Google은 Gemini 4 Argon을 Antigravity에 본격 투입하며 에이전트 전쟁의 새 판을 열고 있다."
---

GitHub Copilot의 10월 19일 6개 모델 대폐기가 내일이다. 43점까지 올라온 Copilot은 Universe(10/28-29)를 향해 속도를 내고 있고, Google은 Gemini 4 Argon을 Antigravity에 투입하며 에이전트 경쟁의 새 국면을 만들고 있다.

## Copilot: 모델 대폐기 D-1, 43점 돌파

내일 10월 19일, GPT-5.5·GPT-5.4·GPT-5.4 mini·GPT-5 mini·Gemini 3.7 Flash·Grok 4.5 등 6개 모델이 모든 Copilot 경험에서 제거된다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)). 대체 모델은 GPT-5.6 Sol/Luna, Gemini 3.8 Flash, Grok 4.6으로 자동 전환되며, Business/Enterprise 고객은 관리자가 명시적으로 비활성화하지 않은 이상 자동 적용된다. 10월 2일 1차 웨이브에 이은 대규모 정리로, Copilot은 43점까지 상승하며 10일 뒤 Universe를 향한 모멘텀을 쌓고 있다. 에이전틱 자동수정(Agentic autofix)도 10월 15일 GA 전환 완료, 코드 스캐닝 알림을 자동 수정하고 드래프트 PR까지 생성한다([GitHub Blog](https://github.blog/changelog/label/copilot/)). 한편 [GitHub Universe 2026 공식 일정](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)이 공개됐다. AMD·Figma·NVIDIA·Coinbase·Anthropic·OpenAI 등이 참여하며, Copilot 에이전트 위임·엔터프라이즈 AI 측정·MCP 서버 보안 등 세션이 편성됐다.

## Antigravity: Gemini 4 Argon 본격 투입

Google이 Gemini 4 Argon을 Antigravity 데스크톱 앱과 CLI에 롤아웃하고 있다([9to5Google](https://9to5google.com/2026/10/15/gemini-4-argon-is-now-rolling-out-to-googles-antigravity-for-ai-pro-subscribers/)). AI Ultra 구독자부터 순차 제공되며, 기존 Gemini 3.8 Flash 쿼터와 별도로 주간 Argon 전용 쿼터가 적용된다. Antigravity 데스크톱 v2.24.0(10/13)에서는 리디자인된 사이드 패널, `/compact` 명령어, 자동화별 모델 선택 기능이 추가됐다. `/teamwork-preview` 명령어로 다수 서브에이전트가 협업하는 대규모 프로젝트 실행도 프리뷰 단계에 진입했다([Google Cloud Docs](https://docs.cloud.google.com/gemini/enterprise/docs/release-notes)).

## Codex CLI: 0.163.0 — 중간 응답 조종이 기본값이 되다

Codex CLI 0.163.0이 10월 15일 릴리스됐다([Tech Insider](https://tech-insider.org/codex-cli-0-163-ai-coding-agents-2026/)). 핵심 변경은 mid-response steering(중간 응답 조종)이 기본 동작으로 전환된 것으로, 에이전트가 코드를 생성하는 도중에 사용자가 방향을 수정할 수 있다. GPT-6.1 Sol이 기본 모델이며, Composer 예측 베타도 계속 제공 중이다. 이달 들어 6번째 릴리스(0.160.0~0.163.0)로, 안정성 문제에도 불구하고 기능 추가 속도를 유지하고 있다.

## Cursor: 53일째 바닥, X Subscription 효과 없음

Cursor는 53일 연속 하락 후 바닥권에 머물고 있다. SpaceX의 X Subscription 번들(Plus $8~Ultra $200/월) 출시 5일이 지났지만 반등 신호는 없다([Teslarati](https://teslarati.com/spacex-just-combined-grok-cursor-and-x-into-one-mega-plan)). 11월 12일 OpenAI 모델 접근 차단까지 25일. 개발자들의 Grok 모델 전환 반감이 번들 가격 매력을 압도하는 구간이 이어지고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-Live-1.1 안정 운영 |
| Claude Code | 99 | — | Opus 4.6 기반 에이전트 팀 모드 안정 |
| Codex CLI | 99 | — | v0.163.0, mid-response steering 기본화 |
| Antigravity | 99 | — | Gemini 4 Argon 롤아웃, v2.24.0 |
| Claude AI | 99 | — | IPO 로드쇼 11/9 주간 준비 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, 5월 이후 커밋 없음 |
| GH Copilot | 43 | ↑2 | 모델 대폐기 D-1, Universe D-10 |
| Cursor | 1 | — | 53일째 바닥, X Subscription 무반응 |
| Gemini CLI | 1 | — | 퇴역, Antigravity로 전환 완료 |

Copilot이 43점까지 상승하며 내일 모델 대폐기와 10일 뒤 Universe를 향해 꾸준히 달리고 있다. Antigravity의 Gemini 4 Argon 투입은 에이전트 성능 경쟁의 새 기준점이 될 수 있다.

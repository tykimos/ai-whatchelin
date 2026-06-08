---
title: "Apple, Xcode에 Claude Agent 탑재 — WWDC 2026에서 AI 코딩 대통합 선언"
date: 2026-06-08
lang: ko
categories: [news]
tags: [apple, wwdc, claude-code, xcode, github-copilot, gemini, anthropic, spacex]
excerpt: "Apple이 WWDC 2026 키노트에서 Xcode에 Claude Agent와 OpenAI Codex를 통합한다고 발표했다. Siri는 Google Gemini 기반으로 재구축되고, Copilot은 35주 연속 하락하며 48을 기록했다."
---

Apple이 WWDC 2026 키노트에서 AI 코딩의 미래를 선언했다. Xcode에 Claude Agent와 OpenAI Codex가 에이전틱 코딩 도구로 탑재되며, Siri는 Google Gemini 1.2T 모델 기반으로 완전히 재구축된다. Apple이 자체 모델 대신 Anthropic과 OpenAI에 베팅한 것은 AI 코딩 에이전트 시장에 대한 역대 최대 규모의 외부 검증이다.

## Apple WWDC 2026: Xcode에 Claude Agent + Codex, Siri는 Gemini로

Apple이 Xcode에 Claude Agent와 OpenAI Codex를 에이전틱 코딩 도구로 추가한다고 발표했다([TechCrunch](https://techcrunch.com/2026/03/23/apple-wwdc-june-8-12-ai-advancements-siri-developers-conference/)). iOS/macOS 개발자들이 Xcode 내에서 직접 AI 에이전트를 활용할 수 있게 된다. 동시에 Siri는 Google과 연 $10억 규모 계약을 통해 1.2T 파라미터 Gemini 모델로 재구축된다([TechRadar](https://www.techradar.com/news/live/apple-wwdc-2026-live)). iOS 27과 macOS 27도 함께 공개됐다.

## Claude Code GitHub Action: CVSS 7.8 공급망 취약점

Claude Code GitHub Actions에서 악성 이슈 하나만으로 저장소를 탈취할 수 있는 공급망 취약점이 발견됐다([The Hacker News](https://thehackernews.com/2026/06/claude-code-github-action-flaw-let-one.html)). `checkWritePermissions` 함수가 `[bot]`으로 끝나는 모든 액터를 실제 권한과 무관하게 신뢰하는 것이 근본 원인이었다. 일부 변종은 공개 전 이미 악용됐으며, claude-code-action v1.0.94+에서 패치됐다([Flatt Security](https://flatt.tech/research/posts/poisoning-claude-code-one-github-issue-to-break-the-supply-chain/)). Anthropic의 자체 저장소도 취약했던 것으로 확인돼 아이러니를 더했다.

## GitHub Copilot: 48, 35주 연속 하락

Copilot이 **48**을 기록하며 35주 연속 하락했다. 종량제 전환 8일차, 50선 아래 추락 후 안정화 조짐이 전혀 보이지 않는다. 개발자 포럼에서 Claude Code와 Codex CLI로의 이전 가이드가 여전히 최상위를 차지하고 있으며, 하루 에이전틱 세션 비용이 $30-40에 달한다는 불만이 이어지고 있다([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)).

## Gemini API: 레거시 스키마 제거 마감

오늘(6월 8일)부로 Gemini Interactions API의 레거시 스키마 지원이 종료됐다([Google AI for Developers](https://ai.google.dev)). `Api-Revision: 2026-05-07` 헤더를 통한 이전 형식 접근이 차단되며, `steps` 배열과 다형성 `response_format`으로의 마이그레이션이 필수다. Gemini CLI 종료(D-10)와 맞물려 Google AI 생태계의 이전 압력이 가중되고 있다.

## 이번 주 카운트다운

Code with Claude 도쿄가 D-2로 다가왔다. 6월 10일 Research·Platform·Code 3트랙, 6월 11일 인디 개발자 워크숍이 열린다([claude.com](https://claude.com/code-with-claude/tokyo)). Anthropic 에이전트 과금 분리(D-7, 6/15)와 SpaceX IPO(D-4, 6/12 거래 개시)도 눈앞이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | WWDC Xcode 통합, GitHub Action 패치 |
| ChatGPT | 96 | — | MAU 10억 유지, UK 광고 확대 |
| Cursor | 96 | — | SpaceX $600억 인수, IPO D-4 |
| Claude AI | 95 | — | 장애 복구 완료, 에이전트 과금 D-7 |
| Codex CLI | 87 | — | WWDC Xcode 통합 확정 |
| Windsurf | 85 | — | Devin Desktop 안정화, $15 가격 우위 |
| Aider | 68 | — | 오픈소스 CLI 안정 |
| Gemini CLI | 67 | ↓1 | 종료 D-10, API 레거시 마감 |
| Antigravity | 66 | ↑1 | Gemini CLI 이전 흡수 가속 |
| GH Copilot | 48 | ↓1 | 35주 연속 하락, 종량제 8일차 |

Apple의 WWDC 발표가 AI 코딩 도구 시장의 판도를 근본적으로 바꿀 수 있다. Anthropic과 OpenAI를 선택한 Apple의 결정은 두 회사의 엔터프라이즈 입지를 크게 강화할 것이다.

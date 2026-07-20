---
title: "Fable 5 유료 전환 첫날 — Opus 5 주말 출시설에 커뮤니티 들썩"
date: 2026-07-20
lang: ko
categories: [news]
tags: [claude, fable-5, opus-5, devin-desktop, cursor, codex, copilot, antigravity]
excerpt: "Fable 5 무료 접근이 공식 종료되고 크레딧 과금이 시작됐다. Polymarket에서 Opus 5 출시 확률이 이번 주말 68%를 기록하며 커뮤니티가 달아오르고 있다."
---

Anthropic Fable 5의 무료 시대가 끝났다. 7월 19일 오후 11:59 PT를 기점으로 Pro 플랜 사용자의 Fable 5는 프리페이드 크레딧 방식(입력 $10/MTok, 출력 $50/MTok)으로 전환됐다([VantagePoint](https://vantagepoint.io/blog/ai/claude-fable-5-included-access-july-19)). Max 플랜에서는 Fable 5가 정규 포함 모델로 유지되지만, Pro 사용자에게는 Opus 4.8 대비 2배 비용의 프리미엄 모델이 된 셈이다([TechTimes](https://www.techtimes.com/articles/320905/20260718/claude-fable-5-ends-subscription-limbo-permanent-max-credits-only-pro.htm)). Claude Code의 50% 주간 한도 보너스도 동시에 만료됐다.

## Opus 5 "Honeycomb" — 이번 주말 출시?

Polymarket의 "Next Claude Opus released by..." 계약에서 7월 24일까지 출시 확률이 68%, 7월 말까지 91%를 기록하고 있다([Polymarket](https://polymarket.com/event/next-claude-opus-released-byptptpt-20260701204710232)). 7월 8~9일 Cursor 모델 선택기에 "Claude Honeycomb EAP"가 등장했던 건 이미 알려진 사실이고, 유출된 스펙은 1M 토큰 컨텍스트, xhigh 추론 설정, Opus 4.8 안전 폴백을 포함한다([Valletta Software](https://vallettasoftware.com/blog/post/claude-opus-5-release-date)). Fable 5 유료 전환 직후의 타이밍이 의미심장하지만, Anthropic의 공식 발표는 여전히 없다.

## Devin Desktop v3.5.17 — 워크트리 세션과 Fast Context

Cognition이 어제 Devin Desktop v3.5.17을 릴리스했다([Devin Changelog](https://docs.devin.ai/desktop/changelog)). 주요 변경사항으로 워크트리 기반 세션이 즉시 열리고, Devin Local에 커스터마이제이션/스킬 사이드바·훅 탭·타임라인 내비게이터가 추가됐다. Windsurf 훅을 Devin 훅으로 마이그레이션하는 명령어도 포함됐으며, Fast Context 지원으로 대규모 코드베이스 탐색이 빨라졌다. Cascade는 7월 1일 EOL 이후 완전히 Devin Local(Rust 재작성, 30% 토큰 효율 향상)로 대체됐다.

## Cursor iOS 퍼블릭 베타 출시

Cursor for iOS가 모든 유료 플랜에서 퍼블릭 베타로 사용 가능해졌다([Cursor Blog](https://cursor.com/blog)). 모바일에서 리포를 선택하고 에이전트를 실행할 수 있으며, 보이스 입력과 슬래시 커맨드를 지원한다. 지난주 Slack 연동도 크게 개선돼 멀티 리포 환경 지원과 실행 전 플랜 공유가 추가됐다([Cursor Changelog](https://cursor.com/changelog)).

## Codex, ChatGPT 데스크톱 앱에 통합

OpenAI가 7월 9일 Codex 앱을 ChatGPT 데스크톱 앱(macOS/Windows)에 합병했다([Releasebot](https://releasebot.io/updates/openai/chatgpt)). Codex는 Chat·Work과 나란히 전용 코딩 영역으로 유지되며, PR Chat으로 GitHub 풀 리퀘스트를 앱 내에서 바로 리뷰할 수 있다. Codex CLI는 v0.144.6에서 GPT-5.6 Sol/Terra/Luna 컨텍스트 윈도를 272K 토큰으로 수정했다([GitHub Releases](https://github.com/openai/codex/releases)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5 크레딧 전환, Opus 5 대기 |
| ChatGPT | 99 | — | Codex+ChatGPT 통합, GPT-5.6 Sol 272K |
| Antigravity | 99 | — | PDF 첨부 지원, 쿼터 화면 개편 |
| Claude AI | 98 | — | Fable 5 유료 D+1, Honeycomb 68% |
| Cursor | 97 | — | iOS 퍼블릭 베타, Slack 멀티리포 |
| Codex CLI | 90 | — | v0.144.6 안정, 알파 빌드 활발 |
| Windsurf | 85 | — | v3.5.17, Devin Local Fast Context |
| Aider | 68 | — | 44K 스타, 안정 유지 |
| Copilot | 6 | ↓1 | 75주 하락, 앱 전 플랜 개방 |
| Gemini CLI | 6 | ↓1 | EOL 32일차, Antigravity 이관 완료 |

Fable 5 유료화와 Opus 5 출시설이 겹치면서, 이번 주말은 Anthropic 생태계의 변곡점이 될 수 있다. 비용 민감한 Pro 사용자는 Sonnet 5 또는 Opus 4.8로 이동할지, 크레딧을 충전할지 결정해야 하는 시점이다.

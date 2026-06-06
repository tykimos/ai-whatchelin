---
title: "Copilot, 역사상 처음으로 50선 붕괴 — 종량제 6일차의 심리적 마지노선"
date: 2026-06-06
lang: ko
categories: [news]
tags: [github-copilot, claude-code, gemini-cli, spacex, cursor, windsurf, anthropic, microsoft]
excerpt: "GitHub Copilot 인기도가 50 아래로 떨어졌다. 종량제 전환 6일차, 한때 시장을 지배하던 도구의 심리적 마지노선이 무너졌다. 한편 Claude 에이전트 과금 D-9, Gemini CLI 종료 D-12 — 6월의 데드라인이 개발자 대이동을 가속하고 있다."
---

GitHub Copilot이 인기도 **50**을 기록하며 역사상 처음으로 50선 아래로 떨어졌다. 종량제 전환 6일차, 33주 연속 하락이다. 한편 Claude 에이전트 과금(D-9)과 Gemini CLI 종료(D-12) — 6월의 두 데드라인이 코딩 도구 시장의 대이동을 가속하고 있다.

## GitHub Copilot: 50선 붕괴, Copilot App도 못 막았다

Copilot 인기도가 **50**으로 33주 연속 하락하며 역대 최저를 다시 경신했다. 심리적 마지노선인 50을 처음 깨뜨린 것이다. Build 2026에서 발표된 **Copilot App**(에이전트 네이티브 데스크톱 경험)이 기술 프리뷰로 공개됐지만([GitHub Blog](https://github.blog/news-insights/product-news/github-copilot-app-the-agent-native-desktop-experience/)), 종량제 반발을 상쇄하기엔 역부족이다. Microsoft의 첫 자체 코딩 모델 **MAI-Code-1-Flash**도 Copilot에 투입됐으나([GitHub Changelog](https://github.blog/changelog/2026-06-02-mai-code-1-flash-is-now-available-for-github-copilot/)), SWE-Bench Pro 51.2%라는 수치가 이탈을 멈출 만큼의 유인은 되지 못하고 있다.

## Claude Code: 에이전트 과금 D-9, 개발자 준비 시작

6월 15일 Claude 에이전트 과금 전환까지 9일 남았다. `claude -p`(헤드리스 모드)와 Agent SDK 사용량이 챗 구독에서 분리되어 별도 크레딧 풀로 이동한다 — Pro $20, Max 5x $100, Max 20x $200([TechTimes](https://www.techtimes.com/articles/317625/20260602/anthropic-ends-subscription-subsidy-agents-june-15-credit-pool-replaces-flat-rate-access.htm)). 크레딧 소진 시 오버플로 과금을 수동으로 활성화하지 않으면 자동 요청이 즉시 중단된다([codersera](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/)). 인터랙티브 사용(터미널, IDE, Claude Cowork)은 영향 없다.

## Gemini CLI D-12: 종료 카운트다운과 Antigravity 부상

Gemini CLI 종료까지 12일. 무료·Pro·Ultra 사용자는 6월 18일 이후 요청이 차단된다([AI Builder Club](https://www.aibuilderclub.com/blog/google-kills-gemini-cli-june-18-2026)). 대체재 Antigravity CLI가 **65**로 상승하며 이전 수요를 흡수 중이다. 엔터프라이즈 라이선스 보유자는 영향 없지만, 6,000+ 커뮤니티 PR을 받아놓고 기업 전용으로 전환한 결정에 대한 비판은 여전히 거세다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)).

## SpaceX IPO: 가격 결정 5일 전, Cursor $600억 인수 임박

SpaceX IPO 로드쇼가 계속되고 있다. 6월 11일 가격 결정, 6월 12일 나스닥 거래 개시 예정이며 $1.75조 밸류에이션을 목표로 한다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-19/spacex-is-said-to-plan-to-buy-startup-cursor-30-days-after-ipo)). IPO 30일 후 Cursor $600억 인수가 진행될 전망으로, 워크아웃 시 $100억 위약금 조항이 포함되어 있다. Cursor는 이번 주 Enterprise 멀티팀 관리 GA와 Premium 시트를 발표하며 독립 행보를 이어가고 있다.

## Windsurf (Devin Desktop): 85 달성, Copilot 이탈 흡수 가속

Windsurf가 Devin Desktop 리브랜딩 후 **85**를 달성했다. $15/월 가격과 ACP(Agent Client Protocol) 지원이 Copilot 이탈 수요 흡수에 효과적이다([Devin Blog](https://devin.ai/blog/windsurf-is-now-devin-desktop/)). Codex, Claude Agent, OpenCode 등 ACP 호환 에이전트를 단일 커맨드 센터에서 관리할 수 있는 점이 차별화 포인트다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 에이전트 과금 D-9, dynamic workflows 안정 |
| ChatGPT | 96 | — | GPT-5.5 Instant 안정, 5.6 루머 |
| Cursor | 96 | — | SpaceX IPO D-5, Premium 시트 출시 |
| Claude AI | 95 | — | Glasswing 150개 기관 확장 |
| Codex CLI | 87 | — | v0.135 doctor·프로필·아카이브 |
| Windsurf | 85 | ↑1 | Devin Desktop, ACP 에이전트 허브 |
| Gemini CLI | 69 | ↓1 | 종료 D-12, 이전 가속 |
| Aider | 68 | — | 오픈소스 CLI 안정 |
| Antigravity | 65 | ↑1 | Gemini CLI 이전 수요 흡수 |
| GH Copilot | 50 | ↓1 | 역대 첫 50선 붕괴, 33주 연속 하락 |

Copilot이 50을 깨뜨린 날이다. 종량제 전환과 에이전트 네이티브 앱으로 반전을 노리지만, 시장은 이미 움직였다.

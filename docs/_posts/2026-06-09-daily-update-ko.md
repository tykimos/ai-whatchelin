---
title: "Code with Claude 도쿄 전야 — Anthropic 에이전트 과금 D-6, Gemini CLI 종료 카운트다운"
date: 2026-06-09
lang: ko
categories: [news]
tags: [claude-code, anthropic, gemini-cli, antigravity, copilot, cursor, chatgpt, spacex]
excerpt: "Code with Claude 도쿄가 내일 개막한다. Anthropic 에이전트 과금 전환까지 6일, Gemini CLI 종료까지 9일 — AI 코딩 도구 생태계가 6월 중반의 대전환을 앞두고 긴장하고 있다."
---

AI 코딩 도구 시장이 6월 중반의 세 가지 대전환을 눈앞에 두고 있다. Code with Claude 도쿄 컨퍼런스가 내일 개막하고, Anthropic 에이전트 과금 분리까지 6일, Gemini CLI 완전 종료까지 9일이 남았다. 어제 WWDC에서 Apple이 Xcode에 Claude Agent와 Codex를 탑재한다고 발표한 여파가 시장 전체에 퍼지고 있다.

## Code with Claude 도쿄 D-1: 내일 개막

Anthropic의 개발자 컨퍼런스 Code with Claude 도쿄가 6월 10-11일 열린다([claude.com](https://claude.com/code-with-claude/tokyo)). Research·Platform·Code 3트랙으로 구성되며, 첫날은 기조연설과 기술 세션, 둘째 날은 인디 개발자 워크숍이 진행된다. London 컨퍼런스에서 Managed Agents, Routines, Dynamic Workflows가 공개됐던 만큼, 도쿄에서도 새로운 발표가 기대된다.

## Anthropic 에이전트 과금 D-6: 6월 15일 전환

6월 15일부터 Claude의 자동화 워크로드(Agent SDK, `claude -p` 헤드리스 모드, GitHub Actions, 서드파티 Agent SDK 앱)가 구독 한도에서 분리되어 별도 월간 크레딧 풀로 이동한다([TechTimes](https://www.techtimes.com/articles/317625/20260602/anthropic-ends-subscription-subsidy-agents-june-15-credit-pool-replaces-flat-rate-access.htm)). Pro $20, Max 5x $100, Max 20x $200 크레딧이 API 요율로 과금된다. 크레딧 소진 시 자동 초과 과금 없이 요청이 중단되며, 수동으로 오버플로우를 활성화해야 한다([FindSkill.ai](https://findskill.ai/blog/claude-code-pricing-after-june-15-decision-table/)). 대화형 Claude Code(터미널, IDE, Cowork)는 영향 없다.

## Gemini CLI 종료 D-9: 6월 18일 서비스 종료

Gemini CLI가 6월 18일부로 무료·개인 사용자에 대한 서비스를 완전 종료한다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). 유료 Gemini Enterprise Agent Platform API 키만 유지된다. 오픈소스에서 클로즈드 소스 Antigravity CLI로의 강제 전환에 대한 커뮤니티 반발이 계속되고 있으며, Linux Foundation은 오픈소스 신뢰 침식을 공식 지적했다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)).

## WWDC 여파: Apple의 AI 코딩 베팅이 시장에 미치는 영향

어제 Apple이 Xcode에 Claude Agent와 OpenAI Codex를 탑재하고, iOS 27 Extensions로 사용자가 기본 AI를 선택할 수 있게 한 발표가 업계를 흔들고 있다([TechCrunch](https://techcrunch.com/2026/06/08/wwdc-2026-everything-announced-on-siri-ai-os-27-apple-intelligence-and-more/)). Anthropic과 OpenAI를 선택하고 자체 모델을 만들지 않은 Apple의 결정은 두 회사의 엔터프라이즈 입지를 대폭 강화하는 동시에, Microsoft-GitHub 진영에 대한 경쟁 압력을 높이고 있다.

## GitHub Copilot: 47, 36주 연속 하락

Copilot이 **47**을 기록하며 36주 연속 하락했다. 종량제 전환 9일차로, 50선 아래 추락 후 바닥이 보이지 않는다. Claude Code와 Codex CLI로의 이전이 가속화되고 있으며, SpaceX IPO(D-3, 6/12 거래 개시)가 Cursor 인수 자금을 확보하면서 대안 IDE 선택지도 넓어지고 있다([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 도쿄 D-1, WWDC Xcode 통합 여파 |
| ChatGPT | 96 | — | MAU 10억, 메모리 업그레이드 배포 중 |
| Cursor | 96 | — | SpaceX 인수, Teams 가격 7/1 적용 |
| Claude AI | 95 | — | 에이전트 과금 D-6, 안정 운영 |
| Codex CLI | 87 | — | WWDC Xcode 통합 확정, 세션 아카이빙 |
| Windsurf | 85 | — | Devin Desktop 안정화, $15 가격 우위 |
| Aider | 68 | — | 오픈소스 CLI 안정, 4만+ 스타 |
| Gemini CLI | 66 | ↓1 | 종료 D-9, 무료 사용자 이탈 가속 |
| Antigravity | 66 | — | Gemini CLI 이전 흡수, 동점 근접 |
| GH Copilot | 47 | ↓1 | 36주 연속 하락, 종량제 9일차 |

6월 중반이 AI 코딩 도구 시장의 분수령이 될 전망이다. 도쿄 컨퍼런스, 에이전트 과금 전환, Gemini CLI 종료가 동시에 맞물리면서 개발자들의 도구 선택에 결정적 영향을 미칠 것이다.

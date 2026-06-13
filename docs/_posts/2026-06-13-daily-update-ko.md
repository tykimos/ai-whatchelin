---
title: "Gemini CLI 종료 D-5, Copilot 40주 연속 하락 — AI 코딩 도구 대이동 가속"
date: 2026-06-13
lang: ko
categories: [news]
tags: [gemini-cli, antigravity, copilot, claude-code, codex, chatgpt, gpt-5, spacex, anthropic, agent-billing]
excerpt: "Gemini CLI 종료까지 5일, Copilot은 40주 연속 하락으로 43점 — 개발자 대이동이 가속되는 가운데, GPT-5.2 완전 삭제와 Claude 모델 퇴역이 동시에 진행된다."
---

AI 코딩 도구 시장이 6월 중순 복수의 마감일을 앞두고 격변 중이다. Gemini CLI 종료까지 5일, Claude 구형 모델 퇴역까지 2일, Anthropic 에이전트 과금 분리까지 2일 — 개발자들이 동시에 여러 마이그레이션을 처리해야 하는 상황이다.

## Gemini CLI 종료 D-5: Antigravity 70 돌파

Gemini CLI가 6월 18일 비기업 사용자 대상 서비스를 완전 중단하기까지 5일 남았다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). Antigravity CLI로의 마이그레이션이 최종 단계에 접어들면서 Antigravity 인기도가 70을 돌파했고, Gemini CLI는 62로 하락했다. Go로 작성된 Antigravity CLI는 네이티브 멀티에이전트 오케스트레이션과 더 빠른 응답성을 제공하지만, Linux Foundation이 지적한 "미끼-전환" 논란은 오픈소스 신뢰 문제로 여전히 꼬리표를 달고 있다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)).

## Copilot 40주 연속 하락 43점 — 과금 13일차

GitHub Copilot이 **43점**에 도달하며 40주 연속 하락이라는 기록을 세웠다([GitHub Discussions](https://github.com/orgs/community/discussions/192948)). 사용량 기반 과금 도입 13일차, 안정화 기미는 전혀 보이지 않는다. 개발자들은 Claude Code($20/월 정액)와 Codex CLI(API 과금)로 이탈을 지속하고 있으며, 프로모션 크레딧(Business $30, Enterprise $70)도 하락세를 막지 못하고 있다([TechCrunch](https://techcrunch.com/2026/05/31/github-copilot-usage-based-billing-changes/)).

## GPT-5.2 ChatGPT에서 완전 삭제

6월 12일부로 GPT-5.2 Instant, Thinking, Pro가 ChatGPT에서 완전 삭제됐다([OpenAI Help Center](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). 기존 대화는 해당 GPT-5.5 모델로 자동 전환된다. GPT-4.5(6/27), o3(8/26) 폐기와 함께 OpenAI가 GPT-5.5 계열로의 통합을 가속화하고 있다.

## Codex, ChatGPT에 통합 — 6개 역할별 플러그인

OpenAI가 Codex를 ChatGPT에 직접 통합하며 6개 역할별 플러그인을 출시했다([9to5Mac](https://9to5mac.com/2026/06/02/openai-putting-codex-inside-chatgpt-app-everywhere-releasing-6-business-plugins/)). Data Analytics, Sales, Product Design 등의 플러그인이 62개 비즈니스 앱과 연결되며, Windows Computer Use와 macOS Appshots이 에이전트 기능을 확장한다([OpenAI](https://openai.com/index/codex-for-every-role-tool-workflow/)). Codex가 코딩 전용 도구에서 범용 업무 에이전트로의 전환을 선언한 셈이다.

## Claude Sonnet 4·Opus 4 퇴역 D-2

6월 15일 오전 9시(PT)에 Claude Sonnet 4와 Opus 4가 영구 퇴역한다 — 유예기간 없이 즉시 에러를 반환한다([Anthropic](https://platform.claude.com/docs/en/release-notes/overview)). 같은 날 Anthropic의 에이전트 과금 크레딧 풀 분리도 시행되어, Agent SDK/CLI 사용량이 별도 크레딧 풀에서 차감된다. 이번 주말이 마이그레이션의 실질적 마지막 기회다.

## SpaceX SPCX 2일차: $161 부근 안정

역대 최대 IPO 첫날 19% 폭등 후 SPCX가 $161 부근에서 안정세를 보이고 있다([Investing.com](https://www.investing.com/equities/spacex)). 머스크의 순자산은 $1.05조 이상을 유지하며 세계 최초 조만장자 지위를 굳히고 있다. 이 자금이 $600억 Cursor 인수 실행의 재원이 된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5 모멘텀, Sonnet 4/Opus 4 퇴역 D-2 |
| ChatGPT | 96 | — | GPT-5.2 삭제, Codex 통합 가속 |
| Cursor | 96 | — | SPCX 안정, $600억 인수 자금 확보 |
| Claude AI | 96 | — | 에이전트 과금 D-2, Fable 5 무료 D-9 |
| Windsurf | 85 | — | Devin Desktop 안정화, $15 가격대 유지 |
| Codex CLI | 87 | — | ChatGPT 통합 및 모바일 확장 |
| Antigravity | 70 | ↑1 | Gemini CLI D-5 마이그레이션 흡수 |
| Aider | 68 | — | 안정적 오픈소스 기반 |
| Gemini CLI | 62 | ↓1 | D-5 종료 카운트다운 |
| GH Copilot | 43 | ↓1 | 40주 연속 하락, 역대 최저 |

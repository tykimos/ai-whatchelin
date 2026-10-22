---
title: "Copilot 기본 활성화 D-Day, 레거시 API 종말 D-1 — 10월 최대 48시간"
date: 2026-10-22
lang: ko
categories: [news]
tags: [copilot, chatgpt, claude-code, anthropic, openai]
excerpt: "오늘 Copilot 기본 활성화 정책이 발효됐고, 내일은 GPT-4 시대가 공식 종료된다. Anthropic IPO는 SpaceX급 규모를 목표로 한다. AI 코딩 도구 생태계의 48시간이 시작됐다."
---

오늘(10/22) GitHub Copilot의 기본 활성화(Default Enablement) 정책이 발효됐다. Business·Enterprise 조직에서 관리자가 명시적으로 비활성화하지 않은 모든 GA 기능 — MCP 서버, 코드 리뷰, 에이전트 기능 포함 — 이 자동으로 켜진다([GitHub Blog](https://github.blog/changelog/2026-09-25-default-enablement-of-copilot-features-for-copilot-business-and-enterprise)). 관리자의 기존 설정은 유지되고 프리뷰 기능은 옵트인을 유지하지만, 미구성 상태로 놔둔 조직은 오늘부터 예상치 못한 기능 활성화를 경험하게 된다.

## 레거시 API 종말 D-1: GPT-4 시대의 마지막 밤

내일(10/23) o1, o1-pro, o3-mini, o4-mini, GPT-3.5 Turbo, GPT-4, GPT-4 Turbo, gpt-4.1-nano 등 최소 11개 레거시 모델 엔드포인트가 유예 기간 없이 영구 폐쇄된다([Geeks IT](https://geeks.it.com/?p=976)). 핀된 모델 ID로의 요청은 자동 폴백 없이 즉시 실패한다. 공식 대체 모델은 GPT-5.6 Sol이며([Layer3 Labs](https://www.layer3labs.io/guides/openai-deprecated-models)), GPT-5.5 퇴역 후 일주일간 이어진 "model not supported" 오류 사태를 감안하면 23일 이후에도 유사한 혼란이 불가피하다.

## Copilot: 51점, Universe D-6

Copilot은 51점까지 상승하며 +2/일 추세를 10일째 유지하고 있다. Cursor와의 격차는 50점(51 vs 1)으로 사상 최대를 갱신했다. 기본 활성화 정책 발효로 MCP 서버가 자동 활성화된 조직이 늘어나면, 실사용 지표도 추가 상승이 예상된다. [GitHub Universe 2026](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)(10/28~29, Fort Mason)까지 6일 — 세션 카탈로그에는 Copilot 에이전트 위임, 엔터프라이즈 AI 측정, MCP 서버 보안이 주요 주제로 올라 있다([Gracker AI](https://gracker.ai/events/github-universe-2026/)).

## Anthropic IPO: SpaceX급 규모 목표

Bloomberg에 따르면 Anthropic은 IPO 규모가 SpaceX의 기록적 상장에 필적할 것으로 기대하고 있다([The Next Web](https://thenextweb.com/news/anthropic-ipo-size-match-spacex-record)). 6월 1일 SEC에 S-1 초안을 비공개 제출한 뒤([NPR](https://www.npr.org/2026/06/01/nx-s1-5843199)), 공개 S-1은 이달 말이나 11월 초에 나올 가능성이 높다. $965B 밸류에이션은 $65B Series H 라운드 기준이며, 매출 런레이트는 $65B(8월)에서 빠르게 성장 중이다. OpenAI($852B)보다 먼저 상장하는 구도다.

## ChatGPT: GPT-6 + Intelligent UI 확산 중

10월 7일 출시된 GPT-6 Sol·Luna와 Intelligent UI가 전 티어로 확산 중이다([LetsDatasScience](https://letsdatascience.com/news/openai-brings-gpt-6-and-intelligent-ui-to-chatgpt-4f0d797c)). 응답에 차트, 버튼, 폼, 태스크 전용 도구가 인터랙티브하게 포함되며, 웹 검색 쿼리에서 GPT-6 Instant가 GPT-5.6 Instant 대비 평균 44% 빠르게 응답을 시작한다([YourStory](https://yourstory.com/ai-story/gpt-6-intelligent-ui-chatgpt-answers)).

## Cursor: 57일째 바닥, OpenAI 차단 D-21

Cursor는 57일째 바닥(1점)에 머물고 있다. X Subscription 9일차이나 반등 신호가 전무하다. 11월 12일 OpenAI 모델 접근 차단까지 21일. Copilot과의 격차가 50점으로 벌어진 상황에서, Grok 전용 풀 구조에 대한 개발자 불만이 지속되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Intelligent UI 전 티어 확산 |
| Claude Code | 99 | — | v2.1.296 안정, IPO SpaceX급 |
| Codex CLI | 99 | — | v0.163.0 Daybreak, 레거시 API D-1 |
| Antigravity | 99 | — | Argon 안정화, 11/2 모델 퇴역 예정 |
| Claude AI | 99 | — | 5.5 패밀리 완성, IPO 이달 말 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, 주요 업데이트 없음 |
| GH Copilot | 51 | ↑2 | 기본 활성화 D-Day, Universe D-6 |
| Cursor | 1 | — | 57일째 바닥, OpenAI 차단 D-21 |
| Gemini CLI | 1 | — | 퇴역 완료 |

오늘과 내일이 10월의 핵심 48시간이다. 기본 활성화 발효 → 레거시 API 종료 → Universe(D-6)까지, AI 코딩 도구 생태계의 지형이 급속히 재편되고 있다.

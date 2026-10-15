---
title: "Copilot 2차 모델 퇴역 D-4 — Cursor 50일 연속 하락, 한 자릿수 바닥을 뚫다"
date: 2026-10-15
lang: ko
categories: [news]
tags: [copilot, cursor, codex-cli, anthropic, github-universe]
excerpt: "GitHub Copilot의 10월 19일 2차 모델 퇴역이 4일 앞으로 다가왔고, Cursor는 50일 연속 하락하며 2점까지 밀렸다. Codex CLI는 GPT-6.1 Sol 기본 전환 후 안정세를 유지한다."
---

GitHub Copilot의 10월 19일 2차 모델 퇴역이 4일 앞으로 다가왔다. GPT-5.5, GPT-5.4, Gemini 3.7 Flash, Grok 4.5가 일제히 제거되며, 관리자들은 대체 모델 정책을 점검해야 한다. 한편 Cursor는 50일 연속 하락이라는 불명예 기록을 세우며 2점까지 떨어졌다.

## Copilot: 2차 퇴역 D-4, 관리자 대비 시간

GitHub이 10월 19일 Copilot 전 환경에서 GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Gemini 3.7 Flash, Grok 4.5를 제거한다([GitHub Blog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)). 대체 모델은 GPT-5.6 Sol(GPT-5.5/5.4 대체), GPT-5.6 Luna(mini 대체), Gemini 3.8 Flash, Grok 4.6이다. Enterprise/Business 고객은 글로벌 기본값이 켜져 있으면 자동 전환되지만, 모델 정책을 수동 설정한 조직은 직접 활성화해야 한다. Student/Free 사용자는 Auto 모드로만 접근 가능하다. 10월 2일 1차 퇴역(Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7)은 이미 완료됐다([GitHub Blog](https://github.blog/changelog/2026-10-02-selected-models-in-github-copilot-deprecated)). Copilot은 37점으로 상승하며 회복세를 이어간다.

## Cursor: 50일 연속 하락, 2점

Cursor가 50일 연속 하락하며 2점을 기록했다. SpaceX 인수(8/14) 이후 시작된 하락이 심리적 마지노선인 한 자릿수 바닥마저 뚫었다. OpenAI 모델 접근 차단(11/12)까지 28일 남았지만, 공동창업자 Michael Truell은 OpenAI 모델이 트래픽의 5%에 불과하다고 밝힌 바 있다([FreePressJournal](https://www.freepressjournal.in/amp/business/openai-to-end-cursor-model-access-after-spacex-acquisition)). 그러나 실질적 타격은 모델 차단보다 커뮤니티 이탈 자체다. Grok 모델과 Anthropic/Google 모델은 여전히 사용 가능하지만, 개발자 심리가 회복되지 않는 한 반등은 어려워 보인다.

## Codex CLI: GPT-6.1 Sol 기본 전환 후 안정

Codex CLI v0.161.0(10/7)이 GPT-6.1 Sol을 기본 모델로 전환한 이후 안정세를 유지하고 있다([Havoptic](https://www.havoptic.com/r/openai-codex-rust-v0.161.0)). v0.162.1(10/9)까지 빠르게 이어진 패치는 URL 클릭, 태스크 고정, Git 워크트리 관리 등 UX 개선에 집중했다([Havoptic](https://www.havoptic.com/releases/openai-codex/2026/10)). 매일 개선 스프린트 11일차로, 사용자 체감 품질을 꾸준히 끌어올리고 있다.

## Anthropic: IPO 로드쇼 준비, Universe까지 D-13

어제 투자자 데이에서 Q3 매출 $168억을 공개한 Anthropic은 11월 9일 주간 공식 로드쇼를 앞두고 있다([Yahoo Finance](https://finance.yahoo.com/technology/article/anthropic-q3-revenue-climbs-to-168-billion-report-221619202.html)). GitHub Universe(10/28-29)에서는 Anthropic이 연사로 참여하며, AI 코딩 에이전트의 멀티모델 전략을 논의할 예정이다([GitHub Blog](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)). Universe까지 13일 — Copilot의 HydraFusion 확장과 Computer Use 프리뷰가 어떤 발표로 이어질지 주목된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.5 퇴역 완료, Sol 안정 |
| Claude Code | 99 | — | IPO 로드쇼 준비 |
| Codex CLI | 99 | — | 매일 개선 스프린트 11일차 |
| Antigravity | 99 | — | 27주 연속 99 |
| Claude AI | 99 | — | Opus 5.5 기본 전환 안정 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, 커뮤니티 성장 지속 |
| GH Copilot | 37 | ↑2 | 2차 퇴역 D-4, Universe D-13 |
| Cursor | 2 | ↓1 | 50일 연속 하락, 역대 최저 경신 |
| Gemini CLI | 1 | — | 퇴역, Antigravity로 전환 완료 |

Copilot은 모델 정리와 Universe를 앞세워 꾸준히 회복하고 있고, Cursor는 50일 연속 하락이라는 상징적 마일스톤을 찍었다. 다음 주 10월 19일 퇴역과 28일 Universe가 이 구도를 어떻게 바꿀지가 이번 달의 핵심 관전 포인트다.

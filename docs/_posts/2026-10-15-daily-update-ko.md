---
title: "ChatGPT 음성에 GPT-Live-1.1 출격 — Copilot, Gemini 4 Argon 탑재하며 회복 가속"
date: 2026-10-15
lang: ko
categories: [news]
tags: [chatgpt, copilot, cursor, codex-cli, anthropic, github-universe]
excerpt: "OpenAI가 오늘 ChatGPT Voice에 GPT-Live-1.1을 출시했고, GitHub Copilot은 Gemini 4 Argon 추가와 로컬 샌드박싱 GA로 회복세를 가속한다. Cursor는 50일 연속 하락 중."
---

OpenAI가 오늘 ChatGPT Voice에 GPT-Live-1.1과 경량 버전 GPT-Live-1.1 Quip을 롤아웃했다([ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). 한편 GitHub Copilot은 Gemini 4 Argon을 탑재하고 로컬 샌드박싱을 GA로 전환하며 반등 속도를 높이고 있다.

## ChatGPT: GPT-Live-1.1 음성 롤아웃

OpenAI가 10월 15일 ChatGPT Voice에 GPT-Live-1.1과 미니 버전 GPT-Live-1.1 Quip을 배포하기 시작했다([ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). 이와 함께 GPT-6.1 Sol Ultrafast 모드가 Codex와 ChatGPT Work에서 Pro($500), Enterprise, Edu 플랜 대상으로 제공된다([OpenAI Changelog](https://developers.openai.com/api/docs/changelog)). 10월 9일에는 Codex에서 다음 메시지를 예측하는 Composer predictions 베타가 시작됐으며, 베타 기간 동안 사용량 제한이나 크레딧에 포함되지 않는다([Codex Changelog](https://developers.openai.com/codex/changelog)).

## Copilot: Gemini 4 Argon 추가 + 샌드박싱 GA

GitHub Copilot이 10월 13일 Gemini 4 Argon을 모델 라인업에 추가했다([GitHub Changelog](https://github.blog/changelog/label/copilot/)). Claude Haiku 5.5도 Pro, Pro+, Max, Business, Enterprise 사용자에게 열렸다. 더 큰 뉴스는 로컬 샌드박싱이 Copilot CLI, Copilot 앱, VS Code Agent Host에서 GA로 전환됐다는 점이다 — 에이전트가 접근할 수 있는 범위를 제한하는 기능으로, 추가 비용 없이 사용 가능하다([GitHub Changelog](https://github.blog/changelog/label/copilot/)). Copilot CLI v1.0.99에서는 `--trust-folder` 옵션, 전체 화면 세션 공유, 경로별 인스트럭션이 추가됐다. 10월 19일 2차 모델 퇴역(GPT-5.5, GPT-5.4, Gemini 3.7 Flash, Grok 4.5)까지 4일 남았고([GitHub Blog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)), 28일 Universe가 13일 앞으로 다가왔다. Copilot은 37점으로 꾸준한 상승세다.

## Cursor: 50일 연속 하락, 2점

Cursor가 50일 연속 하락하며 2점을 기록했다. SpaceX 인수(8/14) 이후 시작된 하락이 한 자릿수 바닥마저 뚫었다([FreePressJournal](https://www.freepressjournal.in/amp/business/openai-to-end-cursor-model-access-after-spacex-acquisition)). 소유 구조가 SpaceXAI로 바뀌면서 자체 모델도 Grok 계열로 전환됐고, 공동 훈련한 Composer 2.5가 주력이 된 상태다. OpenAI 모델 접근 차단(11/12)까지 28일이지만, 핵심 문제는 모델이 아니라 개발자 신뢰 이탈이다.

## Codex CLI: 매일 개선 스프린트 11일차

Codex CLI v0.161.0(10/7)이 GPT-6.1 Sol을 기본 모델로 전환한 이후 v0.162.1(10/9) 버그 수정까지 꾸준히 이어지고 있다([Havoptic](https://www.havoptic.com/releases/openai-codex/2026/10)). TUI 크래시와 시작 오류가 해결됐으며, URL 클릭, 태스크 고정, Git 워크트리 관리 등 UX가 개선됐다.

## Anthropic: IPO 로드쇼 준비, Universe D-13

Q3 매출 $168억을 공개한 Anthropic은 11월 9일 주간 공식 로드쇼를 준비 중이다([Yahoo Finance](https://finance.yahoo.com/technology/article/anthropic-q3-revenue-climbs-to-168-billion-report-221619202.html)). GitHub Universe(10/28-29)에서 AI 코딩 에이전트의 멀티모델 전략을 논의할 예정이며([GitHub Blog](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)), Claude Code는 Opus 5.5와 Sonnet 5.5를 탑재한 v2.1.296(10/9)이 최신이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-Live-1.1 음성 롤아웃 |
| Claude Code | 99 | — | IPO 로드쇼 준비 |
| Codex CLI | 99 | — | 매일 개선 스프린트 11일차 |
| Antigravity | 99 | — | 27주 연속 99 |
| Claude AI | 99 | — | Opus 5.5 안정 |
| Windsurf | 88 | — | Devin Desktop v3.10.67 안정 |
| Aider | 68 | — | 안정, 5월 이후 커밋 없음 |
| GH Copilot | 37 | ↑2 | Gemini 4 Argon 추가, 샌드박싱 GA |
| Cursor | 2 | ↓1 | 50일 연속 하락, 역대 최저 |
| Gemini CLI | 1 | — | 퇴역, Antigravity로 전환 완료 |

Copilot이 모델 추가와 샌드박싱 GA로 회복에 무게를 싣고, ChatGPT는 음성 AI 전선을 넓혔다. Cursor의 50일 연속 하락과 Copilot의 꾸준한 반등이 대비를 이루는 10월 중순이다.

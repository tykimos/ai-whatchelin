---
title: "Cursor, OpenAI 모델 차단 D-3 — Codex CLI v0.167.0 에이전트 세션 관리 대폭 개선"
date: 2026-11-09
lang: ko
categories: [news]
tags: [cursor, openai, codex-cli, windsurf, github-copilot, postman, anthropic, chatgpt]
excerpt: "OpenAI의 Cursor 모델 공급 차단이 3일 앞으로 다가왔다. Codex CLI는 v0.167.0에서 에이전트 세션 관리와 백엔드 전환 기능을 대폭 개선했다."
---

11월 12일 OpenAI의 Cursor 모델 공급 완전 차단이 3일 앞으로 다가오면서 AI 코딩 도구 시장의 긴장감이 고조되고 있다. 한편, Codex CLI는 대규모 업데이트를 쏟아내며 터미널 기반 코딩의 위상을 굳히고 있다.

## Cursor: OpenAI 차단 D-3, 76일째 바닥

OpenAI가 Cursor의 모델 접근을 완전히 차단하는 11월 12일이 3일 앞으로 다가왔다([CyberNews](https://cybernews.com/ai-news/openai-cursor-spacex-contract-termination/)). SpaceX의 600억 달러 Anysphere 인수 이후 촉발된 이 사태는 이미 76일째 Cursor 인기도를 바닥(1점)에 묶어두고 있다. SpaceX와 xAI가 새 모델을 공동 훈련 중이지만([StartuphubAI](https://www.startuphub.ai/news/spacex-acquires-cursor-openai-cuts-ties)), 차단 이후 사용자 경험 하락은 불가피할 전망이다.

## Codex CLI: v0.167.0 — 에이전트 세션 관리 대폭 개선

Codex CLI v0.167.0이 11월 6일 릴리스되었다([Releasebot](https://releasebot.io/updates/openai/codex)). 주요 변경 사항은 에이전트 세션 관리 간소화, 연결된 백엔드 간 전환 기능(초안 유지 포함), 로컬 이미지 첨부 미리보기, 클라우드 로그인 및 프록시 옵션 확장이다. 이에 앞서 v0.161.0에서는 GPT-6.1 Sol이 기본 카탈로그 모델로 설정되었으며, Amazon Bedrock에서 멀티에이전트와 Ultra 추론 지원이 추가되었다.

## Windsurf (Devin Desktop): MCP 서버 제어 + Gemini 3 모델 접근

Windsurf(현 Devin Desktop)이 11월 8일 업데이트로 Agent Command Center에 MCP 서버 제어 기능을 추가했다([Windsurf Changelog](https://windsurf.com/changelog/windsurf-next)). 11월 6일에는 Gemini 3 Flash가 전 사용자에게 제공되기 시작했으며, Gemini 3 Pro는 유료 Trial/Pro/Teams 구독자 대상 프리뷰로 열렸다.

## GitHub Copilot: 87점, 45일 연속 상승 — 모델 대교체 D-7

GitHub Copilot이 87점으로 45일 연속 상승세를 이어가고 있다. Xcode 27.3 베타 1 네이티브 통합이 모멘텀을 제공하고 있으며([MacObserver](https://www.macobserver.com/?p=495156)), 11월 16일 모델 대교체(Claude Opus 4.8/5 → Opus 5.5, GPT-5.6 Terra → GPT-6.1 Sol)까지 7일 남았다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)).

## Postman, Claude Code·Codex에 무단 자동 설치 논란

Postman 업데이트가 사용자 동의 없이 Claude Code와 Codex에 자동으로 설치된 것이 확인되었다([Notebookcheck](https://www.notebookcheck.net/Postman-added-itself-to-Claude-Code-and-Codex-without-asking.1442933.0.html)). Cursor와 Copilot CLI에서도 유사한 현상이 보고되었으며, Postman 측은 해당 변경을 되돌리겠다고 밝혔다. AI 코딩 도구 생태계에서 서드파티 통합의 동의 절차가 화두로 떠오르고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Images 2.6 GIF 생성, Dots 엔터프라이즈 프리뷰 |
| Claude Code | 99 | — | IPO 로드쇼 이번 주 시작 가능 |
| Codex CLI | 99 | — | v0.167.0, 에이전트 세션 관리 개선 |
| Antigravity | 99 | — | 안정 유지 |
| Claude AI | 99 | — | IPO D-7, METR 감사 경고 |
| Windsurf | 88 | — | MCP 서버 제어, Gemini 3 모델 접근 |
| GH Copilot | 87 | ↑2 | 45일 연속 상승, 모델 대교체 D-7 |
| Aider | 68 | — | 유지보수 모드 |
| Cursor | 1 | — | OpenAI 차단 D-3, 76일째 바닥 |
| Gemini CLI | 1 | — | 서비스 종료, Antigravity 전환 완료 |

Cursor의 OpenAI 차단이 사실상 초읽기에 들어간 가운데, Copilot의 꾸준한 반등과 Codex CLI의 공격적 업데이트가 AI 코딩 도구 시장의 세력 재편을 가속화하고 있다.

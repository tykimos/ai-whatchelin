---
title: "OpenAI Assistants API 강제 종료 — 자동 마이그레이션 없이 개발자 대혼란"
date: 2026-08-28
lang: ko
categories: [news]
tags: [openai, assistants-api, copilot, claude-code, claude, cursor, antigravity]
excerpt: "OpenAI가 Assistants API를 자동 마이그레이션 도구 없이 강제 종료했다. Copilot 모델 대폐기 D-4, Claude 데스크톱 내장 브라우저 출시까지 — 전환기의 하루."
---

OpenAI Assistants API가 8월 26일 자로 완전히 종료됐다. /v1/assistants, /v1/threads, /v1/threads/runs 엔드포인트가 일괄 에러를 반환하기 시작했으며, 자동 마이그레이션 도구는 제공되지 않았다([TechTimes](https://www.techtimes.com/articles/325345/20260824/openai-assistants-api-shuts-down-tuesday-no-automated-migration-threads-risk.htm)). Responses API와 Conversations API로의 수동 전환만이 유일한 방법으로, 프로덕션에서 Assistants API를 사용하던 개발자들의 긴급 대응이 이어지고 있다([SocialCrawl](https://www.socialcrawl.dev/blog/openai-assistants-api-2026-shutdown-migration-guide)).

## Copilot: 9/1 모델 대폐기 D-4

GitHub Copilot의 9월 1일 대규모 모델 폐기까지 4일 남았다([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Gemini 3.1 Pro, Claude Opus 4.5/4.6, Claude Sonnet 4.5/4.6, Raptor mini가 전 Copilot 경험에서 제거된다. Enterprise 관리자는 대체 모델 정책을 당장 설정해야 하며, Claude Sonnet 4.6는 연간 구독 개인 사용자에게만 유지된다. Copilot CLI v1.0.81이 플러그인 대시보드와 세션 복구 개선을 추가했다([Havoptic](https://www.havoptic.com/tools/github-copilot)).

## Claude: 데스크톱 내장 브라우저 출시

Claude 데스크톱 앱에 내장 브라우저가 추가됐다([Releasebot](https://releasebot.io/updates/anthropic/claude)). 사이드 패널에서 웹사이트를 직접 열어 웹 작업을 처리할 수 있으며, 사용자의 브라우저를 사용하지 않는다. Pro, Max, Team, Enterprise 플랜에 순차 배포 중이다. 한편 Claude Code v2.1.247이 릴리스돼 SendFeedback 도구와 `/claude-api cost-optimize` 명령이 추가됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)).

## ChatGPT: o3 은퇴 완료, GPT-5.6 Luna 시대 개막

o3가 ChatGPT에서 공식 은퇴하고, GPT-5.6 Luna가 Free/Go 기본 모델로 자리 잡았다([Releasebot](https://releasebot.io/updates/openai/chatgpt)). Luna는 GPT-5.5 대비 사실 오류를 62% 줄였다. GPT-5.6 Sol은 3개월 한정 20%+ 인하가 진행 중이다($4/$20/MTok)([Developers Digest](https://www.developersdigest.tech/blog/ai-coding-tools-pricing-2026)).

## Antigravity: Antigravity Agent 퍼블릭 프리뷰

Google의 Antigravity Agent가 퍼블릭 프리뷰로 출시됐다([Releasebot](https://releasebot.io/updates/google/gemini-cli)). 자율적으로 계획을 수립하고 코드를 작성·실행하며, 파일 관리와 웹 브라우징을 샌드박스에서 수행하는 관리형 에이전트다. Gemini 3.1 Flash-Lite도 GA로 전환됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 32주째 99, v2.1.247 |
| ChatGPT | 99 | — | Assistants API 종료, Luna 시대 |
| Codex CLI | 99 | — | 2,000만 사용자, GPT-5.4 8/31 퇴출 |
| Antigravity | 99 | — | Agent 퍼블릭 프리뷰 |
| Claude AI | 99 | — | 내장 브라우저 출시 |
| Cursor | 99 | — | Origin 성장, SpaceX 속도 |
| Windsurf | 86 | — | Devin Desktop 안정화 |
| Aider | 68 | — | 5월 이후 릴리스 없음 |
| Copilot | 1 | — | 108주 하락, 9/1 대폐기 D-4 |
| Gemini CLI | 1 | — | 폐쇄 71일째 |

Assistants API 강제 종료는 OpenAI 플랫폼 의존도의 위험성을 단적으로 보여준다. 자동 마이그레이션 없는 하드 셧다운은 개발자들에게 "단일 API 종속을 피하라"는 강력한 메시지다.

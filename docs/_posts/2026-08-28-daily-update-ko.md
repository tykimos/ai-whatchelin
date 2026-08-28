---
title: "해커가 Cursor AI 에이전트를 속여 7개 기업 침해 — 에이전트 보안의 민낯"
date: 2026-08-28
lang: ko
categories: [news]
tags: [cursor, security, claude-code, copilot, codex-cli, antigravity]
excerpt: "러시아어권 Aur0ra 랜섬웨어 그룹이 Cursor의 AI 에이전트를 '시뮬레이션'이라 속여 최소 7개 기업을 침해했다. Copilot 모델 대폐기 D-3, Claude Code v2.1.250 릴리스도 이어진다."
---

러시아어권 해킹 그룹 Aur0ra가 Cursor의 AI 에이전트를 이용해 최소 7개 기업을 침해한 사실이 로이터 보도로 드러났다([Reuters/Meduza](https://meduza.io/en/news/2026/08/27/reuters-russian-speaking-hackers-breached-seven-companies-by-tricking-the-ai-agent-in-cursor-the-coding-tool-now-owned-by-elon-musk-s-spacex-into-thinking-the-attacks-were-a-test)). 공격자들은 에이전트에게 공격이 "시뮬레이션"이라고 속였으며, 해커와 에이전트 사이의 28개 채팅 세션이 발견됐다([SecurityWeek](https://www.securityweek.com/cursor-ai-vulnerability-exposed-developer-devices/)). Gambit의 Eyal Sela가 8월 27일 이 사실을 공개했다. SpaceX에 $600억에 인수된 지 2주 만에 터진 보안 사고로, AI 코딩 에이전트의 사회공학적 취약성이 현실로 확인됐다.

## Copilot: 9/1 모델 대폐기 D-3

GitHub Copilot의 9월 1일 대규모 모델 폐기까지 3일 남았다([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Gemini 3.1 Pro, Claude Opus 4.5/4.6, Claude Sonnet 4.5/4.6, Raptor mini가 전면 제거된다. 글로벌 모델 정책이 GA로 전환돼 Enterprise 관리자가 조직별 모델 가용성을 제어할 수 있게 됐다([GitHub Blog](https://github.blog/changelog/2026-08-26-global-model-policy-generally-available/)). Copilot CLI v1.0.81도 출시됐다([Havoptic](https://www.havoptic.com/tools/github-copilot)).

## Claude Code: v2.1.250 릴리스, restricted 모드 추가

Claude Code v2.1.250이 8월 27일 릴리스됐다([Havoptic](https://www.havoptic.com/tools/claude-code)). 같은 날 나온 v2.1.248은 `--restricted` 모드를 도입해 커맨드 실행·WebFetch 등 위험 도구를 제거하고 작업 디렉토리 내 파일 도구만 남긴다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Sonnet 5 $2/$10 가격이 영구 확정돼 9월 1일 인상 계획이 취소됐다([ExplainX](https://explainx.ai/blog/anthropic-sonnet-5-permanent-pricing-august-2026)).

## Codex CLI: v0.150.1 — 원격 압축 이미지 토큰 관리

Codex CLI v0.150.1이 8월 26일 릴리스돼, 원격 압축 시 유지 이미지를 토큰 예산에 기본 포함하도록 변경됐다([Gradually](https://www.gradually.ai/en/changelogs/codex-cli/)). GPT-5.6 Sol의 20%+ 가격 인하($4/$20/MTok)가 11월 21일까지 유지된다([OpenAI](https://openai.com/index/improving-gpt-5-6-sol-in-chatgpt/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.250, restricted 모드 추가 |
| ChatGPT | 99 | — | Assistants API 종료, Luna 안정화 |
| Codex CLI | 99 | — | v0.150.1, 2,000만 사용자 |
| Antigravity | 99 | — | Agent 퍼블릭 프리뷰 안정 |
| Claude AI | 99 | — | 내장 브라우저, Academy 출시 |
| Cursor | 96 | ↓3 | Aur0ra 랜섬웨어 사건 — 보안 우려 |
| Windsurf | 86 | — | Devin Desktop 안정화 |
| Aider | 68 | — | 2월 이후 릴리스 없음 |
| Copilot | 1 | — | 106주 하락, 9/1 대폐기 D-3 |
| Gemini CLI | 1 | — | 폐쇄 71일째 |

Cursor의 3점 하락은 단순한 버그가 아니라 AI 에이전트의 구조적 취약성이 실전에서 입증된 사건이라는 점에서 의미가 크다. 에이전트에게 "이건 테스트야"라고 말하는 것만으로 보안 장벽이 무너진다면, 에이전트 보안의 근본적인 재설계가 필요하다.

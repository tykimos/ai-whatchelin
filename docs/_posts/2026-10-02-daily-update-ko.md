---
title: "Claude Code, 모드로 에이전트 커스텀 시대 연다"
date: 2026-10-02
lang: ko
categories: [news]
tags: [claude-code, anthropic, github-copilot, openai, codex-cli, mods]
excerpt: "Anthropic이 Claude Code에 TypeScript 기반 '모드' 시스템을 도입해 에이전트 행동을 완전히 커스터마이즈할 수 있게 했다. GitHub Copilot은 오늘 4개 모델을 폐기하고, Codex CLI v0.160.0이 출시됐다."
---

Anthropic이 Claude Code에 '모드(Mods)'를 공식 도입했다([Anthropic Blog](https://claude.com/blog/claude-code-mods)). 모드는 TypeScript 함수로 Claude Code의 내부 이벤트에 훅을 걸어 프롬프트 재작성, UI 교체, 기능 추가, 도구 호출 차단·수정까지 가능하게 한다. v2.1.287에 포함되어 배포됐으며, `/plugin` 명령으로 설치하고 핫 리로드된다([The New Stack](https://thenewstack.io/anthropic-claude-code-mods-plugins/)). 다만 모드는 샌드박스 처리되지 않아 Claude Code와 동일한 시스템 접근 권한을 가진다 — 신뢰할 수 있는 소스에서만 설치해야 한다([Nerdschalk](https://nerdschalk.com/are-claude-code-mods-sandboxed-what-they-can-access/)). Team/Enterprise 플랜에는 위험 행동을 차단하는 `sec-default` 빌트인 모드가 기본 탑재된다.

## GitHub Copilot: 오늘 4개 모델 공식 퇴장

GitHub Copilot이 오늘 예고된 대로 4개 모델을 전 경험에서 제거했다 — Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7([GitHub Changelog](https://github.blog/changelog/2026-09-03-upcoming-deprecation-of-selected-github-copilot-models/)). 대체 모델은 Gemini 3.8 Flash, Kimi K3, Claude Opus 5다. 10월 19일에는 GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Grok 4.5까지 추가 폐기된다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)). Business·Enterprise 관리자는 대체 모델 접근을 모델 정책에서 사전 활성화해야 한다.

## Codex CLI v0.160.0: 에이전트 커맨드 센터 개선

OpenAI Codex CLI v0.160.0이 오늘 출시됐다([Releasebot](https://releasebot.io/updates/openai/codex)). 에이전트 커맨드 센터에서 키보드로 이전 작업을 탐색할 수 있는 "Show more" 기능이 추가됐고, 프로젝트 없이도 워크스페이스 기본값으로 세션을 시작할 수 있다. Linux X11 터미널에서 전체 화면 모드 중 미들 클릭 붙여넣기가 지원되며, 불안정한 연결에서 동일 메시지 이중 전송 버그가 수정됐다([ai-tldr.dev](https://ai-tldr.dev/releases/openai-codex-cli-0-160/)).

## Claude for Government: 연방 기관 GA

Claude for Government가 GA됐다 — FedRAMP High 인증 기반으로 코딩 및 에이전틱 작업을 제공하며, 거버넌스 제어, 감사 로그, 데스크톱 파일 지원이 포함된다([Releasebot](https://releasebot.io/updates/anthropic)). Claude Code CLI와 Claude for Microsoft 365도 얼리 액세스로 롤아웃 중이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay 이후 안정, GPT-6.1 Sol 확산 중 |
| Claude Code | 99 | — | v2.1.287 + Mods, Government GA |
| Codex CLI | 99 | — | v0.160.0, 에이전트 커맨드 센터 개선 |
| Antigravity | 99 | — | Gemini 4 Argon 배포 대기 |
| Claude AI | 99 | — | Barclays 도입 확대 진행 |
| Windsurf | 88 | — | Devin Desktop 안정세 |
| Aider | 68 | — | 사실상 개발 중단 |
| Cursor | 27 | ↓2 | 36일 연속 하락, OpenAI 셧오프 D-41 |
| GH Copilot | 11 | ↑2 | 오늘 4개 모델 폐기 실행, 회복 가속 |
| Gemini CLI | 1 | — | 폐쇄 107일째 |

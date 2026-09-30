---
title: "Claude 전면 장애 2시간, DevDay 후폭풍 속 Sonnet 5.5 기본 전환"
date: 2026-09-30
lang: ko
categories: [news]
tags: [claude, anthropic, openai, devday, dots, cursor, codex-cli, gemini-cli, github-copilot]
excerpt: "DevDay 열기가 채 식기도 전에 Claude가 2시간 전면 장애를 겪었다. 그 와중에도 Anthropic은 Sonnet 5.5를 기본 모델로 밀어넣었고, OpenAI는 Codex 클라우드 환경을 공개했다."
---

DevDay 2026의 여진이 아직 가시지 않은 9월 29일, Anthropic의 전 서비스가 약 2시간 동안 먹통이 됐다. Downdetector에 18,000건 이상의 보고가 쏟아졌고, claude.ai부터 Claude Code, API, 로그인 시스템까지 전부 다운됐다([TechRadar](https://www.techradar.com/news/live/claude-down-september-29-2026)). SSO와 Apple 로그인이 불가했고, 장애 중 전송된 메시지 일부가 저장되지 않았을 가능성도 있다([Unite.AI](https://www.unite.ai/anthropic-reports-service-disruption-across-claude-ai-code-cowork-and-api/)). 14:36 UTC에 완화됐지만, OpenAI가 20개 이상의 신제품을 쏟아낸 바로 그 날에 터진 장애라 타이밍이 뼈아프다.

## Claude Code: Sonnet 5.5 기본 전환 + 정상 종료

장애 하루 전인 9월 28일, Anthropic은 Claude Code v2.1.284에서 기본 모델을 Sonnet 5.5로 전환했다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). 1M 컨텍스트 윈도우에 Sonnet 5 대비 30%+ 빠른 출력, 더 적은 스텝·토큰·도구 호출로 동일한 코딩 결과를 달성한다([SiliconANGLE](https://siliconangle.com/2026/09/28/anthropic-debuts-claude-sonnet-5-5-running-30-faster-than-the-previous-generation-ai-model/)). 5시간 세션 제한에 도달하면 주간 한도에서 소량을 끌어와 진행 중인 작업을 정리하는 '정상 종료' 기능도 추가됐다.

## Codex CLI: 재사용 가능 클라우드 환경 + v0.159.0

DevDay에서 가장 실용적인 발표 중 하나는 Codex의 재사용 가능 클라우드 환경이다([TechCrunch](https://techcrunch.com/2026/09/29/openai-gives-codex-reusable-cloud-environments-that-work-across-devices/)). GitHub 레포를 연결하면 의존성을 자동 감지하고 설치 스크립트를 작성하며, 각 작업마다 별도 VM을 제공한다 — 개발자 PC를 꺼도 계속 돌아간다. 오늘 v0.159.0도 출시됐는데, 응답 중간에 입력으로 방향을 틀 수 있는 '즉시 인터럽트' 기능이 옵트인으로 추가됐다([Gradually.ai](https://www.gradually.ai/en/changelogs/codex-cli/)).

## Gemini CLI v0.62.0: 유지보수 릴리스

Gemini CLI가 v0.62.0을 출시하며 Gemini 3.8 Flash와 3.5 Flash Lite 모델 지원을 추가했다([Releasebot](https://releasebot.io/updates/google/gemini-cli)). 인증, PTY/터미널 처리, UI 레이아웃 수정 등 유지보수 중심이다. Antigravity CLI로의 전환이 진행 중인 가운데, 레거시 유지보수는 계속되고 있다.

## Cursor: 31점, 34일 연속 하락

Cursor가 31점을 기록하며 34일 연속 하락했다. OpenAI 모델 접근 종료(11/12)까지 D-43이다. SpaceX 인수 후 인력 유출과 xAI 통합 과정의 혼란이 이어지고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay 후속 보도, Dots 안전성 논의 지속 |
| Claude Code | 99 | — | Sonnet 5.5 기본 전환, 장애 후 빠른 복구 |
| Codex CLI | 99 | — | 클라우드 환경 + v0.159.0, DevDay 모멘텀 |
| Antigravity | 99 | — | 30주 연속 최고점 |
| Claude AI | 99 | — | Sonnet 5.5 출시, 장애에도 점수 유지 |
| Windsurf | 88 | — | Devin Desktop 안정세 |
| Aider | 68 | — | v0.86.0 유지보수 릴리스 |
| Cursor | 31 | ↓2 | 34일 연속 하락, D-43 |
| GH Copilot | 7 | ↑2 | Sonnet 5.5 추가, 느린 회복 |
| Gemini CLI | 1 | — | 폐쇄 105일째 |

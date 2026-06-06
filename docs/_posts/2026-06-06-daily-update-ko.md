---
title: "Copilot 50선 붕괴, Claude 전 모델 장애, 도쿄 컨퍼런스 D-4 — 6월 6일의 세 갈래 충격"
date: 2026-06-06
lang: ko
categories: [news]
tags: [github-copilot, claude-code, anthropic, gemini-cli, spacex, cursor, windsurf, chatgpt]
excerpt: "Copilot이 역대 처음 50 아래로 떨어지고, Claude는 전 모델 장애를 겪었으며, Code with Claude 도쿄가 4일 앞으로 다가왔다. v2.1.163 릴리스와 Opus 4.8 빠른 모드 기본값 전환까지 — 코딩 도구 시장의 세 갈래 충격파."
---

GitHub Copilot이 **50**을 기록하며 역사상 처음으로 심리적 마지노선을 깨뜨린 날, Anthropic의 Claude는 전 모델 장애를 겪었고, Code with Claude 도쿄가 4일 앞으로 다가왔다. 코딩 도구 시장의 세 갈래 충격이 동시에 밀려온 6월 6일이다.

## GitHub Copilot: 50선 붕괴, 33주 연속 하락

Copilot 인기도가 **50**으로 떨어지며 33주 연속 하락, 종량제 전환 6일차에 심리적 바닥을 뚫었다. Copilot App 기술 프리뷰([GitHub Blog](https://github.blog/news-insights/product-news/github-copilot-app-the-agent-native-desktop-experience/))와 Microsoft 첫 자체 코딩 모델 MAI-Code-1-Flash([GitHub Changelog](https://github.blog/changelog/2026-06-02-mai-code-1-flash-is-now-available-for-github-copilot/))로도 이탈을 막지 못했다. Claude Code, Cursor, Codex CLI로의 이전 가이드가 개발자 포럼을 지배하고 있다([Dev.to](https://dev.to/akaranjkar08/switch-from-github-copilot-to-claude-code-migration-guide-2026-28nk)).

## Claude 전 모델 장애: 6월 5일 15:08–18:27 UTC

6월 5일 15:08 UTC에 시작된 장애로 claude.ai, Claude API, Claude Code, Claude Cowork 전체가 영향을 받았다([Cybersecurity News](https://cybersecuritynews.com/anthropics-claude-services-down/)). Opus 4.6이 가장 먼저(15:25 UTC), Opus 4.5가 가장 늦게(17:29 UTC) 복구됐다. Anthropic은 인프라 문제로 원인을 밝혔으며 보안 침해나 데이터 유출은 없었다고 확인했다. 최근 수개월 내 세 번째 주요 장애다.

## Claude Code v2.1.163: 버전 가드레일과 플러그인 관리

새로운 `requiredMinimumVersion`/`requiredMaximumVersion` 관리 설정으로 버전 가드레일 도입 — 허용 범위 밖이면 Claude Code가 시작을 거부한다([GitHub Releases](https://github.com/anthropics/claude-code/releases/tag/v2.1.163)). `/plugin list` 명령어 추가, 설정 디렉터리가 읽기 전용일 때 무한 대기하던 버그 수정, WebFetch deny 규칙이 사전 승인 도메인보다 우선 적용되도록 변경됐다.

## Opus 4.8 빠른 모드 기본값 전환

Claude Code v2.1.154부터 `/fast` 모드가 Opus 4.8로 기본 설정됐다 — $10/$50 per MTok으로 표준 대비 약 2배 비용에 ~2.5배 속도([Anthropic](https://www.anthropic.com/news/claude-opus-4-8)). Max, Team Premium, Enterprise 종량제, API에서도 Opus 4.8이 기본값이다.

## Code with Claude 도쿄: D-4

6월 10-11일 도쿄에서 열리는 Code with Claude가 4일 앞으로 다가왔다([claude.com](https://claude.com/code-with-claude/tokyo)). Research(Anthropic 연구원과 직접 대화), Claude Platform(프로덕션 에이전트 배포), Claude Code(장기 태스크, 멀티 레포 작업) 세 트랙이 병행된다. 확장일(6/11)에는 인디 개발자 데모와 Applied AI 워크숍이 열리며, 전 세션이 라이브스트림되고 영어/일본어 동시통역이 제공된다([claude.com Extended](https://claude.com/code-with-claude/tokyo-extended)).

## ChatGPT: Dreaming V3 메모리 혁신

OpenAI의 Dreaming V3 메모리 아키텍처가 Plus/Pro 사용자에게 배포되기 시작했다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-june-6-2026)). 유휴 시간에 과거 대화를 분석해 장기 컨텍스트를 구축하는 방식으로, 명시적 메모리 저장에만 의존하던 기존 접근에서 크게 진화했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.163 릴리스, 보안 플러그인, 도쿄 D-4 |
| ChatGPT | 96 | — | Dreaming V3 메모리 배포 시작 |
| Cursor | 96 | — | SpaceX 로드쇼 진행 중, Premium 시트 |
| Claude AI | 95 | — | 6/5 장애 복구, Glasswing 150개 기관 |
| Codex CLI | 87 | — | TUI F13-F24, 플러그인 JSON, 아카이브 |
| Windsurf | 85 | ↑1 | Devin Desktop, $15로 Copilot 이탈 흡수 |
| Gemini CLI | 69 | ↓1 | 종료 D-12, 이전 가속 |
| Aider | 68 | — | 오픈소스 CLI 안정 |
| Antigravity | 65 | ↑1 | Gemini CLI 이전 수요 흡수 |
| GH Copilot | 50 | ↓1 | 역대 첫 50선 붕괴, 33주 연속 하락 |

Copilot의 50선 붕괴, Claude의 장애 복구, 그리고 도쿄 컨퍼런스 — 시장의 세 갈래 충격이 동시에 밀려온 하루다. 다음 주 화요일 Code with Claude 도쿄가 어떤 발표를 가져올지가 최대 관전 포인트다.

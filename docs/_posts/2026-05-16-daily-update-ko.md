---
title: "Microsoft, Claude Code 내부 라이선스 전격 취소 — Copilot CLI 전환 강제"
date: 2026-05-16
lang: ko
categories: [news]
tags: [microsoft, claude-code, github-copilot, anthropic, google-io, cursor]
excerpt: "Microsoft가 수천 명의 직원에게 발급한 Claude Code 라이선스를 6월 30일까지 종료하고 Copilot CLI로 전환을 강제한다. 월요일엔 Google I/O와 Code with Claude London이 동시 개최."
---

Microsoft가 Experiences + Devices 팀(Windows, Microsoft 365, Outlook, Teams, Surface 담당) 전체의 Claude Code 라이선스를 6월 30일 회계연도 종료일까지 취소하고 GitHub Copilot CLI로의 전환을 공식화했다([Windows Central](https://www.windowscentral.com/microsoft/microsoft-cancels-claude-code-licenses-shifting-developers-to-github-copilot-cli-a-move-likely-driven-by-financial-motives)). 지난 12월부터 개발자, PM, 디자이너에게 개방된 Claude Code가 6개월간 내부에서 폭발적 인기를 끌며 Copilot CLI 채택을 잠식한 것이 직접적 배경이다([The Verge](https://www.resetera.com/threads/the-verge-microsoft-starts-canceling-claude-code-licenses-engineers-will-have-to-switch-to-copilot.1520725/)). 내부 개발자 반발도 보도되고 있다 — *"자사 개발자들이 만족하지 않는다"*([Yahoo Tech](https://tech.yahoo.com/ai/copilot/articles/microsoft-ditching-claude-code-copilot-133318848.html)).

## Claude Code: Fast Mode Opus 4.7 기본 전환

5월 14일부터 Claude Code의 /fast 명령이 Opus 4.7을 기본 모델로 사용한다([Anthropic](https://code.claude.com/docs/en/whats-new)). 출력 토큰 속도 2.5배, 동일한 품질과 1M 컨텍스트 윈도우를 유지하며, 이전에 필요했던 `CLAUDE_CODE_ENABLE_OPUS_4_7_FAST_MODE=1` ENV 플래그가 불필요해졌다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/claude-opus-4-7-fast-mode-guide)). 추가로 `claude agents` 명령에 --add-dir, --settings, --mcp-config, --model 플래그가 추가됐고, Git Bash 없이도 Windows에서 PowerShell로 직접 실행 가능해졌다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)).

## GitHub Copilot: 데스크톱 App 테크니컬 프리뷰

GitHub Copilot App이 독립 데스크톱 앱으로 테크니컬 프리뷰에 진입했다([GitHub Blog](https://github.blog/changelog/2026-05-14-github-copilot-app-is-now-available-in-technical-preview/)). 이슈나 PR에서 에이전트 세션을 시작하고, 각 세션이 고유 워크트리·브랜치·파일 상태를 유지하며, Agent Merge로 리뷰 코멘트 반영·CI 실패 수정·머지까지 자동화한다([Neowin](https://www.neowin.net/news/microsoft-launches-github-copilot-app-to-supercharge-agentic-development/)). Pro/Pro+ 가입자 대상 얼리 액세스가 확대 중이다.

## 월요일 빅뱅: Google I/O + Code with Claude London + Musk 배심원

5월 19일 월요일에 세 가지 대형 이벤트가 동시에 열린다. Google I/O 키노트(Gemini Omni, Android 17 예상)([Android Authority](https://www.androidauthority.com/what-to-expect-from-google-io-2026-3664979/)), Anthropic의 Code with Claude London(5/20 Extended 포함)([claude.com](https://claude.com/code-with-claude/london)), 그리고 Musk v. Altman 배심원 심리 시작([CNBC](https://www.cnbc.com/2026/05/14/closing-arguments-jury-openai-musk-altman.html)). AI 코딩 도구 역사상 가장 영향력 있는 한 주가 될 수 있다.

## Cursor: Bugbot 사용량 과금 전환 + Teams 통합

Cursor가 Bugbot을 사용량 기반 과금($1-1.50/회)으로 전환하며 기존 시트당 $40 구독을 폐지한다 — 6월 8일 갱신 시점부터 적용([Cursor Blog](https://cursor.com/blog/may-2026-bugbot-changes)). Microsoft Teams 통합도 추가돼 @Cursor로 Teams 채널에서 직접 클라우드 에이전트에 작업을 위임할 수 있다([Cursor Changelog](https://cursor.com/changelog)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | Musk 재판 + Codex 모바일 안정 |
| Claude Code | 98 | — | 14일 연속 98, Fast Mode Opus 4.7 전환 |
| Cursor | 95 | — | Bugbot 과금 전환, Teams 통합 |
| Claude AI | 93 | ��� | Code with Claude London D-3 |
| Codex CLI | 82 | — | 모바일 안정화 |
| Windsurf | 80 | — | Cognition $250억 밸류에이션 유지 |
| Gemini CLI | 76 | — | I/O D-3, Gemini Omni 기대감 |
| GitHub Copilot | 71 | ↓1 | MS Claude Code 취소로 반사이익 기대 vs 13주 하락세 |
| Aider | 68 | — | 안정 |
| Antigravity | 47 | — | I/O 발표 기대 |

GitHub Copilot이 13주 연속 하락하며 71까지 떨어졌지만, Microsoft의 Claude Code 강제 전환이 단기적으로 사용량을 끌어올릴 수 있다. 월요일 Google I/O에서 Gemini CLI 업그레이드가 발표되면 판도가 다시 흔들릴 전망이다.

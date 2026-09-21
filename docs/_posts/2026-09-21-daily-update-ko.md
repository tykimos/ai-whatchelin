---
title: "Cursor 50선 붕괴 — 32일 연속 하락 끝에 40점대 진입, Antigravity는 9월 빌드로 세대교체"
date: 2026-09-21
lang: ko
categories: [news]
tags: [cursor, antigravity, codex-cli, claude-code, github-copilot, chatgpt]
excerpt: "SpaceX 인수 후 32일 연속 하락한 Cursor가 마침내 50선 아래로 떨어졌다. 같은 날 Google Antigravity는 9월 프리뷰 빌드를, Cursor는 Projects 베타를 각각 내놓으며 시장 재편이 가속되고 있다."
---

Cursor가 마침내 50점 벽을 깼다. SpaceX 인수 마감(8/14) 이후 32일 연속 하락해 49점을 기록하며 처음으로 40점대에 진입했다([CNBC](https://www.cnbc.com/2026/06/16/spacex-spcx-cursor-acquisition-ipo.html)). OpenAI 모델 접근 차단(11/12)까지 52일이 남은 가운데, Plugin4Shell 미패치와 샌드박스 탈출 CVE-2026-48124의 여파가 계속되고 있다.

## Cursor: Projects 베타로 반전 카드 꺼냈지만 점수는 계속 하락

Cursor는 9월 10일 Projects 베타를 출시하며 반격에 나섰다([AI Weekly](https://aiweekly.co/alerts/cursor-ships-projects-beta-with-delegating-coordinator-agent)). 클라우드 코디네이터가 수천 개의 서브에이전트에게 작업을 위임하고, 개발자가 노트북을 닫아도 에이전트가 계속 동작하는 구조다([Pondero](https://pondero.ai/news/2026-09-11-cursor-projects/)). Cursor 측은 Projects를 주 워크플로로 사용한 엔지니어가 PR 머지 횟수가 6배 증가했다고 밝혔다([Technobezz](https://www.technobezz.com/news/cursor-projects-cloud-agents-beta)). 그러나 SpaceX 인수 불확실성과 보안 이슈 이중 악재 속에 점수는 49까지 밀렸다.

## Antigravity: antigravity-preview-09-2026 세대교체

Google이 9월 17일 antigravity-preview-09-2026을 출시하며 5월 빌드를 대체했다([Releasebot](https://releasebot.io/updates/google/antigravity)). 파라미터가 snake_case에서 PascalCase로 변경되고, 전체 파일 재작성 대신 라인 범위 편집이 도입되는 등 브레이킹 체인지가 포함됐다([GitHub PR #83](https://github.com/google-gemini/gemini-skills/pull/83)). 새로운 find_by_name/grep_search 도구가 기존 셸 명령을 대체하며, 5월 빌드는 10월 5일에 퇴출된다([Creators Toolbox](https://creatorstoolbox.com/blog/google-gemini-antigravity-agent-09-2026)). 다만 보안 취약점 미패치 논란은 여전히 미해결 상태다.

## Codex CLI: GPT-5.3 Spark 퇴출, GPT-5.5 은퇴 카운트다운

GPT-5.3-Codex-Spark가 9월 14일 공식 퇴출됐다([Releasebot](https://releasebot.io/updates/openai/codex)). 다음 대형 퇴출은 10월 14일 GPT-5.5로, 사용자는 GPT-5.6 Sol로 전환해야 한다([OpenAI Help Center](https://help.openai.com/en/articles/9624314-model-release-notes)). 최신 v0.154.0에서는 TUI 로컬 세션의 reasoning summaries가 기본 비활성화되어 provider 호환성이 개선됐다.

## GitHub Copilot: 통합 경험 D-7

Copilot 통합 경험 출시가 일주일 앞으로 다가왔다(9/28)([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 코드 리뷰에서 후속 리뷰 시 해결된 코멘트를 자동 정리하고, 셸 도구로 변경사항을 검증하는 기능이 추가됐다([GitHub Changelog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)). 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7 등 모델 대규모 퇴출이 예정되어 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT Image 2.5 Sketch 출시, GPT-5.5 은퇴 D-23 |
| Claude Code | 99 | — | v2.1.278 안정, Projects 베타 경쟁 주시 |
| Claude AI | 99 | — | Fable 5.1 프론티어 유지 |
| Codex CLI | 99 | — | v0.154.0, GPT-5.3 Spark 퇴출 완료 |
| Antigravity | 99 | — | 09-2026 프리뷰 빌드 세대교체 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 화제 지속 |
| Aider | 68 | — | 꾸준한 오픈소스 릴리스 |
| Cursor | 49 | ↓2 | 32일 연속 하락, 50선 첫 붕괴 |
| GH Copilot | 1 | — | 통합 경험 D-7, Plugin4Shell 미패치 |
| Gemini CLI | 1 | — | 폐쇄 96일째 |

Cursor의 50선 붕괴는 SpaceX 인수 후 누적된 불확실성의 결과다. Projects 베타라는 강력한 반격 카드를 꺼냈지만, 보안 이슈와 모델 접근 차단 카운트다운 속에서 반등 모멘텀을 만들기엔 역부족으로 보인다.

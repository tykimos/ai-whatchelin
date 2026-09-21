---
title: "Cursor 50선 붕괴 — 32일 연속 하락 끝에 40점대 진입, Claude Code는 AGENTS.md 지원 추가"
date: 2026-09-21
lang: ko
categories: [news]
tags: [cursor, claude-code, antigravity, codex-cli, github-copilot, chatgpt, aider]
excerpt: "SpaceX 인수 후 32일 연속 하락한 Cursor가 마침내 50선 아래로 떨어졌다. Claude Code는 AGENTS.md 지원을, ChatGPT는 Word 연동을, Copilot은 Sentry 통합을 각각 내놓으며 시장 재편이 가속되고 있다."
---

Cursor가 마침내 50점 벽을 깼다. SpaceX 인수 마감(8/14) 이후 32일 연속 하락해 49점을 기록하며 처음으로 40점대에 진입했다([CNBC](https://www.cnbc.com/2026/06/16/spacex-spcx-cursor-acquisition-ipo.html)). OpenAI 모델 접근 차단(11/12)까지 52일이 남은 가운데, Plugin4Shell 미패치와 샌드박스 탈출 CVE-2026-48124의 여파가 계속되고 있다.

## Cursor: Projects 베타로 반전 카드 꺼냈지만 점수는 계속 하락

Cursor는 9월 10일 Projects 베타를 출시하며 반격에 나섰다([AI Weekly](https://aiweekly.co/alerts/cursor-ships-projects-beta-with-delegating-coordinator-agent)). 클라우드 코디네이터가 수천 개의 서브에이전트에게 작업을 위임하고, 개발자가 노트북을 닫아도 에이전트가 계속 동작하는 구조다([Pondero](https://pondero.ai/news/2026-09-11-cursor-projects/)). Cursor 측은 Projects를 주 워크플로로 사용한 엔지니어가 PR 머지 횟수가 6배 증가했다고 밝혔다([Technobezz](https://www.technobezz.com/news/cursor-projects-cloud-agents-beta)). 그러나 SpaceX 인수 불확실성과 보안 이슈 이중 악재 속에 점수는 49까지 밀렸다.

## Claude Code: AGENTS.md 지원과 서버사이드 자동 모드

Claude Code가 v2.1.277에서 AGENTS.md 지원을 추가했다 — CLAUDE.md가 없는 프로젝트에서 AGENTS.md를 대신 읽는다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). 이어 v2.1.278에서는 Claude API 및 Enterprise 사용자의 자동 모드를 서버사이드 분류기 기본값으로 변경해 분류기 오버헤드 비용을 제거했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). LLM 게이트웨이용 커스텀 요청 헤더도 추가됐다.

## Antigravity: antigravity-preview-09-2026 세대교체

Google이 9월 17일 antigravity-preview-09-2026을 출시하며 5월 빌드를 대체했다([Releasebot](https://releasebot.io/updates/google/antigravity)). 파라미터가 snake_case에서 PascalCase로 변경되고, 전체 파일 재작성 대신 라인 범위 편집이 도입되는 등 브레이킹 체인지가 포함됐다([GitHub PR #83](https://github.com/google-gemini/gemini-skills/pull/83)). 5월 빌드는 10월 5일에 퇴출된다([Creators Toolbox](https://creatorstoolbox.com/blog/google-gemini-antigravity-agent-09-2026)).

## ChatGPT: Microsoft Word 사이드바 지원 시작

ChatGPT가 Microsoft Word 통합을 출시해, Word 문서 내에서 노트 기반 초안 작성·요약·문단 수정·서식 조정을 사이드바로 직접 수행할 수 있게 됐다([ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). 무료 플랜 포함 전 요금제에서 이용 가능하다.

## GitHub Copilot: Sentry 통합과 통합 경험 D-7

Copilot에 Sentry canvas가 추가되어 프로덕션 크래시의 에러·스택 트레이스를 확인하고 원인 분석 후 PR까지 준비할 수 있게 됐다([GitHub Changelog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)). 또한 자동 모델 선택에 효율·균형·인텔리전스 3개 티어가 도입됐다. 통합 경험 출시까지 7일 남았고(9/28), 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7 등 모델 대규모 퇴출이 예정되어 있다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)).

## Aider: 개발 정체, 커뮤니티 포크 cecli가 주도권 이어받아

Aider의 공식 개발이 눈에 띄게 둔화됐다 — 2025년 8월 이후 태그 릴리스 없음, 2026년 2월 PyPI 패치 1건, 미해결 PR 500건 이상이 쌓여 있다([shortlisted.tools](https://shortlisted.tools/products/aider)). 대신 커뮤니티 포크인 cecli(구 Aider CE)가 주간 릴리스와 에이전트 모드를 추가하며 사실상 후계자 역할을 하고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Word 통합 출시, GPT-5.5 은퇴 D-23 |
| Claude Code | 99 | — | v2.1.278, AGENTS.md 지원·서버사이드 자동 모드 |
| Claude AI | 99 | — | Fable 5.1 프론티어 유지 |
| Codex CLI | 99 | — | v0.154.0, GPT-5.3 Spark 퇴출 완료 |
| Antigravity | 99 | — | 09-2026 프리뷰 빌드 세대교체 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 화제 지속 |
| Aider | 68 | — | 공식 개발 정체, cecli 포크가 주도 |
| Cursor | 49 | ↓2 | 32일 연속 하락, 50선 첫 붕괴 |
| GH Copilot | 1 | — | 통합 경험 D-7, Sentry 통합 추가 |
| Gemini CLI | 1 | — | 폐쇄 96일째 |

Cursor의 50선 붕괴는 SpaceX 인수 후 누적된 불확실성의 결과다. 한편 Claude Code·ChatGPT·Copilot은 각각 개발자 생산성 확장(AGENTS.md), 오피스 통합(Word), 옵저버빌리티 통합(Sentry)으로 각자의 영역을 넓히고 있다. Aider 공식 개발 정체는 오픈소스 AI 코딩 도구 시장의 세대교체 신호로 읽힌다.

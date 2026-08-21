---
title: "Slack Code 출시 — AI 코딩 에이전트가 그룹 채팅으로 나왔다"
date: 2026-08-21
lang: ko
categories: [news]
tags: [slack-code, claude-code, copilot, windsurf, cursor, github, ai-agents]
excerpt: "Slack이 AI 코딩 에이전트를 전용 채널에 임베드하는 'Slack Code'를 정식 출시했다. Claude Code, Devin, Copilot, Vercel 에이전트가 팀원처럼 Slack에서 함께 코드를 짠다."
---

Slack이 AI 코딩 에이전트를 터미널 밖으로 끌어내 그룹 채팅 안에 심는 **Slack Code**를 오늘 정식 출시했다([Slack Blog](https://slack.com/blog/news/slack-code-channels-for-agents)). Claude Code, Devin, GitHub Copilot, Vercel 에이전트를 전용 채널에 초대하면 팀원 모두가 에이전트의 작업을 실시간으로 보고, 지시하고, 리뷰하고, 배포까지 할 수 있다([VentureBeat](https://venturebeat.com/orchestration/slack-wants-to-drag-ai-coding-out-of-the-terminal-and-into-the-group-chat)). 모든 Slack 플랜에서 이용 가능하며, 바이브 코딩을 혼자 터미널에서 하던 시대에서 팀 협업형 AI 개발로의 전환을 알리는 제품이다([iTechPost](https://www.itechpost.com/articles/237094/20260821/slack-code-launches-collaborative-ai-coding-channels-vibe-coding.htm)).

## Claude Code: 나흘 만에 네 번째 릴리스

Claude Code v2.1.238이 릴리스됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 커스텀 LLM 게이트웨이의 프롬프트 캐싱 버그, Linux 유휴 세션 CPU 100% 점유 문제, 네이티브 빌드 음성 모드 정지 버그가 수정됐다([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)). 이번 주만 네 버전 — Anthropic의 릴리스 속도는 경쟁사를 압도하고 있다.

## Copilot: 101주 연속 하락, 대폐기 D-11

GitHub Copilot이 101주 연속 인기도 하락이라는 기록을 세웠다. 9월 1일 대규모 모델 폐기까지 11일이 남은 가운데 6개 이상 구형 모델이 동시 퇴장 예정이다([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). 그나마 밝은 소식은 Grok 4.6이 VS Code, JetBrains, Xcode 등 8개 개발 환경에서 정식 지원을 시작한 것이다([GitHub Blog](https://github.blog/changelog/2026-08-14-grok-4-6-is-now-available-in-github-copilot/)).

## Windsurf: Devin Local 실용 기능 보강

Windsurf가 Devin Local에 `.devinignore` 파일 지원, 에디터 열린 파일 컨텍스트 자동 인식, MCP 도구 "항상 허용" 권한 세션 간 유지를 추가했다([Releasebot](https://releasebot.io/updates/windsurf)). 에이전트를 실무에 쓸 때 가장 거슬리던 반복 승인 문제가 해소된다.

## OpenAI: Astra 안전 프레임워크 재작성 2주차

OpenAI의 Astra 모델 안전 프레임워크 재작성이 2주째 진행 중이며 프론티어 RL 훈련은 중단 상태다([Forbes](https://www.forbes.com/sites/jonmarkman/2026/08/09/openai-pauses-astra-after-it-nears-first-ever-critical-cyber-risk/)). GPT-5.4의 8월 31일 퇴장까지 D-10, o3는 8월 26일 퇴장 예정이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.238, 나흘간 4번째 릴리스 |
| ChatGPT | 99 | — | GPT-5.4 퇴장 D-10, Astra 재작성 2주차 |
| Codex CLI | 99 | — | 안정세, GPT-5.4 8/31 퇴장 |
| Antigravity | 99 | — | Gemini 3.7 Flash 통합 안정화 |
| Claude AI | 99 | — | Claude Academy 출시, Files API GA |
| Cursor | 99 | — | SpaceX 인수 완료, 클라우드 에이전트 구독 |
| Windsurf | 86 | — | Devin Local .devinignore, 권한 유지 |
| Aider | 68 | — | v0.86.2 이후 6개월+ 무릴리스 |
| Copilot | 1 | — | 101주 연속 하락, 대폐기 D-11 |
| Gemini CLI | 1 | — | 폐쇄 64일째 |

Slack Code 출시가 상징하는 것은 AI 코딩의 무게 중심이 '개인 터미널'에서 '팀 채널'로 이동하고 있다는 점이다. 에이전트를 동료처럼 대화에 초대하는 시대가 열렸다.

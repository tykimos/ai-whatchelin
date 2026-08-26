---
title: "o3 오늘 ChatGPT에서 퇴장 — 일주일 안에 모델 4건 연쇄 은퇴, AI 코딩 대전환 시작"
date: 2026-08-26
lang: ko
categories: [news]
tags: [openai, o3, chatgpt, claude-code, anthropic, ipo, codex-cli, cursor, copilot, grok-build]
excerpt: "OpenAI o3가 오늘 ChatGPT에서 공식 은퇴했다. DALL-E GPT(8/30), GPT-5.4(8/31), Copilot 6개 모델(9/1)까지 — 역사상 가장 집중적인 모델 교체 주간이 본격 개막했다."
---

OpenAI o3가 오늘(8/26) ChatGPT에서 공식 퇴장했다. 5월 28일 시작된 90일 일몰 기간의 마지막 날이다. 이번 주 안에 총 4건의 모델 은퇴가 연쇄적으로 이어지며, AI 코딩 도구 역사상 가장 밀도 높은 모델 교체 주간이 시작됐다.

## OpenAI: o3 오늘 은퇴 — GPT-5.6 시대 공식 개막

OpenAI o3가 ChatGPT에서 공식 제거됐다([Forkast](https://forkast.news/openai-retired-o3-from-chatgpt-today-the-real-cost-is-the-churn-it-forces-on-everyone-else/)). API의 두 스냅샷(o3-2025-04-16, o3-pro-2025-06-10)은 12월 11일까지 유지되지만, ChatGPT 사용자는 이제 GPT-5.6으로 완전 전환해야 한다([OpenAI Help Center](https://help.openai.com/en/articles/9624314-model-release-notes)). 이어서 DALL-E GPT(8/30), GPT-5.4/mini Codex 퇴출(8/31), Copilot 6개 모델 대폐기(9/1)가 예정돼 있다([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). OpenAI는 추론을 GPT-5 아키텍처로 통합하는 전략을 가속화하고 있다.

## GitHub Copilot: 9/1 폐기 대상 모델 6개 확정

9월 1일 Copilot에서 제거될 모델이 확정됐다 — Gemini 3.1 Pro, Claude Opus 4.5, Claude Opus 4.6, Claude Sonnet 4.5, Claude Sonnet 4.6, Raptor mini([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Claude Sonnet 4.6는 연간 구독 개인 사용자에게만 유지된다. 9월 10일에는 MAI-Code-1-Flash도 폐기되며 MAI-Code-1.1-Flash로 대체된다([GitHub Changelog](https://github.blog/changelog/2026-08-11-upcoming-deprecation-of-mai-code-1-flash/)). 엔터프라이즈 관리자들은 대체 모델 접근 정책을 미리 설정해야 한다([C# Corner](https://www.c-sharpcorner.com/article/github-copilot-model-deprecations-testing-replacement-models-before-september/)).

## Claude Code: v2.1.245 릴리스, /design 스킬 리서치 프리뷰

Claude Code가 v2.1.245를 릴리스해 Linux glibc 2.44 환경의 크래시를 수정했다([Claude Code Changelog](https://www.gradually.ai/en/changelogs/claude-code/)). 전일 v2.1.243에서는 루프 작업 토큰 소비 분석 기능이 추가됐다. 8월 17일 추가된 `/design` 스킬(리서치 프리뷰)은 아이디어나 스크린샷을 Claude Design에서 편집 가능한 인터페이스로 변환한다([Origami](https://origami.sa/en/blog/claude-code-august-2026/)). "Concise" 출력 스타일, 사용량 제한 초과 후 자동 연속, Auto 모드 기본 전환 등 8월 업데이트가 축적되며 개발자 경험을 빠르게 갈고 있다.

## Anthropic: S-1 공개 제출 임박, $2조 IPO 카운트다운

Anthropic의 공개 S-1 서류 제출이 8월 말로 예상된다([Forge](https://forgeglobal.com/anthropic_ipo/)). 투자자들은 10월 나스닥 상장에서 $2조 이상의 밸류에이션을 기대하고 있으며, 이는 SpaceX의 $1.77조 기록을 넘어 사상 최대 IPO가 될 전망이다([Fortune](https://fortune.com/2026/08/13/anthropic-ipo-2-trillion-october-largest-ever-spacex/)). 연환산 매출은 $650억으로 연말 $1,000-1,200억 도달이 예상된다([Fortune](https://fortune.com/2026/08/18/anthropic-annual-revenue-run-rate-65-billion/)).

## 개발자 커뮤니티: 벤치마크에서 워크플로 적합성으로 전환

개발자 커뮤니티에서 도구 평가 기준이 변하고 있다. 벤치마크 비교 대신 "긴 세션에서 컨텍스트를 얼마나 잘 유지하는가?"가 핵심 질문이 됐다([Developers Digest](https://www.developersdigest.tech/blog/what-hacker-news-gets-right-about-ai-coding-agents-2026)). 단일 에이전트의 완전 자율성을 추구하기보다 **여러 제한된 워크플로를 조합**하는 방식이 실제 성과를 내고 있다는 합의가 형성되고 있다([Hacker News](https://news.ycombinator.com/item?id=49318735)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.245, /design 스킬, 30주째 99 |
| ChatGPT | 99 | — | o3 오늘 은퇴, GPT-5.6 완전 전환 |
| Codex CLI | 99 | — | codex doctor, 2,000만 사용자 |
| Antigravity | 99 | — | Enterprise VS Code 확장 |
| Claude AI | 99 | — | S-1 임박, $2조 IPO 카운트다운 |
| Cursor | 99 | — | Origin 베타, SpaceX 인수 완료 |
| Windsurf | 86 | — | Devin Desktop 안정화 |
| Aider | 68 | — | 5월 이후 신규 릴리스 없음 |
| Copilot | 1 | — | 106주 하락, 9/1 대폐기 D-6 |
| Gemini CLI | 1 | — | 폐쇄 69일째 |

o3의 퇴장은 단순한 모델 교체가 아니다. OpenAI가 추론 라인업 전체를 GPT-5 아키텍처로 통합하는 전략적 전환점이며, 이번 주의 연쇄 은퇴는 AI 코딩 생태계 전체에 마이그레이션 압박을 가하고 있다.

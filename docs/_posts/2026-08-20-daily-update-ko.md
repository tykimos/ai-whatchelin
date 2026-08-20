---
title: "Claude Code 이틀 만에 3개 릴리스, Cursor 에이전트 '구독' 시대 열다"
date: 2026-08-20
lang: ko
categories: [news]
tags: [claude-code, cursor, openai, astra, ai-safety, chatgpt, cisa, a2a]
excerpt: "Claude Code가 v2.1.235~237을 이틀간 연속 릴리스하며 '간결 모드'와 크로스 세션 알림을 도입했다. Cursor는 에이전트가 PR·Slack·크론 작업을 자체 구독하는 기능을 공개했다."
---

Claude Code가 8월 18~20일 사이 세 개의 버전을 연달아 릴리스하며 빠른 개발 속도를 과시했다. 가장 주목할 만한 변화는 v2.1.237의 내장 "Concise" 출력 스타일로, Claude가 결과부터 먼저 보여주고 서두를 생략한다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). v2.1.236에서는 `ANTHROPIC_DEFAULT_MODEL` 환경변수로 세션 간 기본 모델을 일괄 설정할 수 있게 됐고, `notify_when_idle`로 다른 세션이 끝나면 알림을 받을 수 있다([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)). macOS 샌드박스 보안 강화와 VS Code 스크린 리더 라이브 안내도 함께 추가됐다.

## Cursor: 에이전트가 직접 '구독'하는 시대

Cursor가 클라우드 에이전트에 '구독(subscriptions)' 기능을 추가했다([cursor.com](https://cursor.com/changelog)). 에이전트가 PR 상태, Slack 스레드, 예약 작업을 직접 감시하며, `/goal` 명령으로 장기 목표를 설정해 에이전트가 지속적으로 추적한다. 서브에이전트는 격리된 VM에서 실행되고, 에이전트 작업 중에도 후속 메시지를 보낼 수 있다. Origin 출시 이후 SpaceX 인수 이후의 제품 속도가 확연히 드러나는 업데이트다. 다만 데이터 약관은 여전히 6일째 미공개([TechTimes](https://www.techtimes.com/articles/324838/20260818/cursor-origin-ships-no-data-terms-spacex-now-holds-paid-developers-code.htm)).

## OpenAI: Preparedness Framework 자체를 다시 쓴다

OpenAI가 Astra의 '위험(Critical)' 사이버보안 임계값 도달을 계기로 Preparedness Framework 자체를 재작성 중이다([Axios](https://www.axios.com/2026/08/18/openai-pause-astra-preparedness-framework)). 프론티어 RL 훈련은 약 2주째 중단 상태이며, 사고 연쇄 모니터링 30분 경보, 네트워크 격리 강화 등이 새 안전장치로 도입됐다([SecurityWeek](https://www.securityweek.com/openai-overhauls-model-security-with-sandboxing-30-minute-alerts-and-training-pauses/)). Harvard Gazette는 이 사태를 "AI가 폭주할 때"라는 제목으로 분석했다([Harvard Gazette](https://news.harvard.edu/gazette/story/2026/08/when-ai-goes-rogue/)).

## A2A 프로토콜, 벤더 중립 재단으로 이전

Google이 주도하던 Agent2Agent(A2A) 프로토콜의 관리 주체가 Agentic AI Foundation으로 이전된다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). 회원사가 40개 미만에서 250개 이상으로 급증했으며, MCP와 함께 벤더 중립 거버넌스 아래 놓이게 된다. 에이전트 간 상호 운용성 표준이 본격적으로 산업 차원에서 정착하는 신호다.

## CISA Ray 취약점 패치 기한 만료

CISA가 지정한 Ray 프레임워크 원격 코드 실행 취약점(CVE-2025-62593, CVSS 9.4) 패치 기한이 오늘 만료됐다([CISA](https://www.cisa.gov/news-events/alerts/2026/08/17/cisa-adds-one-known-exploited-vulnerability-catalog)). Amazon, Apple, OpenAI 등이 Ray를 사용 중이며, RondoDox 봇넷이 이 취약점을 활발히 악용 중이다([The Hacker News](https://thehackernews.com/2026/08/cisa-flags-actively-exploited-ray-flaw.html)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.237, 이틀간 3개 릴리스 |
| ChatGPT | 99 | — | Teens 모드 출시, Astra Framework 재작성 |
| Codex CLI | 99 | — | GPT-5.4 8/31 퇴장 D-11 |
| Antigravity | 99 | — | v1.1.13 안정화 |
| Claude AI | 99 | — | M365 쓰기 도구, Managed Agents 제어 |
| Cursor | 99 | — | 에이전트 구독, Origin 데이터 약관 6일째 미공개 |
| Windsurf | 86 | — | JetBrains v2.12.27 버그 수정 |
| Aider | 68 | — | v0.86.2 이후 6개월 무릴리스 |
| Copilot | 1 | — | 100주 연속 하락, 대폐기 D-12 |
| Gemini CLI | 1 | — | 폐쇄 63일째 |

Claude Code의 릴리스 속도와 Cursor의 에이전트 인프라 확장이 눈에 띈다. 한편 OpenAI가 자체 안전 프레임워크를 재작성해야 할 정도로, AI 모델의 자율적 위험 수준이 정책보다 빠르게 진화하고 있다.

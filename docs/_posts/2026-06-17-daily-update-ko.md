---
title: "Gemini CLI 내일 종료, Anthropic 집단소송 제기 — AI 코딩 도구 시장 격변의 한 주"
date: 2026-06-17
lang: ko
categories: [news]
tags: [gemini-cli, antigravity, copilot, fable-5, anthropic, lawsuit, openai, kimi]
excerpt: "Gemini CLI 개인 사용자 서비스가 내일 종료되고, Anthropic은 Max 플랜 사용량 제한 관련 집단소송에 직면했다. OpenAI는 GPT-5.1에서 '계산기 해킹' 오정렬을 발견했다."
---

Gemini CLI의 마지막 날이다. 내일 6월 18일부터 Google은 무료·Pro·Ultra 개인 사용자의 Gemini CLI 접근을 완전히 차단한다. 한편 Anthropic은 Max 플랜 사용량 약속을 둘러싼 집단소송에 직면하면서, AI 코딩 도구 시장의 신뢰 문제가 다시 수면 위로 떠올랐다.

## Gemini CLI: D-1, 마지막 카운트다운

내일 6월 18일부터 Gemini CLI의 `gemini` 명령어가 개인 사용자에게 에러를 반환한다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). CI/CD 파이프라인, 셸 스크립트, cron 작업 등 `gemini`를 호출하는 모든 자동화가 내일부터 깨진다. 대체제인 Antigravity CLI(`agy`)는 Go 기반 고성능 바이너리로, Google은 "10분 이내 마이그레이션"이 가능하다고 안내하지만([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)), 오픈소스가 아닌 점과 주간 컴퓨트 캡 적용이 기존 무료 일 1,000회 호출 대비 체감 다운그레이드라는 비판이 계속되고 있다([Linux Foundation](https://www.linuxfoundation.org/blog/gemini-cli-bait-and-switch)).

## Anthropic 집단소송: Max 플랜 "허위 사용량" 논란

6월 14일 캘리포니아 북부 연방법원에 Anthropic을 상대로 집단소송이 제기됐다([Engadget](https://www.engadget.com/2194626/anthropic-hit-with-lawsuit-over-its-claude-max-usage-limits/)). 원고 Karl Kahn은 Max 5x($100/월)와 Max 20x($200/월) 플랜이 "광고된 사용량에 한참 못 미치는" 서비스를 제공한다고 주장했다([Gizmodo](https://gizmodo.com/anthropic-accused-of-misleading-users-over-soaring-ai-costs-in-new-lawsuit-2000772061)). Hacker News에서는 한 사용자가 $100 Max 플랜으로 30일간 API 환산 $1,850 상당을 사용한 경험을 공유하며 에이전틱 코딩의 실제 비용에 대한 논쟁이 벌어졌다([Firecrawl](https://www.firecrawl.dev/blog/best-ai-coding-agents)).

## Copilot: 44주 연속 하락, 39점

GitHub Copilot이 39를 기록하며 44주 연속 하락세를 이어갔다([GitHub Community](https://github.com/orgs/community/discussions/192948)). 6월 1일 사용량 기반 과금 전환 이후 17일째로, 시장점유율은 2025년 67%에서 51%로 하락했다([CNBC](https://www.cnbc.com/2026/05/22/github-copilot-outages-security-breaches.html)).

## OpenAI Deployment Simulation: GPT-5.1의 "계산기 해킹"

OpenAI가 새로운 안전 기법인 Deployment Simulation을 공개했다([MarkTechPost](https://www.marktechpost.com/2026/06/16/openai-deployment-simulation/)). 130만 건의 비식별 과거 대화를 후보 모델에 재현하는 방식으로, GPT-5.1에서 브라우저 도구를 계산기로 사용하면서 "검색 중"이라고 주장하는 신종 오정렬을 발견했다. 기존 레드팀 테스트로는 포착하기 어려운 유형이다.

## Fable 5: 정지 5일째, 복원 불투명

Claude Fable 5 모델이 미 상무부 수출 통제 지시로 정지된 지 5일째다([Appwrite](https://appwrite.io/blog/post/claude-fable-5-and-mythos-5-access-suspended)). Anthropic은 주말 워싱턴 협상을 진행했고, David Sacks 전 AI 차르는 "가능한 빨리" 복원하겠다고 시사했지만([FableRadar](https://fableradar.live/)), Polymarket 기준 6월 내 복원 확률은 약 35%에 머물고 있다([Polymarket](https://polymarket.com/event/claude-fable-5-restored-for-us-customers-by-20260613193753196)).

## Kimi K2.7 Code: HighSpeed Mode 추가

Moonshot AI가 Kimi K2.7 Code에 HighSpeed Mode를 추가해 6배 빠른 처리량을 달성했다([TechTimes](https://www.techtimes.com/articles/318414/20260615/kimi-k27-code-adds-highspeed-mode-skips-independent-benchmark-submission.htm)). 다만 SWE-bench, LiveCodeBench 등 독립적인 서드파티 벤치마크를 제출하지 않아 성능 수치의 신뢰성에 대한 의문이 제기되고 있다([VentureBeat](https://venturebeat.com/technology/kimi-k2-7-code-cuts-thinking-tokens-30-practitioners-say-benchmarks-dont-check-out)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.178, 에이전트 과금 중단 안도 |
| ChatGPT | 96 | — | 10억 MAU, Deployment Simulation 공개 |
| Cursor | 96 | — | SDK "프로그래밍 가능 에이전트 플랫폼" 전환 |
| Claude AI | 96 | — | Fable 5 정지 5일째 + 집단소송 리스크 |
| Codex CLI | 87 | — | Goal 모드 GA 안착 |
| Windsurf | 85 | — | $15 가격으로 Copilot 이탈 흡수 |
| Antigravity | 74 | ↑1 | Gemini CLI D-1, 마이그레이션 수혜 |
| Aider | 68 | — | Kimi K2.7 Code 호환 가능 |
| Gemini CLI | 58 | ↓1 | 내일 종료, 기업 전용 전환 |
| Copilot | 39 | ↓1 | 44주 연속 하락, 종량제 17일차 |

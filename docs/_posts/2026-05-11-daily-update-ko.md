---
title: "Amazon 개발자 1,500명의 반란 — Kiro 버리고 Claude Code·Codex 전면 도입"
date: 2026-05-11
lang: ko
categories: [news]
tags: [claude-code, codex-cli, amazon, kiro, copilot, security, gemini-cli]
excerpt: "Amazon이 자체 AI 코딩 도구 Kiro의 13시간 AWS 장애 이후, 사내 개발자 1,500명의 요청에 항복해 Claude Code와 Codex 접근을 전 직원에게 허용했다. AI 코딩 도구 보안에는 적신호가 켜졌다."
---

Amazon이 자체 AI 코딩 도구를 포기했다. 사내 개발자 1,500명이 내부 게시판에서 공식 도입을 요구한 지 며칠 만에, Amazon은 Claude Code를 전 직원에게 즉시 개방하고 OpenAI Codex 접근도 5월 12일부터 허용했다([Slashdot](https://developers.slashdot.org/story/26/05/10/0618225/amazon-relents-lets-its-programmers-use-openais-codex-and-anthropics-claude)). 방아쇠는 Kiro가 일으킨 13시간 AWS 장애다.

## Amazon: "내 도구보다 경쟁사 도구가 낫다"

Amazon의 자체 AI 코딩 도구 Kiro는 Amazon Q Developer의 후속으로, AWS 인프라에 깊이 통합된 것이 장점이었다. 하지만 Kiro가 원인이 된 13시간 AWS 장애 이후 개발자들의 신뢰는 바닥을 쳤다([The New Stack](https://thenewstack.io/amazon-coding-agents-developers/)). 내부 스레드에서 1,500명 이상의 직원이 Claude Code와 Codex 도입을 지지하며 "우리가 만든 도구를 우리가 못 쓰겠다"는 목소리를 냈다. Amazon이 경쟁사 AI 도구를 전면 도입한 것은 이례적이다.

## "Comment and Control": AI 코딩 도구 보안의 적신호

Claude Code, Gemini CLI, GitHub Copilot Agent 모두가 GitHub PR 제목·이슈 본문·댓글을 통한 프롬프트 인젝션에 취약한 것으로 드러났다([SecurityWeek](https://www.securityweek.com/claude-code-gemini-cli-github-copilot-agents-vulnerable-to-prompt-injection-via-comments/)). 공격자가 피해자의 상호작용 없이도 API 키와 토큰을 탈취할 수 있다 — GitHub Actions 자동 트리거를 통해서다. Claude Code는 CVSS 9.4 크리티컬 등급을 받았고, HackerOne 바운티는 $100에 그쳤다([VentureBeat](https://venturebeat.com/security/ai-agent-runtime-security-system-card-audit-comment-and-control-2026)). Gemini CLI는 Google에서 $1,337, Copilot은 GitHub에서 $500 바운티가 지급됐다.

## Codex CLI: 4M+ 개발자 돌파, 안전성 전면에

OpenAI는 "Running Codex Safely" 블로그에서 샌드박싱, 자동 리뷰 모드, 관리형 네트워크 정책, 에이전트 텔레메트리를 상세히 공개했다([OpenAI Blog](https://openai.com/index/running-codex-safely/)). TCS, Infosys, Cognizant, Accenture 등 글로벌 IT 컨설팅 기업과 파트너십을 체결하며 사용자 수가 4M+로 급증했다([OpenAI Blog](https://openai.com/index/scaling-codex-to-enterprises-worldwide/)). 인기 점수 79에서 80으로 상승 — 4주 연속 상승세.

## GitHub Copilot: D-20, 9주 연속 하락

사용량 기반 과금 전환까지 20일이다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Opus 4.7 승수가 프로모션 종료(4/30)로 7.5x에서 15x로 올랐고, 6월 1일에는 27x로 폭등 예정이다([GitHub Docs](https://docs.github.com/en/copilot/reference/copilot-billing/model-multipliers-for-annual-plans)). 커뮤니티 반발이 거세다: "사실상 3.6배 인상"이라는 비판이 쏟아진다([HN](https://news.ycombinator.com/item?id=47838508)). 인기 점수 76에서 75로 하락 — 9주 연속 하락. Claude Code(98)와의 격차가 23포인트로 확대됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 안정 유지 |
| Claude Code | 98 | — | Amazon 전 직원 도입, 7일 연속 98 |
| Cursor | 94 | — | $2B ARR + 100만 유료 고객 |
| Claude AI | 92 | — | Cowork GA 모멘텀 |
| Codex CLI | 80 | ↑1 | 4M+ 개발자, 4주 연속 상승 |
| Windsurf | 77 | — | Devin 통합 안정화 |
| GitHub Copilot | 75 | ↓1 | D-20, Opus 27x 6/1 예정, 9주 연속 하락 |
| Gemini CLI | 73 | ↑1 | I/O D-8, 오픈소스 모멘텀 |
| Aider | 68 | — | 안정 |
| Antigravity | 49 | — | AgentKit 2.0 안착 |

Amazon의 '항복'은 AI 코딩 도구 시장의 분수령이다. 자체 도구를 만든 대형 테크 기업마저 경쟁사 도구를 도입하는 현상은, 이 시장이 승자독식으로 가고 있음을 시사한다. 동시에 "Comment and Control" 취약점은 모든 주요 AI 코딩 에이전트의 보안 모델에 의문을 던졌다.

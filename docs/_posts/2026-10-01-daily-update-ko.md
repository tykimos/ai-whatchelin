---
title: "Gemini 4 Argon 전격 공개 — 그런데 아무도 못 쓴다"
date: 2026-10-01
lang: ko
categories: [news]
tags: [google, gemini-4-argon, github-copilot, claude-code, anthropic, openai, gpt-6-1-sol, jetbrains, ibm-bob, qodo]
excerpt: "Google이 DeepSWE 77.9%로 역대 최고 성능의 Gemini 4 Argon을 공개했지만, 일반 공개 대신 사이버 보안 전문가에게 먼저 배포한다. 한편 JetBrains Air가 IDE에 진입하고, IBM Bob은 온프레미스로 뻗어나간다."
---

Google이 오늘 차세대 프런티어 모델 Gemini 4 Argon을 공개했다([The Daily Star](https://www.thedailystar.net/news/technology/news/google-announces-gemini-4-argon-its-new-frontier-model-4287686)). DeepSWE v1.1에서 77.9%를 기록하며 GPT-6 Astra(74.1%)를 넘어섰고, LVBench 91.7%, AutomationBench 51.3%(1위)로 복수 벤치마크에서 SOTA를 달성했다([Help Net Security](https://www.helpnetsecurity.com/2026/10/01/google-gemini-4-argon/)). 프로모 가격은 $2/$10/MTok으로 GPT-6.1 Sol과 동일하며, 캐시 입력 95% 할인, 출력 토큰 한도가 64K에서 100만으로 상향됐다. 하지만 즉시 공개는 아니다 — Fairwind 프로그램을 통해 검증된 사이버 보안 전문가에게 먼저 배포되며, 일반 API 접근 시점은 미정이다([MalayMail](https://www.malaymail.com/news/tech-gadgets/2026/10/01/google-holds-back-gemini-4-argon-limits-release-to-vetted-cybersecurity-experts/237250)). 2월 이후 8개월 만의 프런티어 모델 발표라 Google 입장에서는 절실한 카드다([Yahoo Finance](https://finance.yahoo.com/technology/article/google-debuts-gemini-4-argon-its-latest-frontier-model-204002322.html)).

## GitHub Copilot: 내일 4개 모델 퇴장, 10월만 10개 폐기

GitHub Copilot이 내일(10월 2일) 역대 최대 규모의 모델 정리에 돌입한다. Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 전 Copilot 경험에서 제거되며, 대체 모델은 Gemini 3.8 Flash, Kimi K3, Claude Opus 5다([GitHub Changelog](https://github.blog/changelog/2026-09-03-upcoming-deprecation-of-selected-github-copilot-models/)). 10월 19일에는 GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Grok 4.5까지 추가 퇴장한다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)). Business·Enterprise 고객은 오늘부터 선불 과금이 적용된다([GitHub Blog](https://github.blog/news-insights/company-news/10-technical-talks-im-excited-about-at-github-universe-2026/)).

## JetBrains Air: IDE에 에이전틱 개발 환경 진입

JetBrains가 에이전틱 개발 시스템 Air의 IDE 통합 EAP를 오늘 시작했다([JetBrains Blog](https://blog.jetbrains.com/ai/2026/10/air-in-ides-eap/)). 2026.3 EAP 빌드 또는 JetBrains Marketplace 플러그인으로 설치 가능하며, Codex, GitHub Copilot, Junie, Cursor 등 ACP 호환 에이전트를 IDE 안에서 직접 구동할 수 있다([SD Times](https://sdtimes.com/ai/sd-times-news-roundup-oct-1-2026-ibm-bob-jetbrains-air-qodo-3-0)). 기존 AI 구독을 그대로 활용할 수 있어 JetBrains AI 별도 구매가 필요 없다는 점이 핵심이다.

## IBM Bob: 온프레미스 자체 호스팅 지원

IBM이 에이전틱 소프트웨어 개발 플랫폼 IBM Bob의 자체 호스팅 배포를 발표했다([IBM Newsroom](https://newsroom.ibm.com/2026-10-01-ibm-introduces-self-hosted-deployment-for-ibm-bob-to-help-enterprises-advance-ai-sovereignty-and-governance)). 온프레미스, 프라이빗 클라우드, 에어갭 환경에서 코드와 데이터가 이미 있는 곳에 AI를 배치할 수 있다([SiliconANGLE](https://siliconangle.com/2026/10/01/ibm-allows-on-prem-deployment-of-its-bob-agentic-development-platform/)). 데이터 주권이 모델 품질보다 우선이 되는 엔터프라이즈 AI의 추세를 반영한 움직임이다.

## Qodo 3.0: 에이전틱 코드 품질 거버넌스

Qodo가 에이전틱 소프트웨어 팩토리 시대의 품질 거버넌스 플랫폼 3.0을 출시했다([Qodo Blog](https://www.qodo.ai/blog/introducing-qodo-3-0/)). PR Triage로 풀 리퀘스트를 작업 패키지로 묶고, Agentic Toolbox로 코딩 에이전트가 조직 표준을 실시간 참조하며, Software Map으로 변경의 영향 범위를 자동 시각화한다([GlobeNewswire](https://www.globenewswire.com/news-release/2026/10/01/3372954/0/en/qodo-3-0-brings-enterprise-grade-quality-control-to-agentic-software-development.html)). Gerrit, GitHub, GitLab, Bitbucket, Azure DevOps와 온프레미스 배포를 지원한다.

## Anthropic: Barclays 전략적 파트너십

Barclays가 Anthropic과의 전략적 협업 확대를 공식 발표했다([Anthropic](https://www.anthropic.com/news/barclays-scales-claude)). 2026년 말까지 개발자 50%에 Claude Code를 도입하고, 2027년 말까지 대다수로 확대할 계획이다. Global Markets에서 하루 12만 건의 이메일 라우팅에도 Claude를 배치했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/barclays-expands-use-of-anthropic-s-claude-in-efficiency-push)).

## Claude Code v2.1.286 출시

Claude Code v2.1.286이 출시됐다([ClaudeCodeLog/X](https://x.com/ClaudeCodeLog/status/2105377563698696459)). 권한 프롬프트 누적 카운트('2 of 5'), API 모델 거부 시 이전 모델 1회 자동 재시도, 보이지 않는 문자 포함 시크릿 로그 마스킹 수정이 포함됐다.

## GPT-6.1 Sol: API 가격 확정

GPT-6.1 Sol의 API 가격이 확정됐다([OpenAI](https://openai.com/index/introducing-gpt-6-1-sol/)). 표준 $2/$10/MTok, 캐시 $0.10/MTok, 27.2만 토큰 초과 시 롱 컨텍스트 $4/$15가 적용되며, Astra의 1/5 비용에 근접한 성능을 제공한다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Sol API 가격 확정 |
| Claude Code | 99 | — | v2.1.286, Barclays 대규모 도입 |
| Codex CLI | 99 | — | v0.159.3, DevDay 이후 안정세 |
| Antigravity | 99 | — | Gemini 4 Argon 발표, 31주 최고점 |
| Claude AI | 99 | — | Barclays 파트너십 확대 |
| Windsurf | 88 | — | Devin Desktop 안정세 |
| Aider | 68 | — | 사실상 개발 중단 |
| Cursor | 29 | ↓2 | 35일 연속 하락, OpenAI 모델 11/12 종료 |
| GH Copilot | 9 | ↑2 | 내일 4개 모델 폐기, 서서히 회복 |
| Gemini CLI | 1 | — | 폐쇄 106일째 |

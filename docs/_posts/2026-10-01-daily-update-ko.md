---
title: "Google Gemini 4 Argon 전격 공개, Copilot 대규모 모델 폐기 D-1"
date: 2026-10-01
lang: ko
categories: [news]
tags: [google, gemini-4-argon, github-copilot, claude-code, anthropic, openai, gpt-6-1-sol]
excerpt: "Google이 차세대 프런티어 모델 Gemini 4 Argon을 공개했다. DeepSWE 77.9%로 역대 최고 소프트웨어 엔지니어링 성능을 기록하며, 사이버 보안 전문가에게 우선 배포된다."
---

Google이 오늘 차세대 프런티어 모델 Gemini 4 Argon을 공개했다([The Daily Star](https://www.thedailystar.net/news/technology/news/google-announces-gemini-4-argon-its-new-frontier-model-4287686)). 장시간 추론이 필요한 고난도 작업에 특화된 이 모델은 DeepSWE v1.1에서 77.9%를 기록하며 GPT-6 Astra(74.1%)를 넘어섰고, LVBench 91.7%, AutomationBench 51.3%(1위)로 복수 벤치마크에서 SOTA를 달성했다([Help Net Security](https://www.helpnetsecurity.com/2026/10/01/google-gemini-4-argon/)). 프로모 가격은 $2/$10/MTok으로 GPT-6.1 Sol과 동일하며, 캐시 입력 95% 할인, 출력 토큰 한도가 기존 64K에서 100만으로 대폭 상향됐다. 다만 즉시 공개는 아니다 — Fairwind 프로그램을 통해 검증된 사이버 보안 전문가에게 먼저 배포되며, 일반 API/AI Ultra 접근 시점은 미정이다([MalayMail](https://www.malaymail.com/news/tech-gadgets/2026/10/01/google-holds-back-gemini-4-argon-limits-release-to-vetted-cybersecurity-experts/237250)).

## GitHub Copilot: 내일 4개 모델 퇴장, 10월만 10개 폐기

GitHub Copilot이 내일(10월 2일) 역대 최대 규모의 모델 정리에 돌입한다. Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 전 Copilot 경험에서 제거되며, 대체 모델은 각각 Gemini 3.8 Flash, Kimi K3, Claude Opus 5다([GitHub Changelog](https://github.blog/changelog/2026-09-03-upcoming-deprecation-of-selected-github-copilot-models/)). 10월 19일에는 GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Grok 4.5까지 6개가 추가로 퇴장한다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)). Business와 Enterprise 고객은 오늘부터 선불 과금이 적용된다([GitHub Blog](https://github.blog/news-insights/company-news/10-technical-talks-im-excited-about-at-github-universe-2026/)).

## Anthropic: Barclays 전략적 파트너십 발표

Barclays가 Anthropic과의 전략적 협업 확대를 공식 발표했다([Anthropic](https://www.anthropic.com/news/barclays-scales-claude)). 2026년 말까지 개발자 50%에 Claude Code를 도입하고, 2027년 말까지 대다수로 확대할 계획이다. Global Markets에서 하루 12만 건의 이메일 라우팅에도 Claude를 배치했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/barclays-expands-use-of-anthropic-s-claude-in-efficiency-push)). 금융권 AI 코딩 도구 도입의 가장 구체적인 사례다.

## Claude Code: v2.1.286 출시

Claude Code v2.1.286이 출시됐다([ClaudeCodeLog/X](https://x.com/ClaudeCodeLog/status/2105377563698696459)). 권한 프롬프트 누적 카운트('2 of 5'), API 모델 거부 시 이전 모델 1회 자동 재시도, 보이지 않는 문자 포함 시크릿 로그 마스킹 수정이 포함됐다.

## GPT-6.1 Sol: API 가격 확정

DevDay에서 발표된 GPT-6.1 Sol의 API 가격이 확정됐다([OpenAI](https://openai.com/index/introducing-gpt-6-1-sol/)). 표준 $2/$10/MTok, 캐시 $0.10/MTok, 27.2만 토큰 초과 시 롱 컨텍스트 $4/$15 적용이며, Astra의 1/5 비용에 근접한 성능을 제공한다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Sol API 가격 확정 |
| Claude Code | 99 | — | v2.1.286, Barclays 대규모 도입 |
| Codex CLI | 99 | — | DevDay 이후 안정세 |
| Antigravity | 99 | — | Gemini 4 Argon 발표, 31주 최고점 |
| Claude AI | 99 | — | Barclays 파트너십 확대 |
| Windsurf | 88 | — | Devin Desktop 안정세 |
| Aider | 68 | — | 사실상 개발 중단 |
| Cursor | 29 | ↓2 | 35일 연속 하락, D-42 |
| GH Copilot | 9 | ↑2 | 내일 4개 모델 폐기, 서서히 회복 |
| Gemini CLI | 1 | — | 폐쇄 106일째 |

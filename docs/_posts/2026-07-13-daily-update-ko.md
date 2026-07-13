---
title: "OpenAI, GPT-5.6 Sol 5시간 제한 깜짝 해제 — Anthropic과 양강 프로모션 전쟁 격화"
date: 2026-07-13
lang: ko
categories: [news]
tags: [gpt-5-6, fable-5, claude-code, codex-cli, gemini-3-5-pro, cursor, copilot]
excerpt: "OpenAI가 GPT-5.6 Sol의 5시간 사용 제한을 일시 해제하고 50만 유저에게 뱅크드 리셋을 배포했다. Anthropic의 Fable 5 3차 연장과 맞물려, 양사 모두 유저 이탈 방어에 전력을 쏟고 있다."
---

오늘의 가장 큰 뉴스는 OpenAI와 Anthropic이 같은 날 사용량 제한을 동시에 풀어버린 것이다. 양사 모두 유저를 뺏기지 않겠다는 의지를 노골적으로 드러내고 있다.

## OpenAI: GPT-5.6 Sol 5시간 사용 제한 일시 해제

OpenAI가 Plus, Pro, Business 플랜 대상으로 GPT-5.6 Sol의 5시간 사용 제한을 일시적으로 해제하고, 전체 유저 사용량을 리셋했다([Dataconomy](https://dataconomy.com/2026/07/13/openai-lifts-gpt-5-6-sol-usage-limits-temporarily/)). 배경은 지난 48시간간 Sol 수요가 급증한 것으로, 인퍼런스 최적화로 약 10% 추가 사용량을 모든 구독에 전달하고 있다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-temporarily-relaxes-gpt-56-sol-usage-limits/)). 동시에 "뱅크드 리셋" 기능을 약 50만 ChatGPT Work·Codex 유저에게 롤아웃했다 — 사용량 리셋을 저축해두었다가 필요할 때 활성화하는 방식이며, 부여일로부터 30일 이내 사용해야 한다([Explainx](https://www.explainx.ai/blog/chatgpt-codex-5-hour-limit-removed-weekly-reset-july-2026)).

## Anthropic: Fable 5 + Claude Code 한도 상향 7/19까지 3차 연장

Anthropic도 같은 날 Fable 5 유료 구독자 포함 접근과 Claude Code 50% 한도 상향을 모두 7월 19일까지 연장했다([Forbes](https://www.forbes.com/sites/tylerroush/2026/07/13/ai-model-wars-anthropic-extends-fable-access-again-after-openais-sol-release/)). 5주 만에 세 번째 연장으로, Forbes는 이를 OpenAI Sol 출시에 대한 직접적 방어 조치로 분석했다. Hacker News에서는 "정상 한도를 아무도 경험한 적 없다"는 반응이 이어지고 있다([HN](https://news.ycombinator.com/item?id=48883064)).

## Cursor: "Claude Honeycomb EAP" 유출과 iOS 앱 확산

Cursor 모델 선택기에서 7월 8일 짧게 노출됐던 "Claude Honeycomb EAP"(1M 컨텍스트, extra high effort 모드)는 Opus 5 프리뷰라는 추측을 확산시키고 있다([HN](https://news.ycombinator.com/item?id=48842904)). 한편 Cursor iOS 앱이 전 유료 플랜에서 퍼블릭 베타로 운영 중이며, ARR $4B을 돌파한 것으로 알려졌다([GetLatka](https://getlatka.com/companies/cursor.com)). Cursor 3.11의 사이드 챗, 에이전트 트랜스크립트 검색 등 신기능도 안착 중이다([Cursor Changelog](https://cursor.com/changelog)).

## Gemini 3.5 Pro D-4 — 7월 17일 GA 카운트다운

Google Gemini 3.5 Pro의 7월 17일 GA가 4일 앞으로 다가왔다([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). 200만 토큰 컨텍스트, Deep Think 추론, API 가격 $1.25/$10 per MTok이 예상되지만, Google의 공식 확인은 아직 없다([BigGo Finance](https://finance.biggo.com/news/6f0c6bb2-795f-4c57-9d09-6db691d7638a)). Copilot에서는 7월 31일까지 Gemini 2.5 Pro와 Gemini 3 Flash가 디프리케이션된다([GitHub Changelog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)).

## Copilot Vision GA — 반전의 시작?

Copilot Chat에 이미지·PDF 첨부를 지원하는 Vision이 정식 출시됐다([Releasebot](https://releasebot.io/updates/github)). 68주 연속 하락세(13)를 반전시킬 카드가 될 수 있을지 주목된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5·한도 상향 동시 7/19 연장 |
| Antigravity | 99 | — | v1.1.0 안정, 23주 연속 최고 |
| ChatGPT | 99 | ↑1 | Sol 5시간 제한 해제, 뱅크드 리셋 배포 |
| Claude AI | 98 | — | Fable 5 연장으로 유저 안도 |
| Cursor | 97 | — | iOS 앱 확산, ARR $4B 돌파 |
| Codex CLI | 90 | ↑1 | 뱅크드 리셋 + 데스크톱 통합 가속 |
| Windsurf | 85 | — | Devin Desktop v3.4.27 안정 |
| Aider | 68 | — | 오픈소스 꾸준, 44K 스타 |
| Gemini CLI | 14 | ↓1 | 셧다운 25일째, 기업 전용 |
| Copilot | 13 | ↓1 | 68주 하락, Vision GA가 반전 포인트? |

OpenAI와 Anthropic이 같은 날 프로모션 카드를 동시에 꺼낸 건 우연이 아니다. 양사 모두 7월 19일을 기점으로 "정상 과금"이 시작되면 유저 행동이 어떻게 변할지 지켜보는 중이다. 이번 주 후반 Sonnet 5.5 출시와 Gemini 3.5 Pro GA가 판세를 흔들 최대 변수다.

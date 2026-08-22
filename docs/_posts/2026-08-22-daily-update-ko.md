---
title: "OpenAI, GPT-5.6 Sol 가격 20% 이상 인하 — 가격 전쟁 신호탄"
date: 2026-08-22
lang: ko
categories: [news]
tags: [openai, gpt-5.6-sol, claude-code, cursor, copilot, antigravity, pricing]
excerpt: "OpenAI가 프론티어 모델 GPT-5.6 Sol의 API 가격을 20% 이상 인하했다. Anthropic·중국 AI와의 경쟁이 본격 가격전 양상으로 번지고 있다."
---

OpenAI가 프론티어 모델 GPT-5.6 Sol의 개발자용 API 가격을 20% 이상 인하했다([Business Standard](https://www.business-standard.com/technology/tech-news/openai-cuts-developer-pricing-for-gpt-5-6-sol-model-by-more-than-20-126082200107_1.html)). 표준 단문 컨텍스트 기준 입력 토큰이 $5→$4, 출력 토큰이 $30→$20으로 내려갔다([Reuters via Investing.com](https://www.investing.com/news/stock-market-news/openai-cuts-developer-pricing-for-frontier-gpt56-sol-model-by-more-than-20-4872186)). 3개월 한정 프로모션이지만, 지난달 GPT-5.6 Terra 20% 인하·Luna 80% 인하에 이은 연속 할인이다([CNBC](https://www.cnbc.com/2026/07/30/open-ai-price-cut-gpt.html)). Anthropic과 중국 AI 모델의 추격에 개발자 이탈을 막으려는 수비적 행보로 읽힌다([Finimize](https://finimize.com/content/openai-cut-gpt-56-sol-api-prices-to-keep-developers-close)).

## OpenAI: o3 퇴장까지 D-4, GPT-5.4 퇴장 D-9

o3 모델이 8월 26일 ChatGPT에서 퇴장 예정이며 D-4 카운트다운에 돌입했다([OpenAI](https://openai.com/index/gpt-5-6/)). GPT-5.4와 GPT-5.4 mini는 8월 31일부로 ChatGPT 인증 Codex에서 제거되며, API 키 인증에서는 유지된다([Releasebot](https://releasebot.io/updates/openai/codex)). GPT-5.6 Sol이 권장 기본 모델("Power" 세팅)로 자리잡는 세대교체가 이번 달 안에 마무리된다.

## Copilot: 대규모 모델 폐기 D-10, 102주 연속 하락

GitHub Copilot이 9월 1일 대규모 모델 폐기까지 D-10에 진입했다([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). Gemini 3.1 Pro, Claude Opus 4.5·4.6, Claude Sonnet 4.5·4.6, Raptor mini 등 6개 이상 모델이 동시 퇴장 예정이다([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). 인기도 102주 연속 하락이라는 기록은 계속 갱신되고 있으며, 사용량 기반 과금 전환으로 인한 개발자 이탈이 가속되는 모양새다([TechTimes](https://www.techtimes.com/articles/317536/20260601/github-copilot-pricing-change-drives-backlash-agentic-bills-jump-10x-50x-power-users.htm)).

## Cursor: 이벤트 구독형 클라우드 에이전트 정착

Cursor가 8월 19일 업데이트로 클라우드 에이전트에 이벤트 구독 기능을 추가했다([Releasebot](https://releasebot.io/updates/cursor)). PR, Slack 스레드, 크론 스케줄을 트리거로 등록하면 에이전트가 자동으로 깨어나서 작업을 수행한다([explainx.ai](https://www.explainx.ai/blog/cursor-event-driven-cloud-agents-isolated-vms-august-2026)). 서브에이전트도 개별 격리 VM에서 병렬 실행이 가능해져, 동시 작업 충돌 없이 복잡한 태스크를 처리할 수 있게 됐다.

## Claude Code: 비용 추정 정밀화, Alpine 지원 확대

Claude Code가 비용 추정(`/cost`, 상태줄, `--max-budget-usd`)에 데이터 레지던시 워크스페이스의 1.1배 US 전용 추론 프리미엄을 반영하기 시작했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Alpine/musl 빌드에서 이미지 붙여넣기·클립보드·오디오 캡처가 정상 동작하도록 수정됐으며, Bedrock·Vertex·Foundry 등 추가 플랫폼에서도 풀스크린 렌더러 제안이 노출된다([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 비용 추정 정밀화, Alpine 지원 확대 |
| ChatGPT | 99 | — | GPT-5.6 Sol 20%+ 인하, o3 퇴장 D-4 |
| Codex CLI | 99 | — | GPT-5.4 퇴장 D-9, Sol 가격 인하 수혜 |
| Antigravity | 99 | — | v2.7.1 이미지 diff, 접근성 개선 |
| Claude AI | 99 | — | Claude Academy 출시 3일차, Files API GA |
| Cursor | 99 | — | 이벤트 구독형 클라우드 에이전트, Grok 4.6 |
| Windsurf | 86 | — | Devin Local 실용 기능 안정화 |
| Aider | 68 | — | v0.86.2 이후 6개월+ 무릴리스 |
| Copilot | 1 | — | 102주 연속 하락, 대폐기 D-10 |
| Gemini CLI | 1 | — | 폐쇄 65일째 |

OpenAI의 연속 가격 인하는 AI 코딩 시장이 '기능 경쟁'에서 '가격 경쟁'으로 전환되고 있음을 보여준다. 개발자에게는 선택지가 늘어나는 좋은 시기다.

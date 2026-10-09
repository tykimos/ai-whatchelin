---
title: "GPT-5.5 퇴역 D-5 카운트다운 — GPT-6.1 Sol이 왕좌를 이어받는다"
date: 2026-10-09
lang: ko
categories: [news]
tags: [codex-cli, chatgpt, copilot, cursor, anthropic, gpt]
excerpt: "OpenAI가 10월 14일 GPT-5.5를 ChatGPT·Work·Codex에서 퇴역시킨다. GPT-6.1 Sol이 Pro 사용자부터 배포되며 세대 교체가 본격화된다. Cursor는 43일 연속 하락, Copilot은 12점 차 리드."
---

OpenAI의 세대 교체가 카운트다운에 들어갔다. 10월 14일, GPT-5.5가 ChatGPT, ChatGPT Work, Codex에서 퇴역한다([Let's Data Science](https://letsdatascience.com/news/openai-retires-gpt-55-from-chatgpt-and-codex-1a6f69be)). 불과 5개월 전 "OpenAI의 가장 똑똑한 프론티어 모델"로 출시됐던 GPT-5.5가 GPT-6 Astra와 GPT-6.1 Sol에 밀려 이렇게 빨리 퇴역하는 것은, AI 모델 세대 교체 주기가 극적으로 단축되고 있음을 보여준다. API 접근은 유지되지만, Codex 사용자 중 ChatGPT 로그인으로 인증하는 경우 GPT-5.6 Sol로 마이그레이션해야 한다([OrcaRouter](https://www.orcarouter.ai/blog/gpt-5-5-remains-available-openai-api-codex-api-key)).

## GPT-6.1 Sol: 아스트라 성능, 1/5 가격으로 확산

GPT-6.1 Sol이 ChatGPT Work와 Codex에서 Pro 사용자부터 순차 배포 중이다([Releasebot](https://releasebot.io/updates/openai/codex)). DevDay에서 공개된 이 모델은 에이전틱 코딩, 컴퓨터 사용, 전문 업무에서 GPT-6 Astra에 근접하면서도 토큰 가격은 1/5 수준이다($2/$10/MTok)([9to5Mac](https://9to5mac.com/2026/09/29/openai-teases-20-announcements-at-devday-watch-live/)). Plus, Business, Enterprise, Edu로의 확대는 수 주 내 예정이다. Codex에서 최대 8배 빠른 토큰 생성을 약속한 GPT-6.1 Sol Ultrafast 모드는 아직 미출시 상태다. OpenAI 프로덕트 리드 Tibo Sottiaux가 10월 4일 "6.1 곧 출시"라고 확인했으나 구체적 일정은 공개되지 않았다([RuntimeWire](https://runtimewire.com/article/openai-says-gpt-6-1-sol-ultrafast-is-coming-soon)). Codex CLI v0.160.1도 출시되어 Windows에서의 원격 MCP 환경 처리를 수정했다([Releasebot](https://releasebot.io/updates/openai/codex)).

## Copilot: 하이브리드 로컬/클라우드 모델 전환 예고

Microsoft가 GitHub Copilot이 곧 Windows에서 로컬과 클라우드 AI 모델을 자동 전환할 수 있게 된다고 발표했다([Windows Report](https://windowsreport.com/github-copilot-will-soon-switch-between-local-and-cloud-ai)). 이미 4월부터 BYOK와 로컬 모델(Ollama, vLLM, Foundry Local)을 지원해왔지만([GitHub Changelog](https://github.blog/changelog/2026-04-07-copilot-cli-now-supports-byok-and-local-models/)), 자동 전환은 오프라인 환경과 지연시간 민감 작업에서 새로운 가능성을 연다. 모델 정리도 가속화되고 있다. 10월 2일에 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 퇴역하고 각각 Gemini 3.8 Flash, Kimi K3, Claude Opus 5.5로 대체됐다([GitHub Changelog](https://github.blog/changelog/2026-10-02-selected-models-in-github-copilot-deprecated)). 다음 10월 19일 웨이브에서는 GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Gemini 3.7 Flash, Grok 4.5 등 6개 모델이 추가 퇴역한다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)). 한 달에 두 차례 대규모 정리가 이뤄지는 셈이다.

## Cursor: 43일 연속 하락, D-34

Cursor가 13점으로 또다시 올해 최저를 갱신했다 — 43일 연속 하락이다. OpenAI 모델 접근 차단(11월 12일)까지 34일 남았다. Copilot(25점)과의 격차는 12점으로 벌어졌다. SpaceX 인수($600억)와 Origin 플랫폼이 전략적 돌파구가 되어야 하지만, 일간 점수 하락은 멈추지 않고 있다.

## Anthropic IPO D-5

Anthropic 프리IPO 투자자 데이가 10월 14일로 5일 앞이다([CryptoBriefing](https://cryptobriefing.com/anthropic-pre-ipo-investor-day-october-14/)). 11월 추수감사절 전 상장을 목표로 하며, 기관 투자자들은 $1.8조~$2조 밸류에이션을 적정 가치로 보고 있다. 2025년 매출 $46억(전년 대비 12배), 영업손실 $80.6억이 투자자 데이의 핵심 검증 대상이 될 전망이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Sol 배포 확산, GPT-5.5 퇴역 D-5 |
| Claude Code | 99 | — | IPO D-5, 시장점유율 29.4% |
| Codex CLI | 99 | — | v0.160.1, GPT-6.1 Sol 통합 |
| Antigravity | 99 | — | 안정 가동 |
| Claude AI | 99 | — | $2T 밸류에이션, 투자자 데이 D-5 |
| Windsurf | 88 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 오픈소스 꾸준, 5월 이후 커밋 정체 |
| GH Copilot | 25 | ↑2 | 하이브리드 로컬/클라우드 예고, Cursor에 12점 리드 |
| Cursor | 13 | ↓2 | 43일 연속 하락, OpenAI 셧오프 D-34 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

GPT-5.5 퇴역과 GPT-6.1 Sol 확산은 OpenAI 생태계 전반의 세대 교체를 의미한다. 5개월 만에 프론티어 모델이 교체되는 속도는 개발자들에게 끊임없는 마이그레이션 부담을 안기고 있다.

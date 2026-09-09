---
title: "Claude Code 9/14 한도 17% 삭감 확정 — McKinsey '빌드 vs 바이' 보고서가 AI 코딩 시장 판도를 읽다"
date: 2026-09-09
lang: ko
categories: [news]
tags: [claude-code, github-copilot, cognition, mckinsey, cursor, openhands, codex-cli]
excerpt: "Anthropic이 9월 14일 Claude Code 주간 한도를 17% 삭감한다. McKinsey 보고서는 기업 32%가 AI 코딩 에이전트로 자체 개발을 선택했다고 밝혔다. Cognition $48B, Copilot 통합 리런치, Cursor 14일째 하락까지 — AI 코딩 시장의 일주일."
---

Anthropic이 9월 14일부터 Claude Code의 주간 사용 한도를 사실상 17% 삭감한다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)). 5월 임시 50% 프로모션을 종료하고 영구 25% 인상분만 남기는 구조로, Pro·Max·Team·Enterprise 전 티어에 적용된다([Android Headlines](https://www.androidheadlines.com/2026/08/anthropic-claude-code-weekly-limits-update.html)). Anthropic은 "25% 영구 인상"이라 표현하지만, 현재 기준으로 보면 17% 감소라는 수학적 사실을 커뮤니티가 빠르게 짚어냈다([Claude Lab](https://claudelab.net/en/articles/claude-code/claude-code-weekly-limit-change-september-14-percent-math)).

## McKinsey: 기업 32%가 "안 사고 직접 만든다"

McKinsey의 2026 State of AI 보고서에 따르면, 조사 대상 기업의 32%가 AI 코딩 에이전트를 활용해 소프트웨어를 자체 개발하면서 외부 구매를 포기했다([Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/build-vs-buy-shift-32-113806700.html)). AI로 EBIT 5% 이상을 올리는 '고성과 기업' 6%에서는 이 비율이 거의 절반에 달했다([McKinsey](https://www.mckinsey.com.br/capabilities/quantumblack/our-insights/the-state-of-ai)). 이 트렌드는 SaaS 업계의 매출 구조를 근본적으로 흔들 가능성이 있다([ANI News](https://aninews.in/news/business/ai-coding-agents-threaten-to-reshape-software-spending-as-companies-choose-to-build-rather-than-buy-mckinsey20260906210256/)).

## Cognition AI: $2B 시리즈 E, $48B 밸류에이션

Cognition AI(Devin·Windsurf 모회사)가 Andreessen Horowitz·Accel 공동 리드로 $2B 시리즈 E를 마감했다([TechCrunch](https://techcrunch.com/2026/09/08/cognition-hits-48b-valuation-signaling-investors-believe-ai-coding-is-far-from-a-winner-take-all-market/)). 5월 $26B에서 4개월 만에 거의 두 배로 뛰었고, 런레이트 매출도 $492M→약 $900M으로 급성장했다([Unite.AI](https://www.unite.ai/cognition-raises-over-2b-series-e-at-48b-valuation-to-scale-devin-agents/)). 고객 리스트에 Citi, Goldman Sachs, NASA-JPL, 미 해군까지 포함되며 엔터프라이즈 시장 장악력이 뚜렷하다([ITdaily](https://itdaily.com/news/business/cognition-raises-2-dollars-billion/)).

## GitHub Copilot: 9/28 통합 리런치 + 10/2 모델 교체

GitHub Copilot이 9월 28일부로 Chat·Mobile·Cloud Agent를 단일 경험으로 통합한다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 코드 리뷰 기본값이 Lite→Balanced로 바뀌어 AI 크레딧 소비가 증가할 수 있다. 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 퇴역하고 Gemini 3.8 Flash, Kimi K3, Claude Opus 5로 교체된다([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). 점수 1의 바닥권에서 반등할 수 있을지 9/28이 분수령이다.

## OpenHands 1.0: 오픈소스 코딩 에이전트 첫 프로덕션 릴리스

오픈소스 자율 코딩 에이전트 OpenHands가 1.0에 도달했다([DEV Community](https://dev.to/jamilxt/openhands-just-hit-10-heres-how-to-run-it-on-your-own-machine-without-handing-over-the-keys-5666)). SWE-bench Verified 68%, 셀프 호스팅 시 태스크당 $0.20~$1.05로 상용 에이전트 비용의 1/10 수준이다. McKinsey가 보여준 '빌드 vs 바이' 트렌드와 맞물려, 오픈소스 코딩 에이전트가 세 번째 진영으로 부상하고 있다.

## Cursor: 71점, 14일째 하락 — D-64

Cursor가 71로 14일째 하락을 이어가며 8월 27일(99) 대비 28포인트가 빠졌다. 한편 Cursor는 자체 호스팅 머신과 Linux·Mac 컴퓨터 사용(브라우저·데스크톱 제어) 기능을 추가하며 제품 개선에 집중하고 있다([Cursor Blog](https://cursor.com/blog)). OpenAI 모델 차단(11/12)까지 64일, Fable 5.1이 Cursor 코딩 벤치마크 73.4%로 역대 최고를 기록하며 Anthropic 의존도가 높아지는 역설적 구도다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra GA, DevDay 20일 전 |
| Claude Code | 99 | — | v2.1.261 안정, 9/14 한도 변경 대기 |
| Claude AI | 99 | — | 캐시 비용 75% 인하 유지 |
| Codex CLI | 99 | — | Astra 기본, Security CLI 오픈소스화 |
| Antigravity | 99 | — | Gemini 3.8 Flash 적용 |
| Windsurf | 87 | ↑1 | Cognition $48B, $2B 시리즈 E |
| Cursor | 71 | ↓2 | 14일째 하락, 셀프 호스팅 추가 |
| Aider | 68 | — | v0.86.2 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 9/28 통합 리런치 대기 |
| Gemini CLI | 1 | — | 폐쇄 83일째, Antigravity 대체 |

McKinsey 보고서가 보여주듯 AI 코딩 에이전트가 기업 소프트웨어 구매 패턴 자체를 바꾸고 있다. Cognition/Windsurf($48B) vs SpaceX/Cursor($60B) vs OpenHands 오픈소스 — 3대 진영이 굳어지는 가운데, Claude Code의 9/14 한도 조정과 Copilot의 9/28 리런치가 다음 주 시장 지형을 결정할 변수다.

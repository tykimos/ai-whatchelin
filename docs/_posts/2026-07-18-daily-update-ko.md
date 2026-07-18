---
title: "Fable 5 무료 D-1 카운트다운 — Anaconda가 삼킨 3백만 개발자 에이전트"
date: 2026-07-18
lang: ko
categories: [news]
tags: [claude, fable-5, codex-cli, anaconda, kilo-code, inkling, cursor, devin]
excerpt: "Anthropic Fable 5 무료 접근이 내일(7/19) 자정 만료된다. Anaconda는 Kilo Code를 인수해 월 10조 토큰 파이프라인을 확보했고, Mira Murati의 Inkling이 오픈 웨이트 전선에 합류했다."
---

Anthropic의 Fable 5 무료 접근이 내일 7월 19일 오후 11:59 PT에 종료된다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/claude-fable-5-stays-free-for-paid-users-until-july-19-as-anthropic-buys-more-time/)). 6월 12일 미국 수출 통제로 중단된 이후 세 번째 연장이었지만, 이번에는 더 이상 연장 없이 사용량 크레딧(입력 $10/MTok, 출력 $50/MTok)으로 전환될 전망이다([Dataconomy](https://dataconomy.com/2026/07/13/claude-fable-5-free-access-extended-july-19/)). Opus 5 출시 여부에 커뮤니티의 관심이 집중되고 있다.

## Anaconda, Kilo Code 인수 — 월 10조 토큰의 제국

Anaconda가 3백만 이상 개발자가 사용하는 오픈소스 에이전트 Kilo Code를 인수했다([BusinessWire](https://www.businesswire.com/news/home/20260715437804/en/Anaconda-Acquires-Kilo-Code-to-Power-the-Trillion-Token-Enterprise)). Kilo는 VS Code, JetBrains, CLI에서 월 10조 토큰을 처리하며, 초기 고객들은 Anaconda 플랫폼을 통해 토큰 소비를 30~50% 줄였다고 보고한다([Anaconda Blog](https://www.anaconda.com/blog/anaconda-acquires-kilo-code)). 공동 창업자 Sid Sijbrandij는 *"Kilo와 Anaconda는 겹치는 게 거의 없고, 서로에게 없는 걸 가지고 있다"*고 평가했다.

## Thinking Machines Inkling — Mira Murati의 첫 오픈 웨이트 모델

전 OpenAI CTO Mira Murati의 Thinking Machines Lab이 975B 파라미터 MoE 모델 Inkling을 공개했다([TechCrunch](https://techcrunch.com/2026/07/15/thinking-machines-amps-up-its-bet-against-one-size-fits-all-ai-with-its-first-open-model-inkling/)). 태스크당 41B만 활성화되며 45조 토큰으로 학습했다. 금융 추론에서 84.7%를 기록하면서도 실행 비용은 경쟁 모델의 1/14 수준이다([Fortune](https://fortune.com/2026/07/15/what-is-mira-murati-thinking-machines-first-ai-model-inkling/)). "최강 모델"보다 "커스터마이징 가능한 출발점"을 지향하는 전략이 특징이다.

## Codex CLI v0.144.6 — GPT-5.6 모델 메타데이터 리프레시

오늘 출시된 Codex CLI v0.144.6은 GPT-5.6 Sol, Terra, Luna 번들 인스트럭션을 갱신하고 컨텍스트 윈도우를 272K 토큰으로 수정했다([GitHub](https://github.com/openai/codex/releases)). v0.145.0 알파 빌드도 이틀간 10개 이상 릴리스되며 차기 마이너 버전 개발이 가속화되고 있다.

## Cursor in Slack — 멀티 레포, 크로스 채널 워크플로

Cursor의 Slack 통합이 어제(7/17) 대폭 업그레이드됐다([Cursor Changelog](https://cursor.com/changelog)). 작업 전 계획을 공유하고, 프론트엔드·백엔드·공유 코드를 단일 Slack 요청에서 넘나들며, 다른 채널과 스레드에서 컨텍스트를 끌어오는 크로스 채널 워크플로를 지원한다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 데스크톱 내장 브라우저, /doctor 추가 |
| Antigravity | 99 | — | v2.3.1 핫픽스, 27주 연속 |
| ChatGPT | 99 | — | Work 에이전트 데스크톱 통합 |
| Claude AI | 98 | — | Fable 5 무료 D-1, Opus 5 관심 |
| Cursor | 97 | — | Slack 멀티레포·크로스채널 |
| Codex CLI | 90 | — | v0.144.6, GPT-5.6 272K 컨텍스트 |
| Windsurf | 85 | — | Goldman Sachs "Employee #1" 배치 |
| Aider | 68 | — | v0.86.0, GPT-5·Grok-4 지원 |
| Gemini CLI | 8 | ↓1 | EOL 30일차, 3.5 Pro 지연 지속 |
| Copilot | 8 | ↓1 | 73주 하락, Code Quality GA 임박 |

Fable 5 무료 종료를 앞두고 개발자들의 모델 선택 전략이 달라질 수 있다. Anaconda-Kilo Code 인수는 엔터프라이즈 에이전트 시장에서 패키지 생태계와 에이전트 플랫폼의 결합이라는 새 공식을 제시한다.

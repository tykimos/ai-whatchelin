---
title: "Cursor 3.11 사이드 챗 출격, Antigravity 99 돌파 — Fable 5 구독 포함 D-1"
date: 2026-07-11
lang: ko
categories: [news]
tags: [cursor, antigravity, claude-code, copilot, fable-5, gpt-5-6, gemini-3-5-pro]
excerpt: "Cursor 3.11이 사이드 챗과 에이전트 검색을 도입하고, Antigravity가 99를 찍으며 22주 연속 상승 기록을 세웠다. 내일 Fable 5 구독 포함이 종료된다."
---

Cursor가 3.11 업데이트로 사이드 챗을 도입하며 에이전트 병렬 대화의 새 기준을 제시했다. 메인 에이전트가 작업하는 동안 `/side`로 별도 질문을 던지고, 그 결과를 메인 스레드에 `@`멘션으로 끌어올 수 있다([Cursor Changelog](https://cursor.com/changelog)). 한편 Antigravity는 99를 찍으며 22주 연속 상승이라는 전무후무한 기록을 세웠고, 내일이면 Fable 5의 구독 포함 접근이 종료된다.

## Cursor 3.11: 사이드 챗과 에이전트 트랜스크립트 검색

사이드 챗은 메인 에이전트 대화를 중단하지 않고 탐색, 질문, 검증을 할 수 있는 병렬 에이전트 대화다([Cursor Changelog](https://cursor.com/changelog)). `/side`, `/btw`, 또는 채팅 패널 상단 `+` 버튼으로 생성하며, 각 사이드 챗은 독립적인 에이전트 세션으로 나중에 재방문할 수 있다. 에이전트 트랜스크립트 검색(Cmd+K)도 추가되어 수천 개의 과거 대화를 로컬 인덱스로 즉시 검색할 수 있다. 클라우드 에이전트 훅(`beforeSubmitPrompt`, `afterAgentResponse`, `stop` 등)과 Team MCP 서버 일괄 배포 기능도 함께 출시되었다.

## Antigravity 99 — 22주 연속 상승, Gemini 3.5 Pro 7월 17일 확정

Antigravity가 99를 찍으며 22주 연속 상승 기록을 갱신했다. Gemini 3.5 Pro의 7월 17일 출시가 다수 매체에 의해 보도되면서 Google 에이전틱 생태계에 대한 기대감이 높아졌다([BigGo Finance](https://finance.biggo.com/news/6f0c6bb2-795f-4c57-9d09-6db691d7638a)). 수학적 추론, SVG 생성, 이미지 품질 개선에 집중한 아키텍처 개편이 GPT-5.6, Fable 5와의 경쟁을 겨냥하고 있다. Gemini CLI는 셧다운 23일째로 16까지 하락했다.

## Claude Code v2.1.207 — Bedrock에서 자동 모드 기본 활성화

Claude Code v2.1.207이 출시되어 Bedrock, Vertex AI, Foundry에서 자동 모드가 기본 활성화되었다([Releasebot](https://releasebot.io/updates/anthropic)). Bedrock의 기본 모델이 Opus 4.8로 업그레이드되었으며, 스트리밍 중 터미널 멈춤·키 입력 지연이 수정되었다. 전일 출시된 v2.1.206에서는 데스크톱 내장 브라우저, `/doctor` CLAUDE.md 경량화 제안, `/code-review` Opus 4.8 품질 개선 등이 포함됐다.

## Fable 5 구독 포함 D-1 — 내일 종료

Anthropic이 7월 7일 백래시에 대응해 7월 12일까지 연장한 Fable 5 구독 포함 접근이 내일(PT 기준 23:59:59) 종료된다([Forbes](https://www.forbes.com/sites/sandycarter/2026/07/07/claude-fable-5-extends-by-five-more-days-10-moves-to-make-now/)). 이후 $10/$50 per MTok 사용 크레딧 방식으로 전환되며, Anthropic은 용량 확보 시 구독 플랜 복귀를 예고했지만 구체적 일정은 없다.

## Copilot CLI v1.0.70-71 — GPT-5.6 지원, /refine 명령어

Copilot CLI v1.0.70이 GPT-5.6 Sol/Terra/Luna 모델 지원, 페이지네이션 MCP 리소스 관리, `/refine` 프롬프트 재작성 명령어를 도입했다([Releasebot](https://releasebot.io/updates/github)). v1.0.71에서는 고정 프롬프트(pinned prompts)와 Repo 스코프 탭이 추가됐다. 하지만 Copilot의 인기 점수는 15로 66주 연속 하락 기록을 이어가고 있다.

## SPCX ~$148 — 포스트 IPO 조정 심화

SpaceX 주가가 ~$148로 하락하며 $225 ATH 대비 34% 하락폭을 기록했다([TradingKey](https://www.tradingkey.com/analysis/stocks/us-stocks/262021751-spacex-spcx-stock-forecast-july-10-2026-grok-45-blue-origin-tradingkey)). 8월 6일 실적 발표가 다음 촉매제로 꼽히며, 애널리스트 컨센서스 목표가는 $212로 현재 대비 46% 상승 여력이 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.207, Bedrock 자동 모드 기본 |
| Antigravity | 99 | ↑1 | 22주 연속 상승, 역대 최고 |
| ChatGPT | 98 | — | GPT-5.6 3일차, 슈퍼 앱 안착 |
| Claude AI | 98 | — | Fable 5 구독 포함 내일 종료 |
| Cursor | 96 | — | 3.11 사이드 챗, 에이전트 검색 |
| Codex CLI | 89 | — | GPT-5.6 Bedrock 통합 완료 |
| Windsurf | 85 | — | Devin Desktop 안정화 |
| Aider | 68 | — | 오픈소스 꾸준 |
| Gemini CLI | 16 | ↓1 | 셧다운 23일째, 기업 전용 |
| Copilot | 15 | ↓1 | 66주 연속 하락, 종량제 41일차 |

Cursor의 사이드 챗은 에이전트 병렬 작업의 UX를 한 단계 끌어올렸고, Antigravity는 Gemini 3.5 Pro 확정 기대감으로 Claude Code와 나란히 99에 도달했다. 내일 Fable 5 무료 접근이 종료되면서 크레딧 전환 충격이 올 가능성이 있다.

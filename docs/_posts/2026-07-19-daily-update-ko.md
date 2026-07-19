---
title: "Fable 5 무료 D-Day — Kimi K3가 프론트엔드 코드 벤치 1위를 찍다"
date: 2026-07-19
lang: ko
categories: [news]
tags: [claude, fable-5, kimi-k3, claude-code, gemini, copilot, grok-build, deepseek]
excerpt: "Anthropic Fable 5 무료 접근이 오늘 자정(PT) 종료된다. Moonshot AI의 Kimi K3가 2.8T 파라미터로 Arena.ai 프론트엔드 코드 1위를 차지했고, Gemini 3.5 Pro는 또다시 지연됐다."
---

Anthropic의 Fable 5 무료 접근이 오늘 7월 19일 오후 11:59 PT에 공식 종료된다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/claude-fable-5-stays-free-for-paid-users-until-july-19-as-anthropic-buys-more-time/)). 6월 12일 수출 통제 이후 세 번째 연장이었지만, 이번에는 네 번째 연장 가능성이 보이지 않는다. 내일부터 Fable 5는 프리페이드 크레딧 방식(입력 $10/MTok, 출력 $50/MTok)으로 전환된다([Dataconomy](https://dataconomy.com/2026/07/13/claude-fable-5-free-access-extended-july-19/)). Claude Code의 50% 추가 주간 한도 프로모션도 동시에 만료된다([Help Net Security](https://www.helpnetsecurity.com/2026/07/13/claude-code-weekly-limits-promotion-extended/)).

## Kimi K3 — 2.8T 파라미터의 중국발 도전장

Moonshot AI가 2.8T 파라미터 MoE 모델 Kimi K3를 공개했다([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/moonshot-releases-2-8-trillion-parameter-kimi-k3)). Arena.ai 프론트엔드 코드 아레나에서 76% 쌍대 비교 승률로 Fable 5를 꺾고 1위를 차지했으며, Terminal-Bench 2.1에서 88.3점을 기록했다([Fortune](https://fortune.com/2026/07/16/moonshots-kimi-k3-pushes-chinese-ai-into-fable-level-territory/)). 가격은 입력 $3, 출력 $15/MTok으로 설정됐고, 7월 27일까지 오픈 웨이트 공개가 예고돼 있다([CNBC](https://www.cnbc.com/2026/07/17/moonshot-ai-kimi-k3-model-openai-anthropic-china.html)).

## Claude Code v2.1.215 — 자율 스킬 실행 제한

오늘 출시된 Claude Code v2.1.215는 `/verify`와 `/code-review` 스킬을 사용자가 직접 호출했을 때만 실행하도록 변경했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 전날의 v2.1.214는 Windows PowerShell 5.1 권한 우회 수정, 10,000자 이상 명령어의 강제 프롬프트, 장시간 도구 호출에 대한 하트비트 기능 등을 포함하는 대형 보안·안정성 패치였다.

## Gemini 3.5 Pro — 또 한 번의 지연

Google이 Gemini 3.5 Pro 출시를 다시 연기했다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-july-18-2026)). 리빌드된 모델이 코딩 및 복잡한 추론 테스트에서 기대에 미치지 못한 것이 원인이다. Alphabet 주가가 약 4% 하락했다. Gemini CLI는 이미 Antigravity CLI로 전환이 완료된 상태에서([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)), 3.5 Pro 지연은 Google AI 에코시스템 전체에 불확실성을 더하고 있다.

## Copilot CLI v1.0.71 — 보이스·캔버스 지원

GitHub Copilot CLI v1.0.71이 `/voice devices` 명령으로 음성 입력 디바이스 선택·저장을 지원하고, 확장 기반 캔버스 인터랙션과 플랜 모드의 워크스페이스 수정 차단 기능을 추가했다([GitHub Releases](https://github.com/github/copilot-cli/releases/tag/v1.0.71)). 74주째 하락세지만 기능 면에서는 여전히 업데이트가 이어지고 있다.

## Opus 5 "Honeycomb" — 커뮤니티 소문

7월 8~9일 Cursor 모델 선택기에 "Claude Honeycomb EAP"가 잠깐 등장했다([TechTimes](https://www.techtimes.com/articles/320265/20260712/fable-5-free-through-july-19-anthropic-blinks-again-opus-5-leak-surfaces-cursor.htm)). 유출된 스펙은 1M 토큰 컨텍스트, xhigh 추론 설정, Opus 4.8 안전 폴백을 포함하며, 커뮤니티에서는 7월 중순~8월 초 출시를 전망하고 있다. Anthropic의 공식 발표는 아직 없다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.215, 자율 스킬 실행 제한 |
| ChatGPT | 99 | — | GPT-5.5 Instant Mini 롤아웃 |
| Antigravity | 99 | — | v2.3.1, 28주 연속 상승 |
| Claude AI | 98 | — | Fable 5 무료 D-Day, Opus 5 관심 |
| Cursor | 97 | — | Slack 크로스채널, SpaceX 인수 진행 |
| Codex CLI | 90 | — | v0.144.6 안정, GPT-5.6 272K |
| Windsurf | 85 | — | Devin Desktop 리브랜딩 안착 |
| Aider | 68 | — | 안정 유지 |
| Copilot | 7 | ↓1 | 74주 하락, CLI v1.0.71 보이스 추가 |
| Gemini CLI | 7 | ↓1 | EOL 31일차, 3.5 Pro 지연 심화 |

Fable 5 유료 전환과 Kimi K3의 등장이 동시에 일어나면서, 개발자들의 모델 선택지가 그 어느 때보다 다양해졌다. 비용 대비 성능이 핵심 기준이 되는 시대가 본격화되고 있다.

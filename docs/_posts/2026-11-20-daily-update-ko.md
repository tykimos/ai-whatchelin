---
title: "Gemini 4 Neon, CursorBench 1위로 코딩 모델 전쟁 재점화"
date: 2026-11-20
lang: ko
categories: [news]
tags: [google, gemini, antigravity, openai, codex-cli, github-copilot, microsoft, cursor, anthropic]
excerpt: "Google이 Gemini 4 Neon을 출시하며 코딩 벤치마크 판도를 뒤흔들었다. Codex CLI는 TUI 워크스페이스를 기본 활성화하고, 5개 도구 99점 동률은 5일째 이어지고 있다."
---

Google이 화요일 발표한 Gemini 4 Neon이 코딩 모델 경쟁 구도를 다시 뒤흔들고 있다. CursorBench에서 1위를 차지하고 Vals Index에서 70.9%로 Anthropic Claude Fable 5.2(71.3%)에 불과 0.4%p 차이로 2위를 기록했다([blog.google](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-neon/)). Artificial Analysis 코딩 에이전트 지수에서도 61점으로 Claude Opus 5.5(59점)와 GPT-6.2 Sol(57점)을 앞섰다. 특히 Terminal-Bench 4.0 치팅률 0.0%는 Gemini 4 모델군 최저치로, Argon 세대에서 지적받았던 벤치마크 신뢰도 문제를 정면으로 돌파한 셈이다.

## Codex CLI: v0.171.0 TUI 워크스페이스 기본 활성화

OpenAI Codex CLI가 오늘 v0.171.0을 릴리스했다([Releasebot](https://releasebot.io/updates/openai)). TUI 워크스페이스가 기본 활성화되어 리치 미리보기, 실행취소/다시실행 설정, 원격 세션 제어가 추가됐다. 이틀 전 v0.170.0에서 도입된 WebRTC 음성 통화에 이어 Codex CLI의 TUI 환경이 빠르게 진화하고 있다.

## GPT-6.2 Astra & Sol: 출시 3일차 — Fable 5.2에 밀려

GPT-6.2 Astra와 Sol이 11월 17일 출시된 이후 3일째 운영 중이다([openai.com](https://openai.com/index/introducing-gpt-6-2-astra-sol)). Astra는 $8/$40/MTok(GPT-6 Astra 대비 20% 인하), Sol은 $2/$10/MTok으로 가격 경쟁력을 갖췄다. 그러나 독립 테스트에서 Astra는 Fable 5.2에 이어 2위로 평가되고 있으며([Decrypt](https://decrypt.co/383488/openai-gpt-6-2-astra-challenges-anthropic-price-but-not-every-benchmark)), Gemini 4 Neon의 등장으로 3위 싸움도 시작됐다.

## Microsoft MAI Code 2: Ignite 발표 후 Copilot 통합 진행

Microsoft가 Ignite에서 발표한 MAI Code 2와 Code 2 Flash가 GitHub Copilot에서 사용 가능하다([InfoWorld](https://www.infoworld.com/article/4250152/microsoft-launches-mai-code-2-models-to-challenge-openai-and-anthropic-in-ai-coding.html)). GPT-6 Luna 대비 65% 비용, Claude Haiku 5.5 대비 20% 비용으로 동급 성능을 주장하고 있다. Microsoft의 첫 본격적 자체 코딩 모델 도전이다.

## Cursor: OpenAI 차단 9일째

OpenAI 모델 공급 종료 이후 9일째다. Tab 자동완성, 클라우드 에이전트, CLI 등 핵심 기능이 여전히 작동하지 않으며 89일째 바닥(1점)을 기록 중이다. Live Apps, Voice Chat 등 기능 출시는 계속되지만, 엔진 없는 혁신이라는 역설은 해소되지 않고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 3일차, Codex 0.171.0 TUI 워크스페이스 |
| Claude Code | 99 | — | ANT 상장 2일차, Fable 5.2 Vals Index 1위 유지 |
| Codex CLI | 99 | — | v0.171.0 TUI 기본 활성화, 연일 릴리스 |
| Antigravity | 99 | — | Gemini 4 Neon 롤아웃, CursorBench 1위 |
| Claude AI | 99 | — | ANT $95 부근 안정화 |
| GH Copilot | 99 | — | 58일 연속 최고점, MAI Code 2 추가 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 9일째, 89일 연속 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 |

5개 도구 99점 동률이 5일째 이어지고 있다. 이번 주에만 GPT-6.2 Astra/Sol, Gemini 4 Neon, MAI Code 2가 동시 출시되면서 코딩 모델 전쟁이 역대 가장 치열한 국면에 접어들었다.

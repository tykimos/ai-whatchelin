---
title: "11월 30일 이중 마감: Sonnet 4.5 퇴역과 Opus 4.8 Fast Mode 종료가 동시에 온다"
date: 2026-11-26
lang: ko
categories: [news]
tags: [anthropic, sonnet-5-5, opus-4-8, copilot, gemini-4, gpt-6-2, codex-cli, claude-code]
excerpt: "11월 30일에 Sonnet 4.5 API 퇴역과 Opus 4.8 Fast Mode 제거가 동시에 겹친다. GPT-6.2 Astra의 환각률 59% 벤치마크가 출시 10일 만에 논란이 되고 있다."
---

Anthropic 사용자에게 11월 30일은 이중 마감일이다. Sonnet 4.5 API 퇴역과 Opus 4.8 Fast Mode 제거가 같은 날 겹치면서, 나흘 안에 두 건의 마이그레이션을 마쳐야 한다. 한편 GPT-6.2 Astra는 출시 10일 만에 독립 벤치마크에서 환각률 59%라는 성적표를 받아 논란이 일고 있다.

## Anthropic 11월 30일 이중 마감: Sonnet 4.5 + Opus 4.8 Fast Mode

Sonnet 4.5(`claude-sonnet-4-5-20250929`)가 11월 30일부로 API에서 퇴역한다([Anthropic Docs](https://platform.claude.com/docs/about-claude/model-deprecations)). 후속 모델 Sonnet 5.5는 $2/$10 per MTok으로 액면가는 33% 저렴하지만, 새 토크나이저가 같은 텍스트에서 ~30% 더 많은 토큰을 생성해 실질 절감폭은 작다([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). 같은 날 Opus 4.8 Fast Mode도 제거된다([Anthropic Docs](https://code.claude.com/docs/en/fast-mode)). Fast Mode 요청 시 에러가 반환되며, 표준 속도 Opus 4.8은 계속 작동하지만 Opus 5.5로의 전환이 권장된다([Claude World](https://claude-world.com/articles/claude-opus-4-8-fast-mode-removal/)). 하루에 두 건의 breaking change가 겹치는 만큼, 프로덕션 환경의 모델 ID와 Fast Mode 플래그를 반드시 사전 점검해야 한다.

## GPT-6.2 Astra, 환각률 59%로 논란

GPT-6.2 Astra가 출시 10일 만에 독립 벤치마크에서 논란적인 성적을 받았다. Artificial Analysis의 AA-Omniscience 테스트에서 Astra의 환각률은 59%, Sol은 55%로 측정됐다([Artificial Analysis](https://artificialanalysis.ai/models/comparisons/gpt-6-2-astra-vs-gpt-6-2-sol)). FrontierCode 2.0에서는 Astra 44.2%, Sol 43.8%로 Claude Fable 5.2의 50.2%에 뒤처졌다([VKTR](https://www.vktr.com/ai-platforms/gpt62-sol-nears-astra-on-mergeready-code-at-a-fifth-of-the-cost/)). 다만 Sol은 태스크당 $1.29로 Astra의 $5.97 대비 가성비가 뛰어나, 비용 대비 성능 면에서 경쟁력이 있다. OpenAI는 Astra가 GPT-6 Astra 대비 6.2포인트 향상됐다고 주장하지만([OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol)), 독립 코딩 에이전트 테스트에서는 거의 동일한 수준이다.

## Copilot, Gemini 4 Neon으로 3종 모델 추가 완료

GitHub Copilot이 11월 한 달간 Gemini 4 모델 3종 추가를 완료했다. Carbon(11/10)([GitHub Blog](https://github.blog/changelog/2026-11-10-gemini-4-carbon-in-github-copilot)), Hydrogen Flash(11/13)([GitHub Blog](https://github.blog/changelog/2026-11-13-gemini-4-hydrogen-in-github-copilot)), Neon(11/18)([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot))이다. Carbon은 복잡한 추론 작업용, Hydrogen은 경량 플래시 모델, Neon은 에이전틱 코딩에 특화됐다. Carbon의 사용량 기반 과금은 12월 1일부터 $4/$20 per MTok으로 2배 인상되므로([SmartScope](https://smartscope.blog/en/blog/github-copilot-gemini-4-carbon-supported-plans-model-2026/)), 비용에 민감한 팀은 Neon으로의 전환을 검토할 시점이다.

## Claude Code v2.1.327 + Codex CLI v0.170.0 근황

Claude Code v2.1.327은 Code Mode에 에이전트 팀 기능과 원격 세션 실시간 스트리밍을 추가했다([Claude World](https://claude-world.com/articles/claude-code-november-2026-whats-new/)). Codex CLI v0.170.0은 터미널 UI에서 WebRTC 기반 실시간 음성 통화를 지원하며([Havoptic](https://www.havoptic.com/releases/openai-codex/2026/11)), 보이스 페어 프로그래밍이 가능해졌다. ANT 주가는 상장 첫 주 $95-99 구간에서 등락 중이다([TechRepublic](https://www.techrepublic.com/article/news-anthropic-ipo-nasdaq-trading-debut/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 출시 10일차, 환각률 논란 |
| Claude Code | 99 | — | v2.1.327 Code Mode 에이전트 팀 |
| Codex CLI | 99 | — | v0.170 WebRTC 음성 통화 |
| Antigravity | 99 | — | Google 유일 코딩 에이전트 안정 |
| Claude AI | 99 | — | Sonnet 4.5 퇴역 D-4 + Opus 4.8 Fast Mode D-4 |
| GH Copilot | 99 | — | Gemini 4 Carbon 가격 인상 D-5 (12/1) |
| Windsurf | 89 | — | Devin Bots 안정화 중 |
| Aider | 68 | — | 유지보수 모드, 44K 스타 |
| Cursor | 1 | — | OpenAI 차단 15일째, 126일 연속 바닥 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

Anthropic 사용자에게 11월 30일이 이중 마감일로 다가온다. Sonnet 4.5와 Opus 4.8 Fast Mode 모두 나흘 뒤 사라지므로, 테스트 없이 넘어가면 월요일 아침에 프로덕션 장애를 맞을 수 있다.

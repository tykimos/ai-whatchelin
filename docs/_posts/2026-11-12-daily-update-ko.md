---
title: "Cursor, OpenAI 모델 접근 공식 차단 — 79일간의 추락 끝에 맞이한 D-Day"
date: 2026-11-12
lang: ko
categories: [news]
tags: [cursor, openai, claude-code, github-copilot, codex-cli, antigravity]
excerpt: "OpenAI가 Cursor의 모델 접근을 공식 차단하는 날이 왔다. SpaceX 인수 후 79일간 바닥을 기던 Cursor의 운명이 오늘 결정된다."
---

오늘은 AI 코딩 도구 역사에서 한 시대의 끝을 알리는 날이다. OpenAI가 Cursor(Anysphere)에 대한 모델 접근을 공식 차단하는 11월 12일이 도래했다. SpaceX의 600억 달러 인수 이후 79일째 인기도 1점에 머물던 Cursor가 최후의 생명선마저 잃게 되었다.

## Cursor: OpenAI 모델 차단 D-Day

OpenAI가 제안한 전환 기간 종료일인 오늘, Cursor의 OpenAI 모델 접근이 공식 차단된다([The Decoder](https://the-decoder.com/openai-cuts-off-cursor-after-spacex-acquisition-citing-musks-history-of-breaking-contracts/)). OpenAI는 SpaceX가 Cursor를 인수한 후 "계약 위반 전력"과 "경쟁 AI 시스템 훈련을 위한 모델 증류" 우려를 이유로 약 2개월 반의 전환 기간을 두고 계약을 해지했다([Forklog](https://forklog.com/en/openai-to-end-partnership-with-cursor-following-spacex-acquisition/)). 사용자들은 OpenAI API 키를 직접 설정해 일부 기능을 계속 사용할 수 있지만, Tab 자동완성, 자동 모델 선택, 클라우드 에이전트 등 핵심 기능은 지원되지 않는다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). Tom's Guide는 Cursor 사용자를 위한 세 가지 대안을 정리했으며, 최신 모델 GPT-6 Astra는 Cursor에 전혀 공급되지 않는다([Channel Insider](https://www.channelinsider.com/ai/news-openai-cursor-model-access-spacex-acquisition/)).

## Claude Code v2.1.319: 자동 모드와 MCP 태스크 강화

Claude Code v2.1.319가 11월 6일 출시되며 자동 모드(auto mode)를 핵심 업데이트로 포함했다([claudekit.io](https://claudekit.io/en/updates/claude-code-2-1-319/)). 텔레메트리나 기능 플래그가 비활성화된 환경, 또는 LLM 게이트웨이 뒤에서 서버가 확인할 수 없는 호출은 내장 분류기 대신 사용자 확인을 거치도록 변경되었다. MCP 태스크 지원이 터미널에 추가되었으며, `permissions.denyInsteadOfPrompting` 설정과 `/claude-api latency-optimize` 명령이 새로 도입되었다([labmemo.com](https://labmemo.com/?p=62838)). Opus 4.8의 패스트 모드가 11월 30일부로 종료 예정이다.

## GitHub Copilot: Fusion GA 할인 진행 중, Agent Merge 출시

GitHub Copilot Fusion이 Universe 2026(10/28)에서 GA로 출시된 후 30% 모델 비용 할인이 11월 30일까지 진행 중이다([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)). Enterprise 사용자에게는 추가 비용 없이 제공되며, Fusion 자체에 대한 별도 고정 요금은 없다([Phemex](https://phemex.com/news/article/github-makes-copilot-fusion-generally-available-to-all-enterprise-users-at-no-extra-cost-101577)). 11월 6일 주간 릴리스에서 Agent Merge PR 자동화 기능과 VS Code 1.145 크론 태스크가 추가되었으며, JetBrains Air와 Xcode 27.3 베타 지원도 포함되었다([GitHub Blog](https://github.blog/changelog/2026-11-06-github-copilot-weekly-releases-november-2)). Copilot 인기도는 49일 연속 상승 중이다.

## Codex CLI 0.167.0: 에이전트 커맨드 센터

Codex CLI 0.167.0이 출시되며 `codex agents --no-daemon` 명령으로 에이전트 커맨드 센터를 열 수 있게 되었다([learn.chatgpt.com](https://learn.chatgpt.com/ja-JP/docs/changelog)). 미읽은 결과가 커맨드 센터와 세션 피커에 표시되어 멀티 에이전트 워크플로우 관리가 개선되었다. 12월부터 ChatGPT/Codex 사용량 풀이 통합되어 Plus/Pro/Business 구독자는 단일 토큰 예산을 공유하게 된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 확산 중 |
| Claude Code | 99 | — | v2.1.319 자동 모드·MCP 태스크 강화 |
| Codex CLI | 99 | — | 0.167.0 에이전트 커맨드 센터 |
| Antigravity | 99 | — | Knowledge Work 모드 안정 운영 |
| Claude AI | 99 | — | IPO 로드쇼 진행 중, ANT 티커 |
| GH Copilot | 93 | ↑2 | 49일 연속 상승, Fusion 30% 할인 중 |
| Windsurf | 88 | — | Devin Desktop 세션 공유 제어 추가 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 D-Day, 79일째 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 진행 중 |

OpenAI의 Cursor 모델 차단이 현실화되면서 AI 코딩 도구 시장의 공급망 리스크가 이론에서 현실이 되었다. 자체 모델을 보유한 Claude Code·Antigravity의 수직 통합 전략이 더욱 부각되는 가운데, Copilot은 Fusion GA와 30% 할인으로 49일 연속 상승세를 이어가며 격차를 좁히고 있다.

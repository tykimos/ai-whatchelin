---
title: "Codex CLI 0.166 출시, Copilot에서 Claude Opus·GPT-5.6 모델 퇴장 임박"
date: 2026-11-01
lang: ko
categories: [news]
tags: [codex-cli, github-copilot, deepseek, anthropic]
excerpt: "Codex CLI 0.166.0이 키보드 기반 트랜스크립트 검색과 queue --resume을 추가했다. GitHub Copilot은 11월 16일부로 Claude Opus 4.8·5.0, GPT-5.6 Terra를 전면 퇴장시킨다."
---

11월의 첫날, AI 코딩 도구 시장은 작은 변화들이 겹치며 새 흐름을 예고하고 있다. Codex CLI가 주간 릴리스를 이어가고, Copilot은 모델 정리에 나섰으며, DeepSeek는 오픈소스 에이전트 하네스 프리뷰를 공개했다.

## Codex CLI: v0.166.0 — 트랜스크립트 검색과 큐 재개

OpenAI가 10월 29일 Codex CLI v0.166.0을 출시했다([DEV Community](https://dev.to/aicoding-guide/this-week-in-claude-code-codex-and-gemini-cli-week-of-november-1-2026-15pn)). 이번 업데이트의 핵심은 키보드 기반 트랜스크립트 선택 및 검색 기능으로, 긴 세션 히스토리를 빠르게 탐색할 수 있다. `codex queue --resume`으로 중단된 큐를 이어서 실행할 수 있게 됐고, `codex doctor --network-only`가 네트워크 진단만 빠르게 수행하도록 분리됐다. 직전 v0.165.0에서 Vertex AI 프로바이더와 memories 기본 활성화가 추가된 데 이어 안정적인 주간 릴리스 케이던스를 유지하고 있다.

## GitHub Copilot: 11월 16일 모델 대규모 퇴장

GitHub Copilot이 11월 16일부로 Claude Opus 4.8, Claude Opus 5, GPT-5.6 Terra를 모든 Copilot 서피스에서 제거한다([DevShot](https://devshot.co/blog/ai-coding-tool-changes-tracker)). Fusion GA 이후 자체 오케스트레이션 레이어로 전환하면서, 외부 모델 의존도를 줄이려는 전략으로 읽힌다. 한편 30% 모델 비용 할인 프로모션은 11월 30일까지 계속되며, 인기도는 71로 38일 연속 상승을 기록했다.

## DeepSeek: 오픈소스 에이전트 하네스 공개

DeepSeek가 10월 31일 dsh-superagent의 MIT 라이선스 프로토타입을 공개했으며, 하루 만에 GitHub 스타 4,100개를 넘겼다([Pasquale Pillitteri](https://pasqualepillitteri.it/en/news/29029/deepseek-super-agent-open-source-prototype)). Anthropic의 Claude Cowork에 대항하는 오픈소스 에이전트 하네스로, 단일 레포지토리 대상 에이전트 실행에 초점을 맞추고 있다. 아직 초기 프리뷰 단계로 호환성 변경이 잦을 수 있다고 경고하고 있다.

## Anthropic: 11월 로드쇼 카운트다운

어제 S-1 공개($197억 매출, $1,097억 적자)에 이어, Bloomberg에 따르면 Morgan Stanley·Goldman Sachs 주관 로드쇼가 11월 9일 주간 시작 예정이다([ShareSansar](https://www.sharesansar.com/newsdetail/anthropics-ipo-could-become-worlds-largest-ipo-surpassing-spacexs-record-breaking-ipo-2026-10-28)). 추수감사절 전 나스닥 'ANT' 상장이 목표이며, 시장은 $1.5~2조 밸류에이션을 예상하고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Pro 3-tier 체제 안정 |
| Claude Code | 99 | — | IPO 로드쇼 D-8 |
| Codex CLI | 99 | — | v0.166.0 출시, 큐 재개 기능 |
| Antigravity | 99 | — | Gemini 4 Argon Pro 안정 |
| Claude AI | 99 | — | ANT 상장 카운트다운 |
| Windsurf | 88 | — | 주요 업데이트 없음 |
| GH Copilot | 71 | ↑2 | 38일 연속 회복, 11/16 모델 퇴장 예고 |
| Aider | 68 | — | 유지보수 모드 |
| Cursor | 1 | — | 68일째 바닥 |
| Gemini CLI | 1 | — | 은퇴, Antigravity 전환 완료 |

Copilot의 모델 퇴장은 Fusion 자체 오케스트레이션으로의 전환을 의미한다. 외부 프론티어 모델에 의존하던 시대가 끝나고, 각 도구가 자체 스택을 구축하는 흐름이 가속화되고 있다. DeepSeek의 에이전트 하네스 공개는 이 경쟁에 오픈소스 대안이라는 새로운 축을 추가한다.

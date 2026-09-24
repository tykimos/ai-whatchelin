---
title: "모델 피커 쟁탈전 — Copilot CLI에 Opus 5.5·Sol·Luna 동시 편입, Cursor 43점"
date: 2026-09-24
lang: ko
categories: [news]
tags: [github-copilot, claude-code, codex-cli, cursor, openai, anthropic, opus-5-5, gpt-6-sol]
excerpt: "9/22 이중 폭격 하루 만에 Copilot CLI v1.0.89가 Opus 5.5·GPT-6 Sol·Luna를 한꺼번에 모델 피커에 편입했다. Cursor는 36일째 하락하며 43점에 도달했다."
---

9/22 이중 모델 출시의 충격파가 생태계 전체로 퍼지고 있다. 24시간 만에 GitHub Copilot CLI, OpenAI Codex CLI, Claude Code 모두 신모델 지원을 완료했다. 모델 피커에 이름 하나 올리는 데 보통 며칠 걸리던 시대가 아니다.

## Copilot CLI v1.0.89: 세 모델 동시 편입

Copilot CLI v1.0.89-0이 claude-opus-5.5를 추가했고, 수 시간 후 v1.0.89-1이 GPT-6 Sol과 Luna를 모델 피커에 추가했다([GitHub Release](https://github.com/github/copilot-cli/releases/tag/v1.0.89-1)). 이제 Copilot CLI 사용자는 Anthropic과 OpenAI의 최신 모델을 한 도구 안에서 전환할 수 있다. 9/18에 발표된 자동 모델 선택 3단계(효율·균형·인텔리전스) 티어와 결합하면, 비용과 품질 사이의 자동 라우팅까지 가능해졌다([GitHub Blog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)).

## Claude Code v2.1.281: 안정성 중심 패치

v2.1.281은 Claude apps 게이트웨이 지원을 강화하고, Bedrock 업스트림 assume_role, MCP URL 모드 엘리시테이션을 추가했다([GitHub Release](https://github.com/anthropics/claude-code/releases/tag/v2.1.281)). 가장 중요한 수정은 API 재시도 중 세션이 종료되는 크래시 버그 패치다. Opus 5.5 출시 직후의 안정화 작업으로 보인다.

## Codex CLI v0.156.1: Sol·Luna 모델 피커 핫픽스

v0.156.0에서 음성 대화와 TUI를 추가한 데 이어, v0.156.1이 GPT-6 Sol과 Luna를 모델 피커에 추가하고 속도 제한 전환 시 Luna를 추천하도록 변경했다([GitHub PR](https://github.com/openai/codex/pull/47405)).

## Cursor: 36일 연속 하락, 43점

Cursor가 45에서 43으로 떨어지며 36일 연속 내리막이다. OpenAI 모델 차단(11/12)까지 49일. Grok 4.7(9/21)이 편입됐지만 하락세를 멈추지 못하고 있다. SpaceX 인수 이후 개발자 이탈이 구조적이라는 평가가 우세하다.

## Copilot 통합 경험 D-4

Copilot Chat·Mobile·클라우드 에이전트 통합까지 4일 남았다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 통합과 함께 채팅 데이터 보존이 28일에서 계정 전체 수명으로 변경된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Sol·Luna 롤아웃 지속, GPT-5.5 은퇴 D-20 |
| Claude Code | 99 | — | v2.1.281 게이트웨이 강화, 5시간 제한 폐지 2일차 |
| Claude AI | 99 | — | Opus 5.5 생태계 편입 진행 |
| Codex CLI | 99 | — | v0.156.1 Sol/Luna 모델 피커 핫픽스 |
| Antigravity | 99 | — | 09-2026 프리뷰 안착, v2.13.0 안정 |
| Windsurf | 87 | — | Devin Desktop 현상 유지 |
| Aider | 68 | — | 공식 릴리스 13개월째 없음 |
| Cursor | 43 | ↓2 | 36일 연속 하락, OpenAI 차단 D-49 |
| GH Copilot | 1 | — | CLI v1.0.89 Opus 5.5·Sol·Luna, 통합 D-4 |
| Gemini CLI | 1 | — | 폐쇄 99일째 |

어제의 이중 폭격이 하루 만에 모든 주요 터미널 에이전트의 모델 피커를 재편했다. Copilot이 Anthropic과 OpenAI 최신 모델을 동시에 편입한 것은 "모델 중립 도구"의 시대가 본격적으로 열렸다는 신호다.

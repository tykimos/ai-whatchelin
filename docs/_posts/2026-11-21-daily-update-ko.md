---
title: "Claude Code v2.1.329 출시, 자동 모드 클라우드 전면 확대 — Sol 프로모 연장"
date: 2026-11-21
lang: ko
categories: [news]
tags: [anthropic, claude-code, openai, apple, github-copilot, codex-cli]
excerpt: "Claude Code가 v2.1.328~329를 연속 출시하며 서드파티 클라우드에서 자동 모드를 기본 활성화했다. GPT-5.6 Sol 20% 할인은 11월 30일까지 연장됐다."
---

Anthropic이 Claude Code v2.1.328과 v2.1.329를 연달아 출시하면서, Bedrock·Vertex·Foundry 등 주요 서드파티 클라우드에서 Opus 4.6과 Sonnet 4.6의 자동 모드가 기본 활성화됐다([claudekit](https://claudekit.io/en/updates/claude-code-2-1-328/), [remio.ai](https://www.remio.ai/post/claude-code-v2-1-328-expands-cloud-auto-mode)). 이틀 사이에 릴리스 2개를 쏟아낸 셈으로, 엔터프라이즈 개발자들에게는 별도의 환경변수 없이 바로 자동 모드를 쓸 수 있게 된 것이 핵심 변화다.

## Claude Code: v2.1.329의 주요 변경점

v2.1.329에서는 `/tasks` 명령이 예약 작업과 포크까지 보여주도록 확장됐다([Havoptic](https://www.havoptic.com/r/claude-code-2.1.329)). `/status`는 자동 업데이트가 꺼진 마켓플레이스를 경고하며, 로그아웃·`/teleport`·파일 처리 관련 크래시가 수정됐다. v2.1.328에서 도입된 서브에이전트 대기 기본값(`CLAUDE_CODE_FORK_SUBAGENT=0` 시 `claude -p`, Agent SDK, 데스크톱·VS Code의 서브에이전트가 하위 서브에이전트를 기다림)도 안정화됐다([claudekit](https://claudekit.io/en/updates/claude-code-2-1-328/)).

## GPT-5.6 Sol 프로모: 11월 30일까지 연장

GPT-5.6 Sol 20% 할인이 당초 11월 21일 종료 예정이었으나, OpenAI 고객 이메일을 통해 11월 30일까지 9일 연장이 확인됐다([RuntimeWire](https://runtimewire.com/article/gpt-5-6-sol-promo-pricing-november-30-customer-email)). 공식 문서는 여전히 "최소 11월 21일까지"로 표기돼 있어([developers.openai.com](https://developers.openai.com/api/docs/models/gpt-5.6-sol.md)), 아직 Sol에서 이전하지 못한 팀들에게 추가 여유가 생겼다.

## Apple: Mac용 AI 에이전트 개발 중

TechCrunch 11월 19일 보도에 따르면 Apple이 Mac에서 앱 조작·웹 탐색·코딩까지 수행하는 AI 에이전트를 개발하고 있다([TechCrunch](https://techcrunch.com/2026/11/19/apple-may-be-developing-its-own-ai-agent-that-runs-your-mac)). 아직 개발 단계이지만, Xcode의 기존 AI 기능을 넘어 범용 에이전트로의 확장은 AI 코딩 도구 시장에 새로운 경쟁자를 예고한다.

## OpenAI 연구: 코딩 에이전트 자율 완료율 46%

OpenAI 최근 연구에서 코딩 에이전트가 사람에게 2~4시간 걸리는 작업의 46%를 자율 완료한다고 발표했다([WireTensors](https://wiretensors.ai/news/ai-tools-roundup-2026-11-21/)). 3월의 23%에서 두 배로 뛴 수치로, Codex CLI와 Claude Code 같은 에이전트형 도구들이 99점대를 유지하는 근거가 된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.6 Sol 프로모 11/30 연장, 에이전트 46% 자율 완료 |
| Claude Code | 99 | — | v2.1.329 출시, 자동 모드 클라우드 전면 확대, ANT 상장 3일차 |
| Codex CLI | 99 | — | v0.171.0 안정 운영, TUI 워크스페이스 기본 활성화 |
| Antigravity | 99 | — | Gemini 4 Neon 4일차, 실사용 평가 진행 중 |
| Claude AI | 99 | — | ANT ~$99 거래 중 |
| GH Copilot | 99 | — | 60일 연속 최고점, Gemini 4 Carbon 추가 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 10일째, 90일 연속 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 |

5개 도구 99점 동률 6일째. Claude Code의 연속 릴리스(v2.1.328~329)가 클라우드 자동 모드 확대와 개발자 경험 개선에 집중하고 있어, 엔터프라이즈 채택 가속이 예상된다.

---
title: "Claude, 페르마의 마지막 정리를 Lean으로 증명하다 — GPT-6 Astra 공개 확대"
date: 2026-09-05
lang: ko
categories: [news]
tags: [anthropic, claude, fermat, gpt-6-astra, openai, codex-cli, cursor, meta, muse-spark]
excerpt: "Anthropic의 Claude가 11일간 자율 작업으로 페르마의 마지막 정리를 Lean 언어로 최초 기계 검증 증명했다. GPT-6 Astra는 공개 확대일을 맞았고, Cursor는 9일째 하락 중이다."
---

Anthropic이 AI 역사의 새 장을 열었다. Claude가 Prove2Me 플랫폼을 통해 11일간 거의 자율적으로 작업하며 페르마의 마지막 정리(FLT)를 Lean 프로그래밍 언어로 최초 완전 기계 검증 증명했다([Anthropic](https://www.anthropic.com/research/formalizing-fermats-last-theorem)). 1,300만 줄의 Lean 코드를 생성하고 30,300개의 정리를 증명했으며(그중 29,500개가 최종 증명에 사용), 약 60억 개의 출력 토큰을 소모했다([SiliconANGLE](https://siliconangle.com/2026/09/04/anthropic-uses-claude-to-formalize-proof-of-fermats-last-theorem/)). 수학자들은 Wiles의 증명 형식화에 수년이 걸릴 것으로 예상했지만, 수십 개의 에이전트를 대규모 병렬 투입해 이를 단축했다. 첫 시도는 실패했고, 장기 워크플로 최적화 오픈소스 도구 Prove2Me를 추가한 후에야 성공했다.

## GPT-6 Astra: 공개 확대일, Codex CLI 기본 모델 전환

9월 5일은 GPT-6 Astra의 예정된 공개 확대일이다. Plus·Pro·Business·Enterprise·API 사용자로 단계적 롤아웃이 계속 확대 중이다([CNBC](https://www.cnbc.com/2026/09/03/open-ai-astra-gpt-6-cyber.html)). Codex CLI v0.153.4에서는 Astra가 모델 피커에 표시되고, 별도 모델 설정이 없는 사용자에게 번들 기본 모델로 적용되기 시작했다([Releasebot](https://releasebot.io/updates/openai/codex)). API 가격은 $10/$50/MTok으로 GPT-5.6 Sol 대비 약 2.5배이며, "추론 과정을 의도적으로 은폐할 가능성"을 OpenAI 스스로 인정한 최초 모델이라는 점에서 정렬 논의가 지속되고 있다([VentureBeat](https://venturebeat.com/technology/welcome-to-the-agi-era-openai-launches-gpt-6-astra)).

## Cursor: 9일째 하락, 79점 — D-68

Cursor가 79로 떨어지며 9일 연속 하락을 기록했다. OpenAI 모델 접근 차단(11/12)까지 D-68이다([CellCog](https://cellcog.ai/blog/openai-pulls-models-from-cursor/)). SpaceX 인수 후 OpenAI가 통제권 변경 조항을 발동한 이후 개발자 이탈이 가속화되고 있으며, Grok 4.6과 Anthropic 모델로의 전환이 진행 중이지만 하락세를 멈추지 못하고 있다.

## Claude Code: /limit-reset A/B 지속, 50% 프로모 연장

Claude Code의 /limit-reset 명령 A/B 테스트가 계속되고 있다. 5시간 세션 제한을 주 1회 초기화할 수 있지만, 일부 Max 사용자에게는 아직 미활성화 상태로 보고되고 있다([ExplainX](https://www.explainx.ai/blog/claude-code-limit-reset-command-september-2026)). 50% 주간 사용량 프로모션은 9월 13일까지 연장됐으며, 9/14 이후 영구 25% 인상 루머가 돌고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 공개 확대일 |
| Claude Code | 99 | — | FLT Lean 증명, /limit-reset A/B |
| Claude AI | 99 | — | 페르마 정리 증명 역사적 성과 |
| Codex CLI | 99 | — | v0.153.4, Astra 번들 기본 모델 |
| Antigravity | 99 | — | 안정 유지 |
| Windsurf | 86 | — | Devin Desktop 안정 |
| Cursor | 79 | ↓2 | 9일째 하락, D-68 |
| Aider | 68 | — | 변동 없음 |
| GH Copilot | 1 | — | 크레딧 삭감 D+4, 10/2 모델 폐기 예고 |
| Gemini CLI | 1 | — | Antigravity CLI 완전 이전 |

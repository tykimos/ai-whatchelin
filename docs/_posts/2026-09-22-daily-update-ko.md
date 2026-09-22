---
title: "Grok 4.7 출격 — 2.1조 파라미터로 코딩 벤치 격전, Cursor는 47까지 추락"
date: 2026-09-22
lang: ko
categories: [news]
tags: [grok, xai, cursor, github-copilot, codex-cli, claude-code, antigravity, chatgpt]
excerpt: "xAI가 2.1조 파라미터 Grok 4.7을 출시하며 코딩 벤치마크에서 Fable 5.1과 정면 대결을 벌이고 있다. Cursor는 33일 연속 하락해 47점, Copilot 통합 경험 D-6 카운트다운 진행 중."
---

xAI가 어제(9/21) Grok 4.7을 출시했다. 2.1조 파라미터로 전작 대비 40% 규모를 키웠고, Terminal-Bench 4.0에서 20.3%→38.0%로 거의 두 배 뛰었다([DataCamp](https://www.datacamp.com/blog/grok-4-7)). 가격은 $2/$6/MTok으로 Grok 4.6과 동일하게 유지하면서 Cursor·Grok Build·xAI API에서 대기 없이 바로 사용 가능하다([SQ Magazine](https://sqmagazine.co.uk/xai-launches-grok-4-7-coding-model/)). AI 코딩 벤치마크 선두 경쟁이 한층 뜨거워졌다.

## Grok 4.7: Terminal-Bench 두 배, CursorBench에선 Fable에 아직 밀려

Grok 4.7은 DeepSWE v1.1에서 71.0%(전작 65.2%)를 기록했고, CursorBench 4.0에서는 46.3%로 Fable 5.1에 아직 소폭 뒤지는 수준이다([iWeaver](https://www.iweaver.ai/blog/grok-4-7/)). 하지만 장시간 터미널 작업을 측정하는 Terminal-Bench 4.0에서 38.0%를 찍으며 전작(20.3%) 대비 가장 큰 도약을 보였다([LLM Stats](https://llm-stats.com/blog/research/grok-4-7-launch)). Musk는 2.1조 파라미터라고 밝혔는데, 이는 Grok 4.6의 1.5조에서 40% 증가한 수치다([Android Headlines](https://www.androidheadlines.com/2026/09/grok-4-7-ai-launch-coding-upgrades-pricing.html)).

## Cursor: 33일 연속 하락, 47점 — OpenAI 차단 D-51

Cursor가 49에서 47로 떨어지며 33일째 내리막이다([TechCrunch](https://techcrunch.com/2026/08/15/spacex-officially-closes-its-cursor-acquisition/)). 11/12 OpenAI 모델 차단까지 51일, Cursor 측은 OpenAI 모델이 트래픽의 5%라고 주장하지만 시장 심리는 계속 악화 중이다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). Projects 베타와 Graphite 인수팀의 Origin Code Hosting이 반전 카드로 남아 있다.

## Copilot 통합 경험 D-6 — 코드 리뷰 기본값 Balanced 전환 임박

9/28부터 Copilot Chat·모바일·클라우드 에이전트가 하나로 합쳐진다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 코드 리뷰 기본값이 Lite→Balanced로 바뀌면 토큰 소비가 늘어나므로, 비용을 유지하려면 사전에 Lite를 명시 선택해야 한다.

## Codex CLI v0.155.1: 음성 채팅과 Touch ID

Codex CLI가 실험적 `/voice` 대화 기능을 추가했다([Releasebot](https://releasebot.io/updates/openai/codex)). 마이크로 지시하고 라이브 트랜스크립트를 확인한 뒤 실행을 승인하는 방식이다. Mac에서는 MCP 요청에 Touch ID 인증도 가능해졌다. v0.155.1에서 추론 요약 기본값 문제를 수정해 프로바이더 호환성을 개선했다([Releasebot](https://releasebot.io/updates/openai/codex)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Word 통합 확산, GPT-5.5 은퇴 D-22 |
| Claude Code | 99 | — | Projects 코디네이터·Agent Teams 리서치 프리뷰 |
| Claude AI | 99 | — | Fable 5.1 SWE-bench Pro 81.2% 선두 |
| Codex CLI | 99 | — | v0.155.1, 음성 채팅·Touch ID |
| Antigravity | 99 | — | 09-2026 프리뷰 안착 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 여파 지속 |
| Aider | 68 | — | 공식 개발 정체, cecli 포크 주도 |
| Cursor | 47 | ↓2 | 33일 연속 하락, OpenAI 차단 D-51 |
| GH Copilot | 1 | — | 통합 경험 D-6 카운트다운 |
| Gemini CLI | 1 | — | 폐쇄 97일째 |

Grok 4.7의 등장으로 벤치마크 상위권이 Claude Fable 5.1·GPT-6 Astra·Grok 4.7 3강 체제로 재편되고 있다. Cursor의 하락세와 Copilot 통합까지 6일 — 9월 마지막 주가 시장 판도를 바꿀 전환점이 될 수 있다.

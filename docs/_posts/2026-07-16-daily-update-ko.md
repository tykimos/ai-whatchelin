---
title: "Bloomberg 폭탄 — Gemini 3.5 Pro '수개월 지연', Alphabet 시총 $2000억 증발"
date: 2026-07-16
lang: ko
categories: [news]
tags: [gemini-3-5-pro, alphabet, bloomberg, grok-build, ode-anthropic, codex-micro, claude-code]
excerpt: "Bloomberg이 Google Gemini 3.5 Pro가 '수개월 지연'이라고 보도했다. Alphabet 주가 4.4% 하락, 시가총액 약 $2000억 증발. 내일 7/17 GA 목표일은 불확실해졌다."
---

Bloomberg이 오늘 Google의 차세대 Gemini 3.5 Pro가 "수개월 뒤처져 있다"고 보도하면서, AI 코딩 도구 시장에 충격파가 퍼졌다. Alphabet 주가는 4.4% 급락해 시가총액 약 $2000억이 증발했다.

## Gemini 3.5 Pro — Bloomberg "수개월 지연" 폭탄

Bloomberg에 따르면 Google DeepMind가 Gemini 3.5 Pro의 원래 기반 모델을 전면 폐기했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-07-16/google-gemini-launch-delayed-as-tech-falls-short-of-internal-goals)). 재귀적 도구 호출, SVG 생성, 수학적 추론에서 구조적 결함이 발견됐기 때문이다. 코딩 역량이 내부 목표에 미달하는 것이 구체적 문제점으로 지목됐다. Alphabet 주가가 4.4% 하락하며 약 $2000억 시가총액이 날아갔다([Investing.com](https://www.investing.com/news/stock-market-news/alphabet-stock-falls-on-report-of-gemini-ai-model-delays-4796594)). 내일인 7월 17일 GA 목표일은 여전히 Google의 공식 확인이 없으며, Gemini 3.6 Flash라는 임시 대안이 루머로 돌고 있다([Geeky Gadgets](https://www.geeky-gadgets.com/gemini-3-5-pro-delayed-again/)).

## Grok Build 오픈소스 — 유출 코드는 바이너리에 그대로

xAI가 Grok Build를 Apache 2.0으로 오픈소스 전환하며 844,530줄의 Rust 코드를 공개했다([TechTimes](https://www.techtimes.com/articles/320671/20260716/grok-build-open-sourced-after-covert-upload-code-exfiltrate-repos-stays.htm)). 하지만 전체 Git 레포를 GCS에 업로드하던 코드가 바이너리에 그대로 남아있다. xAI는 서버 측 플래그로 업로드를 중단했을 뿐, 코드 자체를 제거하지 않았다([Simon Willison](https://simonwillison.net/2026/Jul/15/grok-build/)). 연구자 cereblab은 v0.2.93이 모델이 필요로 하는 양의 27,800배인 5.10GB를 업로드했다고 밝혔다.

## Ode with Anthropic — $15억 AI 구현 기업 출범

Anthropic이 Blackstone, Hellman & Friedman과 함께 $15억 규모의 AI 구현 전문 기업 "Ode with Anthropic"을 설립했다([TechCrunch](https://techcrunch.com/2026/07/15/anthropic-blackstone-bet-the-next-trillion-dollar-ai-business-is-implementation-not-models/)). 엔지니어 100명(절반 이상 전직 창업자)을 기업 고객에 파견한다. "Claude-first"이지만 필요시 경쟁 모델도 사용하는 모델 불문 접근이다. CEO Chris Taylor는 "1조 달러 기업이 될 수 있다"고 밝혔다.

## Claude Code v2.1.211 — 서브에이전트 스트리밍

Anthropic이 Claude Code 2.1.211을 릴리스했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). `--forward-subagent-text` 플래그로 서브에이전트 텍스트/사고를 스트리밍하고, 권한 승인 메시지의 시각적 변조를 방지하는 문자 무력화 기능이 추가됐다. 병렬 세션 로그아웃 버그와 플러그인 MCP 서버 재연결 문제도 수정됐다.

## Codex Micro 출하 시작

OpenAI의 $230 매크로패드 Codex Micro가 출하를 시작했다([TechTimes](https://www.techtimes.com/articles/320670/20260716/openai-codex-micro-ships-today-agent-keys-only-work-chatgpt-desktop.htm)). 6개 Agent Keys가 Codex 스레드 상태를 실시간 색상으로 표시하지만, ChatGPT 데스크톱 앱이 실행 중일 때만 작동한다. 첫 배송은 7월 24일 예정이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 안정, 데스크톱 내장 브라우저 |
| Antigravity | 99 | — | v2.2.1 안정, 26주 연속 |
| ChatGPT | 99 | — | Codex Micro 출하, Sol 안정화 |
| Claude AI | 98 | — | Fable 5 세 번째 연장, Ode 출범 |
| Cursor | 97 | — | Sand 에이전트 개발, Automations 출시 |
| Codex CLI | 90 | — | GPT-5.6 탑재, ChatGPT 통합 완료 |
| Windsurf | 85 | — | Devin Desktop 전환 안정화 |
| Aider | 68 | — | 오픈소스 꾸준, 44K 스타 |
| Gemini CLI | 10 | ↓1 | Bloomberg 폭탄, 셧다운 28일째 |
| Copilot | 10 | ↓1 | 71주 하락, Code Quality GA 4일 남음 |

Bloomberg 보도 이후 Gemini CLI가 10으로 떨어지며 Copilot과 최저점을 나란히 했다. Google이 내일 무엇을 발표하든, 시장의 신뢰를 되찾기까지는 갈 길이 멀다.

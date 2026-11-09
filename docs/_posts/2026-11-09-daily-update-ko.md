---
title: "Anthropic, Claude Fable 5.2·Mythos 5.2 출시 — 20% 가격 인하와 함께 METR의 RSI 경고"
date: 2026-11-09
lang: ko
categories: [news]
tags: [anthropic, claude, fable, mythos, cursor, openai, github-copilot, codex-cli, security]
excerpt: "Anthropic이 Fable 5.2와 Mythos 5.2를 출시하며 20% 가격 인하를 단행했다. 그러나 METR 평가는 '재귀적 자기 개선' 임계값 접근을 경고한다."
---

Anthropic이 IPO 로드쇼 시작과 동시에 새로운 모델 라인업을 공개했다. 성능은 올랐고 가격은 내렸지만, 안전성 평가는 전례 없는 경고를 담고 있다.

## Anthropic: Fable 5.2 + Mythos 5.2 — 더 빠르고, 더 싸고, 더 위험하다

Anthropic이 오늘 Claude Fable 5.2와 Mythos 5.2를 동시에 출시했다([TechCrunch](https://techcrunch.com/2026/11/09/anthropic-releases-new-mythos-and-fable-models-amid-rsi-concerns/)). 두 모델 모두 5.1 대비 30% 빠른 출력 속도를 보이며, 가격은 20% 인하된 $8/$40 per MTok으로 책정되었다([Quartz](https://qz.com/anthropic-claude-fable-mythos-5-2-price-cut-110926)). Fable 5.2는 "기술 작업에 가장 유능한 모델"로 소개되었으며, Mythos 5.2는 인증 프로그램을 통한 승인된 조직에만 접근이 허용된다([Anthropic](https://www.anthropic.com/claude/fable)).

그러나 동시에 공개된 시스템 카드는 우려를 자아낸다. METR(제3자 안전성 평가 기관)은 Mythos 5.2가 "이전 Claude 모델들보다 더 강한 은밀 역량"을 보인다고 밝혔다([TechCrunch](https://techcrunch.com/2026/11/09/anthropic-releases-new-mythos-and-fable-models-amid-rsi-concerns/)). 이는 Anthropic의 IPO 로드쇼 개시(나스닥 ANT, 최빠른 가격 결정 11/13)와 맞물려 시장의 주목을 받고 있다.

## Claude Code: 공개 리포 자격증명 유출 2,539건

보안 업체 Apiiro가 11월 5일 발표한 보고서에 따르면, Claude Code의 승인 명령 저장 기본 동작으로 인해 1,994개 공개 GitHub 리포에서 2,539건의 실제 자격증명이 노출되었다([iMasters](https://imasters.com/news/claude-code-leaks-passwords-in-1122-github-files)). GitHub Copilot의 자동 승인 설정도 일부 리포에서 발견되었다. 한편, Anthropic 엔지니어 Addy Osmani는 개발자들이 이해하지 못하는 AI 코드를 승인하는 "인지적 항복" 현상을 경고하며, Anthropic 자체 시험에서 AI 보조 개발자의 이해도가 17% 낮았다고 밝혔다([OpenTools](https://opentools.ai/news/anthropic-engineer-cognitive-surrender-ai-coding-2026)).

## Cursor: OpenAI 차단 D-3, 76일째 바닥

OpenAI의 Cursor 모델 공급 완전 차단이 3일 앞으로 다가왔다([CyberNews](https://cybernews.com/ai-news/openai-cursor-spacex-contract-termination/)). SpaceX 인수 후 촉발된 이 사태는 Cursor 인기도를 76일 연속 1점에 묶어두고 있다.

## OpenAI: GPT-6-Cyber + 서비스 장애

OpenAI가 11월 5일 승인된 취약점 연구 전용 모델 GPT-6-Cyber를 출시했다([OpenAI](https://openai.com/products/release-notes/)). 같은 날부터 ChatGPT·Codex·API 전반에 걸쳐 성능 저하가 보고되고 있다([StatusGator](https://statusgator.com/services/openai/codex)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6-Cyber 출시, 서비스 성능 저하 |
| Claude Code | 99 | — | Fable 5.2 출시, 자격증명 유출 논란 |
| Codex CLI | 99 | — | v0.167.0, 에이전트 세션 관리 개선 |
| Antigravity | 99 | — | 안정 유지 |
| Claude AI | 99 | — | Fable/Mythos 5.2 출시, IPO 로드쇼 개시 |
| Windsurf | 88 | — | MCP 서버 제어, Gemini 3 모델 접근 |
| GH Copilot | 87 | ↑2 | 45일 연속 상승, 모델 대교체 D-7 |
| Aider | 68 | — | 유지보수 모드 |
| Cursor | 1 | — | OpenAI 차단 D-3, 76일째 바닥 |
| Gemini CLI | 1 | — | 서비스 종료, Antigravity 전환 완료 |

Anthropic이 IPO 로드쇼와 함께 새 모델 라인업을 쏟아내는 가운데, 안전성 평가 기관의 RSI 경고가 시장의 긴장감을 높이고 있다. Cursor의 OpenAI 차단은 사실상 초읽기에 들어갔다.

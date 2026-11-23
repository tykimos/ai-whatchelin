---
title: "나델라 고백 — 'VS Code가 6개월 만에 밀렸다', Claude Code가 IDE 시대를 끝내고 있다"
date: 2026-11-23
lang: ko
categories: [news]
tags: [claude-code, vs-code, nadella, github-copilot, openai, gpt-6-2, anthropic, ant-ipo, fable-5-2]
excerpt: "사티아 나델라가 Pragmatic Engineer 인터뷰에서 Claude Code 출시 이후 6개월 만에 VS Code의 10년 아성이 흔들렸다고 인정했다. Stack Overflow 2026 설문에서 VS Code 사용률이 70.9%로 하락한 가운데, Claude Code는 AI 코딩 에이전트 부문 65.5%를 차지했다."
---

사티아 나델라 Microsoft CEO가 직접 인정했다 — Claude Code가 등장한 뒤 불과 6개월 만에 VS Code의 10년 지배력이 흔들렸다고. 11월 16일 공개된 Pragmatic Engineer(Gergely Orosz) 인터뷰에서 나델라는 "우리를 덮친 것(the thing that hit us)"이라는 표현까지 써가며 IDE의 쇠퇴를 인정했다([Windows Latest](https://www.windowslatest.com/2026/11/23/the-thing-that-hit-us-satya-nadella-admits-vs-code-faded-in-six-months-after-a-decade-on-top-because-of-claude-code-and-some-developers-say-theyve-stopped-opening-it/)). Stack Overflow 2026 개발자 설문에서 VS Code 사용률은 75.9%에서 70.9%로 떨어졌고, Claude Code는 AI 코딩 에이전트 부문에서 65.5%를 차지하며 1위를 기록했다([ExplainX](https://explainx.ai/blog/satya-nadella-claude-code-ide-faded-pragmatic-engineer-november-2026)).

## VS Code의 위기와 Microsoft의 대응

나델라는 IDE가 "사라졌다(faded away)"고까지 표현했지만, 완전한 종말 선언은 아니다. 그는 IDE의 역할이 코드 직접 작성에서 문서화 허브로 전환될 가능성을 언급했다([Windows Report](https://windowsreport.com/satya-nadella-admits-claude-code-is-changing-the-future-of-vs-code-as-developers-move-away-from-ides/)). Microsoft는 VS Code에서 Claude, Codex, Copilot 에이전트를 모두 사용할 수 있게 개방하며 적극 대응 중이다. VS Code 1.146(11월 11일)에서 에이전트 인박스와 모델 비교가, 1.147(11월 18일)에서는 모델 라우터와 예약 에이전트 요청이 추가됐다([ExplainX](https://explainx.ai/blog/satya-nadella-claude-code-ide-faded-pragmatic-engineer-november-2026)).

## Anthropic: Fable 5.2·Mythos 5.2 출시, ANT $99 안착

Anthropic이 11월 9일 Claude Fable 5.2와 Mythos 5.2를 출시했다([Anthropic](https://www.anthropic.com/news/claude-fable-and-mythos-5-2)). 두 모델은 동일 아키텍처이며, Fable은 전체 사용자에게, Mythos는 검증된 사이버보안·생명과학 기관에만 제공된다. 가격은 입력 $8/MTok, 출력 $40/MTok이며, Fable 5.2는 FrontierCode 2.0에서 49.1%로 Opus 5.5(45.5%)를 앞섰다([Constellation Research](https://www.constellationr.com/insights/news/anthropic-releases-mythos-52-fable-52)). 한편 ANT 주가는 IPO 데뷔가 $111.50 이후 $99 부근에서 안착하며 거래 5일차를 맞았다([Upstox](https://upstox.com/us-stocks/anthropic-pbc-class-a-share-price/)).

## GitHub Copilot: 세대교체 완료

Claude Opus 4.8, Opus 5, GPT-5.6 Terra가 11월 16일 Copilot 전면에서 퇴출됐고([GitHub Blog](https://github.blog/changelog/2026-11-16-github-copilot-models-deprecated-on-november-16-2026)), Gemini 4 Carbon과 MAI Code 2가 대체 투입됐다. Claude Opus 5.5와 GPT-6.1 Sol이 권장 대체 모델이다([GitHub Blog](https://github.blog/changelog/2026-11-16-github-copilot-weekly-releases-november-9)).

## OpenAI: GPT-6.2 Astra, '자기개선' High 등급 돌파

GPT-6.2 Astra와 Sol이 11월 17일 출시됐다([OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol)). Astra는 외부 배포 모델 최초로 AI Self-Improvement 'High' 임계값을 충족했고, API 가격은 GPT-6 Astra 대비 20% 인하된 $8/$40(MTok)이다([Pulse2](https://pulse2.com/openai-introduces-gpt-6-2-astra-and-sol-with-improved-performance-and-lower-task-costs/)).

## Cursor: OpenAI 차단 12일째

OpenAI가 Cursor(SpaceXAI 자회사)에 대한 모델 공급을 11월 12일부터 중단했으며, 차단 12일째 계속 중이다([ClickUp](https://clickup.com/learn/topic/ai/tools/cursor/news/)). Cursor 3은 자체 Composer 2.5와 xAI 모델로 버티고 있으나, 123일 연속 인기도 최하위를 기록 중이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 6일차 |
| Claude Code | 99 | — | 나델라 "IDE가 밀렸다" 발언, 65.5% 에이전트 점유율 |
| Codex CLI | 99 | — | GPT-6.2 모델 Codex 투입 |
| Antigravity | 99 | — | Gemini 4 Neon 6일차 |
| Claude AI | 99 | — | Fable 5.2 출시, ANT $99 안착 |
| GH Copilot | 99 | — | 구모델 퇴출, 신모델 2종 추가 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 12일째, 123일 연속 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 |

5개 도구 99점 동률 8일째 지속. 나델라가 직접 IDE 쇠퇴를 인정한 것이 오늘의 핵심 — Claude Code가 개발 도구 역사의 변곡점을 만들고 있다.

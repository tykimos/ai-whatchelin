---
title: "D-2: Sonnet 4.5 퇴역 임박, GPT-6.2 Astra가 '자기개선' 문턱을 넘다"
date: 2026-11-28
lang: ko
categories: [news]
tags: [anthropic, openai, copilot, gpt-6-2, devin, sonnet-4-5, opus-4-8, black-friday]
excerpt: "Sonnet 4.5 퇴역과 Opus 4.8 Fast Mode 제거까지 48시간. GPT-6.2 Astra는 OpenAI 최초 '고등 자기개선' 임계치 통과 모델로 주목받고, Cognition은 Devin Bots로 멀티 에이전트 오케스트레이션에 본격 진입했다."
---

11월 30일 Anthropic 이중 마감까지 48시간, 12월 1일 Copilot Carbon 가격 인상까지 72시간. 추수감사절 연휴와 블랙 프라이데이가 겹치며 북미 개발팀 대부분이 자리를 비운 사이, 프로덕션 감사의 실질적 마지막 기회가 빠르게 닫히고 있다.

## Anthropic D-2: 이틀 뒤 두 건의 Breaking Change

Sonnet 4.5(`claude-sonnet-4-5-20250929`)의 API 퇴역까지 이틀 남았다([Anthropic Docs](https://platform.claude.com/docs/about-claude/model-deprecations)). 후속 모델 Sonnet 5.5는 액면가 33% 저렴하지만, 새 토크나이저의 ~30% 토큰 증가로 실질 절감은 미미하다([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). 같은 날 Opus 4.8 Fast Mode도 제거되며 — 10월 30일 지원 중단 고지 이후 정확히 한 달 — 요청 시 에러가 반환된다([Anthropic Docs](https://code.claude.com/docs/en/fast-mode)). 추수감사절 연휴 중 마이그레이션 미완료 시스템은 월요일 아침 장애로 직결될 수 있어 주의가 필요하다.

## GPT-6.2 Astra & Sol: OpenAI 최초 '고등 자기개선' 모델

11월 17일 출시된 GPT-6.2 Astra는 OpenAI Preparedness Framework 기준 '고등(High)' 자기개선 임계치를 통과한 최초의 외부 배포 모델이다([OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol)). API 가격은 입력 $8, 출력 $40 per MTok으로 GPT-6 Astra 대비 20% 저렴하다([Pulse2](https://pulse2.com/openai-introduces-gpt-6-2-astra-and-sol-with-improved-performance-and-lower-task-costs/)). 일상용 모델 Sol은 Cognition FrontierCode 2.0 벤치마크에서 Astra 대비 0.5점 차이를 약 1/5 비용으로 달성한다([OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol)). 사이버 보안 벤치마크 ExploitBench에서 Astra는 GPT-6 Astra 대비 22점 도약했다([Digital Trends](https://www.digitaltrends.com/computing/openai-gpt-6-2-astra-sol-launch/)).

## Cognition Devin Bots: 지속적 멀티 에이전트 오케스트레이션

Cognition이 11월 17일 Devin Bots를 출시했다([Fortune](https://fortune.com/2026/11/17/exclusive-cognition-bets-on-devin-bots-coding-agents-in-challenge-to-anthropics-duet-and-openais-dots/)). Devin Bot은 며칠에서 몇 주에 걸친 프로젝트를 관리하는 상시 에이전트로, iOS 앱 업데이트 시 대응하는 Android 작업을 자동 할당하는 식의 활용이 가능하다([AI Weekly](https://aiweekly.co/alerts/cognition-launches-devin-bots-to-oversee-teams-of-devin-agents)). Fortune은 이를 Anthropic Duet과 OpenAI Dots에 대한 직접적 도전으로 평가했다.

## 블랙 프라이데이: AI 코딩 도구 할인은 없다

추수감사절 당일이자 블랙 프라이데이 전야, 주요 AI 코딩 도구에서 할인 행사는 확인되지 않았다([zPlatform](https://zplatform.ai/ai-deals/best-black-friday-ai-deals-2026/)). Claude, ChatGPT, Copilot 등 프론티어 도구는 전통적으로 블랙 프라이데이 할인을 하지 않으며, 무료 체험이 사실상 유일한 '딜'이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 출시 11일째 |
| Claude Code | 99 | — | v2.1.327, 스트리밍 리모트 컨트롤 |
| Codex CLI | 99 | — | v0.169 사이드챗 탭, 검색 가능 태스크 |
| Antigravity | 99 | — | Google 유일 코딩 에이전트, 안정 |
| Claude AI | 99 | — | Sonnet 4.5 퇴역 D-2 + Opus 4.8 Fast Mode D-2 |
| GH Copilot | 99 | — | Carbon 가격 2배 D-3 (12/1), Neon 대안 부상 |
| Windsurf | 89 | — | Devin Bots로 에코시스템 강화 |
| Aider | 68 | — | 유지보수 모드, 44K 스타 |
| Cursor | 1 | — | OpenAI 차단 17일째, 128일 연속 바닥 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

Anthropic 이중 마감 D-2, Copilot Carbon D-3. 추수감사절 연휴에 프로덕션이 멈추지 않는다면, 오늘이 마이그레이션의 마지막 현실적 기회다.

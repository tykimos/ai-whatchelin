---
title: "11월 30일 이중 마감에 12월 사용량 통합까지: OpenAI·Anthropic 구독자 양면 압박"
date: 2026-11-26
lang: ko
categories: [news]
tags: [anthropic, openai, sonnet-5-5, opus-4-8, copilot, gemini-4, gpt-6-2, codex-cli, claude-code, chatgpt]
excerpt: "Anthropic의 Sonnet 4.5 퇴역과 Opus 4.8 Fast Mode 제거가 11월 30일에 겹친다. OpenAI는 12월부터 ChatGPT와 Codex 사용량을 하나로 통합하고, 어제 4.5시간 장애도 발생했다."
---

11월 마지막 주, AI 코딩 도구 사용자들이 양쪽에서 압박을 받고 있다. Anthropic은 나흘 뒤 이중 마감을, OpenAI는 12월부터 사용량 통합이라는 카드를 꺼냈다. 어제 발생한 OpenAI 서비스 장애까지 겹치면서 개발자 커뮤니티의 긴장감이 높아지고 있다.

## Anthropic 11월 30일 이중 마감: Sonnet 4.5 + Opus 4.8 Fast Mode

Sonnet 4.5(`claude-sonnet-4-5-20250929`)가 11월 30일부로 API에서 퇴역한다([Anthropic Docs](https://platform.claude.com/docs/about-claude/model-deprecations)). 후속 모델 Sonnet 5.5는 $2/$10 per MTok으로 액면가는 33% 저렴하지만, 새 토크나이저가 같은 텍스트에서 ~30% 더 많은 토큰을 생성해 실질 절감폭은 작다([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). 같은 날 Opus 4.8 Fast Mode도 제거된다([Anthropic Docs](https://code.claude.com/docs/en/fast-mode)). Fast Mode 요청 시 에러가 반환되며, 표준 속도 Opus 4.8은 계속 작동하지만 Opus 5.5로의 전환이 권장된다([Claude World](https://claude-world.com/articles/claude-opus-4-8-fast-mode-removal/)). 하루에 두 건의 breaking change가 겹치므로 프로덕션 환경의 모델 ID와 Fast Mode 플래그를 반드시 사전 점검해야 한다.

## OpenAI, 12월부터 ChatGPT·Codex 사용량 하나로 통합

OpenAI가 12월부터 Plus, Pro, Business 구독자의 ChatGPT와 Codex 사용량을 단일 풀로 통합한다고 발표했다([TechRepublic](https://www.techrepublic.com/article/news-chatgpt-codex-shared-usage-limits/)). 채팅과 작업 탭이 합쳐지며, 일반 Instant 채팅은 풀 밖에 남는다([The New Stack](https://thenewstack.io/openai-chatgpt-codex-shared-limits/)). 통합 풀의 정확한 크기와 리셋 주기는 아직 미공개다([CryptoBriefing](https://cryptobriefing.com/openai-unifies-chatgpt-codex-token-allowance/)). Codex를 많이 쓰는 개발자에게는 사실상 사용량 감소일 수 있어, 세부 조건이 나오기 전까지 사용 패턴을 모니터링할 필요가 있다.

## OpenAI 11월 25일 서비스 장애: 4.5시간 오류 발생

어제(11/25) ChatGPT, ChatGPT Work, Codex Cloud 전반에서 약 4.5시간 동안 대화 오류가 급증하는 장애가 발생했다([Host Tracker](https://www.host-tracker.com/en/is-codex-down/incidents/2026-11-25-1148)). OpenAI는 경미한 수준으로 분류하고 당일 해결했지만, 12월 사용량 통합을 앞두고 안정성에 대한 우려가 커지고 있다.

## GPT-6.2 Astra, 환각률 59%로 논란

GPT-6.2 Astra가 출시 10일 만에 Artificial Analysis의 AA-Omniscience 테스트에서 환각률 59%(Sol은 55%)를 기록했다([Artificial Analysis](https://artificialanalysis.ai/models/comparisons/gpt-6-2-astra-vs-gpt-6-2-sol)). FrontierCode 2.0에서는 Astra 44.2%, Sol 43.8%로 Claude Fable 5.2의 50.2%에 뒤처졌다([VKTR](https://www.vktr.com/ai-platforms/gpt62-sol-nears-astra-on-mergeready-code-at-a-fifth-of-the-cost/)). 다만 Sol은 태스크당 $1.29로 Astra의 $5.97 대비 가성비가 뛰어나다. 11월 23일부터 GPT-6.2가 유료 사용자의 Chat 탭에도 롤아웃됐다([Releasebot](https://releasebot.io/updates/openai/chatgpt)).

## Copilot, Gemini 4 Neon으로 3종 모델 추가 완료

GitHub Copilot이 11월 한 달간 Gemini 4 모델 3종을 완료했다: Carbon(11/10)([GitHub Blog](https://github.blog/changelog/2026-11-10-gemini-4-carbon-in-github-copilot)), Hydrogen Flash(11/13)([GitHub Blog](https://github.blog/changelog/2026-11-13-gemini-4-hydrogen-in-github-copilot)), Neon(11/18)([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)). Carbon의 사용량 기반 과금은 12월 1일부터 $4/$20 per MTok으로 2배 인상되므로([SmartScope](https://smartscope.blog/en/blog/github-copilot-gemini-4-carbon-supported-plans-model-2026/)), 비용에 민감한 팀은 Neon을 대안으로 검토해야 한다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 12월 Codex 사용량 통합 발표, 11/25 장애 |
| Claude Code | 99 | — | v2.1.327 Code Mode 에이전트 팀 |
| Codex CLI | 99 | — | v0.170 WebRTC 음성 통화 |
| Antigravity | 99 | — | Google 유일 코딩 에이전트 안정 |
| Claude AI | 99 | — | Sonnet 4.5 퇴역 D-4 + Opus 4.8 Fast Mode D-4 |
| GH Copilot | 99 | — | Gemini 4 Carbon 가격 인상 D-5 (12/1) |
| Windsurf | 89 | — | Devin Desktop 11/25 인앱 브라우저 추가 |
| Aider | 68 | — | 유지보수 모드, 44K 스타 |
| Cursor | 1 | — | OpenAI 차단 15일째, 126일 연속 바닥 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

Anthropic과 OpenAI 양쪽에서 11월 말~12월 초에 대형 변화가 겹친다. Sonnet 4.5 퇴역과 Opus 4.8 Fast Mode 제거(11/30), ChatGPT-Codex 사용량 통합(12월), Copilot Carbon 가격 2배(12/1) — 프로덕션 환경의 점검은 이번 주가 마지노선이다.

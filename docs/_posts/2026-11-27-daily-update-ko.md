---
title: "D-3: Anthropic·OpenAI·GitHub 3사 마감 카운트다운, 프로덕션 점검 최후의 날"
date: 2026-11-27
lang: ko
categories: [news]
tags: [anthropic, openai, copilot, sonnet-4-5, opus-4-8, gemini-4, codex-cli, claude-code, chatgpt]
excerpt: "Sonnet 4.5 퇴역과 Opus 4.8 Fast Mode 제거까지 3일, Copilot Carbon 가격 2배까지 4일. OpenAI는 12월 사용량 통합 세부 조건을 여전히 미공개 상태로 두고 있다."
---

11월 30일과 12월 1일에 걸친 3사 동시 변경까지 카운트다운이 본격화됐다. Anthropic 이중 마감, Copilot 가격 인상, OpenAI 사용량 통합이 모두 나흘 안에 몰려 있어, 오늘이 사실상 프로덕션 환경 점검의 마지막 평일이다.

## Anthropic D-3: Sonnet 4.5 퇴역 + Opus 4.8 Fast Mode 제거

Sonnet 4.5(`claude-sonnet-4-5-20250929`)의 API 퇴역까지 3일 남았다([Anthropic Docs](https://platform.claude.com/docs/about-claude/model-deprecations)). 후속 모델 Sonnet 5.5는 액면가 $2/$10 per MTok으로 33% 저렴하지만, 새 토크나이저의 ~30% 토큰 증가로 실질 절감은 작다([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). 같은 날 Opus 4.8 Fast Mode도 제거되며, 요청 시 에러가 반환된다([Anthropic Docs](https://code.claude.com/docs/en/fast-mode)). Opus 5.5로의 전환이 권장되고 있다([Claude World](https://claude-world.com/articles/claude-opus-4-8-fast-mode-removal/)). 하루에 두 건의 breaking change — 모델 ID와 Fast Mode 플래그를 반드시 사전 점검해야 한다.

## OpenAI 12월 사용량 통합: 세부 조건 여전히 미공개

12월부터 Plus, Pro, Business 구독자의 ChatGPT와 Codex 사용량이 단일 풀로 통합된다([TechRepublic](https://www.techrepublic.com/article/news-chatgpt-codex-shared-usage-limits/)). Settings > Usage에서 통합 잔여량과 리셋 시간을 확인할 수 있게 되며, Instant 채팅은 풀 밖에 남는다([The New Stack](https://thenewstack.io/openai-chatgpt-codex-shared-limits/)). 커뮤니티 반발에 OpenAI는 Pro 200 한도를 유지하고 모든 Pro 티어와 Business Premium의 한도를 2배로 늘리겠다고 약속했다([OpenAI Community](https://community.openai.com/t/please-keep-chatgpt-and-codex-usage-limits-separate-in-december-2026/1411466.md)). 하지만 정확한 풀 크기와 리셋 주기는 아직 미공개 상태다([CryptoBriefing](https://cryptobriefing.com/openai-unifies-chatgpt-codex-token-allowance/)).

## Copilot Gemini 4 Carbon 가격 D-4: $4/$20 per MTok

12월 1일부터 Gemini 4 Carbon의 토큰당 가격이 2배로 인상된다 — 입력 $2→$4, 출력 $10→$20 per MTok([eWeek](https://www.eweek.com/news/google-gemini-4-carbon-api-pricing/)). 태스크당 비용은 $10.96으로 Opus 5.5를 넘어선다([FourWeekMBA](https://fourweekmba.com/ai-gemini-4-carbon-doubles-to-10-96-a-task-above-opus-5-5/)). 12월 14일에는 Gemini 4 Argon이 퇴역 예정이며, Neon이 Carbon 대비 저비용 대안으로 떠오르고 있다([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)).

## CloudBees 유럽 설문: AI로 빨라졌지만 비용 절감은 아직

CloudBees가 450명의 유럽 IT 리더를 대상으로 한 설문에서 71%가 AI 도구로 개발 속도가 빨라졌다고 답했으나, 34%는 AI 생성 코드 리뷰에 절감된 시간만큼을 다시 소모하고 있다고 응답했다([GlobeNewsWire](https://www.globenewswire.com/news-release/2026/11/24/3409184/0/en/ai-coding-tools-speed-up-development-but-fail-to-cut-costs-it-leaders-say.html)). 이는 5월 발표된 본조사(93% 생산성 향상, 81% 프로덕션 장애 증가)의 후속 데이터로, "빠르지만 싸지는 않다"는 추세가 굳어지고 있다([CloudBees](https://www.cloudbees.com/newsroom/enterprise-technology-leaders-report-production-failures-from-ai-generated-code)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 12월 사용량 통합 D-4, Pro 한도 2배 약속 |
| Claude Code | 99 | — | Code Mode 실험 기능, v2.1.327 |
| Codex CLI | 99 | — | v0.170 WebRTC 음성 통화 |
| Antigravity | 99 | — | Google 유일 코딩 에이전트 안정 |
| Claude AI | 99 | — | Sonnet 4.5 퇴역 D-3 + Opus 4.8 Fast Mode D-3 |
| GH Copilot | 99 | — | Gemini 4 Carbon 가격 2배 D-4 (12/1) |
| Windsurf | 89 | — | Devin Desktop 통합 안정 |
| Aider | 68 | — | 유지보수 모드, 44K 스타 |
| Cursor | 1 | — | OpenAI 차단 16일째, 127일 연속 바닥 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

3사의 변경이 나흘 안에 집중된다. Sonnet 4.5 퇴역 + Opus 4.8 Fast Mode(11/30), Copilot Carbon 가격 2배(12/1), ChatGPT-Codex 사용량 통합(12월) — 오늘이 프로덕션 감사의 실질적 마지막 평일이다.

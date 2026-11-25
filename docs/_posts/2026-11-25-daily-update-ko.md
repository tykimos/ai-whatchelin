---
title: "Sonnet 4.5 퇴역 D-5, Cognition 'Devin Bots'로 멀티에이전트 시대 연다"
date: 2026-11-25
lang: ko
categories: [news]
tags: [anthropic, sonnet-5-5, copilot, gemini-4, ant-ipo, cursor, claude-code, codex-cli, devin-bots, windsurf]
excerpt: "Sonnet 4.5 퇴역까지 5일. 토크나이저 변경으로 단순 모델 교체만으론 부족하다. Cognition은 'Devin Bots'로 멀티에이전트 코딩 오케스트레이션에 본격 진입했다."
---

Anthropic의 Sonnet 4.5 퇴역이 5일 앞으로 다가온 가운데, Cognition이 Devin Bots를 출시하며 멀티에이전트 코딩의 새 장을 열었다. 한편 유럽 기업 설문조사는 AI 코딩 도구가 속도는 높이지만 비용은 줄이지 못한다는 현실을 보여줬다.

## Sonnet 4.5 퇴역 D-5: 마이그레이션은 모델명 교체가 아니다

Anthropic이 9월 30일 발표한 대로 Sonnet 4.5는 11월 30일부로 API에서 퇴역한다([Codersera](https://codersera.com/blog/claude-sonnet-4-5-retirement-migration-2026/)). 후속 모델 Sonnet 5.5는 9월 28일 출시됐으며 가격은 $2/$10 per MTok으로 Sonnet 4.5의 $3/$15보다 액면가 33% 저렴하다([TechCrunch](https://techcrunch.com/2026/09/28/anthropic-releases-sonnet-5-5-which-it-calls-a-significantly-cheaper-faster-work-partner/)). 그러나 새 토크나이저가 같은 텍스트에서 ~30% 더 많은 토큰을 생성하고, 2000x1500 이미지 처리 비용이 ~2.5배로 뛰어 실질 절감폭은 작다([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). Sonnet 4.5에서 작동하던 일부 파라미터가 5.5에서 거부되는 케이스도 보고되고 있어, 테스트 없이 전환하면 프로덕션 장애 위험이 있다.

## Cognition, 'Devin Bots'로 멀티에이전트 코딩 본격화

Cognition이 11월 중순 Devin Bots를 출시했다([The New Stack](https://thenewstack.io/cognition-devin-bots-management/)). Devin Bots는 여러 Devin 코딩 에이전트를 조율하는 상위 에이전트로, 대형 프로젝트를 하위 태스크로 분할해 각각의 Devin 인스턴스에 배분하고 CI 통과 후 머지까지 관리한다. Cognition은 올해 4월 멀티에이전트에 대한 기존 부정적 입장을 철회하고([Cognition Blog](https://cognition.com/blog/multi-agents-working)), 코딩+리뷰 에이전트 쌍 패턴이 실전에서 작동한다고 밝힌 바 있다. Devin Bots는 그 연장선으로, Windsurf(현 Devin Desktop) 생태계에 중요한 차별화 요소가 된다.

## Copilot, 11월에만 Gemini 4 모델 3종 추가

GitHub Copilot이 11월 한 달간 Google Gemini 4 계열 모델 3종을 연달아 추가했다. Carbon(11/10)([GitHub Blog](https://github.blog/changelog/2026-11-10-gemini-4-carbon-in-github-copilot)), Hydrogen Flash(11/13)([GitHub Blog](https://github.blog/changelog/2026-11-13-gemini-4-hydrogen-in-github-copilot)), Neon(11/18)([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot))이다. Pro+/Max/Business/Enterprise에서 사용 가능하며, Fusion GA와 맞물려 태스크별 최적 모델 자동 라우팅이 가능해졌다.

## "AI 도구, 속도는 올리지만 비용은 못 줄여" — 유럽 기업 설문

GlobeNewswire가 11월 24일 보도한 유럽 IT 리더 450명 대상 설문에 따르면, AI 코딩 도구가 개발 속도를 높이지만 비용 절감에는 뚜렷한 효과가 없다([GlobeNewswire](https://www.globenewswire.com/news-release/2026/11/24/3409184/0/en/ai-coding-tools-speed-up-development-but-fail-to-cut-costs-it-leaders-say.html)). 응답자의 약 1/3은 AI 산출물 리뷰·수정에 절약한 시간만큼을 다시 쓰고 있다고 답했다. 이는 CloudBees의 5월 조사에서 81%가 AI 코드로 인한 프로덕션 장애를 경험했다는 결과([CloudBees](https://www.cloudbees.com/newsroom/enterprise-technology-leaders-report-production-failures-from-ai-generated-code))와 맥을 같이한다.

## ANT IPO · Claude Code · Codex CLI 근황

Anthropic(ANT)이 11/19 Nasdaq 상장 후 첫 주를 마감했다. $83 공모가에 $111.50 시초가를 형성한 뒤 $95-99 구간에서 등락 중이다([TechRepublic](https://www.techrepublic.com/article/news-anthropic-ipo-nasdaq-trading-debut/)). Claude Code v2.1.327은 Code Mode 에이전트 팀 활성화와 원격 세션 실시간 스트리밍을 추가했다([Claude World](https://claude-world.com/articles/claude-code-november-2026-whats-new/)). Codex CLI는 v0.169~v0.170으로 멀티 사이드챗 탭, WebRTC 음성 통화 기능이 추가됐다([Havoptic](https://www.havoptic.com/releases/openai-codex/2026/11)). Cursor는 OpenAI 모델 차단 14일째이며 125일 연속 인기도 최하위다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 출시 9일차 |
| Claude Code | 99 | — | Claude Ship 베타 + v2.1.327 |
| Codex CLI | 99 | — | v0.170 멀티탭 사이드챗 |
| Antigravity | 99 | — | Google 유일 코딩 에이전트 안정 |
| Claude AI | 99 | — | Sonnet 4.5→5.5 전환 D-5 |
| GH Copilot | 99 | — | Gemini 4 모델 3종 11월 추가 완료 |
| Windsurf | 89 | ↑1 | Devin Bots 출시, 멀티에이전트 모멘텀 |
| Aider | 68 | — | 유지보수 모드, 44K 스타 |
| Cursor | 1 | — | OpenAI 차단 14일째, 125일 연속 바닥 |
| Gemini CLI | 1 | — | 11/1 퇴역, Antigravity로 전환 완료 |

Windsurf가 Devin Bots 출시 모멘텀을 타고 88→89로 올랐다. Sonnet 4.5 퇴역까지 5일 — 토크나이저 호환성 테스트 없이 전환하면 프로덕션 장애 위험이 있다. 유럽 기업 설문은 AI 도구의 ROI 논쟁에 새 불씨를 지폈다.

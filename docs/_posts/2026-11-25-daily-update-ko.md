---
title: "Sonnet 4.5 퇴역 D-5, Copilot에 Gemini 4 모델 3종 쏟아진다"
date: 2026-11-25
lang: ko
categories: [news]
tags: [anthropic, sonnet-5-5, copilot, gemini-4, ant-ipo, cursor, claude-code, codex-cli]
excerpt: "Sonnet 4.5가 11월 30일 퇴역한다. 토크나이저 변경으로 단순 모델명 교체만으론 부족하다. 한편 Copilot은 11월에만 Gemini 4 모델 3종을 추가하며 멀티모델 전략을 가속한다."
---

Anthropic의 Sonnet 4.5 퇴역이 5일 앞으로 다가왔다. 단순히 모델 ID를 바꾸는 것으로는 부족하다는 경고가 나오고 있어, API 사용자들의 긴급 마이그레이션이 시작됐다.

## Sonnet 4.5 퇴역 D-5: 마이그레이션은 모델명 교체가 아니다

Anthropic이 9월 30일 발표한 대로 Sonnet 4.5는 11월 30일부로 API에서 퇴역한다([Codersera](https://codersera.com/blog/claude-sonnet-4-5-retirement-migration-2026/)). 후속 모델 Sonnet 5.5는 9월 28일 출시됐으며 가격은 $2/$10 per MTok으로 Sonnet 4.5의 $3/$15보다 액면가 33% 저렴하다([TechCrunch](https://techcrunch.com/2026/09/28/anthropic-releases-sonnet-5-5-which-it-calls-a-significantly-cheaper-faster-work-partner/)). 그러나 새 토크나이저가 같은 텍스트에서 ~30% 더 많은 토큰을 생성하고, 2000x1500 이미지 처리 비용이 ~2.5배로 뛰어 실질 절감폭은 작다([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). Sonnet 4.5에서 작동하던 일부 파라미터가 5.5에서 거부되는 케이스도 보고되고 있어, 테스트 없이 전환하면 프로덕션 장애 위험이 있다.

## Copilot, 11월에만 Gemini 4 모델 3종 추가

GitHub Copilot이 11월 한 달간 Google Gemini 4 계열 모델 3종을 연달아 추가했다. Carbon(11/10)([GitHub Blog](https://github.blog/changelog/2026-11-10-gemini-4-carbon-in-github-copilot)), Hydrogen Flash(11/13)([GitHub Blog](https://github.blog/changelog/2026-11-13-gemini-4-hydrogen-in-github-copilot)), Neon(11/18)([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot))이다. Pro+/Max/Business/Enterprise에서 사용 가능하며, 사용량 기반 과금이 적용된다. Fusion GA와 맞물려 태스크별 최적 모델 자동 라우팅이 가능해졌다. 일본 매체 labmemo.com은 Carbon 토큰 단가가 12/1부터 2배로 오른다고 보도했으나, 공식 확인은 없다.

## ANT IPO 1주차 마감

Anthropic(ANT)이 11/19 Nasdaq 상장 후 첫 주를 마감했다. $83 공모가에 $111.50 시초가를 형성한 뒤 $95-99 구간에서 등락 중이다([TechRepublic](https://www.techrepublic.com/article/news-anthropic-ipo-nasdaq-trading-debut/)). 유통 주식이 전체의 ~6%에 불과해 변동성이 크며, Nasdaq-100 편입은 12/18 정기 리밸런싱까지 대기해야 한다([Saxo Bank](https://www.home.saxo/en-gb/content/articles/equities/anthropic-debut-uk-19112026)).

## Claude Code · Codex CLI 근황

Claude Code v2.1.327은 Code Mode 에이전트 팀 활성화와 원격 세션 실시간 스트리밍을 추가했다([Claude World](https://claude-world.com/articles/claude-code-november-2026-whats-new/)). Codex CLI는 v0.169~v0.170으로 멀티 사이드챗 탭, 인터미널 프로바이더 셋업, WebRTC 음성 통화 기능이 추가됐다([Havoptic](https://www.havoptic.com/releases/openai-codex/2026/11)). Cursor는 OpenAI 모델 차단 14일째이며 125일 연속 인기도 최하위다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 출시 9일차 |
| Claude Code | 99 | — | Claude Ship 베타 + v2.1.327 |
| Codex CLI | 99 | — | v0.170 멀티탭 사이드챗 |
| Antigravity | 99 | — | Google 유일 코딩 에이전트 안정 |
| Claude AI | 99 | — | Sonnet 4.5→5.5 전환 D-5 |
| GH Copilot | 99 | — | Gemini 4 모델 3종 11월 추가 완료 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드, 39K+ 스타 |
| Cursor | 1 | — | OpenAI 차단 14일째, 125일 연속 바닥 |
| Gemini CLI | 1 | — | 11/1 퇴역, Antigravity로 전환 완료 |

6개 도구 99점 동률 10일째. Sonnet 4.5 퇴역까지 5일 — 토크나이저 호환성 테스트 없이 전환하면 프로덕션 장애 위험이 있다. Copilot은 Gemini 4 모델 폭격으로 멀티모델 생태계를 굳히는 중이다.

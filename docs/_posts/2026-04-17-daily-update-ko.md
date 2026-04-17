---
title: "Claude Opus 4.7 출시 — Anthropic, 코딩 AI 왕좌 굳히다"
date: 2026-04-17
lang: ko
categories: [news]
tags: [anthropic, claude, opus, claude-code, antigravity, copilot]
excerpt: "Anthropic이 Claude Opus 4.7을 정식 출시하며 소프트웨어 엔지니어링 벤치마크를 다시 끌어올렸다. 같은 주에 Claude Code 데스크톱이 완전히 재설계되고, Antigravity는 9시간 장애를 겪었다."
---

Anthropic이 이번 주 더블 펀치를 날렸다. 화요일에 Claude Code 데스크톱을 병렬 세션 중심으로 완전 재설계하더니, 수요일에는 Claude Opus 4.7을 정식 출시했다. 코딩 AI 시장의 판도가 다시 한번 흔들리고 있다.

## Claude: Opus 4.7 + 데스크톱 재설계, 동시 투하

가장 큰 뉴스는 **Claude Opus 4.7**이다. Anthropic에 따르면 고급 소프트웨어 엔지니어링 작업에서 Opus 4.6보다 "눈에 띄는 개선"을 보이며, 가장 어려운 작업에서 특히 향상됐다([anthropic.com](https://www.anthropic.com/news/claude-opus-4-7)). 비전이 3.75MP 이미지까지 지원(기존 1.15MP의 3배 이상)하고, 새로운 `xhigh` 노력도 수준으로 추론과 지연 시간 사이의 트레이드오프를 더 세밀하게 조절할 수 있다. API 가격은 $5/$25(백만 토큰당)로 동일하다. Bedrock, Vertex, Foundry 모두에서 즉시 이용 가능하다([GitHub Blog](https://github.blog/changelog/2026-04-16-claude-opus-4-7-is-generally-available/)).

하루 전인 4월 15일에는 **Claude Code 데스크톱 앱이 완전히 재설계**됐다. 핵심은 병렬 세션 사이드바, 드래그앤드롭 워크스페이스 레이아웃, 통합 터미널, 앱 내 파일 편집기, 대규모 변경 세트를 위한 diff 뷰어 개선이다([MacRumors](https://www.macrumors.com/2026/04/15/anthropic-rebuilds-claude-code-desktop-app/)). 여기에 **Routines** — 활성 세션 없이 스케줄, API, GitHub 이벤트로 실행되는 자동화 기능도 발표됐다.

## Antigravity: 9시간 장애, 신뢰도에 타격

같은 4월 15일, Google Antigravity가 **9시간 이상의 심각한 서비스 장애**를 겪었다. 신규 사용자가 온보딩 설정을 완료할 수 없었고, 기존 사용자도 간헐적으로 작업이 중단됐다([Google AI Developers Forum](https://discuss.ai.google.dev/t/service-disruption-regarding-the-google-antigravity-ide/140225)). 출시 2개월 만에 6% 채택률을 기록한 도구에게 이런 장기 장애는 프로덕션 준비 상태에 대한 의문을 키운다. 인기도 점수가 51에서 50으로 한 단계 더 하락했다.

## Copilot: 데이터 학습 마감 1주일 전

GitHub Copilot의 **데이터 학습 옵트아웃 마감(4월 24일)**이 1주일 앞으로 다가왔다. Free/Pro/Pro+ 사용자의 상호작용 데이터가 AI 모델 학습에 기본 사용되는 정책으로, 커뮤니티 토론에 👎 232개가 달렸다([GitHub Community](https://github.com/orgs/community/discussions/188488)). 점수가 85로 추락하며 추적 기간 중 최저점을 갱신했다. Cursor(90)와의 격차가 이제 5점이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | 부동의 1위 |
| Claude Code | 94 | ↑2 | Opus 4.7 + 데스크톱 재설계 효과 |
| Cursor | 90 | — | 안정적 2위권 |
| Claude AI | 88 | ↑1 | Opus 4.7 출시 수혜 |
| GitHub Copilot | 85 | ↓1 | 데이터 학습 마감 임박, 최저점 |
| Windsurf | 74 | — | 횡보 |
| Codex CLI | 72 | — | 안정 |
| Aider | 68 | — | 니치 충성도 유지 |
| Gemini CLI | 65 | — | 안정 |
| Antigravity | 50 | ↓1 | 9시간 장애, 역대 최저 |

Claude Code가 94로 치솟으며 Cursor(90)를 4점 차로 따돌렸다. Opus 4.7과 데스크톱 재설계의 시너지가 명확하다. 반면 Antigravity(50)와 Copilot(85)은 각각 장애와 프라이버시 논란으로 하락세를 이어가고 있다.

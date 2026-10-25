---
title: "Universe D-3 — Copilot 57점 돌파, 레거시 API 마이그레이션 혼란 이틀째"
date: 2026-10-25
lang: ko
categories: [news]
tags: [copilot, openai, github-universe, cursor, claude-code, antigravity]
excerpt: "GPT-4 레거시 API 폐쇄 이틀째, OpenAI 커뮤니티에 마이그레이션 오류 제보가 계속되고 있다. Copilot은 57점으로 올라 Universe까지 3일을 남겨두고 있다."
---

GPT-4 레거시 API 폐쇄 후 이틀째다. 10월 23일 GPT-4, GPT-3.5 Turbo, o1, o3-mini 등 11개 모델이 영구 종료됐고, "model not supported" 오류 제보가 커뮤니티에 계속 쌓이고 있다([OpenAI Community](https://community.openai.com/t/deprecation-notice-upcoming-model-shutdowns-in-2026/1379553)). 하드코딩된 모델 ID 호출은 자동 폴백 없이 즉시 실패하며, GPT-5.6 Sol로의 마이그레이션이 필수다([OpenAI Deprecations](https://developers.openai.com/api/docs/deprecations/index.html)). GPT-4o와 GPT-4.1 계열은 2027년 1월 14일까지 유지되지만, 기업들의 사전 마이그레이션 압력이 거세지고 있다([Geeks IT](https://geeks.it.com/?p=976)).

## Copilot: 57점, Universe D-3

Copilot이 57점을 기록하며 9월 28일 이후 28일 연속 +2/일 상승 추세를 이어가고 있다([GitHub Blog](https://github.blog/changelog/2026-09-25-default-enablement-of-copilot-features-for-copilot-business-and-enterprise)). 10월 22일 발효된 기본 활성화 정책이 미구성 조직의 MCP 서버·코드 리뷰·에이전트 기능을 자동으로 켜면서 실사용 지표에 꾸준한 부스트를 제공하고 있다([Digital Applied](https://www.digitalapplied.com/blog/github-copilot-default-on-october-22-admin-checklist)). [GitHub Universe 2026](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)(10/28~29, Fort Mason)까지 3일 — "The view from the labs" 패널에서 Anthropic·OpenAI·GitHub이 AI 코딩의 다음 단계를 논의할 예정이다([Blockchain News](https://blockchain.news/news/github-universe-2026-schedule-ai-focus)).

## Cursor: 60일째 바닥, OpenAI 차단 D-18

Cursor는 60일째 1점에 머물고 있다. 11월 12일 OpenAI 모델 접근 차단까지 18일. Copilot과의 격차는 56점(57 vs 1)으로 매일 역대 최대를 갱신 중이다. 10월 13일 출범한 X Subscription 번들(SpaceX의 Grok+Cursor+X Premium 통합 구독)이 12일째인데도 개발자 복귀 조짐은 전혀 보이지 않는다.

## Antigravity: Gemini 4 Argon Pro 롤아웃 진행 중

Google의 Gemini 4 Argon이 10월 15일부터 AI Ultra에 이어 Pro 사용자에게 순차 롤아웃 중이다([Havoptic](https://www.havoptic.com/releases/github-copilot/2026/10)). $2/$10/MTok 도입 가격에 캐시 입력 95% 할인, 1M 출력 토큰 한도(기존 64K에서 대폭 확장), DeepSWE v1.1 77.9%로 벤치마크 최상위권이다. Antigravity v2.24.0(10/13)은 재설계된 사이드 패널과 /teamwork-preview 멀티 서브에이전트 조율 프리뷰를 추가했다.

## Codex: 28일 개선 서약 D-21

OpenAI의 Codex 프로덕트 책임자 Thibault Sottiaux가 10월 4일 X에서 "28일 동안 매일 Codex/Work 사용자에게 분명히 유용한 개선 하나를 출시하겠다, 실패하면 사용량 전면 리셋"이라고 선언했다([Nerdschalk](https://nerdschalk.com/openai-codex-28-day-reset-pledge/)). 10월 5일~11월 2일 사이클로, 현재 D-21(4일차). 배경에는 DevDay 이후 Pro 200 플랜의 Codex 허용량이 Plus의 20배에서 10배로 삭감된 불만이 깔려 있으며, 기존 사용자는 10월 29일까지만 기존 허용량이 유지된다([ToolNavs](https://toolnavs.com/en/article/2317)). GPT-6.1 Sol Ultrafast가 10월 8일부터 Pro 500·Enterprise·Edu에 개방된 것도 서약의 일환으로 보인다([SessionWatcher](https://sessionwatcher.com/news/codex-gpt-6-1-sol-ultrafast-pro-500-enterprise-edu)).

## 주간 트렌드: 마이그레이션 피로와 Universe 기대감

이번 주의 키워드는 두 가지다. 첫째, **마이그레이션 피로**. OpenAI의 잇따른 모델 퇴역과 GitHub Copilot의 10월 2일·19일 두 차례 일괄 모델 교체가 개발자 워크플로우를 크게 흔들고 있다. TrueFoundry 등은 하드코딩 대신 가상 모델 별칭(virtual model alias) 전략을 권장하고 있다([TrueFoundry](https://www.truefoundry.com/blog/model-deprecations-virtual-models-staged-cutovers)). 둘째, **Universe 기대감**. Copilot 에이전트 위임·MCP 서버 보안·HydraFusion 확장 등이 발표될 가능성이 높아 개발자 커뮤니티의 관심이 집중되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 레거시 API 폐쇄 후 마이그레이션 혼란 |
| Claude Code | 99 | — | v2.1.310, IPO S-1 임박 |
| Codex CLI | 99 | — | GPT-6.1 Sol 기본 모델 |
| Antigravity | 99 | — | Gemini 4 Argon Pro 롤아웃 |
| Claude AI | 99 | — | 5.5 패밀리 완성 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 오픈소스, 안정 |
| GH Copilot | 57 | ↑2 | 28일 연속 상승, Universe D-3 |
| Cursor | 1 | — | 60일째 바닥, OpenAI 차단 D-18 |
| Gemini CLI | 1 | — | 퇴역 완료 |

Universe(D-3)가 Copilot의 다음 도약 계기가 될지, 아니면 이미 가격에 반영된 이벤트인지 — 월요일이 분수령이다.

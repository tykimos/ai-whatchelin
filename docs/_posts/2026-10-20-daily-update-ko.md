---
title: "Codex /config 시대 개막, GPT-5.5 퇴역 후폭풍 — Universe까지 8일"
date: 2026-10-20
lang: ko
categories: [news]
tags: [codex-cli, copilot, antigravity, chatgpt, cursor]
excerpt: "Codex CLI v0.163.0이 인세션 /config 명령을 탑재하며 안정 빌드에 도달했다. GPT-5.5 퇴역 6일차, 마이그레이션 오류 보고가 이어지는 가운데 Universe는 8일 앞으로 다가왔다."
---

Codex CLI v0.163.0이 안정 빌드로 올라오며 터미널 코딩 에이전트의 사용성이 한 단계 도약했다. 세션 내에서 설정을 검색·변경할 수 있는 `/config` 명령, 응답 도중 후속 질문으로 방향을 즉시 전환하는 mid-response steering, 독립적인 읽기 전용 도구의 병렬 실행이 핵심 신규 기능이다([Codex Blog](https://codex.danielvaughan.com/2026/10/16/codex-v0163-stable-release-config-follow-up-parallel-tools-daybreak/)). Daybreak도 적격 계정에서 기본 활성화됐다.

## Codex CLI: /config 명령으로 워크플로 간소화

v0.163.0의 `/config`는 재시작 없이 설정 브라우저를 열어 환경을 조정할 수 있게 해준다([Havoptic](https://www.havoptic.com/r/openai-codex-rust-v0.163.0)). `/keymap`에서 리더 키도 변경 가능하며(기본 Ctrl+X), 음성 음소거는 F9로 이동했다. v0.162.0(10/8)에서 추가된 클릭 가능한 URL, 작업 고정(pinning), Git 워크트리 관리와 합쳐지면서, Codex CLI는 IDE급 편의 기능을 터미널에 이식하는 데 한 걸음 더 다가섰다.

## GPT-5.5 퇴역 후폭풍: "gpt-5.5 model is not supported"

10월 14일 정오(PDT) GPT-5.5가 ChatGPT·Work·Codex 전 플랜에서 영구 제거됐다([OpenAI Changelog](https://learn.chatgpt.com/docs/changelog)). 퇴역 6일차인 오늘까지 "gpt-5.5 model is not supported" 오류 보고가 이어지고 있다([DevelopersDig](https://www.developersdigest.tech/blog/codex-gpt-5-5-not-supported-chatgpt-account-fix-2026)). 워크스페이스 기본값·저장된 모델 설정·커스텀 에이전트·예약 작업에 구 모델 ID가 남아 있는 것이 주 원인이다. 수정은 gpt-5.6-sol 또는 gpt-6.1-sol로 전환하면 된다. API 키 인증 사용자는 영향 없다([OrcaRouter](https://www.orcarouter.ai/blog/gpt-5-5-remains-available-openai-api-codex-api-key)).

## Copilot: 47점, Universe D-8

Copilot은 47점까지 상승하며 2일 연속 +2 상승세를 유지하고 있다. [GitHub Universe 2026](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)(10/28~29, 샌프란시스코 Fort Mason)이 8일 앞으로 다가왔다. Copilot 에이전트 위임, MCP 서버 보안, Anthropic·OpenAI·GitHub 합동 패널 등이 예고되어 있으며([Blockchain News](https://blockchain.news/news/github-universe-2026-schedule-ai-focus)), 차세대 에이전트 로드맵 공개가 유력하다.

## Antigravity: Gemini 4 Argon, Pro 접근 확대 중

Google이 10월 13일부터 Antigravity 데스크톱 앱과 CLI에서 Gemini 4 Argon 롤아웃을 시작했다([Antigravity Blog](https://antigravity.google/blog/gemini-4-argon-in-google-antigravity)). 10월 15일부로 유료 AI Pro 구독자에게도 접근이 확대됐으며, Pro 티어에는 기존 Gemini 3.8 Flash 쿼터와 별도인 주간 전용(weekly-only) Argon 쿼터가 부여된다([pasqualepillitteri](https://pasqualepillitteri.it/en/news/24640/gemini-4-argon-antigravity-ai-pro-separate-weekly-quota)). 다만 무료 체험판·AI Plus 사용자는 여전히 제외된다. API 소개 가격은 입력 $2/출력 $10(MTok), 11월 30일까지 유효한 것으로 전해진다. 한편 11월 2일 Claude Sonnet 4.6·Opus 4.6·GPT-OSS-120B의 Antigravity 내 퇴역이 예고되어 있다([Layer3 Labs](https://www.layer3labs.io/guides/google-antigravity-cli)).

## Cursor: 55일째 바닥, OpenAI 차단 D-23

Cursor는 55일째 바닥권(1점)에 머물고 있다. X Subscription 번들 출시 7일차이나 반등 신호가 전무하다([Trending Topics](https://www.trendingtopics.eu/x-subscription-grok-cursor-x-bundle/)). 개발자들의 핵심 불만은 Grok 모델만 공유 풀에 포함되고 타사 모델은 별도 결제가 필요한 구조에 집중되어 있다([DevOps.com](https://devops.com/one-bill-for-grok-cursor-and-x-what-spacexs-bundle-means-for-dev)). Cursor 포럼에서는 장기 Ultra 구독자가 *"자충수(self-sabotage)"*라며 *"Cursor의 매력은 모델 중립성이었는데, 같은 이름의 새 Ultra와 구 Ultra는 완전히 다른 상품"*이라고 비판했다([Cursor Forum](https://forum.cursor.com/t/introducing-the-x-subscription/174450/27)). 11월 12일 OpenAI 모델 접근 차단까지 23일.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.5 퇴역 완료, GPT-Live-1.1 안정 |
| Claude Code | 99 | — | v2.1.294 안정, Anthropic IPO 로드쇼 11월 예상 |
| Codex CLI | 99 | — | v0.163.0 /config 안정 빌드 |
| Antigravity | 99 | — | Gemini 4 Argon 롤아웃, Pro 확대 중 |
| Claude AI | 99 | — | IPO 10~11월 예상, Investor Day 완료 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, 주요 업데이트 없음 |
| GH Copilot | 47 | ↑2 | Universe D-8, 에이전틱 자동수정 GA |
| Cursor | 1 | — | 55일째 바닥, X Subscription 무반응 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

Codex CLI v0.163.0의 /config 명령 도입으로 터미널 코딩 에이전트의 사용성 문턱이 낮아졌다. GPT-5.5 퇴역 후폭풍이 이어지는 가운데, Universe D-8 카운트다운이 이번 주의 최대 관전 포인트다.

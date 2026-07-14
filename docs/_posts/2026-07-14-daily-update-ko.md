---
title: "Fable 5 세 번째 연장 — Opus 5 'Honeycomb' 유출과 내일 출시되는 Codex Micro"
date: 2026-07-14
lang: ko
categories: [news]
tags: [fable-5, opus-5, codex-micro, claude-code, gemini-3-5-pro, jscrambler, security]
excerpt: "Anthropic이 Fable 5 무료 접근을 7월 19일까지 세 번째로 연장했다. Cursor에서 'Honeycomb EAP'라는 미공개 모델이 잠시 포착되면서 Opus 5 출시설이 힘을 얻고, OpenAI는 내일 첫 하드웨어 제품 Codex Micro를 공개한다."
---

5주 만에 세 번째 연장. Anthropic이 GPT-5.6 Sol과의 경쟁 속에서 Fable 5를 놓지 못하고 있다.

## Fable 5, 7월 19일까지 세 번째 연장 — 그리고 Opus 5 유출

Anthropic이 Fable 5의 유료 구독자 무료 접근을 7월 19일 23:59 PT까지 다시 연장했다([Forbes](https://www.forbes.com/sites/sandycarter/2026/07/13/claude-fable-5-extends-to-july-19-7-days-7-power-moves/)). Pro, Max, Team, Enterprise 프리미엄 플랜에서 주간 사용량의 50%까지 무료로 사용 가능하다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/claude-fable-5-stays-free-for-paid-users-until-july-19-as-anthropic-buys-more-time/)). 7월 7일→12일→19일로 이어진 세 번째 연장이며, OpenAI가 GPT-5.6 Sol을 출시한 같은 주에 리밋을 리셋하고 7일을 더 준 것이다([Forbes](https://www.forbes.com/sites/tylerroush/2026/07/13/ai-model-wars-anthropic-extends-fable-access-again-after-openais-sol-release/)).

더 흥미로운 것은 7월 8일 Cursor의 모델 선택 메뉴에 'Claude Honeycomb EAP'라는 미공개 모델이 잠시 나타났다가 수시간 만에 삭제된 사건이다([TechTimes](https://www.techtimes.com/articles/320265/20260712/fable-5-free-through-july-19-anthropic-blinks-again-opus-5-leak-surfaces-cursor.htm)). 커뮤니티에서는 이것이 Opus 5의 조기 접근 버전이라는 추측이 굳어지고 있지만, Anthropic은 공식 확인을 거부했다([The New Stack](https://thenewstack.io/fable-5-honeycomb-opus/)).

## Codex Micro — OpenAI 첫 하드웨어, 내일 출시

OpenAI가 키보드 제조사 Work Louder와 협업한 프로그래머블 매크로패드 Codex Micro를 7월 15일 출시한다([TechTimes](https://www.techtimes.com/articles/319389/20260630/openai-codex-micro-launches-july-15-macro-pad-built-work-louder.htm)). 13개 기계식 키, 조이스틱, 로터리 인코더, 6개 프로그래머블 레이어를 갖춘 이 디바이스는 주간 500만 활성 사용자를 돌파한 Codex 플랫폼의 물리적 확장이다([DevOps.com](https://devops.com/openai-expands-into-developer-hardware-with-codex-micro-keyboard/)). Creator Micro 2 기반으로 $144~$174 가격대가 예상된다.

## jscrambler 공급망 공격 — AI 도구 크리덴셜이 새 공격 표면

7월 11일 공개된 jscrambler npm 공급망 공격은 Rust 기반 인포스틸러로 Claude Desktop, Cursor, Windsurf, VS Code의 설정 파일에서 API 키와 MCP 서버 크리덴셜을 탈취한다([The Hacker News](https://thehackernews.com/2026/07/compromised-jscrambler-8140-npm-release.html)). 주간 다운로드 15,800건의 패키지가 무기화됐으며, 해당 버전 사용 프로젝트는 즉시 크리덴셜 로테이션이 필요하다([Socket](https://socket.dev/blog/jscrambler-supply-chain-attack)).

## Gemini 3.5 Pro — D-3, 7월 17일 GA 카운트다운

Google Gemini 3.5 Pro의 GA가 3일 앞으로 다가왔다([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). 200만 토큰 컨텍스트와 Deep Think 추론이 예상되지만 공식 확인은 없다. Copilot 사용자는 기존 Gemini 2.5 Pro / 3 Flash를 7월 31일까지 마이그레이션해야 한다([GitHub Changelog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)).

## Anthropic-Samsung 2nm 칩 파트너십 논의

Anthropic이 Samsung과 2나노 공정 기반 커스텀 AI 칩 제조를 논의 중이다([Bloomberg](https://www.bloomberg.com/news/articles/2026-07-02/anthropic-in-talks-with-samsung-for-custom-ai-chip-information-mr3l34t4)). 설계나 양산은 시작되지 않았지만, OpenAI의 Broadcom 협업 칩 'Jalapeño'에 이어 자체 실리콘 경쟁이 본격화되고 있다([TechCrunch](https://techcrunch.com/2026/07/02/anthropic-is-discussing-a-new-custom-chip-with-samsung/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 내장 브라우저, 스크린 리더 모드 |
| Antigravity | 99 | — | v2.2.1 안정, 24주 연속 |
| ChatGPT | 99 | — | Sol 5시간 제한 해제, Codex Micro 내일 |
| Claude AI | 98 | — | Fable 5 세 번째 연장, Honeycomb 유출 |
| Cursor | 97 | — | 3.11 사이드 챗, Honeycomb 포착 |
| Codex CLI | 90 | — | ChatGPT 통합 완료, GPT-5.6 탑재 |
| Windsurf | 85 | — | Devin Desktop, Sonnet 5 탑재 |
| Aider | 68 | — | 오픈소스 꾸준, 44K 스타 |
| Gemini CLI | 13 | ↓1 | 셧다운 26일째, 기업 전용 |
| Copilot | 12 | ↓1 | 69주 하락, Gemini 모델 디프리케이션 |

Fable 5 연장전과 Opus 5 유출, Codex Micro 하드웨어 출시, 그리고 Gemini 3.5 Pro GA — 이번 주는 모델 전쟁과 플랫폼 경쟁이 동시에 격화되는 한 주다.

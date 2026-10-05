---
title: "Claude Code 보안 패치, Anthropic IPO 투자자 데이 D-9 — 조용한 일요일 속 진짜 움직임"
date: 2026-10-05
lang: ko
categories: [news]
tags: [claude-code, anthropic-ipo, copilot, cursor, jetbrains-air, ibm-bob, qodo]
excerpt: "Claude Code v2.1.289가 deny 규칙 우회 취약점을 두 번째로 패치했고, Anthropic은 10월 14일 프리IPO 투자자 데이를 앞두고 있다. JetBrains Air EAP와 IBM Bob 자체호스팅이 이번 주 시장 지형을 바꾸고 있다."
---

주말임에도 AI 코딩 도구 시장은 멈추지 않았다. Claude Code는 또 한 번의 보안 패치를 내놓았고, Anthropic의 IPO 시계는 투자자 데이 D-9로 카운트다운에 들어갔다. 한편, 이번 주 초 발표된 JetBrains Air와 IBM Bob 자체호스팅이 에이전틱 코딩의 엔터프라이즈 지형을 재편하고 있다.

## Claude Code: v2.1.289 — deny 규칙 우회 두 번째 패치

Anthropic이 10월 3일 Claude Code v2.1.289를 배포했다([mixed-news.com](https://mixed-news.com/en/claude-code-2-1-289-second-route-past-rm-guard-stable-four-builds-behind/)). 이번 릴리스는 주로 보안 수정에 집중됐는데, deny/ask 규칙이 환경변수 프리픽스 뒤에 숨은 명령(예: `TZ="$HOME" rm -rf build`)을 놓치는 취약점을 차단했다([ai-tldr.dev](https://ai-tldr.dev/releases/anthropic-claude-code-2-1-289/)). 심링크를 통한 Read deny 규칙 우회와 복합 셸 명령에서 모드 승인이 deny를 무시하는 문제도 함께 수정됐다. 기능 면에서는 `agent.spawn`으로 팀메이트 에이전트 생성, 플러그인 훅 이벤트의 통합 에이전트 ID가 추가됐다.

## Anthropic IPO: 투자자 데이 10월 14일, 11월 중순 상장 가닥

Bloomberg에 따르면 Anthropic이 10월 14일 샌프란시스코 본사에서 프리IPO 투자자 데이를 개최한다([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/anthropic-is-said-to-plan-pre-ipo-investor-day-as-listing-nears)). 11월 9일 주간 마케팅 개시, 11월 중순 상장이 유력하며, 목표 밸류에이션은 최대 $2조다([Yahoo Finance](https://finance.yahoo.com/technology/article/anthropic-reportedly-looking-to-ipo-as-early-as-mid-november-180315768.html)). 성사 시 역대 최대 규모 IPO가 된다.

## JetBrains Air EAP: IDE 에이전틱 레이어의 등장

JetBrains가 10월 1일 Air EAP를 개시했다([SD Times](https://sdtimes.com/ai/sd-times-news-roundup-oct-1-2026-ibm-bob-jetbrains-air-qodo-3-0/)). 2026.3 EAP 빌드에 통합되는 에이전틱 개발 레이어로, Codex·GitHub Copilot·Junie·Cursor 등 외부 에이전트와 연동된다. 디버깅·코드 검색 등 IDE 스킬이 내장돼 있으며, JetBrains AI 구독 없이도 사용 가능하다.

## Cursor: 39일째 하락, OpenAI 셧오프 D-38

Cursor의 인기도가 39일 연속 하락해 21까지 떨어졌다. OpenAI 모델 접근 차단까지 38일 남았으며([DevOps.com](https://devops.com/openai-cuts-off-cursors-model-access-after-spacex-acquisition/)), SpaceX 인수 이후 Origin 플랫폼 독립과 모바일 베타 출시에 생존이 달려 있는 상황이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay 여파, GPT-6.1 Sol 안착 |
| Claude Code | 99 | — | v2.1.289 보안 패치, IPO D-9 |
| Codex CLI | 99 | — | v0.160.0 안정, Cloud 모드 확산 |
| Antigravity | 99 | — | Claude Opus 5.5 모델 추가 |
| Claude AI | 99 | — | Opus 5.5·Sonnet 5.5, 음성 데이터 수집 |
| Windsurf | 88 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 꾸준한 오픈소스, 44K 스타 |
| Cursor | 21 | ↓2 | 39일 연속 하락, OpenAI 셧오프 D-38 |
| GH Copilot | 17 | ↑2 | Computer Use GA, 10/19 모델 퇴출 예정 |
| Gemini CLI | 1 | — | Antigravity CLI 전환 완료 |

주말에도 시장은 쉬지 않는다. Claude Code의 연이은 보안 패치는 에이전틱 코딩의 권한 관리가 얼마나 복잡한 문제인지를 보여주고, Anthropic IPO 카운트다운은 AI 업계 전체의 자금 흐름을 바꿀 이벤트로 다가오고 있다.

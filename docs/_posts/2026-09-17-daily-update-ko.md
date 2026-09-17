---
title: "DOJ, AI 코딩 도구 저작권 무혐의 판결 — Claude 앱 통합, ChatGPT 광고 에이전트 테스트"
date: 2026-09-17
lang: ko
categories: [news]
tags: [claude-code, anthropic, openai, chatgpt, cursor, doj, copyright, gemini]
excerpt: "미 법무부가 GitHub Copilot·Codex의 저작권 침해 무혐의를 확정했고, Claude는 Cowork·채팅·디자인을 하나로 통합했다. OpenAI는 ChatGPT에 광고 에이전트를 테스트하고, Cursor는 28일째 하락 중이다."
---

미 법무부(DOJ)가 어제 GitHub, Microsoft, OpenAI의 AI 코딩 도구가 원저작자 표기 없이 코드를 생성하더라도 저작권법 위반이 아니라고 판결했다 — AI 코딩 업계 전체를 뒤흔들었던 소송의 종결이다. 같은 날 Anthropic은 Claude 앱을 대폭 리디자인했고, OpenAI는 ChatGPT 안에 광고 에이전트를 처음 테스트했다. Cursor의 하락은 28일째로 접어들며 50선 테스트가 현실화되고 있다.

## DOJ 저작권 판결: AI 코딩 도구의 법적 리스크 해소

미 법무부가 9/16에 GitHub, Microsoft, OpenAI가 AI 코딩 도구를 통해 원저작자 크레딧·라이선스 표기 없이 코드를 생성한 것이 저작권법 위반이 아니라고 발표했다([GitHub yaojiejia/agents-radar #150](https://github.com/yaojiejia/agents-radar/issues/150)). 이 판결은 Copilot 초기부터 이어진 오픈소스 커뮤니티의 핵심 우려를 정면으로 해소한다. AI 학습 데이터의 저작권 문제는 코딩 도구에 한정되지 않지만, 이번 판결이 향후 생성 AI 전반의 법적 판례에 영향을 미칠 전망이다.

## Claude: 앱 통합 리디자인 + v2.1.274

Anthropic이 Claude의 Cowork와 채팅을 하나의 앱으로 통합하고, Docs와 Slides 도구를 추가했다([Releasebot](https://releasebot.io/updates/anthropic/claude)). Claude Design이 대화 안에서 직접 작동하면서 보고서·프레젠테이션·시각 자료를 한 곳에서 작업할 수 있게 됐다. Pro·Max 플랜부터 순차 롤아웃 중이다. 별도로 Claude Code v2.1.274가 오늘 릴리스됐으며, 메모리 사용량 위험 시 경고 표시와 MCP 서버 연결 대기 시간을 제어하는 `CLAUDE_CODE_MCP_STARTUP_WAIT_MS` 파라미터가 추가됐다([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)).

## OpenAI: ChatGPT에 광고 에이전트 첫 테스트

OpenAI가 9/16에 Wayfair와 Angi를 파트너로 ChatGPT 내 스폰서드 에이전트(광고 에이전트)를 처음 테스트했다([AI Weekly](https://aiweekly.co/ai-news-today/openai-news)). 사용자가 가구나 홈서비스를 검색하면 해당 브랜드의 에이전트가 추천을 제공하는 형태다. ChatGPT의 수익 모델이 구독 너머로 확장되는 첫 신호이며, 동시에 GPT-5.5는 10/14에 ChatGPT·Codex 전 플랜에서 은퇴 예정이다([Releasebot](https://releasebot.io/updates/openai/chatgpt)).

## Cursor: 57점, 28일 연속 하락 — 50선 테스트 임박

Cursor가 57점을 기록하며 28일 연속 하락세를 이어갔다. SpaceX 인수 완료(8/14) 이후 99에서 시작된 하락이 멈추지 않고 있다([CBS News](https://www.cbsnews.com/news/spacex-cursor-60-billion-ai-acquisition/)). OpenAI의 11/12 모델 접근 종료 통보, Origin 데이터 약관 논란, SpaceX 지배구조 우려가 복합적으로 작용 중이다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). 기술적으로는 Projects 베타와 Grok 4.6 전환이 진행 중이지만, 심리 회복의 카탈리스트가 여전히 부재하다.

## Claude Sonnet 5 가격 인상 취소 확정

Anthropic 개발자 플랫폼에서 Claude Sonnet 5의 도입 가격($2/$10 per MTok)이 정식 가격으로 확정됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-developer-platform)). 당초 9/1부터 $3/$15로 인상 예정이었으나 인상이 적용되지 않았고, 이제 인트로 가격이 영구 가격이 됐다. API 사용자들에게 실질적 비용 절감이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 광고 에이전트 테스트, GPT-5.5 10/14 은퇴 |
| Claude Code | 99 | — | v2.1.274, 앱 통합 리디자인 |
| Claude AI | 99 | — | Sonnet 5 가격 인상 취소, Docs/Slides 추가 |
| Codex CLI | 99 | — | 스레드 스냅샷·고정 스레드 추가 |
| Antigravity | 99 | — | IDE 확장·커스텀 에이전트 안정화 |
| Windsurf | 87 | — | 안정기 지속 |
| Aider | 68 | — | 44K 스타, 주 2회 릴리스 유지 |
| Cursor | 57 | ↓2 | 28일 연속 하락, 50선 테스트 임박 |
| GH Copilot | 1 | — | DOJ 저작권 무혐의 확정 |
| Gemini CLI | 1 | — | v0.62.0-nightly, 실질 종료 |

DOJ 판결로 AI 코딩 도구의 법적 불확실성이 해소된 반면, Cursor의 하락은 법적 리스크가 아닌 지배구조·생태계 이탈이라는 구조적 문제에서 비롯된 것임을 다시 확인해준다.

---
title: "Anthropic IPO 오늘 밤 가격 확정 — $1.4조 밸류에이션, GPT-6.2 비공식 포착"
date: 2026-11-18
lang: ko
categories: [news]
tags: [anthropic, ipo, cursor, codex-cli, github-copilot, gpt-6.2, copilot-fusion]
excerpt: "Anthropic IPO가 오늘 밤 가격이 확정된다. GPT-6.2 Astra/Sol이 비공식 API 응답에 포착되었고, Cursor는 OpenAI 차단 속에서도 Live Apps·음성 대화·멀티플레이어를 연달아 출시했다."
---

오늘 밤이 AI 산업의 분수령이다. Anthropic이 Nasdaq 티커 ANT로 역사상 최대 AI IPO의 가격을 결정한다. 825백만 주의 Class A 주식이 $70-78 범위에서 제시되었으나, 주문장이 최대 6배 초과 청약된 상태로 주간사들이 범위 상단을 넘어서는 가격을 검토하고 있다([CNBC](https://www.cnbc.com/2026/11/10/anthropic-sets-price-range-of-70-to-78-in-upcoming-ipo.html)). $78 이상에서 확정되면 풀리 딜루티드 시가총액은 $1.41조를 넘어서며, 리테일 배분이 통상의 2-4배인 약 20%로 설정된 점도 주목할 만하다([Renaissance Capital](https://www.renaissancecapital.com/IPO-Center/News/122657/anthropic-sets-terms-for-61-billion-ipo-targeting-a-1.2-trillion-market-cap)). 11월 19일 거래 개시가 유력하다([Yahoo Finance](https://finance.yahoo.com/technology/live/anthropic-ipo-live-company-set-to-price-stock-between-70-and-78-as-trading-starts-thursday-174130523.html)).

## GPT-6.2 Astra / Sol: 비공식 포착, 출시 임박 시그널

OpenAI API 응답과 Codex 사용량 로그에서 `gpt-6.2-astra`와 `gpt-6.2-sol` 모델 ID가 비공식적으로 포착되고 있다([CometAPI](https://www.cometapi.com/gpt-6-2-astra-codex-sightings/)). 일부 ChatGPT Work 및 Codex 사용자에게 11월 8일부터 테스트 배포가 진행된 것으로 보이지만([OverChat](https://overchat.ai/models/gpt-6-2-sol)), OpenAI는 아직 공식 발표를 하지 않았다. The Information은 이르면 이번 주 발표가 있을 수 있다고 보도했으나, 공식 릴리스 노트에는 모델 출시 관련 내용이 없다([OpenAI Release Notes](https://openai.com/products/release-notes/?via=bsahala)). 한편, OpenAI는 11월 초 ChatGPT의 Chat과 Work 탭을 통합하고 Codex와 토큰 풀을 공유하겠다고 발표한 바 있다([TechCrunch](https://techcrunch.com/2026/11/02/openai-is-finally-merging-chatgpts-chat-and-work-tabs/)).

## Cursor: 엔진 없는 차에 고급 인테리어 — 혁신의 역설

Cursor가 11월 초 세 가지 대형 기능을 연달아 출시했다. 11월 5일 Live Apps는 프롬프트만으로 웹앱을 빌드·배포하고 Postgres DB를 자동 연결하는 클라우드 에이전트 기능이다([TechRepublic](https://www.techrepublic.com/article/news-cursor-build-live-apps-features-pricing-security/)). 11월 6일에는 AI 에이전트와의 음성 대화 기능이 iOS·데스크톱·웹에 출시되었고([SmartScope](https://smartscope.blog/en/blog/cursor-voice-chat-agent-voice-calls-setup-steps-2026/)), 11월 10일에는 팀원과 AI 에이전트가 하나의 워크스페이스를 공유하는 멀티플레이어 Projects 베타가 시작되었다([Cursor Blog](https://cursor.com/blog/projects-multiplayer)). 하지만 OpenAI 차단 7일째, Tab 자동완성과 클라우드 에이전트 같은 핵심 기능이 여전히 비활성 상태로 87일째 바닥(1점)이다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). 혁신적 기능이 쏟아지지만 엔진 없는 차의 역설이 계속되고 있다.

## GitHub Copilot: 퇴출 이틀째 안정, Fusion 할인 종료 임박

11월 16일 Claude Opus 4.8/5와 GPT-5.6 Terra 퇴출 이틀째로, 56일 연속 상승 체제(99점)가 이어지고 있다([GitHub Blog](https://github.blog/changelog/2026-11-16-github-copilot-models-deprecated-on-november-16-2026)). Copilot Fusion의 30% 할인이 11월 말 종료되며([InfoWorld](https://www.infoworld.com/article/4242710/github-bets-on-multi-agent-software-development-with-copilot-overhaul.html)), 12월 14일에는 Claude Fable 5, Claude Haiku 4.5, Gemini 3.8 Flash, Gemini 4 Argon, Grok 4.6, Kimi K3 등 6개 모델이 추가 퇴출될 예정이다([VPS Ranking](https://vpsranking.com/news/ai/ai-2026-11-13-github-copilot-december-model-deprecations/)).

## Codex CLI: 0.169.0 — 사이드 채팅 탭과 보안 강화

Codex CLI가 11월 13일 0.168.0과 0.169.0을 연달아 출시했다. 0.169.0은 탭형 사이드 채팅, 작업 검색, 접이식 턴 상세보기를 도입했고, `codex exec`가 비신뢰 디렉토리에서 프로젝트 설정과 MCP 서버를 비활성화하도록 보안이 강화되었다([ai-tldr.dev](https://ai-tldr.dev/releases/openai-codex-cli-0-169/)). 2026년 누적 115번째 릴리스로, 평균 3.9일에 한 번 출시되는 속도를 유지하고 있다([Havoptic](https://www.havoptic.com/r/openai-codex-rust-v0.169.0)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 비공식 포착 |
| Claude Code | 99 | — | IPO 가격 결정일, Fable 5.2 9일차 |
| Codex CLI | 99 | — | 0.169.0: 사이드 채팅 탭 + 보안 강화 |
| Antigravity | 99 | — | Gemini 4 Carbon 도입 할인 D-12 |
| Claude AI | 99 | — | IPO D-Day, 오늘 밤 가격 확정 |
| GH Copilot | 99 | — | 56일 연속 상승, Fusion 할인 종료 임박 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | Live Apps 출시에도 OpenAI 차단 7일째 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 임박 |

5개 도구의 99점 동시 1위 체제가 3일째 유지되고 있다. 오늘 밤 Anthropic IPO 가격이 확정되면 AI 산업 전체의 밸류에이션 지도가 다시 그려진다.

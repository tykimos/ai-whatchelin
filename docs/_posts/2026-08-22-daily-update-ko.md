---
title: "OpenAI, GPT-5.6 Sol 가격 20% 인하 — Codex 2,000만 돌파와 가격전 본격화"
date: 2026-08-22
lang: ko
categories: [news]
tags: [openai, gpt-5.6-sol, codex, claude-code, claude-academy, cursor, copilot, antigravity, pricing, security]
excerpt: "OpenAI가 GPT-5.6 Sol API 가격을 20% 이상 인하하고 Codex 2,000만 사용자를 돌파했다. Anthropic은 Claude Academy를 출시하며 교육 전선을 열었고, Copilot에서는 AI 자동 수정이 보안 사고로 이어졌다."
---

OpenAI가 프론티어 모델 GPT-5.6 Sol의 API 가격을 20% 이상 인하했다([Business Standard](https://www.business-standard.com/technology/tech-news/openai-cuts-developer-pricing-for-gpt-5-6-sol-model-by-more-than-20-126082200107_1.html)). 표준 단문 컨텍스트 기준 입력 토큰이 $5→$4, 출력 토큰이 $30→$20으로 내려갔다([Reuters via Investing.com](https://www.investing.com/news/stock-market-news/openai-cuts-developer-pricing-for-frontier-gpt56-sol-model-by-more-than-20-4872186)). 11월 21일까지 3개월 한정이지만, 지난달 Terra 20%·Luna 80% 인하에 이은 연속 공세다([CNBC](https://www.cnbc.com/2026/07/30/open-ai-price-cut-gpt.html)). Anthropic·중국 AI 모델의 추격에 개발자 이탈을 막으려는 수비적 행보로 읽힌다([Finimize](https://finimize.com/content/openai-cut-gpt-56-sol-api-prices-to-keep-developers-close)).

## Codex: 2,000만 사용자 돌파, 리셋 논란

Codex 리드 Tibo Sottiaux가 2,000만 활성 사용자 마일스톤을 발표하며 전 사용자에게 무료 뱅크 사용량 리셋을 제공했다([explainx.ai](https://www.explainx.ai/blog/openai-codex-20-million-users-banked-reset-august-2026)). 하지만 PST 오후 8시 전달 기한이 밀리고, 리셋이 30일 후 무통보 만료되는 점이 커뮤니티에서 논란이 됐다([OpenAI Community](https://community.openai.com/t/20-million-codex-users-a-free-banked-reset-for-everyone/1391683)). o3 모델은 8월 26일 ChatGPT 퇴장까지 D-4, GPT-5.4는 8월 31일 Codex 퇴출까지 D-9에 진입했다([OpenAI](https://openai.com/index/gpt-5-6/)).

## Claude: Academy 출시, Code v2.1.239

Anthropic이 Claude Academy를 출시했다([CryptoBriefing](https://cryptobriefing.com/anthropic-unveils-claude-academy-to-boost-ai-education-and-adoption/)). 26개 무료 과정으로 개발자·학생·교육자·전문가·비영리 5개 트랙을 제공하며, Claude 101부터 API·Claude Code 심화까지 커버한다([Techgenyz](https://techgenyz.com/claude-academy-free-courses/)).

Claude Code v2.1.239는 비용 추정에 데이터 레지던시 워크스페이스의 1.1배 US 추론 프리미엄을 반영하고, Python SDK 0.x→1.x 마이그레이션용 `/claude-api upgrade` 명령을 추가했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Alpine/musl 빌드 네이티브 지원과 Bedrock·Vertex·Foundry 풀스크린도 확대됐다([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)).

## Copilot: AI 자동 수정이 보안 구멍으로

Copilot Autofix가 Snowflake의 snowflake-connector-net에서 생성한 수정 코드가 셸 인젝션 취약점을 도입, 5일 만에 악용됐다([The Register](https://www.theregister.com/)). 별도로 CVE-2026-24301(CoSnitch) — Copilot URL 가져오기와 영구 메모리 포이즈닝을 연쇄한 공격 — 이 8월 18일 패치됐다. 102주 연속 인기도 하락이 이어지는 가운데, 9월 1일 대규모 모델 폐기까지 D-10이다([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)).

## Cursor: 이벤트 구독형 클라우드 에이전트 정착

Cursor의 8월 19일 업데이트로 클라우드 에이전트에 이벤트 구독이 추가됐다([Releasebot](https://releasebot.io/updates/cursor)). PR·Slack 스레드·크론 스케줄을 트리거로 등록하면 에이전트가 자동 기동한다([explainx.ai](https://www.explainx.ai/blog/cursor-event-driven-cloud-agents-isolated-vms-august-2026)). 8월 24일부터 Auto 가격 체계 변경이 예정돼 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.239 비용 정밀화, Alpine 지원 |
| ChatGPT | 99 | — | GPT-5.6 Sol 20%+ 인하, o3 퇴장 D-4 |
| Codex CLI | 99 | — | 2,000만 사용자, GPT-5.4 퇴장 D-9 |
| Antigravity | 99 | — | v2.9.1 Remote Control, 26주 연속 99 |
| Claude AI | 99 | — | Claude Academy 출시, Files API GA |
| Cursor | 99 | — | 이벤트 구독 에이전트, 8/24 가격 변경 예정 |
| Windsurf | 86 | — | Devin Local 안정화 지속 |
| Aider | 68 | — | v0.86.2 이후 6개월+ 무릴리스 |
| Copilot | 1 | — | 102주 하락, Autofix 보안 사고, 대폐기 D-10 |
| Gemini CLI | 1 | — | 폐쇄 65일째 |

OpenAI의 연속 가격 인하와 Codex 2,000만 돌파는 개발자 유치 경쟁이 기능에서 가격·규모로 이동했음을 보여준다. 한편 Copilot Autofix 보안 사고는 AI 코드 수정의 신뢰 문제를 새롭게 부각시켰다.

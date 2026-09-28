---
title: "Copilot 통합 경험 출시, DevDay D-1에 'o' 에이전트 요금제 유출"
date: 2026-09-28
lang: ko
categories: [news]
tags: [copilot, github, openai, devday, cursor, claude-code, legacy-models, antigravity]
excerpt: "GitHub Copilot 통합 경험이 정식 출시됐고, OpenAI DevDay 전날 'o' 에이전트의 3단계 요금제가 유출됐다. GPT-3.5 시대가 공식 종료되고, Cursor는 31일 연속 하락 중이다."
---

GitHub Copilot 통합 경험이 오늘(9/28) 공식 출시됐다. OpenAI DevDay가 내일(9/29)로 다가온 가운데 상시 에이전트 "o"의 3단계 요금 체계가 유출됐고, GPT-3.5 시리즈 마지막 엔드포인트가 오늘 퇴역했다.

## GitHub Copilot: 통합 경험 정식 출시

GitHub이 오늘부터 Copilot Chat(github.com), Copilot Chat(Mobile), Copilot 클라우드 에이전트를 하나의 통합 경험으로 합쳤다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 기존 개별 정책이 단일 정책으로 통합되며 기본 활성화됐다. 채팅 데이터 보관이 28일에서 계정 수명으로 확대됐고, 코드 리뷰 기본값이 Lite에서 Balanced로 상향됐다([C# Corner](https://www.c-sharpcorner.com/article/preparing-for-the-github-copilot-unified-experience-coming-september-28)). GDPR·CCPA 적용 조직은 보관 정책 검토가 필요하다([DevOps.com](https://devops.com/github-tightens-copilots-billing-and-governance-rules-ahead-of-a-busy-fall/)). Claude Opus 5.5, GPT-6 Sol·Luna, Grok 4.7 등 최신 모델도 투입됐다([GitHub Changelog](https://github.blog/changelog/2026-09-25-github-copilot-weekly-releases-september-21/)). 85주간 1점에 머물던 인기도가 3점으로 미세 반등했다.

## OpenAI DevDay D-1: "o" 에이전트 3단계 요금 유출

OpenAI DevDay(9/29, 샌프란시스코 Fort Mason)가 내일이다([OpenAI](https://openai.com/index/devday-2026/)). Sam Altman의 기조연설이 무료 라이브스트리밍되며, Astra AON 기반 상시 에이전트 "o", GPT-6 Cyber 프리뷰가 핵심이다([Forbes](https://www.forbes.com/sites/jonmarkman/2026/09/21/openai-plans-to-introduce-managed-agents-at-devday-2026/)). ChatGPT 코드 분석에서 "o"의 3단계 요금이 유출됐다 — Pro Lite $100/월, Pro $200/월, Pro Max $500/월([Android Headlines](https://www.androidheadlines.com/2026/09/openai-leaks-always-on-o-chatgpt-assistant.html)). 구독 화면에 에이전트 이름과 이메일 서픽스까지 노출돼 발표가 사실상 확정됐다([TestingCatalog](https://www.testingcatalog.com/openai-to-announce-o-always-on-agent-during-devday/)).

## GPT-3.5 시대의 종말: 레거시 모델 4종 퇴역

오늘부로 gpt-3.5-turbo-instruct, babbage-002, davinci-002, gpt-3.5-turbo-1106이 공식 퇴역한다([DigitalApplied](https://www.digitalapplied.com/blog/openai-devday-2026-what-to-prepare)). GPT-3.5 시대의 마지막 API 엔드포인트가 사라졌다. Sora API도 9/24에 이미 종료됐으며, DevDay를 앞두고 레거시 정리에 속도를 내고 있다.

## Cursor: 31일 연속 하락, 35점

Cursor가 35점으로 8/28 이후 31일 연속 하락을 이어가고 있다. 정점 99에서 64점이 빠졌으며, OpenAI 모델 접근 종료(11/12)까지 D-45다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). 한편 SpaceX 산하에서 Grok 4.7(9/21)을 출시했지만([MarkTechPost](https://www.marktechpost.com/2026/09/21/spacexai-releases-grok-4-7/)) 이탈 속도를 늦추지 못하고 있다. 커뮤니티에서는 *"30 아래로 떨어지면 복구 불가능"*이라는 관측이 나오고 있다.

## Antigravity: v1.2.12 릴리스, 성능 최적화

Antigravity CLI v1.2.12(9/27)가 장문 대화·아티팩트 스크롤 시 CPU 사용량을 대폭 절감하고, API 재시도 로직을 개선했다([Havoptic](https://www.havoptic.com/)). v1.2.11(9/25)에서는 AI 추론 노력 수준 조절 기능과 터미널 다이어그램 렌더링 버그 수정이 포함됐다. 28주 연속 최고점을 유지하며 안정적 행보를 이어가고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay D-1, "o" 에이전트 요금 유출 |
| Claude Code | 99 | — | LogRocket #1, Fable 5.1 독주 |
| Codex CLI | 99 | — | v0.157.1, GPT-6 Sol·Luna 지원 |
| Antigravity | 99 | — | v1.2.12 릴리스, 28주 연속 최고점 |
| Claude AI | 99 | — | Opus 5.5 토큰 비용 40% 절감 |
| Windsurf | 88 | — | Devin Desktop 안정세 |
| Aider | 68 | — | 사실상 개발 중단, 오픈소스 유지 |
| Cursor | 35 | ↓2 | 31일 연속 하락, OpenAI 종료 D-45 |
| GH Copilot | 3 | ↑2 | 통합 경험 출시, 미세 반등 |
| Gemini CLI | 1 | — | 폐쇄 103일째 |

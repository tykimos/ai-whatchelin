---
title: "D-2: Sonnet 4.5 퇴역 임박 — ANT 상장 9일째, Replit은 에이전트 떼를 풀었다"
date: 2026-11-28
lang: ko
categories: [news]
tags: [anthropic, openai, copilot, gpt-6-2, devin, sonnet-4-5, opus-4-8, black-friday, claude-ship, gemini-4-neon, ant-ipo, replit-missions, arc-agi-3]
excerpt: "Sonnet 4.5 퇴역과 Opus 4.8 Fast Mode 제거까지 48시간. Anthropic ANT는 사상 최대 IPO 후 9일째 거래 중이고, Replit Missions는 에이전트 떼로 며칠짜리 빌드를 맡긴다."
---

11월 30일 Anthropic 이중 마감까지 48시간, 12월 1일 Copilot Carbon 가격 인상까지 72시간. 추수감사절 연휴와 블랙 프라이데이가 겹치며 북미 개발팀 대부분이 자리를 비운 사이, 프로덕션 감사의 실질적 마지막 기회가 빠르게 닫히고 있다. 한편 Anthropic의 Nasdaq 상장과 Replit의 멀티 에이전트 런칭이 코딩 도구 생태계의 판도를 바꾸고 있다.

## Anthropic D-2: 이틀 뒤 두 건의 Breaking Change

Sonnet 4.5(`claude-sonnet-4-5-20250929`)의 API 퇴역까지 이틀 남았다([Anthropic Docs](https://platform.claude.com/docs/about-claude/model-deprecations)). 후속 모델 Sonnet 5.5는 액면가 33% 저렴하지만, 새 토크나이저의 ~30% 토큰 증가로 실질 절감은 미미하다([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). 같은 날 Opus 4.8 Fast Mode도 제거되며 — 10월 30일 지원 중단 고지 이후 정확히 한 달 — 요청 시 에러가 반환된다([Anthropic Docs](https://code.claude.com/docs/en/fast-mode)). 추수감사절 연휴 중 마이그레이션 미완료 시스템은 월요일 아침 장애로 직결될 수 있어 주의가 필요하다.

## Anthropic ANT: 사상 최대 IPO 후 9일째

Anthropic이 11월 19일 Nasdaq에 티커 ANT로 상장했다([CNBC](https://www.cnbc.com/2026/11/19/anthropic-ipo-ant-live-updates.html)). 주당 $83에 9.8억 주를 발행해 $813억을 조달하며 SpaceX를 넘어 역대 최대 IPO를 기록했다([Fox Business](https://www.foxbusiness.com/markets/anthropic-begins-trading-nasdaq-record-breaking-ipo)). 첫날 $111.50에 개장해 $97.17에 마감, 시가총액은 약 $1.76조에 달했다([CNN](https://www.cnn.com/2026/11/19/business/live-news/anthropic-ipo)). IPO 물량의 최대 20%를 Fidelity, Robinhood 등을 통해 개인 투자자에게 배분한 점도 이례적이다([Al Jazeera](https://www.aljazeera.com/economy/2026/11/19/anthropic-starts-trading-in-the-us-after-blockbuster-ipo)). AI 모델 회사의 공개 시장 진출은 개발자 도구 투자에도 직접적 영향을 미칠 것으로 보인다.

## GPT-6.2 Astra: ARC-AGI-3 100% 달성과 자기개선 임계치

11월 17일 출시된 GPT-6.2 Astra는 OpenAI Preparedness Framework 기준 '고등(High)' 자기개선 임계치를 통과한 최초의 외부 배포 모델이다([OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol)). ARC Prize Foundation의 검증 결과, 프로바이더 어댑터 하네스 기준으로 ARC-AGI-3에서 100% 점수를 기록한 최초의 모델이 되었다([Emergent](https://emergent.sh/news/gpt-6-2-astra-scores-100-arc-agi-3-benchmark)). 다만 표준 하네스에서는 70.3%에 그치며, 같은 조건에서 Claude Fable 5.2가 81.2%로 앞선다([FourWeekMBA](https://fourweekmba.com/ai-openais-gpt-6-2-astra-is-first-to-100-on-arc-agi-3-4-1k/)). API 가격은 입력 $8, 출력 $40 per MTok으로 GPT-6 Astra 대비 20% 저렴하다([Pulse2](https://pulse2.com/openai-introduces-gpt-6-2-astra-and-sol-with-improved-performance-and-lower-task-costs/)). 로보틱스 쪽에서도 AA-Robotics v0.1 리더보드 1위(79점)를 차지했다([Crypto Briefing](https://cryptobriefing.com/gpt-6-2-astra-tops-aa-robotics-benchmark/)).

## Replit Missions: 에이전트 떼가 며칠간 빌드한다

Replit이 11월 17일 Missions를 출시했다([Replit Blog](https://replit.com/blog/introducing-replit-missions)). 목표와 예산을 설정하면 에이전트 떼가 계획·빌드·테스트·이터레이션을 수행하며, 수 시간에서 수 주까지 작업을 이어간다([The New Stack](https://thenewstack.io/replit-missions-agent-swarms/)). Replit은 NumPy 벤치마크 13개 태스크에서 에이전트 1개 4배, 16개 17배, 32개 19배 속도 향상을 보고했으나, 독립 검증은 아직 없다([Byteiota](https://byteiota.com/replit-missions-agent-swarm/)). 플래그십 데모로 모니터링 플랫폼 DataCat을 $3,000 예산, 2일 만에 구축했다고 밝혔다([Replit Blog](https://replit.com/blog/introducing-replit-missions)).

## Cognition Devin Bots: 지속적 멀티 에이전트 오케스트레이션

Cognition이 11월 17일 Devin Bots를 출시했다([Fortune](https://fortune.com/2026/11/17/exclusive-cognition-bets-on-devin-bots-coding-agents-in-challenge-to-anthropics-duet-and-openais-dots/)). Devin Bot은 며칠에서 몇 주에 걸친 프로젝트를 관리하는 상시 에이전트로, iOS 앱 업데이트 시 대응하는 Android 작업을 자동 할당하는 식의 활용이 가능하다([AI Weekly](https://aiweekly.co/alerts/cognition-launches-devin-bots-to-oversee-teams-of-devin-agents)). Fortune은 이를 Anthropic Duet과 OpenAI Dots에 대한 직접적 도전으로 평가했다.

## Claude Ship 베타: AI가 PR을 리뷰하고 직접 고친다

Anthropic이 11월 23일 Claude Ship 베타를 출시했다. 일상적인 코드 변경사항을 AI 에이전트가 리뷰·수정·승인하는 도구로, 초기 도입 기업들이 프로덕션에서 테스트 중이다. Claude Code의 기존 코드 리뷰 기능이 PR 단위 버그 탐지에 집중했다면, Ship은 반복적 변경의 전체 사이클을 자동화하는 방향으로 진화한 형태다.

## 블랙 프라이데이: 프론티어 도구 할인은 없지만, 마감 임박 프로모션 주의

추수감사절 당일이자 블랙 프라이데이 전야, 주요 AI 코딩 도구에서 신규 할인 행사는 확인되지 않았다([zPlatform](https://zplatform.ai/ai-deals/best-black-friday-ai-deals-2026/)). 다만 기존 프로모션 마감이 임박해 있다: GitHub Copilot Fusion의 30% 모델 비용 할인이 11월 30일 종료되고([GitHub Docs](https://docs.github.com/en/copilot/reference/copilot-billing/models-and-pricing)), Gemini 4 Carbon의 도입 가격($2/$10 per MTok)도 12월 1일부터 $4/$20으로 2배 인상된다([eWeek](https://www.eweek.com/news/google-gemini-4-carbon-api-pricing/)). 한편 Gemini 4 Neon이 11월 18일 Copilot에서 GA 되어, Carbon의 가격 인상 전 저비용 대안으로 주목받고 있다([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra ARC-AGI-3 100%, 출시 11일째 |
| Claude Code | 99 | — | v2.1.327, ANT 상장으로 투자 가속 전망 |
| Codex CLI | 99 | — | v0.169 사이드챗 탭, 검색 가능 태스크 |
| Antigravity | 99 | — | Google 유일 코딩 에이전트, 안정 |
| Claude AI | 99 | — | Sonnet 4.5 퇴역 D-2 + Opus 4.8 Fast Mode D-2 |
| GH Copilot | 99 | — | Carbon 가격 2배 D-3 (12/1), Neon 대안 부상 |
| Windsurf | 89 | — | Devin Bots + Replit Missions로 에이전트 시대 가속 |
| Aider | 68 | — | 유지보수 모드, 44K 스타 |
| Cursor | 1 | — | OpenAI 차단 17일째, 128일 연속 바닥 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

Anthropic 이중 마감 D-2, Copilot Carbon D-3. 에이전트 떼(Replit Missions, Devin Bots)의 등장으로 코딩 도구의 단위가 '어시스턴트'에서 '팀'으로 넘어가는 주간이다.

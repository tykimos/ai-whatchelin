---
title: "Copilot 모델 대폐기 D-2, SpaceX의 X Subscription 번들이 Cursor를 살릴 수 있을까"
date: 2026-10-17
lang: ko
categories: [news]
tags: [copilot, cursor, spacex, codex-cli, anthropic]
excerpt: "GitHub Copilot의 10월 19일 6개 모델 대폐기가 2일 앞으로 다가왔고, SpaceX는 Grok+Cursor+X Premium을 $8~$200 번들로 묶었지만 Cursor의 바닥 탈출은 아직 요원하다."
---

GitHub Copilot의 10월 19일 모델 대폐기까지 2일. 41점으로 꾸준히 올라오는 Copilot과 1점 바닥에 갇힌 Cursor의 양극화가 극에 달한 가운데, SpaceX가 내놓은 X Subscription 통합 번들이 반전의 계기가 될 수 있을지 시장이 주목하고 있다.

## Copilot: 모델 대폐기 D-2, 41점까지 상승

GitHub Copilot의 두 번째 10월 모델 퇴역 웨이브가 2일 뒤인 10월 19일에 실행된다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)). GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Gemini 3.7 Flash, Grok 4.5 등 6개 모델이 모든 Copilot 경험에서 제거되며, 대체 모델(GPT-5.6 Sol/Luna, Gemini 3.8 Flash, Grok 4.6)이 자동 전환된다. 10월 2일 1차 웨이브(Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7)에 이어 Universe(10/28-29)를 앞두고 한 세대 전체의 모델을 정리하는 대대적인 쇄신이다. 에이전틱 자동수정(Agentic autofix)도 GA로 전환되어 코드 스캐닝 알림을 자동 수정하고 드래프트 PR까지 생성한다([GitHub Blog](https://github.blog/changelog/label/copilot/)).

## Cursor: X Subscription 출시했지만 바닥은 바닥

SpaceX가 10월 13일 'The X Subscription'을 출시, Grok·Cursor·Grok Bot·X Premium을 4개 유료 티어(Plus $8/월, Premium $30/월, Super $100/월, Ultra $200/월)로 통합했다([Teslarati](https://teslarati.com/spacex-just-combined-grok-cursor-and-x-into-one-mega-plan)). SpaceX는 Premium이 기존 개별 구독 ~$90/월을 대체한다고 주장하지만, 출시 4일이 지난 지금도 Cursor는 1점에서 꿈쩍하지 않는다. 52일 연속 하락 기록이며, 11월 12일 OpenAI 모델 접근 차단까지 26일 남았다. 번들 가격 매력보다 Grok 모델 전환에 대한 개발자 반감이 더 크다는 것이 시장의 판단이다.

## Codex CLI: Composer 예측 베타, 다음 메시지를 미리 안다

Codex CLI에 Composer 예측 베타가 추가됐다([OpenAI Community](https://community.openai.com/t/codex-can-now-suggest-your-next-message-composer-predictions-beta/1404842)). Codex가 응답을 완료하면 다음 메시지를 자동 제안하고, Tab으로 즉시 수락할 수 있다. GPT-6 Astra와 GPT-6.1 Sol을 사용하며, 베타 기간 중 추가 사용량이나 크레딧 소비가 없다. 매일 개선 스프린트 14일차에 접어든 Codex는 안정성 문제(이달 6건 장애: 10/5, 10/7×3, 10/13, 10/14)([SessionWatcher](https://sessionwatcher.com/news/codex-chatgpt-desktop-work-errors-october-14-2026))에도 불구하고 기능 추가 속도를 늦추지 않고 있다.

## Anthropic: IPO 로드쇼 11월 9일 주간 유력

Anthropic의 IPO 로드쇼가 11월 9일 주간에 시작될 것으로 보인다([Implicator](https://www.implicator.ai/anthropic-could-start-ipo-roadshow-week-of-nov-9-putting-debut-before-thanksgiving/)). 10월 14일 SF 본사에서 열린 기관 투자자 데이에는 Morgan Stanley, Goldman Sachs, JPMorgan, Citi가 주관사로 참여했으며, 밸류에이션 목표는 $1.8조~$2조로 5월 시리즈 H($9,650억) 대비 약 2배 수준이다([Crypto Briefing](https://cryptobriefing.com/anthropic-targets-november-ipo-delay/)). 추수감사절 전 상장이 목표지만, 허위 살인 제보 사건의 여파가 내러티브에 그림자를 드리우고 있다.

## GitHub Universe D-11: 스케줄 확정, Anthropic·OpenAI 연사 포진

GitHub Universe 2026이 10월 28-29일 샌프란시스코 Fort Mason Center에서 개최된다([GitHub Blog](https://github.blog/news-insights/the-library/github-universe-the-big-bang/)). 테마는 "All together now, in the agentic era"이며, Anthropic·OpenAI·NVIDIA·AMD·Figma·Coinbase에서 연사가 확정됐다. Copilot에 실제 업무 위임, MCP 서버 보안, 엔터프라이즈 AI 측정 등이 주요 세션으로 포함된다. 2차 모델 퇴역(10/19)과 기본 기능 정책(10/22) 직후 열리는 만큼, 대규모 신규 발표가 예상된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-Live-1.1 안정 운영 |
| Claude Code | 99 | — | Haiku 5.5 기본 안정화 |
| Codex CLI | 99 | — | Composer 예측 베타, 이달 장애 6건 |
| Antigravity | 99 | — | v2.21.1(10/7), 무료 Claude Opus 4.6 11/2 종료 |
| Claude AI | 99 | — | IPO 로드쇼 11/9 주간 유력 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, 5월 이후 커밋 없음 |
| GH Copilot | 41 | ↑2 | 모델 대폐기 D-2, Universe D-11 |
| Cursor | 1 | — | 52일째 바닥, X Subscription 반전 실패 |
| Gemini CLI | 1 | — | 퇴역, Antigravity로 전환 완료 |

Copilot이 41점까지 상승하며 Universe(10/28-29)를 향해 모멘텀을 쌓고 있는 반면, Cursor는 X Subscription 통합 번들에도 불구하고 바닥에서 벗어나지 못하고 있다. 번들 가격 경쟁력보다 개발자 신뢰 회복이 먼저라는 냉정한 현실이 드러나는 구간이다.

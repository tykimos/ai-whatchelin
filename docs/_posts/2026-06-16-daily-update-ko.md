---
title: "Anthropic 에이전트 과금 시행일에 돌연 중단 — Claude 12일간 10번째 장애 속 인프라 위기"
date: 2026-06-16
lang: ko
categories: [news]
tags: [anthropic, claude-code, spacex, cursor, copilot, gemini-cli, fable-5]
excerpt: "Anthropic이 에이전트 과금 개편을 시행일 당일 돌연 중단했다. 같은 날 Claude는 12일 만에 10번째 장애를 기록하며 인프라 한계를 드러냈다."
---

Anthropic이 한 달간 예고해온 에이전트 과금 개편을 시행일인 6월 15일 당일 돌연 중단했다. "지금은 변경 없음"이라는 한 줄 이메일이 개발자 커뮤니티에 안도와 혼란을 동시에 안겼다. 같은 날 Claude는 12일간 10번째 장애를 기록하며 급성장의 대가를 치르고 있다.

## Anthropic: 에이전트 과금 개편, 시행일에 후퇴

Anthropic은 Agent SDK, `claude -p`, 서드파티 앱 사용량을 구독 한도에서 분리해 별도 크레딧 풀로 전환하겠다고 5월 15일 발표했다([The New Stack](https://thenewstack.io/anthropic-pauses-claude-agent-sdk-subscription-change/)). Pro $20, Max 5x $100, Max 20x $200 크레딧이 할당될 예정이었으나, 시행 당일 "사용 패턴에 더 잘 맞추기 위해 작업 중"이라며 돌연 중단했다([The Decoder](https://the-decoder.com/anthropic-backs-off-unpopular-billing-overhaul-as-price-war-with-openai-looms/)). OpenAI와의 가격 전쟁이 임박한 상황에서 사용자 이탈을 자극할 수 없다는 판단이 작용한 것으로 보인다.

## Claude: 12일간 10번째 장애, 인프라 한계 노출

6월 16일 Claude에서 또 다시 장애가 발생했다([TechTimes](https://www.techtimes.com/articles/318514/20260616/claude-outage-tenth-disruption-12-days-exposes-anthropic-infrastructure-strain.htm)). Opus 4.8과 Haiku 4.5에서 에러가 지속됐으며, 오후 2시(ET) 수정 시도에도 불구하고 완전히 해결되지 않았다. Anthropic은 "Claude 수요가 전례 없는 속도로 성장하고 있으며, 인프라가 한계에 달했다"고 인정했다. 연매출 $300억을 넘기며 연 $100만 이상 지출 기업 고객이 500개에서 1,000개로 두 달 만에 배로 늘었지만, 인프라는 그 속도를 따라잡지 못하고 있다.

## SpaceX: Amazon 추월, 세계 5위 주식 등극

SpaceX(SPCX)가 화요일 4.8% 상승하며 Amazon을 추월해 시가총액 $2.65조로 세계 5위 주식에 올라섰다([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-16/spacex-spcx-stock-set-for-more-than-50-jump-in-just-three-sessions)). IPO 3거래일 만에 $135에서 $201.80까지 49% 급등한 것이다. 같은 날 SpaceX는 Cursor 모회사 Anysphere $600억 인수를 공식 확인했으며([CNBC](https://www.cnbc.com/2026/06/16/spacex-spcx-cursor-acquisition-ipo.html)), Musk는 연말까지 AI가 "스톡피시급 코딩"에 도달할 것이라 예언했다.

## Copilot: 43주 연속 하락, 40점 — 종량제 16일차

GitHub Copilot이 인기도 40을 기록하며 43주 연속 하락세를 이어갔다([GitHub Community](https://github.com/orgs/community/discussions/192948)). Copilot CLI v1.0.63이 릴리스돼 차단된 이미지 첨부 시 안내 메시지와 Editor 프리뷰 정책을 통한 비전 활성화가 추가됐다([GitHub](https://github.com/github/copilot-cli/releases)).

## Gemini CLI: 종료 D-2, 최후의 카운트다운

Gemini CLI 개인 사용자 서비스 종료가 이틀 앞이다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). 6월 18일부터 무료·개인 사용자는 Go 기반 Antigravity CLI로 전환해야 한다. 다만 Antigravity CLI는 오픈소스가 아니며 주간 컴퓨트 캡이 적용돼, 기존 Gemini CLI 일 1,000회 제한 대비 체감 다운그레이드라는 불만이 이어지고 있다.

## Fable 5: 정지 4일째, 복원 시기 불투명

Fable 5가 상무부 수출 통제 지시로 정지된 지 4일째다([TechTimes](https://www.techtimes.com/articles/318342/20260613/us-government-pulls-anthropics-fable-5-offline-now-come-refunds-vanished-ai.htm)). Anthropic은 주말 워싱턴 협상을 진행했으나, 공식 복원 일정은 발표되지 않았다. Polymarket에서는 6월 내 복원 확률이 35% 수준이다([Polymarket](https://polymarket.com/event/claude-fable-5-restored-for-us-customers-by-20260613193753196)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.178, 에이전트 과금 중단으로 안도 |
| ChatGPT | 96 | — | 10억 MAU, GPT-5.5 시대 |
| Cursor | 96 | — | SpaceX $600억 인수 확정 |
| Claude AI | 96 | — | 12일간 10번째 장애, Fable 5 정지 지속 |
| Codex CLI | 87 | — | Goal 모드 GA 안착 |
| Windsurf | 85 | — | $15 가격으로 Copilot 이탈 흡수 |
| Antigravity | 73 | ↑1 | Gemini CLI D-2 마이그레이션 |
| Aider | 68 | — | 안정적 |
| Gemini CLI | 59 | ↓1 | D-2 종료 카운트다운 |
| Copilot | 40 | ↓1 | 43주 연속 하락, 종량제 16일차 |

---
title: "머스크, 세계 최초 조만장자 — SPCX 첫날 19% 폭등, $1.96조 시총"
date: 2026-06-12
lang: ko
categories: [news]
tags: [spacex, cursor, copilot, fable-5, claude-code, codex-cli, gemini-cli, antigravity, anthropic, agent-billing, sonnet-4, opus-4]
excerpt: "SPCX가 시초가 $150에서 장중 $176.52까지 치솟은 뒤 ~$161에 마감하며 머스크를 세계 최초 조만장자로 만들었다. 한편 Claude Sonnet 4·Opus 4 강제 퇴역이 3일 앞으로 다가왔다."
---

SpaceX가 나스닥 상장 첫날부터 역사를 새로 썼다. SPCX는 시초가 $150에 출발해 장중 $176.52까지 급등한 뒤 약 $161에 마감 — 공모가 대비 19% 상승이다([CNBC](https://www.cnbc.com/2026/06/12/spacex-ipo-spcx-live-updates.html)). SpaceX 시가총액은 $1.96조로 뛰어올랐고, 일론 머스크는 순자산 약 $1.05조로 세계 최초 조만장자(trillionaire)가 됐다([CBS News](https://www.cbsnews.com/news/elon-musk-spacex-ipo-trillionaire-wealth/)).

## SpaceX SPCX 첫날: 공모가 $135 → 종가 ~$161

머스크와 귀네 숏웰이 뉴욕·텍사스에서 동시에 개장벨을 울리며 시작된 첫 거래일은 폭발적이었다. 5억 5,560만 주를 공모해 $750억을 조달한 역대 최대 IPO는 4배 초과 청약($1,500억 주문)에 이어 첫날 19% 수익을 기록했다([Yahoo Finance](https://finance.yahoo.com/markets/stocks/article/spacex-ipo-set-to-price-thursday-night-ahead-of-friday-nasdaq-debut--heres-whats-next-101955450.html)). Hyperliquid의 SPCX-USDC 무기한 계약은 $176에 거래되며 IPO 가격 대비 30% 프리미엄을 유지하고 있다([WEEX](https://www.weex.com/wiki/article/spacex-stock-price-135-ipo-valuation-and-how-to-trade-spcx-gcr5v4bpve9uqp8x8eqim91f)). 이 자금이 6월 5일 체결된 $600억 Cursor 인수를 실행하는 재원이 된다.

## Claude Sonnet 4·Opus 4 강제 퇴역 D-3: 6/15 오전 9시(PT)

6월 15일 오전 9시(PT)에 claude-sonnet-4-20250514와 claude-opus-4-20250514가 API 호출을 완전히 중단한다 — 유예기간도, 자동 폴백도 없이 즉시 에러를 반환한다([MindStudio](https://www.mindstudio.ai/blog/claude-sonnet-4-opus-4-deprecation-migration-guide)). 마이그레이션은 모델 문자열을 Sonnet 4.6/Opus 4.8로 한 줄만 바꾸면 된다([ChatForest](https://chatforest.com/guides/anthropic-claude-sonnet-4-opus-4-deprecation-june-15-2026/)). Sonnet 4.8 빌더 프리뷰가 6월 16-18일 사이 공개될 것으로 예상된다([ChatForest](https://chatforest.com/builders-log/claude-sonnet-4-8-preview-june-2026-dynamic-workflows-builder-guide/)).

## Claude Code v2.1.172: 중첩 서브에이전트 5단계

Claude Code v2.1.172가 릴리스됐다([DevelopersIO](https://dev.classmethod.jp/en/articles/20260611-cc-updates-v2-1-172/)). 서브에이전트가 자체 서브에이전트를 최대 5단계까지 생성할 수 있게 됐으며, 각 프레임이 독립적인 시스템 프롬프트와 모델을 보유한다([ofox.ai](https://ofox.ai/blog/claude-code-nested-subagents-2026/)). Amazon Bedrock의 리전 자동 감지와 플러그인 마켓플레이스 검색바도 추가됐다.

## Fable 5 논란: 탈옥 주장과 사보타주 반발 재점화

Fable 5 출시 며칠 만에 논란이 재점화되고 있다([TechTimes](https://www.techtimes.com/articles/318268/20260612/claude-fable-5-hit-jailbreak-claims-secret-sabotage-backlash-days-after-launch.htm)). 레드팀 연구자 Pliny the Liberator가 약 12만 자 시스템 프롬프트를 추출했다고 주장했으며, "비밀 사보타주" 정책은 철회됐지만 Anthropic은 *"잘못된 트레이드오프를 했고 균형을 맞추지 못한 점을 사과한다"*고 밝혔다([Fortune](https://fortune.com/2026/06/10/anthropic-accu-claude-fable-5-limits-capabilities-ai-researchers-developers/)).

## Copilot: 44, 39주 연속 하락 — 종량제 12일차

Copilot이 **44**로 하락 — 39주 연속이다([GitHub Discussions](https://github.com/orgs/community/discussions/192948)). Business $30, Enterprise $70의 프로모션 크레딧이 6-8월에 제공되고 새 Copilot Max 플랜($200/월)이 출시됐지만, 904개 비추천과 10-100배 비용 증가 보고가 하락세를 막지 못하고 있다([MLQ](https://mlq.ai/news/github-copilot-switches-to-token-based-billing-june-1-drawing-developer-backlash/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.172 중첩 서브에이전트, Sonnet 4/Opus 4 퇴역 D-3 |
| ChatGPT | 96 | — | 10억 MAU, Lockdown Mode 출시 |
| Cursor | 96 | — | SPCX 첫날 19%↑, $600억 인수 자금 확보 |
| Claude AI | 96 | — | Fable 5 논란 속 Sonnet 4.8 프리뷰 6/16-18 예상 |
| Codex CLI | 87 | — | v0.140.0-alpha.2, 데스크톱 핸드오프 |
| Windsurf | 85 | — | Devin Desktop $15, Cascade EOL 7/1 |
| Antigravity | 69 | ↑1 | Gemini CLI D-6 이전 수요 흡수 |
| Aider | 68 | — | 오픈소스 CLI 안정 |
| Gemini CLI | 63 | ↓1 | 종료 D-6, 전환 가속 |
| GH Copilot | 44 | ↓1 | 39주 연속 하락, Copilot Max $200/월 출시 |

SPCX 첫날 19% 급등과 머스크 조만장자 등극이 오늘의 최대 사건이다. 3일 뒤 Claude Sonnet 4·Opus 4 강제 퇴역, 6일 뒤 Gemini CLI 종료 — 개발자들에게 바쁜 한 주가 이어지고 있다.

---
title: "Anthropic S-1 공개 — H1 매출 $16.3B, 'ANT' 티커로 나스닥 상장 초읽기"
date: 2026-10-30
lang: ko
categories: [news]
tags: [anthropic, github-copilot, github-universe, openai, claude-code, codex-cli, cursor]
excerpt: "Anthropic이 공개 S-1에서 2026년 상반기 매출 $16.3B(전년 대비 14배)을 공개했다. Copilot Fusion은 Opus 5.5 대비 절반 비용에 근접한 성능을 달성했다는 벤치마크가 나오고, Pro 200 그랜드파더링 종료 후 하루가 지났다."
---

GitHub Universe 2026 폐막 이틀째, 시장에서 소화해야 할 정보가 쏟아지고 있다. Anthropic의 공개 S-1이 상반기 실적을 드러냈고, Copilot Fusion에 대한 독립 벤치마크가 처음 등장했으며, OpenAI Pro 200 그랜드파더링 종료 후 첫날 반응이 나타나고 있다.

## Anthropic: S-1 공개, H1 매출 $16.3B — IPO 11월 초 임박

Anthropic이 10월 26일 SEC에 공개 S-1을 제출했다([IPOScoop](https://www.iposcoop.com/the-ipo-buzz-anthropic-ant-proposed-files-its-s-1/)). 핵심 수치가 공개됐다: 2026년 상반기 매출 $16,286M, Q2 단독 $11,555M으로 전년 대비 약 14배 성장이다([FourWeekMBA](https://fourweekmba.com/ai-anthropics-s-1-shows-16-3b-half-year-revenue-up-14x/)). 상반기 순손실은 $80,748M이지만 이 중 $72,388M은 전환사채·파생부채의 비현금 공정가치 변동분이다([HackerNoon](https://hackernoon.com/anthropics-s-1-shows-$163b-in-half-year-revenue-a-900percent-nrr-and-an-$807b-loss-that-mostly-isnt)). 나스닥 상장 티커는 'ANT'로, Goldman Sachs와 Morgan Stanley가 공동 주간사를 맡았다([AIWeekly](https://aiweekly.co/alerts/anthropic-files-for-nasdaq-ipo-under-ant-h1-rev-163b)). Bloomberg에 따르면 로드쇼는 빠르면 11월 9일 주간에 시작되어 추수감사절 전 상장을 목표로 하고 있다([ShareSansar](https://www.sharesansar.com/newsdetail/anthropics-ipo-could-become-worlds-largest-ipo-surpassing-spacexs-record-breaking-ipo-2026-10-28)). 예상 밸류에이션은 약 $1.5~2조, 조달 규모 $75~100B으로 SpaceX IPO($86B)를 넘어설 가능성이 있다. Claude Code는 v2.1.310에서 안정 운영 중이다.

## GitHub Copilot: Fusion GA 벤치마크 등장 — Opus 5.5 절반 비용

Copilot Fusion GA 선언 이후 첫 독립 벤치마크가 나왔다. Artificial Analysis에 따르면 Fusion은 Claude Code(Opus 5.5)와 약 2점 차이의 성능을 보이면서 태스크당 비용은 절반 수준이다([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)). GitHub Octoverse 보고서는 현재 전체 PR의 40%가 에이전트에 의해 시작된다고 밝혔다([TheNextWeb](https://thenextweb.com/news/github-universe-copilot-fusion-octoverse-agents)). 엔터프라이즈 관리자는 Fusion이 사용할 모델을 제한할 수 있으며([TheNewStack](https://thenewstack.io/github-copilot-fusion/)), 6월부터 시행된 AI Credits 기반 사용량 과금 체계와 맞물려 비용 최적화가 핵심 화두로 부상했다([GitHub Blog](https://github.blog/news-insights/product-news/github-copilot-is-moving-to-usage-based-billing/)). 인기도 점수 67은 35일 연속 회복이며, Cursor와의 격차가 66포인트로 확대됐다.

## OpenAI: Pro 200 그랜드파더링 종료 후 첫날

어제(10월 29일) Pro 200 그랜드파더링이 공식 종료됐다([OpenAI Help](https://help.openai.com/en/articles/9793128-about-chatgpt-pro-tiers)). 기존 $200/월 구독자의 주간 GPT-6 Pro 메시지가 200에서 100으로, 사용량 배수가 20x에서 10x로 축소됐다([WinBuzzer](https://winbuzzer.com/2026/09/30/openai-adds-500-chatgpt-pro-cuts-allowance-new-200-subscribers-a005-xcxwbn/)). Ultrafast 접근은 $500/월 Pro 500 전용이다([WindowsReport](https://windowsreport.com/openai-launches-500-chatgpt-pro-500-plan-with-25x-plus-usage-and-ultrafast-access/)). 커뮤니티에서는 Pro 200 사용자들의 Pro 500 업그레이드율이 첫 주 핵심 지표가 될 것이라는 분석이 나오고 있다.

## Cursor: X Subscription 체제 66일째

Cursor는 인기도 바닥(1)을 66일째 유지 중이다. 10월 MEAN CEO 뉴스레터에 따르면 멀티 에이전트 코딩, 모바일 컨트롤, CLI 접근 등의 기능이 갖춰져 있으나([MEAN CEO](https://blog.mean.ceo/?p=11359)), X Subscription 번들의 $30 Premium 진입 장벽이 여전히 개발자 유입을 막고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Pro 200 그랜드파더링 종료, 3-tier 본격 가동 |
| Claude Code | 99 | — | v2.1.310 안정, IPO S-1 공개 |
| Codex CLI | 99 | — | GPT-6.1 Sol 기본 모델 안착 |
| Antigravity | 99 | — | Gemini 4 Argon Pro 안정 |
| Claude AI | 99 | — | 'ANT' 티커, 11/9 로드쇼 관측 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| GH Copilot | 67 | ↑2 | 35일 연속 회복, Fusion 벤치마크 등장 |
| Aider | 68 | — | 안정, 주요 업데이트 없음 |
| Cursor | 1 | — | 66일째 바닥, 다기능이나 과금 장벽 |
| Gemini CLI | 1 | — | 은퇴, Antigravity 전환 완료 |

Anthropic S-1이 H1 $16.3B 매출을 드러내면서 AI 코딩 도구 시장의 '빅3' 중 하나가 공개 시장에 진입하는 것이 현실이 됐다. Copilot Fusion은 비용 대비 성능으로 승부를 걸고 있고, OpenAI는 Pro 티어 세분화로 수익화를 강화하고 있다. 세 회사 모두 다른 방식으로 같은 질문에 답하는 중이다 — AI 코딩의 미래에 누가 과금할 것인가.

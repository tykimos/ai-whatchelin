---
title: "Claude Mythos, 1,000개 오픈소스서 2만 3천 취약점 발견 — GitHub 또 장애, Uber는 AI 예산 바닥"
date: 2026-05-26
lang: ko
categories: [news]
tags: [claude-mythos, copilot, gemini-cli, antigravity, anthropic, vibe-coding, openai, github]
excerpt: "Claude Mythos가 Project Glasswing으로 오픈소스 보안의 판을 바꾸고, Apple macOS 커널 취약점까지 찾아냈다. GitHub은 올해 13번째 장애를 겪었고, Uber COO는 AI 투자 ROI에 의문을 던졌다."
---

AI 보안의 새로운 시대가 열렸다. Anthropic의 Claude Mythos가 1,000개 이상의 오픈소스 프로젝트를 스캔해 23,019개 취약점을 찾아냈고, Apple macOS 커널의 루트 권한 상승 버그까지 발견했다. 한편 GitHub은 올해 13번째 대형 장애를 기록했고, Uber는 AI 예산을 4월에 전부 소진했다고 고백했다.

## Claude Mythos: Project Glasswing이 오픈소스 보안의 판을 바꾸다

Claude Mythos의 Project Glasswing 결과가 오늘 공개됐다. 1,000개 이상의 오픈소스 프로젝트에서 총 23,019개 이슈를 발견했으며, 6,202개가 고위험/치명적으로 분류됐다([Help Net Security](https://www.helpnetsecurity.com/2026/05/26/anthropic-project-glasswing-update/)). 독립 보안 기업들이 90% 이상을 진양성으로 검증했다. AWS, Apple, Microsoft, Google, NVIDIA가 파트너로 참여했다.

더 놀라운 건 실전 성과다. 보안 연구자들이 Claude Mythos Preview로 Apple macOS 커널의 정수 오버플로(CVE-2026-28952)를 발견했다 — M5 아키텍처에서 루트 권한 상승이 가능한 취약점이다([Tom's Hardware](https://www.tomshardware.com/tech-industry/cyber-security/apple-m5-architecture-suffers-first-privilege-escalation-exploit-anthropics-claude-mythos-helps-researchers-bypass-memory-integrity-enforcement)). AI 에이전트가 발견한 최초의 주요 CVE로, Apple이 macOS Tahoe 26.5에서 즉시 패치했다([Apple](https://support.apple.com/en-us/127115)). Mythos 토글(`claude-mythos-1-preview`)이 5월 25일 Claude Code UI에 잠시 나타났다가 사라졌으며, Anthropic은 "더 강력한 세이프가드 개발 후 Mythos급 모델을 일반 출시할 것"이라고 밝혔다([WinBuzzer](https://winbuzzer.com/2026/05/26/anthropics-mythos-moves-closer-to-claude-code-xcxwbn/)).

## GitHub: 올해 13번째 대형 장애, Copilot D-5

UTC 10:57경 인증 장애가 발생해 GitHub Actions와 Pages가 전 세계적으로 2시간 이상 중단됐다([Cyber Security News](https://cybersecuritynews.com/github-down-authentication-issues/)). 13:18 UTC에 복구됐지만, Hacker News에서 644포인트를 기록하며 개발자 불만이 폭발했다. CNBC가 보도한 "3월 이후 12회 이상 장애"에 하나가 더 추가됐다([CNBC](https://www.cnbc.com/2026/05/22/microsoft-was-positioned-to-win-in-ai-coding-outages-got-in-the-way.html)). Copilot 인기도는 61점으로 22주 연속 하락 중이며, 6월 1일 사용량 기반 과금 전환까지 5일 남았다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)).

## ING: 바이브코딩이 은행 트레이딩 플로어에 진입

ING가 AI '바이브코딩'으로 외환·신용 전자 거래 도구를 구축하고 있다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-26/ing-s-vibe-coding-ai-is-building-its-new-trading-systems)). 실시간 가격·입금 거래·성과 지표를 보여주는 분석 대시보드를 시간 단위로 완성했다. AI 통화 가격 모델은 대형 거래 건수를 50% 늘렸다([Yahoo Finance](https://finance.yahoo.com/markets/crypto/articles/ing-built-trading-system-hours-153057815.html)). ING는 은행업계 전체가 1년 내 채택할 것으로 전망했다.

## Uber: AI 예산을 4월에 다 쓴 뒤 ROI를 찾지 못했다

Uber COO가 2026년 AI 예산 전체를 4월까지 소진했으며, Claude Code 토큰 소비가 더 유용한 기능 출시와 연관된다는 증거를 찾지 못했다고 밝혔다([MLQ](https://mlq.ai/news/uber-burned-through-its-entire-2026-ai-budget-by-april-coo-questions-roi/)). *"그 연결고리는 아직 없다"*는 발언은 AI 도구 도입의 ROI 문제를 정면으로 제기한다.

## HN 1위: "AI로 더 느리게 더 나은 코드"

Nolan Lawson의 "Using AI to write better code more slowly"가 Hacker News 1위를 차지했다(1,114포인트). AI를 속도가 아닌 코드 품질 향상에 사용하자는 주장이다. Google I/O에서 피차이가 밝힌 "구글 코드 75%가 AI 생성"과 맥을 같이하면서도, 방향성은 반대다 — 커뮤니티가 '더 빠르게'에서 '더 좋게'로 성숙하고 있다.

## Anthropic: $300억 라운드 마감 + 10월 IPO

Anthropic의 $300억+ 라운드가 이번 주 마감 전망이다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-22/anthropic-to-close-over-30-billion-round-as-soon-as-next-week)). $9,000억+ 밸류에이션으로 세계 최고 가치 비상장 AI 기업이 된다. 10월 IPO에서 $600억+ 조달을 목표로 Wilson Sonsini가 상장 준비를 맡았다([City AM](https://www.cityam.com/anthropic-targets-october-for-mega-ipo/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | 안정 |
| Claude Code | 98 | — | Mythos 공개 임박 + $300억 라운드 |
| Cursor | 96 | — | Composer 2.5 안정화 |
| Claude AI | 94 | — | 사상 첫 흑자 분기 예상 |
| Codex CLI | 88 | — | Goal 모드 정식 출시 |
| Gemini CLI | 81 | ↓1 | 종료 D-23 |
| Windsurf | 81 | — | 안정 기조 |
| Aider | 68 | — | 기준선 유지 |
| Copilot | 61 | ↓1 | 22주 하락 + 오늘 또 장애, D-5 |
| Antigravity | 55 | ↑1 | v2.0.0 패치 회복세 |

Mythos의 보안 분야 실증 결과가 인상적이다. Uber의 ROI 의문과 HN의 "더 느리게" 담론은 AI 코딩 도구 시장이 '도입'에서 '가치 증명' 단계로 넘어가고 있음을 보여준다.

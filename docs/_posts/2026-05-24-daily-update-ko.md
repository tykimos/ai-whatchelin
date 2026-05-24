---
title: "Google, Antigravity 대참사에 긴급 패치 — 'Open IDE' 버튼과 쿼터 전면 초기화"
date: 2026-05-24
lang: ko
categories: [news]
tags: [antigravity, copilot, anthropic, openai, gemini-cli]
excerpt: "5일간의 개발자 반발 끝에 Google이 Antigravity 2.0 v2.0.0 정식 패치를 배포했다. 'Open IDE' 버튼 복구, 원클릭 마이그레이션, 전 사용자 Gemini 쿼터 초기화까지 — 그러나 신뢰 회복은 다른 문제다."
---

5일간 계속된 Antigravity 2.0 자동 업데이트 대참사가 전환점을 맞았다. Google이 v2.0.0 정식 빌드를 배포하며 긴급 수습에 나섰다. 하지만 Copilot은 사용량 기반 과금 D-8을 앞두고 20주 연속 하락을 기록하고 있고, Anthropic과 OpenAI는 각각 사상 최대 규모의 자금 조달과 IPO를 향해 질주하고 있다.

## Antigravity: Google, "혼란스러운 한 주"에 대해 사과하다

Google이 Antigravity 2.0 v2.0.0 정식 패치를 배포했다([Piunikaweb](https://piunikaweb.com/2026/05/23/google-antigravity-2-0-ide-update-gemini-quota-reset/)). 핵심 변경사항은 세 가지다: 프로젝트 대화 화면 우상단에 잘 보이는 "Open IDE" 버튼이 추가됐고, 기존 설치에서 설정·확장·키바인딩을 복원하는 원클릭 마이그레이션 도구가 들어갔으며, 전 사용자의 Gemini 주간 사용량 쿼터가 완전 초기화됐다. Google은 "팀이 더 잘했어야 했다"며 사과했다([Piunikaweb](https://piunikaweb.com/2026/05/23/google-antigravity-2-0-ide-update-gemini-quota-reset/)).

다만 인기도는 53에서 크게 반등하지 못했다. I/O 전 48에서 62까지 치솟았던 기세가 자동 업데이트 참사 이후 완전히 꺾인 상태여서, 기능 복구만으로는 깨진 신뢰를 되돌리기 어려운 상황이다.

## GitHub Copilot: 20주 연속 하락, 사용량 과금 D-8

Copilot이 63으로 밀리며 20주 연속 하락 기록을 갱신했다. 6월 1일 사용량 기반 과금 전환까지 8일 남았다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). AI 크레딧 체계에서 1 크레딧 = $0.01로, 모델별 토큰 소비량에 따라 과금된다. 코드 완성과 Next Edit Suggestions는 무제한으로 유지되지만, Chat·CLI·클라우드 에이전트·Spaces·Spark 등 나머지 기능은 모두 크레딧을 소비한다. 커뮤니티의 "덜 받고 같은 값"이라는 불만이 지속되고 있다([Visual Studio Magazine](https://visualstudiomagazine.com/articles/2026/04/27/devs-sound-off-on-usage-based-copilot-pricing-change-you-will-get-less-but-pay-the-same-price.aspx)).

## Anthropic $30B+ 라운드, 다음 주 마감 전망

Anthropic의 사상 최대 펀딩 라운드가 5월 26일 주에 마감될 전망이다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-22/anthropic-to-close-over-30-billion-round-as-soon-as-next-week)). 프리머니 밸류에이션 $900B 이상으로 OpenAI의 $852B을 넘어 세계에서 가장 비싼 비상장 AI 스타트업이 된다. Sequoia, Dragoneer, Altimeter, Greenoaks가 각각 약 $20억씩 공동 리드한다. Q2 매출 $109억 전망과 첫 흑자 분기가 가시화된 시점에서의 자금 조달이다.

## OpenAI, IPO 비밀 신청서 준비 — 9월 상장 목표

OpenAI가 IPO 비밀 신청서를 제출할 준비를 하고 있으며, Goldman Sachs와 Morgan Stanley가 주관사로 참여 중이다([CNBC](https://www.cnbc.com/2026/05/20/openai-ipo-filing.html)). $1조 밸류에이션에 $600억 이상 조달을 목표로 하며, Musk v. Altman 배심원 만장일치 기각 판결이 법적 장벽을 제거했다. SpaceX도 같은 주에 IPO 신청서를 제출해, 사상 최대 상장 타이틀을 놓고 직접 경쟁하게 됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | IPO 모멘텀 지속 |
| Claude Code | 98 | — | $30B 라운드 마감 임박 |
| Cursor | 96 | — | 3.5 Automations 안착 |
| Claude AI | 94 | — | 첫 흑자 분기 전망 |
| Codex CLI | 88 | ↑1 | Goal 모드 정식 전환 후 6주 연속 상승 |
| Gemini CLI | 83 | ↓1 | Antigravity CLI 전환 6/18 불안감 |
| Windsurf | 81 | — | Devin 통합 안정화 |
| Aider | 68 | — | 오픈소스 커뮤니티 안정 |
| Copilot | 63 | ↓1 | 20주 연속 하락, 사용량 과금 D-8 |
| Antigravity | 53 | ↑1 | 긴급 패치로 출혈 멈춤, 신뢰 미회복 |

Antigravity가 패치 이후 소폭 반등했지만, 52→53은 상징적 의미에 불과하다. 진짜 반등은 6월 18일 Antigravity CLI 전환 후 안정성이 증명돼야 시작될 것이다.

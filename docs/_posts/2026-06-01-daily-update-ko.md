---
title: "Anthropic S-1 IPO 신청 — Copilot 종량제 반란 속 AI 역사가 쓰이다"
date: 2026-06-01
lang: ko
categories: [news]
tags: [anthropic, github-copilot, nvidia, grok-build, microsoft-build, gemini-cli]
excerpt: "Anthropic이 메이저 AI 랩 최초로 IPO를 신청했고, Copilot 종량제 첫날 904 비추천이 쏟아지고, Jensen Huang은 Computex에서 차세대 칩 6종을 공개했다."
---

오늘은 AI 산업의 세 축이 동시에 움직인 날이다. Anthropic이 SEC에 S-1 IPO 신청서를 제출하며 AI 역사를 썼고, GitHub Copilot 종량제 첫날 개발자 반란이 폭발했으며, Jensen Huang이 Computex에서 차세대 칩을 공개했다.

## Anthropic: 메이저 AI 랩 최초 IPO 신청

Anthropic이 6월 1일 SEC에 S-1 등록 신청서를 비밀리에 제출했다([NPR](https://www.npr.org/2026/06/01/nx-s1-5843199/anthropic-ipo-filing-ai-large)). $9,650억 밸류에이션에 연간 매출 런레이트 $470억으로, 빠르면 10월 상장을 목표로 한다([NBC News](https://www.nbcnews.com/business/corporations/anthropic-files-ipo-openai-rcna347897)). OpenAI(9월 IPO 목표)보다 먼저 신청서를 제출한 것으로, 두 조 단위 AI 기업이 수개월 간격으로 상장하는 전례 없는 레이스가 시작됐다([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/anthropic-files-confidential-1-joins-161008569.html)).

## GitHub Copilot: 정액제의 종말, 그리고 분노

GitHub 공식 커뮤니티 토론 스레드에 비추천 904개, 추천 22개, 댓글 435개 이상이 달렸다([GitHub Community](https://github.com/orgs/community/discussions/192948)). Pro($10/월)에는 AI 크레딧 $10, Pro+($39/월)에는 $39가 포함되며 코드 완성은 무료지만 에이전틱·채팅 기능은 크레딧을 소모한다([GitHub Docs](https://docs.github.com/en/copilot/reference/copilot-billing/models-and-pricing)). 한 개발자는 2시간 만에 월 크레딧 8%를 소진했다고 보고했고, Reddit에서는 헤비 유저의 월 비용이 $29에서 $750까지 치솟을 수 있다는 계산도 등장했다([Dataconomy](https://dataconomy.com/2026/06/01/github-copilot-token-pricing-backlash/)). GitHub CEO Thomas Dohmke는 "Claude Sonnet 4.5, o3-pro 같은 고비용 모델 접근으로 정액제가 지속 불가능해졌다"고 밝혔다.

Copilot의 인기도 점수는 28주 연속 하락해 55를 기록했다 — 추적 시작 이래 최저치다. 2026년 초 80대에서 시작한 하락세가 멈출 기미가 보이지 않는다.

## xAI: Grok Build 0.1 API로 가격 전쟁 선포

같은 날 xAI가 Grok Build 0.1 API를 퍼블릭 베타로 출시했다([xAI](https://x.ai/news/grok-build-0-1)). 입력 $1/M, 출력 $2/M — Anthropic($5/$25)의 5분의 1, OpenAI의 10분의 1 수준이다. 256K 컨텍스트 윈도와 100+ 토큰/초의 속도, Agent Client Protocol(ACP) 완전 지원으로 오케스트레이션 플랫폼과의 통합이 가능하다. SuperGrok이나 X Premium+ 없이도 API만으로 접근할 수 있게 되면서, 코딩 에이전트 시장이 본격적인 4파전(Anthropic·OpenAI·Google·xAI)에 돌입했다.

## Microsoft Build 2026: Project Polaris와 OpenAI 탈출

내일(6월 2일) 샌프란시스코 포트메이슨 센터에서 Build 2026이 개막한다. 핵심은 이미 유출된 'Project Polaris' — GitHub Copilot을 위한 Microsoft 자체 MoE 코딩 모델이다([ChatForest](https://chatforest.com/builders-log/microsoft-build-2026-recap-windows-agent-platform-project-polaris-copilot-workspace/)). HumanEval과 MBPP에서 GPT-4 Turbo를 능가한다고 알려졌으며, 8월 GA가 목표다. Microsoft가 핵심 개발자 도구에서 OpenAI 의존도를 줄이겠다는 가장 선명한 신호다.

Build 전야제로 NVIDIA가 RTX Spark 슈퍼칩을 공개했다([NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-microsoft-windows-pcs-agents-rtx-spark)). ARM CPU + Blackwell GPU + 최대 128GB 통합 메모리를 결합한 AI 노트북 플랫폼으로, Microsoft Surface Laptop Ultra가 첫 탑재 기기다.

## NVIDIA Computex 2026: 차세대 칩 6종 공개

Jensen Huang이 Computex 타이페이 키노트에서 6종의 신규 칩을 발표했다([FourWeekMBA](https://fourweekmba.com/nvidia-computex-2026-five-layer-strategy/)). 핵심은 Vera Rubin — 3,360억 트랜지스터, NVL72 랙당 50 페타플롭스 FP4, Blackwell 대비 추론 5배·토큰당 비용 10분의 1로, 2026년 하반기 출하한다. Nemotron 3 Ultra(5,000억 파라미터 에이전틱 워크플로우용 오픈 모델)와 DSX OS(오픈소스 AI 팩토리 프레임워크)도 공개했다([Yahoo Finance](https://finance.yahoo.com/sectors/technology/live/tech-stocks-today-nvidia-ceo-calls-ai-a-profit-generator-at-computex-taipei-unveils-new-laptop-processor-100000230.html)).

## Gemini CLI: 종료까지 17일

Gemini CLI가 비엔터프라이즈 사용자 대상으로 6월 18일 서비스를 종료한다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). 스크립트·CI 파이프라인·크론 작업 모두 중단된다. Antigravity CLI로 마이그레이션이 필수이며, Code Assist Standard/Enterprise 라이선스 보유 기관만 예외다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 모멘텀 지속, 안정적 1위 |
| ChatGPT | 96 | — | GPT-5.6 루머에도 불구 안정 |
| Cursor | 96 | — | 사용량 과금 전환 첫날 |
| Claude AI | 95 | — | 엔터프라이즈 확대 지속 |
| Codex CLI | 87 | — | Pro 부스트 만료 후 안정화 |
| Windsurf | 81 | — | Wave 13 멀티에이전트 효과 |
| Gemini CLI | 74 | ↓1 | 종료 D-17 카운트다운 |
| Antigravity | 61 | ↑1 | 롤백 위기 후 회복 7주차 |
| Aider | 68 | — | 오픈소스 안정세 |
| GH Copilot | 55 | ↓1 | 28주 연속 하락, 사용량 과금 반발 |

Copilot의 하락세가 멈추려면 Build 2026에서 강력한 반전 카드가 나와야 한다. 하지만 사용량 과금 첫날의 반발 강도를 보면, 가격 정책 그 자체가 회복의 발목을 잡을 가능성이 높다.

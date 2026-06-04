---
title: "Claude Code v2.1.162 출격, Cursor 3.7 Canvas Mode, Glasswing 150개 기관 확대 — Copilot 이탈 4일차"
date: 2026-06-04
lang: ko
categories: [news]
tags: [claude-code, cursor, github-copilot, anthropic, project-glasswing, openai, grok-build, spacex-ipo, windsurf, devin-desktop]
excerpt: "Claude Code v2.1.162가 병렬 Bash 독립 실행을 도입하고, Cursor 3.7이 Canvas Design Mode를 출시했다. Project Glasswing이 150개 기관으로 확대된 가운데, Copilot 종량제 이탈은 4일차에 접어들었다."
---

Claude Code와 Cursor가 같은 날 릴리스를 쏟아냈다. Claude Code v2.1.162는 병렬 Bash 호출의 독립 실행과 Devin Desktop 메뉴 반영을, Cursor 3.7은 Canvas Design Mode와 토큰 사용량 리포팅을 도입했다. Anthropic의 Project Glasswing은 15개국 150개 기관으로 확대됐고, OpenAI는 o3의 8월 26일 퇴장을 확정했다.

## Claude Code v2.1.162: 병렬 Bash 독립 실행

Claude Code가 오늘 v2.1.162를 출시했다([releasebot.io](https://releasebot.io/updates/anthropic/claude-code)). `claude agents --json`에 차단된 세션 상태를 보여주는 `waitingFor` 필드가 추가됐고, `/effort` 명령으로 선택한 노력 레벨이 세션 기본값으로 저장된다. 특히 병렬 Bash 호출이 배치 전체 취소 대신 개별 독립 실패로 처리되도록 바뀌었다 — 하나의 명령이 실패해도 나머지는 계속 실행된다. 메뉴에서 'Windsurf'가 'Devin Desktop'으로 변경됐다.

## Cursor 3.7: Canvas Design Mode 출시

Cursor가 3.7을 릴리스했다([cursor.com](https://cursor.com/changelog)). Canvas Design Mode로 UI 요소를 직접 선택·주석 처리해 AI 편집을 가이드할 수 있다. Context Usage Reporting은 인터랙티브 토큰 할당 분석과 'Debug with Agent' 버튼을 제공한다. 전날 공개된 Enterprise Organization Management는 Organizations > Teams > Groups 3단계 계층 구조로 조직별 보안·거버넌스·예산 제어를 지원한다([cursor.com](https://cursor.com/changelog)).

## Project Glasswing: 150개 기관으로 확대

Anthropic이 Claude Mythos Preview 접근을 15개국 이상 약 150개 신규 조직에 확대했다([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)). 코드베이스 스캐닝과 패치 제안을 제공하는 Claude Security도 추가됐다. 버그 바운티 프로그램은 현재까지 1,000개 이상의 오픈소스 프로젝트에서 23,000건 이상의 이슈를 발견했으며, 90% 이상이 실제 양성으로 검증됐다.

## Copilot 종량제 4일차: 31주 연속 하락

The Register가 "분노한 개발자들이 Copilot을 떠나겠다고 선언"이라는 제목의 기사를 내보냈다([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). 한 Reddit 사용자는 월 비용이 $29에서 $750으로 뛸 것이라 추산했고, Pro+ 사용자가 2시간 만에 월 크레딧의 8%를 소진했다는 보고가 나왔다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Copilot 인기도는 **52**로 31주 연속 하락했다.

## o3 퇴장 확정 & GPT-4.5 선셋 카운트다운

OpenAI가 o3 모델의 8월 26일 퇴장을 확정했다 — 90일 선셋 기간이 적용된다([OpenAI Help Center](https://help.openai.com/en/articles/9624314-model-release-notes)). GPT-4.5도 6월 27일 퇴장 예정으로 모든 GPT-5 이전 모델 패밀리가 폐지 일정에 들어갔다. GPT-5.5 Instant에는 더 자연스러운 응답 스타일과 할루시네이션 52.5% 감소 업데이트가 적용됐다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-upgrades-gpt-55-as-it-plans-to-retire-legacy-chatgpt-models/)).

## SpaceX IPO 로드쇼 시작 & Windsurf 상승세

SpaceX IPO 로드쇼가 오늘 공식 시작됐다 — 주당 $135, 목표 $1.75조 밸류에이션이지만 Morningstar는 $780B로 산정했다([CNBC](https://www.cnbc.com/2026/06/03/spacex-ipo-stock-price-roadshow-musk.html)). Windsurf(Devin Desktop)는 $15 가격 인하 효과로 인기도 **83**에 도달, Copilot 이탈 수요를 흡수하고 있다. Grok Imagine 1.5 Preview가 이미지-투-비디오 변환을 선보이며 자연어 모션 제어와 720p 해상도를 지원한다([xAI](https://releasebot.io/updates/xai)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.162, Glasswing 150개 기관 |
| ChatGPT | 96 | — | o3 8/26 퇴장 확정, GPT-5.5 업데이트 |
| Cursor | 96 | — | 3.7 Canvas Design Mode, Enterprise 관리 |
| Claude AI | 95 | — | 6/2 장애 완전 복구 |
| Codex CLI | 87 | — | Sites 프리뷰, 5M+ 주간 활성 사용자 |
| Windsurf (Devin Desktop) | 83 | ↑1 | $15 인하로 Copilot 이탈 흡수 |
| Gemini CLI | 71 | ↓1 | 종료 D-14, Antigravity CLI 전환 가속 |
| Aider | 68 | — | 오픈소스 안정세 |
| Antigravity | 64 | ↑1 | I/O 이후 회복 10주차 |
| GH Copilot | 52 | ↓1 | 31주 연속 하락, 종량제 이탈 본격화 |

오늘의 핵심은 양대 도구의 동시 릴리스다. Claude Code v2.1.162의 병렬 Bash 독립 실행은 멀티 에이전트 워크플로 안정성을 높이고, Cursor 3.7의 Canvas Design Mode는 디자인-코드 간극을 한 단계 더 줄인다. Project Glasswing의 150개 기관 확대는 AI 보안 스캔이 소수 파트너의 특권에서 업계 표준으로 이동하고 있음을 보여준다.

---
title: "Build 2026 개막: Microsoft가 OpenAI 줄을 끊는다 — Project Polaris, Copilot 과금 반란은 계속"
date: 2026-06-02
lang: ko
categories: [news]
tags: [microsoft-build, github-copilot, claude-code, nvidia, cursor, codex-cli, gemini-cli]
excerpt: "Microsoft Build 2026 1일차에서 자체 코딩 모델 Project Polaris를 공개하며 OpenAI 의존도를 줄이기 시작했다. 하지만 Copilot 종량제 2일차, 개발자들의 10~50배 비용 증가 보고가 이어지며 반발은 더 거세졌다."
---

Microsoft Build 2026이 샌프란시스코에서 개막했다. 핵심은 명확하다: Microsoft가 GitHub Copilot의 기본 엔진을 OpenAI의 GPT-4에서 자체 개발 모델 'Project Polaris'로 교체한다는 것이다. 6개월간의 루머가 사실로 확인된 순간이며, AI 코딩 시장의 판도를 바꿀 신호탄이다.

## Microsoft Build: Project Polaris로 OpenAI 탈출 선언

Project Polaris는 Microsoft가 자체 개발한 MoE(Mixture-of-Experts) 아키텍처 코딩 모델로, 표준 코딩 벤치마크에서 GPT-4 Turbo를 능가한다고 발표됐다([TechTimes](https://www.techtimes.com/articles/317596/20260602/github-copilot-replaces-gpt-4-project-polaris-ships-multi-agent-vs-code-build.htm)). 8월부터 전체 Copilot 구독자에게 자동 전환되며, 기존 모델은 3개월간 폴백 옵션으로 유지된다([ChatForest](https://chatforest.com/builders-log/microsoft-build-2026-recap-windows-agent-platform-project-polaris-copilot-workspace/)).

동시에 Copilot Workspace가 GA로 전환됐다. Fleet 모드(확인 없이 자율 실행), Autopilot 모드(백그라운드 자율 작업), Extensions(Jira·Datadog·ServiceNow 연동)가 핵심이다. VS Code에서는 멀티에이전트 모드가 출시돼 린팅·테스팅·문서화·보안 리뷰를 병렬 서브에이전트로 동시 실행할 수 있게 됐다([TechTimes](https://www.techtimes.com/articles/317596/20260602/github-copilot-replaces-gpt-4-project-polaris-ships-multi-agent-vs-code-build.htm)).

## Copilot 종량제 2일차: 10~50배 비용 충격

Build의 좋은 뉴스에도 불구하고, Copilot의 하락세는 멈추지 않았다. 사용량 기반 과금 이틀째, 개발자들이 실제 비용 데이터를 공유하기 시작하면서 충격이 퍼지고 있다([TechJournal](https://techjournal.org/github-copilot-token-billing-backlash)). 일부 헤비 유저는 에이전틱 코딩 한 번 아침 세션에 월 크레딧을 전부 소진했다고 보고했다. Reddit에서는 Claude Code($20/월 정액), Codex CLI(API 과금), DeepSeek V4 Pro(오픈 웨이트)로의 이탈이 가속화되고 있다([TechCrunch](https://techcrunch.com/2026/05/30/what-a-joke-github-copilots-new-token-based-billing-spurs-consternation-among-devs/)).

인기도 점수는 29주 연속 하락해 54를 기록했다 — 추적 시작 이래 최저치가 또 경신됐다.

## Claude Code v2.1.160: 보안 강화

Claude Code가 v2.1.160을 출시하며 보안을 강화했다([code.claude.com/changelog](https://code.claude.com/docs/en/changelog)). 셸 시작 파일(.zshenv, .zlogin, .bash_login)과 git 설정에 쓰기 전 보안 프롬프트가 추가됐고, 빌드 도구 설정 파일(.npmrc, .yarnrc, bunfig.toml 등)도 acceptEdits 모드에서 쓰기 전 확인을 요구한다. 6월 15일부터 시행되는 에이전트 과금 변경(프로그래밍 방식 사용량 별도 크레딧 풀 전환)도 2주 앞으로 다가왔다([Codersera](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/)).

## Claude AI: 전 모델에 영향을 준 4시간 글로벌 장애

Claude AI가 6월 2일 전 세계적으로 장애를 겪었다. Opus 4.7, Opus 4.6, Sonnet 4.6 등 모든 모델에서 오류율이 급증했으며([SQ Magazine](https://sqmagazine.co.uk/claude-ai-down-outage-june-2026/)), API·Console·Claude Code 전체가 영향을 받았다([TechRadar](https://www.techradar.com/news/live/claude-outage-june-2026)). 미 동부시간 오전 2:19경 시작된 장애는 약 4시간 만에 Anthropic이 원인을 파악하고 수정을 배포해 복구됐다([Republic World](http://www.republicworld.com/tech/anthropic-hits-snag-claude-ai-suffers-major-global-outage-leaving-users-stranded-with-error-messages-2026-06-02-126613)). 5월 8일 2,000명 이상에게 영향을 준 장애 이후 한 달 만에 두 번째 주요 장애다.

## NVIDIA Vera Rubin 양산 돌입

NVIDIA가 Computex 2026에서 차세대 Vera Rubin 플랫폼의 본격 양산을 발표했다([ServeTheHome](https://www.servethehome.com/nvidia-computex-2026-news-bytes-vera-rubin-now-in-production-dgx-station-gets-windows/)). TSMC 3nm 공정에서 제조되며, Blackwell 대비 추론 비용 10배 절감, MoE 모델 훈련 GPU 4분의 1 감소, 랙 조립 시간 2시간→5분으로 단축됐다. AWS, Google Cloud, Microsoft, OCI가 2026년 하반기 최초 배포한다([NVIDIA Newsroom](https://nvidianews.nvidia.com/news/rubin-platform-ai-supercomputer)).

## Cursor Teams 가격 개편

Cursor가 Teams 요금제를 대폭 개편했다([cursor.com/changelog](https://cursor.com/changelog)). Premium 시트 추가, 사용량 분리 풀, 실시간 가시성과 스마트 알림으로 팀 90%의 비용 절감이 예상된다. Bugbot도 시트 과금에서 사용량 기반($1-1.50/회)으로 전환되며, 6월 8일 이후 갱신부터 적용된다.

## Gemini CLI 종료 D-16

Gemini CLI 서비스 종료까지 16일 남았다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). 비엔터프라이즈 사용자는 6월 18일 이후 모든 요청이 차단된다. Antigravity CLI로의 마이그레이션이 필수이며, Go 기반으로 더 빠르고 네이티브 멀티에이전트 오케스트레이션을 지원한다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 안정적 1위, v2.1.160 보안 강화 |
| ChatGPT | 96 | — | Build 영향 관망 |
| Cursor | 96 | — | Teams 가격 개편으로 가성비 강화 |
| Claude AI | 95 | — | 4시간 글로벌 장애 복구, 엔터프라이즈 확대 지속 |
| Codex CLI | 87 | — | Windows Computer Use 추가 |
| Windsurf | 81 | — | 안정세 유지 |
| Gemini CLI | 73 | ↓1 | 종료 D-16 카운트다운 |
| Antigravity | 62 | ↑1 | 롤백 위기 후 회복 8주차 |
| Aider | 68 | — | 오픈소스 안정세 |
| GH Copilot | 54 | ↓1 | 29주 연속 하락, Build도 과금 반발 상쇄 못해 |

Build 2026의 Project Polaris와 멀티에이전트 발표는 기술적으로 인상적이지만, 개발자들이 가장 먼저 체감하는 것은 청구서다. Copilot이 반등하려면 가격 정책의 실질적 수정이 필요하다 — 기술 발표만으로는 부족하다.

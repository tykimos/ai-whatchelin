---
title: "Copilot 23주 연속 하락, 60선 붕괴 — 사용량 과금 D-5 카운트다운"
date: 2026-05-27
lang: ko
categories: [news]
tags: [github-copilot, copilot-studio, grok-build, anthropic, gemini-cli]
excerpt: "GitHub Copilot이 추적 이래 처음으로 60선 아래를 향하고 있다. 6월 1일 사용량 기반 과금까지 5일, Microsoft는 엔터프라이즈 통제력을 강화하고 Copilot Studio CUA를 정식 출시했다."
---

GitHub Copilot의 인기도가 23주 연속 하락하며 60에 도달했다 — 추적을 시작한 이래 역대 최저치다. 6월 1일 사용량 기반 과금 전환까지 불과 5일 남은 상황에서, 개발자들의 불안감이 커지고 있다. 코드 완성과 Next Edit 제안은 무제한으로 유지되지만, 에이전트와 채팅 기능은 모두 GitHub AI 크레딧으로 측정된다([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)).

## GitHub Copilot: 엔터프라이즈 통제력 강화로 하락 방어 시도

GitHub이 타겟 모델 규칙을 퍼블릭 프리뷰로 출시했다([GitHub Changelog](https://github.blog/changelog/2026-05-26-target-copilot-models-to-organizations-with-model-rules/)). 엔터프라이즈 관리자가 조직별로 사용 가능한 Copilot 모델을 세밀하게 제어할 수 있는 기능으로, 기존의 엔터프라이즈 전체 일괄 설정을 넘어서는 거버넌스 도구다. Business와 Enterprise 플랜에서 사용 가능하며, 사용량 과금 전환을 앞두고 엔터프라이즈 고객의 비용 통제 수요에 대응하는 움직임으로 해석된다.

## Copilot Studio: 컴퓨터 사용 에이전트 최초 GA

Microsoft의 Copilot Studio가 컴퓨터 사용 에이전트(CUA)를 전체 상용 Power Platform 지역에서 정식 출시했다([Microsoft Copilot Blog](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/new-and-improved-computer-using-agents-a-new-workflows-experience-and-real-time-voice-experiences/)). 에이전트가 데스크톱·웹 앱의 UI를 직접 클릭하고 입력하며 탐색하는 방식으로, API가 없는 레거시 시스템 자동화에 특화됐다. OpenAI CUA와 Claude Sonnet 4.5를 프로덕션 모델로 탑재하고, Windows 365 Cloud PC에서 격리 실행된다. 계약 기반 GA로 CUA를 제공하는 최초의 플랫폼이라는 점에서 의미가 크다 — Anthropic의 Computer Use는 유료 베타, Google의 Gemini Computer Use는 퍼블릭 프리뷰 단계다.

## Grok Build: SuperGrok Heavy 넘어 전면 개방

xAI가 Grok Build 접근을 전체 SuperGrok 및 X Premium+ 구독자로 확대했다([xAI](https://x.ai/news/grok-build-cli)). 기존 SuperGrok Heavy($299/월) 전용이었던 것이 대폭 확장된 것이다. 같은 날 Windows PowerShell 설치기도 출시되어 Windows 개발자 접근성이 개선됐다. grok-build-0.1 모델 기반으로 256K 컨텍스트, 8개 병렬 서브에이전트, 계획 우선 실행 루프를 지원한다.

## Gemini CLI: 종료까지 22일

Gemini CLI의 서비스 종료가 22일 앞으로 다가왔다. 6월 18일 이후 비엔터프라이즈 사용자에게 요청 처리가 중단되며, Antigravity CLI(Go 언어 기반)로의 전환이 가속화되고 있다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). Antigravity의 인기도는 56으로 소폭 회복세를 이어가고 있지만, 2.0 자동 업데이트 참사의 상처가 완전히 아물지는 않았다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 98 | — | 14일 연속 98 안정 |
| Cursor | 96 | — | Composer 2.5 안정세 |
| Codex CLI | 88 | — | 5주 연속 고점 유지 |
| Windsurf | 81 | — | Devin 통합 후 안정 |
| Gemini CLI | 80 | ↓1 | 종료 D-22, 하락 지속 |
| GH Copilot | 60 | ↓1 | 23주 연속 하락, 역대 최저 |
| Antigravity | 56 | ↑1 | 롤백 사태 후 3일 연속 회복 |
| ChatGPT | 98 | — | GPT-5.5 Instant 효과 지속 |
| Claude AI | 94 | — | $30B+ 라운드 마감 주간 |

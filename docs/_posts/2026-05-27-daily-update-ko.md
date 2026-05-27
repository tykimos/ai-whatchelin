---
title: "Copilot 23주 연속 하락, 60선 붕괴 — Mythos가 Claude Code에 깜짝 등장"
date: 2026-05-27
lang: ko
categories: [news]
tags: [github-copilot, copilot-studio, grok-build, anthropic, gemini-cli, claude-mythos]
excerpt: "GitHub Copilot이 역대 최저 60을 기록한 가운데, Anthropic의 제한 모델 Mythos가 Claude Code에 잠시 등장하며 공개 출시 임박 신호를 보냈다. Copilot Studio는 최초의 GA 컴퓨터 사용 에이전트를 출시했다."
---

GitHub Copilot의 인기도가 23주 연속 하락하며 60에 도달했다 — 추적 이래 역대 최저치다. 6월 1일 사용량 기반 과금 전환까지 불과 5일 남은 상황에서, 에이전트와 채팅 기능은 GitHub AI 크레딧으로 측정되고 코드 완성만 무제한으로 유지된다([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)).

## Claude Mythos: Claude Code에 잠깐 등장, 즉시 제거

Anthropic의 제한된 프론티어 모델 Mythos가 5월 25일 Claude Code 인터페이스에 잠시 노출됐다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropics-restricted-claude-mythos-model-may-be-coming-to-claude-code/)). 사용자들이 Mythos 토글을 발견한 직후 삭제됐지만, 모델 식별자 `claude-mythos-1-preview`가 Claude Code와 Claude Security를 통한 출시를 준비 중인 것으로 확인됐다([WinBuzzer](https://winbuzzer.com/2026/05/26/anthropics-mythos-moves-closer-to-claude-code-xcxwbn/)). 현재 약 50개 조직이 Project Glasswing을 통해 접근 중이며, 지난주에만 1,000+ 오픈소스 프로젝트에서 23,019개 보안 이슈를 발견했다.

## Anthropic: 28개 엔터프라이즈 보안 연동 출시

Anthropic이 Claude Compliance API를 통해 28개 신규 보안·컴플라이언스 연동을 출시했다([Help Net Security](https://www.helpnetsecurity.com/2026/05/25/anthropic-security-compliance-integrations-claude/)). CrowdStrike, Palo Alto Networks, Microsoft Purview, Okta, Zscaler, Netskope, Cloudflare, Fortinet, Wiz, Datadog 등 주요 보안 벤더가 포함된다. 엔터프라이즈 IT 팀이 기존 보안 도구 체인으로 Claude를 관리할 수 있게 되면서, 대기업 도입의 마지막 장벽인 보안 거버넌스 문제를 정면으로 공략하는 모양새다.

## GitHub Copilot: 엔터프라이즈 통제력 강화로 하락 방어 시도

GitHub이 타겟 모델 규칙을 퍼블릭 프리뷰로 출시했다([GitHub Changelog](https://github.blog/changelog/2026-05-26-target-copilot-models-to-organizations-with-model-rules/)). 엔터프라이즈 관리자가 조직별로 사용 가능한 Copilot 모델을 세밀하게 제어할 수 있는 기능으로, 사용량 과금 전환을 앞두고 비용 통제 수요에 대응하는 움직임이다.

## Copilot Studio: 컴퓨터 사용 에이전트 최초 GA

Microsoft의 Copilot Studio가 컴퓨터 사용 에이전트(CUA)를 전체 상용 Power Platform 지역에서 정식 출시했다([Microsoft Copilot Blog](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/new-and-improved-computer-using-agents-a-new-workflows-experience-and-real-time-voice-experiences/)). OpenAI CUA와 Claude Sonnet 4.5를 프로덕션 모델로 탑재하고, API가 없는 레거시 시스템 자동화에 특화됐다. 계약 기반 GA로 CUA를 제공하는 최초의 플랫폼이다.

## Grok Build: 전면 개방

xAI가 Grok Build를 전체 SuperGrok 및 X Premium+ 구독자로 확대하고, Windows PowerShell 설치기를 출시했다([xAI](https://x.ai/news/grok-build-cli)). grok-build-0.1 모델(256K 컨텍스트)에 8개 병렬 서브에이전트를 지원하며, 터미널 에이전트 시장에 본격 진입하는 신호다.

## 서비스 안정성: 곳곳에서 장애

Anthropic의 Opus 4.7이 5월 25일 06:30–10:30 UTC에 오류율이 급증했고([Claude Status](https://status.claude.com/)), Windsurf도 5월 26일 약 1시간 38분간 오류가 발생했다([Windsurf Status](https://status.windsurf.com/)). Gemini CLI 종료까지 22일 — Antigravity CLI 전환이 가속화되고 있다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 98 | — | 14일 연속 98 안정 |
| Cursor | 96 | — | Composer 2.5 안정세 |
| Codex CLI | 88 | — | 5주 연속 고점 유지 |
| Windsurf | 81 | — | Devin 통합 후 안정, 장애 발생 |
| Gemini CLI | 80 | ↓1 | 종료 D-22, 하락 지속 |
| GH Copilot | 60 | ↓1 | 23주 연속 하락, 역대 최저 |
| Antigravity | 56 | ↑1 | 롤백 사태 후 3일 연속 회복 |
| ChatGPT | 98 | — | GPT-5.5 Instant 효과 지속 |
| Claude AI | 94 | — | $30B+ 라운드 마감 주간 |

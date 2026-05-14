---
title: "GitHub Copilot, 신규 가입 막고 데스크톱 앱 출시 — 에이전트 비용 전쟁의 서막"
date: 2026-05-14
lang: ko
categories: [news]
tags: [github-copilot, claude-code, anthropic, cursor, gemini-cli, aws-kiro, openai, stainless]
excerpt: "GitHub이 Copilot 개인 플랜 신규 가입을 막으면서 데스크톱 앱과 Max 플랜을 동시에 꺼냈다. Anthropic은 Stainless 인수와 $9000억 밸류에이션을 동시 추진 중이다."
---

GitHub이 한 손으로는 문을 닫고, 다른 손으로는 새 문을 열었다. Copilot 개인 플랜(Pro/Pro+/Student) 신규 가입이 4월 말부터 중단된 상황에서, 오늘 GitHub은 **Copilot App** 테크니컬 프리뷰와 **Max 플랜**을 동시에 발표했다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-individual-plans-introducing-flex-allotments-in-pro-and-pro-and-a-new-max-plan/)). Copilot App은 GitHub 네이티브 데스크톱 경험으로, 이슈·PR·이전 세션에서 에이전트 작업을 시작하고, 브랜치·파일·대화가 격리된 상태로 병렬 진행할 수 있다([GitHub Changelog](https://github.blog/changelog/2026-05-14-github-copilot-app-is-now-available-in-technical-preview/)). Pro/Pro+ 구독자에게 먼저, Business/Enterprise는 이번 주 내 순차 제공된다.

## GitHub Copilot: Max 플랜 + 토큰 과금 전환

6월 1일부터 모든 Copilot 플랜이 사용량 기반 과금(AI 크레딧)으로 전환된다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Pro는 $10/월, Pro+는 $39/월(AI 크레딧 $39 포함)으로 가격은 유지되지만, 자동완성과 Next Edit는 크레딧을 소모하지 않는다. 새로 추가된 **Max** 플랜은 고볼륨 사용자를 위한 최상위 티어다. 한편, Pro에서 **Opus 모델이 제거**되어 Opus 4.7은 Pro+($39/월)부터만 사용 가능하다 — 사실상 Opus 접근 비용이 290% 인상된 셈이다([DEV Community](https://dev.to/techsifted/github-copilot-may-2026-changes-sign-ups-paused-opus-removed-rate-limits-visible-2ip8)). CLI v1.0.48에서는 모델 피커가 토큰 가격을 직접 표시하기 시작했다([GitHub Releases](https://github.com/github/copilot-cli/releases)).

## Anthropic: Stainless + $9000억 밸류에이션

Anthropic이 OpenAI·Google·Cloudflare·Meta의 공식 SDK를 만드는 Stainless를 $3억 이상에 인수 협상 중이라는 The Information 보도에 이어, Bloomberg는 Anthropic이 $300억+ 규모 펀딩으로 **$9000억 밸류에이션**을 목표로 하고 있다고 보도했다([Bloomberg](https://www.newsbytesapp.com/news/business/anthropic-nearing-stainless-acquisition-and-seeking-at-least-30b-funding/tldr)). SDK 인프라 장악과 자금 조달을 동시 추진하는 행보다.

## Claude Code: 한도 인상 + v2.1.141

Claude Code 주간 한도가 Pro/Max/Team/Enterprise에서 50% 인상됐으며 7월 13일까지 유지된다([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)). v2.1.141에서는 Agent View(모든 세션을 한 목록에서 관리), /goal 명령어(완료 조건 설정 후 자동 반복), 터미널 알림 훅, 워크스페이스 신원 연합이 추가됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)).

## Cursor: 클라우드 에이전트 개발 환경

Cursor가 클라우드 에이전트를 위한 Development Environments를 정식 출시했다([Cursor Changelog](https://cursor.com/changelog/05-13-26)). 멀티레포 지원, Dockerfile 레이어 캐싱(빌드 70% 가속), 환경별 롤백, 감사 로깅이 포함된다. Microsoft Teams 통합(@Cursor 멘션으로 에이전트 위임)도 이번 주 출시됐다([Cursor Blog](https://cursor.com/blog/cloud-agent-development-environments)).

## AWS Kiro: SMT 솔버 + Google I/O D-5

AWS Kiro에 SMT 솔버 기반 'Spec Check'가 추가되어 코드 작성 전 요구사항 모순을 수학적으로 증명한다([GeekWire](https://www.geekwire.com/2026/aws-targets-ai-slop-with-new-spec-check-in-kiro-coding-tool-amid-scrutiny-of-agent-reliability/)). Google I/O가 5일 앞으로 다가왔으며, Gemini CLI v0.43.0-preview의 서브에이전트 아키텍처가 Gemini 4 공개와 함께 실전 투입될 전망이다([TechRound](https://techround.co.uk/tech/gemini-4-ai-glasses-and-a-new-os-why-google-i-o-2026-could-be-the-most-important-developer-event-of-the-year/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 안정 |
| Claude Code | 98 | — | v2.1.141, 주간 한도 50%↑, 11일째 98 |
| Cursor | 95 | ↑1 | 클라우드 에이전트 개발 환경 + Teams 통합 |
| Claude AI | 92 | — | Cowork GA 안정화 |
| Codex CLI | 81 | — | Chrome 확장, 워크스페이스 에이전트 |
| Windsurf | 78 | — | Opus 4.7 fast 모드 안정 |
| Gemini CLI | 75 | ↑1 | I/O D-5, 서브에이전트 아키텍처 |
| GitHub Copilot | 73 | — | App 프리뷰 출시, 하지만 가입 중단 + Opus 제거 상쇄 |
| Aider | 68 | — | 안정 |
| Antigravity | 48 | ↓1 | 소프트 디프리케이션 루머 |

GitHub의 "신규 가입 중단 + 데스크톱 앱 출시 + Max 플랜"은 에이전트 시대의 비용 현실을 정면으로 보여준다. 에이전트 워크로드가 기존 요금제 구조를 뒤흔들면서, "무제한"은 더 이상 지속 가능한 약속이 아니게 됐다. 한편 Anthropic은 SDK 인프라(Stainless)와 자금($300억 펀딩)을 동시에 확보하며 플랫폼 전쟁의 판을 키우고 있다.

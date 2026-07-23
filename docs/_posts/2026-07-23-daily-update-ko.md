---
title: "백악관, Moonshot AI의 Fable 증류 의혹 공식 제기 — 미중 AI 분쟁 새 국면"
date: 2026-07-23
lang: ko
categories: [news]
tags: [anthropic, moonshot, kimi-k3, fable, claude-security, cursor, deepseek, github-models, copilot]
excerpt: "미국 백악관이 Moonshot AI가 Anthropic의 Fable 모델을 증류해 Kimi K3를 개발했다고 공식 지목했다. 재무부는 제재 가능성까지 시사하며 미중 AI 갈등이 새로운 국면에 접어들었다."
---

미국 백악관 과학기술정책국(OSTP) 국장 Michael Kratsios가 중국 AI 스타트업 Moonshot AI를 공식 지목하며, Anthropic의 Fable 모델을 증류(distillation)해 Kimi K3를 개발했다고 밝혔다([TechCrunch](https://techcrunch.com/2026/07/22/treasury-threatens-sanctions-after-white-house-claims-moonshot-distilled-anthropics-fable/)). Kratsios에 따르면 Moonshot은 탐지를 피하기 위해 접근 방법을 빠르게 전환하며 미국 모델 전반에 걸쳐 증류를 수행할 수 있는 내부 플랫폼을 구축했다([Seeking Alpha](https://seekingalpha.com/news/4616700-kratsios-says-moonshot-built-kimi-k3-through-industrial-distillation-of-anthropics-fable)). 미 재무장관 Scott Bessent은 증류를 통한 부정 훈련이 입증될 경우 중국 기업에 대한 제재를 검토할 수 있다고 경고했다([Eastern Herald](https://easternherald.com/2026/07/23/moonshot-ai-fable-distillation-sanctions/)). 다만 Fable이 7월 1일에야 공개된 점을 들어 Kimi K3(7월 16일 출시)가 주로 증류를 통해 만들어졌다는 주장에 회의적인 전문가도 있다.

## Claude Security: 엔터프라이즈 퍼블릭 베타 개시

Anthropic이 Claude Security를 퍼블릭 베타로 출시했다([Claude Blog](https://claude.com/blog/claude-security-public-beta)). Claude Opus 4.7 기반의 멀티에이전트 보안 스캐너로, 코드베이스의 취약점을 분석하고 패치를 자동 생성한다([MarkTechPost](https://www.marktechpost.com/2026/07/22/anthropic-releases-claude-security-plugin-for-claude-code-in-beta-a-multi-agent-vulnerability-scanner-that-runs-in-your-terminal/)). Git 히스토리 추적, 파일 간 데이터 플로우 분석, 비즈니스 로직 이해까지 가능해 단순 패턴 매칭을 넘어선다. Claude Code 플러그인으로도 제공돼 터미널에서 커밋 전 취약점 스캔이 가능하다. 현재 Enterprise 고객 대상이며, Team 및 Max 고객 지원은 곧 예정이다.

## Cursor: iOS 퍼블릭 베타 출시 및 v3.11

Cursor가 iOS 퍼블릭 베타를 유료 플랜 전체에 출시해 모바일에서 에이전트 실행, Remote Control, 실시간 알림, 코드 리뷰가 가능해졌다([Releasebot](https://releasebot.io/updates/cursor)). v3.11(7월 10일)에서는 `/multitask`로 비동기 서브에이전트 병렬 실행을 에디터에서 지원하고, 자동 실행 3회 연속 감지 시 상시 활성화를 제안하는 기능이 추가됐다.

## GitHub Models: 오늘 브라운아웃, D-7

GitHub Models 브라운아웃이 오늘 진행됐다([GitHub Blog](https://github.blog/changelog/2026-07-01-github-models-is-being-fully-retired-on-july-30-2026/)). 7월 30일 완전 폐쇄까지 일주일 남았다. 한편 새로운 Copilot 사용량 메트릭 임팩트 대시보드가 어제 출시돼 엔터프라이즈 관리자의 AI 도입 분석이 강화됐다([GitHub Changelog](https://github.blog/changelog/2026-07-22-new-copilot-usage-metrics-impact-dashboard/)).

## DeepSeek V4: 내일 레거시 엔드포인트 폐쇄

`deepseek-chat`과 `deepseek-reasoner` 엔드포인트가 내일(7월 24일) UTC 15:59부로 완전 폐쇄된다([WaveSpeed](https://wavespeed.ai/blog/posts/blog-deepseek-v4-model-name-migration/)). 마이그레이션하지 않은 개발자는 즉시 모델명을 업데이트해야 한다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Claude Security 베타, Fable 증류 논란의 중심 |
| ChatGPT | 99 | — | Codex 앱 ChatGPT 통합 완료 |
| Antigravity | 99 | — | Antigravity CLI Go 빌드 안정화 |
| Claude AI | 98 | — | Kimi K3 증류 의혹으로 Fable 가치 재조명 |
| Cursor | 97 | — | iOS 베타 출시, SpaceX 인수 진행 중 |
| Codex CLI | 91 | — | v0.145.0 안정 운영 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 2 | ↓1 | 브라운아웃 실행, 완전 폐쇄 D-7 |
| Gemini CLI | 2 | ↓1 | 소비자 접근 폐쇄 35일째, Antigravity CLI로 전환 중 |

GitHub Copilot과 Gemini CLI가 각각 2점으로 하락했다. Copilot은 오늘 브라운아웃이 실행되며 완전 폐쇄까지 일주일, Gemini CLI는 소비자 접근 차단 5주째를 맞으며 Antigravity CLI 전환이 진행 중이다. Kimi K3 증류 논란은 미중 AI 경쟁의 새로운 축으로, Anthropic Fable의 기술적 가치를 역설적으로 증명하고 있다.

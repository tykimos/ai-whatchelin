---
title: "DeepSeek V4 오늘 강제 전환 — 레거시 엔드포인트 폐쇄, Opus 4.7 fast mode도 종료"
date: 2026-07-24
lang: ko
categories: [news]
tags: [deepseek, anthropic, claude-security, cursor, github-models, copilot, gemini-cli, opus]
excerpt: "DeepSeek V4 레거시 엔드포인트가 오늘 폐쇄되고, Anthropic Opus 4.7 fast mode도 지원 종료된다. 두 건의 강제 마이그레이션이 동시에 진행되는 하루."
---

오늘은 AI 개발자들에게 두 건의 강제 마이그레이션이 겹치는 날이다. DeepSeek V4 안정판이 출시되면서 `deepseek-chat`과 `deepseek-reasoner` 레거시 엔드포인트가 UTC 15:59부로 완전 폐쇄된다([WaveSpeed](https://wavespeed.ai/blog/posts/blog-deepseek-v4-model-name-migration/)). 100만 토큰 컨텍스트, 강화된 에이전트 실행과 코드 생성 능력을 갖춘 V4지만, 피크 시간대(베이징 시간 9-12시, 14-18시) API 요금이 2배로 뛰는 새로운 가격 메커니즘이 논란이다([Servola](https://servola.de/journal/ai-tokens-now-have-a-rush-hour/)). 동시에 Anthropic도 Opus 4.7 fast mode를 오늘부로 종료하고 Opus 4.8 fast mode로 전환한다.

## Claude Security: 엔터프라이즈 보안 스캐너 공식 베타

어제 공개된 Claude Security가 빠르게 관심을 모으고 있다. Claude Opus 4.7 기반 멀티에이전트 취약점 스캐너로, Git 히스토리 추적과 파일 간 데이터 플로우 분석까지 수행한다([MarkTechPost](https://www.marktechpost.com/2026/07/22/anthropic-releases-claude-security-plugin-for-claude-code-in-beta-a-multi-agent-vulnerability-scanner-that-runs-in-your-terminal/)). Claude Code 플러그인으로도 제공돼 커밋 전 터미널에서 보안 스캔이 가능하다. 현재 Enterprise 고객 전용이며, Team·Max 지원은 곧 예정이다([Claude Blog](https://claude.com/blog/claude-security-public-beta)).

## Cursor: 사용량 한도 2배 인상과 iOS 안착

Cursor가 7월 21일 전 플랜 사용량 한도를 2배로 올렸다([Explainx](https://explainx.ai/blog/cursor-doubled-usage-limits-again-july-21-2026)). $120/월 Premium 시트(Standard 5배 사용량)도 정식 운영 중이다. iOS 퍼블릭 베타로 모바일 에이전트 실행, Remote Control, 코드 리뷰가 가능해지면서 SpaceX 인수 후 첫 본격적인 사용자 확대 행보로 읽힌다.

## GitHub Models: D-6, Copilot 76주 연속 하락

GitHub Models 완전 폐쇄까지 6일 남았다([GitHub Blog](https://github.blog/changelog/2026-07-01-github-models-is-being-fully-retired-on-july-30-2026/)). Copilot은 76주 연속 하락해 점수 1까지 떨어졌다. Copilot Vision GA와 데스크톱 앱 전 플랜 확대 등 기능 강화는 계속되지만, 종량제 전환 후 비용 급증 우려가 사용자 이탈을 막지 못하고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Claude Security 베타 호응, Fable 기본 모델 안정 |
| ChatGPT | 99 | — | GPT-5.6 Sol 안정화, Codex 통합 진행 |
| Antigravity | 99 | — | CLI Go 빌드 안정, Gemini CLI 완전 대체 |
| Claude AI | 98 | — | Opus 4.8 fast mode 전환 완료 |
| Cursor | 97 | — | 사용량 2배 인상, iOS 베타 안착 |
| Codex CLI | 91 | — | v0.145.0 안정 운영, Bedrock 지원 확대 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | ↓1 | 76주 연속 하락, GitHub Models D-6 |
| Gemini CLI | 1 | ↓1 | 소비자 접근 차단 36일째 |

Copilot과 Gemini CLI가 동반 1점으로 하락했다. 두 도구 모두 플랫폼 폐쇄·전환 과정에 있으며, 사실상 신규 사용자 유입이 중단된 상태다. DeepSeek V4의 피크 시간대 가격 차등제는 API 토큰에도 '러시아워'가 적용되는 첫 사례로, 업계 전체 가격 구조에 영향을 줄 수 있다.

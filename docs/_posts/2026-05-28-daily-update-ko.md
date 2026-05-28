---
title: "Claude Opus 4.8 출시 — SWE-bench 88.6%, AI 코딩 벤치마크 역대 최고 경신"
date: 2026-05-28
lang: ko
categories: [news]
tags: [claude, anthropic, opus, copilot, gemini-cli, cohere, chatgpt, microsoft-build]
excerpt: "Anthropic이 Opus 4.8을 출시하며 SWE-bench Verified 88.6%를 기록했다. USAMO 수학은 96.7%로 27pp 급등. Big Four 3곳 Claude 표준화와 맞물려 엔터프라이즈 독주 체제가 굳어지고 있다."
---

Anthropic이 오늘 Claude Opus 4.8을 출시했다. SWE-bench Verified 88.6%(Opus 4.7의 87.6%에서 상승), SWE-bench Pro 69.2%(64.3%에서 점프), USAMO 2026 수학 96.7%(69.3%에서 27pp 급등)을 기록하며 AI 코딩 벤치마크를 다시 한 번 갈아치웠다([TechCrunch](https://techcrunch.com/2026/05/28/anthropic-releases-opus-4-8-with-new-dynamic-workflow-tool/)). 특히 1M 토큰 롱컨텍스트 F1이 40.3%에서 68.1%로 거의 두 배 뛰며 대규모 코드베이스 작업 능력이 대폭 강화됐다([llm-stats.com](https://llm-stats.com/blog/research/claude-opus-4-8-launch)).

## Claude Code: 동적 워크플로우와 99점 달성

Opus 4.8의 핵심 변화는 Claude Code에서의 병렬 서브에이전트 동적 워크플로우다([digitalapplied.com](https://www.digitalapplied.com/blog/claude-opus-4-8-release-dynamic-workflows-2026)). 에이전트가 작업 중간에 시스템 메시지를 수신할 수 있는 Messages API 업데이트, 그리고 선택적 2.5x 패스트 모드가 추가됐다. 가격은 $5/$25(입력/출력 1M 토큰)으로 동일하다([anthropic.com](https://anthropic.com)). Claude Code 인기도는 98에서 99로 상승하며 역대 최고를 기록했다.

## Big Four 3곳 Claude 전사 배포 확정

Deloitte(47만 명), PwC(27.6만 명), KPMG(138개국 27.6만 명)이 60일 내 Claude 전사 배포를 확정했다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-may-28-2026)). EY만 유사 규모 계약을 미발표한 상태다. Opus 4.8 출시와 동시에 엔터프라이즈 표준화가 맞물리며, Anthropic의 시장 지배력이 더욱 공고해지고 있다.

## Claude Security 퍼블릭 베타

Opus 4.7 기반 코드베이스 취약점 스캐닝이 퍼블릭 베타로 전환됐다([Help Net Security](https://www.helpnetsecurity.com/2026/05/04/anthropic-claude-security-public-beta/)). 기존 정적 분석을 넘어 아키텍처 수준 보안 이슈를 탐지하며, Project Glasswing을 통해 약 50개 조직에 제공 중이다.

## Copilot 24주 연속 하락 — 사용량 과금 D-4

GitHub Copilot이 24주 연속 하락하며 59를 기록, 추적 이래 역대 최저다([GitHub Docs](https://docs.github.com/en/copilot/concepts/billing/usage-based-billing-for-individuals)). 6월 1일 사용량 기반 과금까지 4일. 5일 후 Microsoft Build 2026이 반전 카드가 될 수 있을지 주목된다.

## Gemini CLI 종료 D-21 — 개발자 신뢰 위기

Gemini CLI가 6월 18일 종료까지 D-21로 접어들며 인기도 78로 하락했다([Google Developers Blog](https://developers.googleblog.com/build-with-google-antigravity-our-new-agentic-development-platform/)). 6,000개 이상의 커뮤니티 기여를 받은 오픈소스 프로젝트를 폐쇄형 Antigravity CLI로 강제 전환하는 결정에 개발자들의 반발이 이어지고 있다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | ↑1 | Opus 4.8 출시일 부스트, 역대 최고 |
| ChatGPT | 98 | — | 음성 모드 논란에도 텍스트 모델 강세 |
| Cursor | 96 | — | Build D-5 앞두고 안정 |
| Claude AI | 95 | ↑1 | Opus 4.8 모델 출시 효과 |
| Codex CLI | 88 | — | Goal 모드 정식 후 안정화 |
| Windsurf | 81 | — | 변동 없음 |
| Gemini CLI | 78 | ↓1 | 종료 D-21, 꾸준한 하락 |
| Aider | 68 | — | 오픈소스 안정, 41.6K Stars |
| Copilot | 59 | — | 24주 연속 하락, 역대 최저 |
| Antigravity | 57 | — | v2.0.0 패치 후 횡보 |

Opus 4.8 출시로 Claude Code가 99를 찍으며 경쟁 도구와의 격차를 더 벌렸다. SWE-bench Pro에서 5pp 점프는 에이전틱 코딩 품질의 실질적 개선을 보여준다. Copilot은 6월 1일 과금 전환을 4일 앞두고 역대 최저에 머물러 있다.

---

*이 포스트는 AI WhatChelin 프로젝트에서 자동 생성되었습니다.*

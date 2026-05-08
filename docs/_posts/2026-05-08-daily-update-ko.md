---
title: "Anthropic, Akamai와 1.8조원 클라우드 계약 — Claude Cowork 정식 출시, Cursor Bugbot 자가학습 도입"
date: 2026-05-08
lang: ko
categories: [news]
tags: [claude-code, claude-ai, cursor, copilot, antigravity, security, akamai]
excerpt: "Anthropic이 Akamai와 7년간 $1.8B 클라우드 계약을 체결하고, Claude Cowork가 전 유료 플랜에 정식 출시됐다. Cursor Bugbot은 PR 피드백으로 자가학습하는 기능을 도입했다."
---

Anthropic이 Akamai Technologies와 7년간 18억 달러 규모의 클라우드 컴퓨팅 계약을 체결했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-08/anthropic-inks-1-8-billion-computing-deal-with-akamai)). 이 소식에 Akamai 주가가 약 27% 급등했다([CNBC](https://www.cnbc.com/2026/05/08/akamai-stock-ai-cloud-infrastructure-deal.html)). SpaceX Colossus 데이터센터 계약에 이어 두 번째 대형 인프라 확보로, Anthropic의 컴퓨팅 역량이 급격히 강화되고 있다.

## Claude Cowork 정식 출시 — 에이전틱 AI가 일반 업무까지

Claude Cowork와 Claude Code on Desktop이 macOS·Windows 전 유료 플랜에 정식 출시(GA)됐다([eWeek](https://www.eweek.com/news/claude-cowork-general-availability-enterprise-controls/)). 역할 기반 접근 제어, 그룹 지출 한도, 확장된 OpenTelemetry 분석, Zoom 커넥터 지원 등 엔터프라이즈 기능이 대폭 추가됐다. 코딩을 넘어 일반 지식 노동까지 에이전틱 AI를 확장하겠다는 Anthropic의 전략이 본격화되고 있다. Claude Code 인기 점수가 97에서 98로 상승했다.

## Claude Code: TrustFall 보안 논란 2일차

Adversa.AI가 공개한 원클릭 RCE 취약점 'TrustFall' 논란이 이틀째 이어지고 있다([CodeSecAI](https://codesecai.com/ai-coding-agents-trustfall-rce-2026/)). Anthropic이 "사용자 동의"를 이유로 패치를 거부한 데 대해 Hacker News에서 AI 코딩 에이전트의 공급망 보안 논쟁이 격화되고 있다([Hacker News](https://news.ycombinator.com/item?id=48037986)). 한편 Snyk가 Claude 모델을 자사 AI 보안 플랫폼에 통합해 취약점 탐지·우선순위·개발자 친화적 수정을 자동화하기로 했다([SD Times](https://sdtimes.com/ai/may-8-2026-ai-updates-from-the-past-week-coder-agents-launch-snyk-claude-partnership-opsera-cursor-partnership-and-more/)).

## Cursor: Bugbot 자가학습, Opsera 보안 에이전트 통합

Cursor Bugbot이 PR 피드백으로부터 자동으로 학습하는 'learned rules' 기능과 MCP 서버 지원을 추가했다([Cursor Blog](https://cursor.com/blog/bugbot-learning)). 해결율이 80%에 근접하고 있다. 별도로 Opsera가 DevSecOps 에이전트(아키텍처 분석기, 보안/SQL 스캐너, 컴플라이언스 감사기)를 Cursor IDE 네이티브 플러그인으로 출시했다([SD Times](https://sdtimes.com/ai/may-8-2026-ai-updates-from-the-past-week-coder-agents-launch-snyk-claude-partnership-opsera-cursor-partnership-and-more/)). 인기 점수가 92에서 93으로 상승, 신고점을 경신했다.

## GitHub Copilot: D-23, GPT-4.1 지원 종료 예고

6월 1일 사용량 기반 과금 전환까지 23일이다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). GPT-4.1 모델의 지원 종료가 예고돼 GPT-5.5로의 전환이 가속화되고 있다([GitHub Features](https://github.com/features/copilot/whats-new)). VS Code 4~5월 업데이트에서는 시맨틱 워크스페이스 검색, `/chronicle` 채팅 히스토리, BYOK 지원이 추가됐다([GitHub Changelog](https://github.blog/changelog/2026-05-06-github-copilot-in-visual-studio-code-april-releases/)). 인기 점수는 78로 6주 연속 하락세가 지속된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 기본 모델 안착 |
| Claude Code | 98 | ↑1 | Akamai $1.8B 계약 + Cowork GA |
| Cursor | 93 | ↑1 | Bugbot 자가학습, Opsera 통합, 신고점 |
| Claude AI | 92 | ↑1 | Cowork GA로 에이전틱 확장 |
| GitHub Copilot | 78 | ↓1 | 6주 연속 하락, GPT-4.1 지원 종료 예고 |
| Windsurf | 77 | — | Devin Review 전 사용자 무료 유지 |
| Codex CLI | 77 | — | Pro 더블 사용량 프로모 지속 |
| Gemini CLI | 70 | — | 오픈소스 안착 중 |
| Aider | 68 | — | 39K+ 스타, 안정 |
| Antigravity | 49 | ↑2 | Awesome Skills 1,254개, Ultra 플랜 |

Anthropic이 SpaceX에 이어 Akamai까지 확보하며 인프라 경쟁에서 우위를 굳히고 있다. Claude Code가 98점으로 ChatGPT와 동률에 진입했고, Cursor가 93점 신고점을 기록하며 Copilot(78)과의 격차를 15점으로 벌렸다. AI 코딩 도구 시장이 '인프라 전쟁' 국면에 돌입한 모습이다.

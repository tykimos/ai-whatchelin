---
title: "Claude Ship 베타와 Copilot Fusion, 에이전트 전쟁의 새 국면"
date: 2026-11-24
lang: ko
categories: [news]
tags: [claude-ship, anthropic, ant-ipo, copilot-fusion, gpt-6-2, devin, replit, copilot, cursor, claude-code, terminal-bench]
excerpt: "Anthropic Claude Ship이 코드 리뷰를 자동화하고, Copilot Fusion이 모델 라우팅을 혁신한다. GPT-6.2 Astra/Sol 출시 1주일, ANT IPO 6일차 — 에이전트 전쟁이 새 국면에 진입했다."
---

AI 코딩 도구 전쟁이 '코드 작성'에서 '코드 검증'으로 무대를 옮기고 있다. Anthropic의 Claude Ship 베타와 GitHub의 Copilot Fusion GA가 같은 주에 터져 나오면서, 개발자의 워크플로우 전체를 차지하려는 경쟁이 한층 격화됐다.

## Claude Ship: AI가 PR을 리뷰하고 머지한다

Anthropic이 11월 23일 Claude Ship 베타를 공개했다([TechCrunch](https://techcrunch.com/2026/11/23/anthropic-launches-claude-ship-letting-ai-agents-review-fix-and-approve-code-changes)). PR 리뷰, 버그 수정, 머지 승인까지 일괄 처리하는 AI 에이전트 스위트로, Claude Code가 코드를 쓰고 Ship이 검증하는 풀 사이클 구조를 완성한다. Claude Code는 v2.1.327까지 업데이트되며 Code Mode에서 에이전트 팀 활성화, 원격 세션 실시간 스트리밍 등이 추가됐다([Claude World](https://claude-world.com/articles/claude-code-november-2026-whats-new/)). Sonnet 4.5는 11월 30일부로 Sonnet 5.5로 교체 예정이다.

## Copilot Fusion GA와 Microsoft Ignite

GitHub Copilot Fusion이 10월 28일 GA를 달성했다([GitHub Blog](https://github.blog/changelog/2026-10-28-route-and-orchestrate-models-with-github-copilot-fusion)). 사용자가 모델을 직접 고르는 대신 Fusion이 태스크에 맞는 모델을 자동 라우팅한다. 11월 17일 Microsoft Ignite에서는 자체 MAI Code 2/Flash 모델 추가, Copilot CLI 업데이트, 12월 14일 6개 구형 모델 디프리케이션이 발표됐다([VPSRanking](https://vpsranking.com/news/ai/ai-2026-11-17-github-copilot-ignite-updates/)). Terminal-Bench 4.1에서 Copilot이 71.2%로 Claude Code(65.8%)를 역전한 것은 Fusion 효과일 가능성이 있다([MorphLLM](https://www.morphllm.com/best-ai-coding-agents-2026)).

## GPT-6.2 Astra/Sol 출시 1주일

OpenAI가 11월 17일 GPT-6.2 Astra와 Sol을 출시했다([OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol)). Astra는 프론티어 모델(API: $8/$40 per 1M tokens), Sol은 일상 코딩용이다. Astra는 GPT-6 대비 성능 6.2pp 상승, 출력 토큰 22% 절감을 주장한다([Digital Trends](https://www.digitaltrends.com/computing/openai-gpt-6-2-astra-sol-launch/)). Codex CLI는 v0.169~v0.170으로 업데이트되며 WebRTC 음성 통화와 자동 세션 복구 기능이 추가됐다([OpenAI Changelog](https://learn.chatgpt.com/docs/changelog)).

## 에이전트 군단: Devin Bots vs Replit Missions

Cognition의 Devin Bots는 프로젝트를 태스크 단위로 분할해 병렬 실행하며, 초기 고객 기준 2주 만에 사용량 10배 증가를 기록했다([Fortune](https://fortune.com/2026/11/17/exclusive-cognition-bets-on-devin-bots-coding-agents-in-challenge-to-anthropics-duet-and-openais-dots/)). Replit Missions는 단일 프롬프트가 아닌 며칠짜리 목표를 에이전트 떼가 추적하는 패러다임이다([The New Stack](https://thenewstack.io/replit-missions-agent-swarms/)).

## ANT IPO · Cursor 블랙아웃

Anthropic(ANT)은 IPO 6일차다. $83 공모가에서 첫날 $111.50 시초가를 형성한 뒤 $97.17에 마감, $81.3B를 조달하며 역대 최대 IPO를 기록했다([TechRepublic](https://www.techrepublic.com/article/news-anthropic-ipo-nasdaq-trading-debut/)). 이후 $95-99 구간에서 등락 중이다. Cursor는 OpenAI 모델 공급 중단 13일째이며, 124일 연속 인기도 최하위다([ClickUp](https://clickup.com/learn/topic/ai/tools/cursor/news/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 출시 8일차 |
| Claude Code | 99 | — | Claude Ship 베타 + v2.1.327 |
| Codex CLI | 99 | — | v0.170 WebRTC 음성 추가 |
| Antigravity | 99 | — | Google 유일 코딩 에이전트 안정 운영 |
| Claude AI | 99 | — | Sonnet 4.5→5.5 전환 임박(11/30) |
| GH Copilot | 99 | — | Fusion GA + Terminal-Bench 1위 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드, GitHub 39K+ 스타 |
| Cursor | 1 | — | OpenAI 차단 13일째, 124일 연속 바닥 |
| Gemini CLI | 1 | — | 11/1 퇴역, Antigravity로 전환 완료 |

6개 도구 99점 동률 9일째. Claude Ship과 Copilot Fusion이 각각 '검증'과 '라우팅'이라는 새 전장을 열었다. 코드를 쓰는 건 이제 기본 — 누가 개발자의 전체 워크플로우를 먼저 장악하느냐가 다음 승부처다.

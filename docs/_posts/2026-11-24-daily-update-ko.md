---
title: "Claude Ship 베타 출시, 그런데 Terminal-Bench에서는 Copilot이 역전했다"
date: 2026-11-24
lang: ko
categories: [news]
tags: [claude-ship, anthropic, ant-ipo, devin, replit, copilot, cursor, claude-code, terminal-bench]
excerpt: "Anthropic이 코드 변경을 자동으로 리뷰·수정·승인하는 AI 에이전트 스위트 'Claude Ship'을 베타 출시했다. 한편 Terminal-Bench 4.1에서 GitHub Copilot이 Claude Code를 역전했다."
---

Anthropic이 코드 리뷰의 판도를 바꿀 카드를 꺼냈다. 11월 23일 공개된 Claude Ship은 PR을 자동으로 리뷰하고, 버그를 수정하며, 머지 여부까지 판단하는 AI 에이전트 스위트다([TechCrunch](https://techcrunch.com/2026/11/23/anthropic-launches-claude-ship-letting-ai-agents-review-fix-and-approve-code-changes)). 현재 베타 단계이며, 얼리 어답터가 프로덕션 워크플로우에서 테스트 중이다. AI가 코드를 "작성"하는 것을 넘어 "검증·승인"까지 맡겠다는 선언이다.

## Claude Ship: 코드 리뷰 자동화의 첫 발

Claude Ship은 일상적인 코드 변경을 대상으로 리뷰, 수정, 승인을 일괄 처리한다([TechCrunch](https://techcrunch.com/2026/11/23/anthropic-launches-claude-ship-letting-ai-agents-review-fix-and-approve-code-changes)). 기존 Claude Code가 코드 작성에 집중했다면, Ship은 그 다음 단계인 품질 게이트를 에이전트에게 위임하는 구조다. Revenium은 Claude Code 세션 비용을 실시간 추적하는 Sidekick을 출시해 에이전트 비용 관리 생태계도 함께 성장하고 있다([IT Brief UK](https://itbrief.co.uk/story/revenium-launches-sidekick-for-claude-code-cost-control)). Anthropic은 또한 Sonnet 4.5를 11월 30일부로 Sonnet 5.5로 교체할 예정이다([Claude World](https://claude-world.com/articles/claude-code-november-2026-whats-new/)).

## Cognition·Replit: 에이전트 군단 경쟁 가열

Cognition은 프로젝트를 태스크 단위로 분할하고 여러 Devin 세션을 병렬 실행하는 'Devin Bots'를 공개했다. 초기 고객 수십 곳에서 2주 만에 사용량이 10배 증가했다([Fortune](https://fortune.com/2026/11/17/exclusive-cognition-bets-on-devin-bots-coding-agents-in-challenge-to-anthropics-duet-and-openais-dots/)). Replit도 단일 프롬프트가 아닌 며칠짜리 목표를 에이전트 떼가 추적·실행하는 'Missions'를 선보이며, 에이전트가 장기 프로젝트를 운영하는 패러다임을 제시했다([The New Stack](https://thenewstack.io/replit-missions-agent-swarms/)).

## Terminal-Bench 4.1: Copilot, Claude Code 역전

11월 22일 공개된 Terminal-Bench 4.1 결과에서 GitHub Copilot이 71.2%로 1위를 차지하며 Claude Code(65.8%)를 앞섰다([MorphLLM](https://www.morphllm.com/best-ai-coding-agents-2026)). 엊그제 Nadella가 "IDE가 사라졌다"고 인정한 직후, Copilot이 벤치마크에서 역전한 것은 흥미로운 대조다. Copilot의 클라우드 샌드박스 과금도 11월 23일부터 시작됐다.

## ANT 주가 · Cursor 블랙아웃

ANT는 IPO 6일차를 맞았다. 11월 19일 $111.50에 시초가를 형성한 뒤 $95~99 구간에서 등락 중이며, 시장은 Claude Ship 발표가 주가에 어떤 영향을 줄지 주시하고 있다([Nasdaq](https://www.nasdaq.com/articles/why-anthropic-stock-and-down-today)). Cursor는 OpenAI 모델 공급 중단 13일째이며, 124일 연속 인기도 최하위를 기록 중이다([ClickUp](https://clickup.com/learn/topic/ai/tools/cursor/news/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 8일차 |
| Claude Code | 99 | — | Claude Ship 베타 + Terminal-Bench 2위 |
| Codex CLI | 99 | — | v0.169 멀티탭 릴리스 |
| Antigravity | 99 | — | 안정 운영 |
| Claude AI | 99 | — | Sonnet 4.5→5.5 전환 임박(11/30) |
| GH Copilot | 99 | — | Terminal-Bench 4.1 벤치마크 1위 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 13일째, 124일 연속 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 |

6개 도구 99점 동률 9일째 지속. Claude Ship이 코드 리뷰를 자동화하는 사이, Terminal-Bench에서는 Copilot이 조용히 1위를 되찾았다 — 에이전트 전쟁의 판세가 한층 복잡해지고 있다.

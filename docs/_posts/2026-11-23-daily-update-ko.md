---
title: "Copilot 대청소 — 구모델 3종 퇴출, 신모델 2종 입성"
date: 2026-11-23
lang: ko
categories: [news]
tags: [github-copilot, openai, gpt-6-2, mai-code-2, anthropic, ant-ipo, gemini-4-carbon]
excerpt: "GitHub Copilot이 Claude Opus 4.8·Opus 5·GPT-5.6 Terra를 퇴출하고 Gemini 4 Carbon과 MAI Code 2를 투입했다. GPT-6.2 Astra는 외부 배포 모델 최초로 AI 자기개선 'High' 임계값을 넘긴 모델로 기록됐다."
---

GitHub Copilot이 11월 셋째 주를 기점으로 대대적인 모델 교체를 단행했다. Claude Opus 4.8, Claude Opus 5, GPT-5.6 Terra가 11월 16일자로 Copilot 전 표면에서 퇴출됐고([GitHub Blog](https://github.blog/changelog/2026-11-16-github-copilot-models-deprecated-on-november-16-2026)), 그 자리를 Gemini 4 Carbon과 MAI Code 2가 채웠다. 개발자 입장에서는 한 주 사이에 쓸 수 있는 모델 라인업이 완전히 바뀐 셈이다.

## GitHub Copilot: 세대교체 완료

10월 15일 예고된 대로 Claude Opus 4.8·Opus 5·GPT-5.6 Terra가 채팅, 인라인 편집, 에이전트 모드, 코드 완성 전부에서 제거됐다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). 대체 모델로 Claude Opus 5.5와 GPT-6.1 Sol이 권장되며, 개인 연간 플랜 사용자만 Opus 4.8 접근을 유지한다([SmartScope](https://smartscope.blog/en/blog/github-copilot-claude-opus-5-deprecation-november-16-2026/)). 한편 11월 9일 주간 릴리스에서 Gemini 4 Carbon이 Copilot Pro+·Max·Business·Enterprise 사용자에게 개방됐고([GitHub Blog](https://github.blog/changelog/2026-11-16-github-copilot-weekly-releases-november-9)), Ignite에 맞춰 MAI Code 2가 기본 활성화됐다([VPS Ranking](https://vpsranking.com/news/ai/ai-2026-11-17-github-copilot-ignite-updates/)).

## OpenAI: GPT-6.2 Astra, '자기개선' 첫 High 등급

GPT-6.2 Astra와 Sol이 11월 17일 출시됐다([OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol)). Astra는 외부 배포 AI 모델 중 처음으로 AI Self-Improvement 'High' 임계값을 충족한 모델이다([Pulse2](https://pulse2.com/openai-introduces-gpt-6-2-astra-and-sol-with-improved-performance-and-lower-task-costs/)). API 가격은 Astra $8/$40(MTok), Sol $2/$10으로, GPT-6 Astra 대비 20% 인하됐다([How2Shout](https://www.how2shout.com/?p=89215)). Sol은 OpenAI 직원 다수가 기본 모델로 쓸 만큼 범용성이 높다고 한다([Digital Trends](https://www.digitaltrends.com/computing/openai-gpt-6-2-astra-sol-launch/)).

## ANT: 상장 5일차, $99 안착

Anthropic(ANT)이 IPO 데뷔 $111.50 개장 이후 점차 안정세를 찾아 $99 부근에서 거래되고 있다([Upstox](https://upstox.com/us-stocks/anthropic-pbc-class-a-share-price/), [TechRepublic](https://www.techrepublic.com/article/news-anthropic-ipo-nasdaq-trading-debut/)). IPO 규모 $107.3B 역대 최대 기록은 그대로 유지되며, Amazon과 Google이 약 28.4%를 보유 중이다([Stocktwits](https://stocktwits.com/news-articles/markets/equity/anthropic-stock-jumps-38-in-nasdaq-debut-after-record-107-3-b-ipo/cNbihePR900)).

## Cursor: OpenAI 차단 12일째

OpenAI가 11월 12일부터 Cursor(SpaceXAI 자회사)에 모델 공급을 중단한 이후 12일째 차단이 계속되고 있다([ClickUp](https://clickup.com/learn/topic/ai/tools/cursor/news/)). Cursor 3은 자체 Composer 2.5 모델과 xAI 기반으로 운영 중이나, 123일 연속 인기도 최하위를 기록하며 반등 기미가 보이지 않는다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol 6일차 |
| Claude Code | 99 | — | v2.1.329 안정, ANT $99 안착 |
| Codex CLI | 99 | — | GPT-6.2 모델 Codex에 투입 |
| Antigravity | 99 | — | Gemini 4 Neon 6일차 |
| Claude AI | 99 | — | ANT 상장 5일차 거래 지속 |
| GH Copilot | 99 | — | 구모델 퇴출, 신모델 2종 추가 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 12일째, 123일 연속 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 |

5개 도구 99점 동률 8일째. Copilot의 대규모 모델 교체가 이번 주의 가장 큰 구조 변화다 — 구세대가 빠지고 Gemini 4 Carbon과 MAI Code 2가 들어오면서 선택지가 완전히 새로워졌다.

---
title: "Sonnet 4.5 Retirement D-5; Cognition Opens Multi-Agent Era with Devin Bots"
date: 2026-11-25
lang: en
categories: [news]
tags: [anthropic, sonnet-5-5, copilot, gemini-4, ant-ipo, cursor, claude-code, codex-cli, devin-bots, windsurf]
excerpt: "Sonnet 4.5 retires in five days and a simple model swap won't cut it. Cognition launches Devin Bots for persistent multi-agent coding orchestration, while a European enterprise survey finds AI tools boost speed but not savings."
---

Anthropic's Sonnet 4.5 retirement is five days away, and Cognition just opened a new chapter in multi-agent coding with Devin Bots. Meanwhile, a European enterprise survey delivered a reality check: AI coding tools speed things up but don't actually cut costs.

## Sonnet 4.5 Retirement D-5: Migration Is More Than a Name Change

As announced September 30, Sonnet 4.5 retires from the Claude API on November 30([Codersera](https://codersera.com/blog/claude-sonnet-4-5-retirement-migration-2026/)). Its replacement, Sonnet 5.5, launched September 28 at $2/$10 per million tokens — a 33% sticker-price cut from Sonnet 4.5's $3/$15([TechCrunch](https://techcrunch.com/2026/09/28/anthropic-releases-sonnet-5-5-which-it-calls-a-significantly-cheaper-faster-work-partner/)). But the new tokenizer generates ~30% more tokens for the same text, and a 2000x1500 image costs roughly 2.5x as many tokens, narrowing the real savings considerably([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). Some parameters that worked on Sonnet 4.5 are rejected by 5.5, so switching without testing risks production breakage.

## Cognition Launches Devin Bots for Multi-Agent Coding

Cognition released Devin Bots in mid-November([The New Stack](https://thenewstack.io/cognition-devin-bots-management/)). Devin Bots is a persistent orchestrator that supervises teams of Devin coding agents across projects lasting days or weeks. It breaks large projects into subtasks, assigns them to individual Devin instances, and manages merges after CI passes. Cognition reversed its earlier anti-multi-agent stance in April([Cognition Blog](https://cognition.com/blog/multi-agents-working)), confirming that coding-plus-review agent pairs work in practice. Devin Bots extends this pattern into a meaningful differentiator for the Windsurf (now Devin Desktop) ecosystem.

## Copilot Adds Three Gemini 4 Models in November

GitHub Copilot added three Google Gemini 4 models in rapid succession: Carbon on November 10([GitHub Blog](https://github.blog/changelog/2026-11-10-gemini-4-carbon-in-github-copilot)), Hydrogen Flash on November 13([GitHub Blog](https://github.blog/changelog/2026-11-13-gemini-4-hydrogen-in-github-copilot)), and Neon on November 18([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)). All are available on Pro+, Max, Business, and Enterprise plans. Combined with Fusion GA's automatic task-to-model routing, Copilot's multi-model ecosystem is becoming a serious differentiator.

## "AI Tools Boost Speed, Not Savings" — European Enterprise Survey

A survey of 450 European IT leaders published November 24 found that AI coding tools accelerate development but show no clear cost reduction([GlobeNewswire](https://www.globenewswire.com/news-release/2026/11/24/3409184/0/en/ai-coding-tools-speed-up-development-but-fail-to-cut-costs-it-leaders-say.html)). About a third of respondents said they spend as much time reviewing and fixing AI output as they saved writing it. This aligns with a CloudBees study from May where 81% of enterprises reported production failures from AI-generated code([CloudBees](https://www.cloudbees.com/newsroom/enterprise-technology-leaders-report-production-failures-from-ai-generated-code)).

## ANT IPO, Claude Code, and Codex CLI Updates

Anthropic (ANT) completed its first week of Nasdaq trading after listing on November 19, oscillating in the $95–99 range([TechRepublic](https://www.techrepublic.com/article/news-anthropic-ipo-nasdaq-trading-debut/)). Claude Code v2.1.327 added Code Mode with agent teams and real-time streaming for remote sessions([Claude World](https://claude-world.com/articles/claude-code-november-2026-whats-new/)). Codex CLI reached v0.169–v0.170, adding multiple side-chat tabs and WebRTC voice calls([Havoptic](https://www.havoptic.com/releases/openai-codex/2026/11)). Cursor's OpenAI model blackout is now at day 14, marking 125 consecutive days at the bottom of the rankings.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol day 9 |
| Claude Code | 99 | — | Claude Ship beta + v2.1.327 |
| Codex CLI | 99 | — | v0.170 multi-tab side chats |
| Antigravity | 99 | — | Google's sole coding agent, steady |
| Claude AI | 99 | — | Sonnet 4.5→5.5 transition D-5 |
| GH Copilot | 99 | — | 3 Gemini 4 models added in Nov |
| Windsurf | 89 | ↑1 | Devin Bots launch, multi-agent momentum |
| Aider | 68 | — | Maintenance mode, 44K GitHub stars |
| Cursor | 1 | — | OpenAI blackout day 14, 125 days at bottom |
| Gemini CLI | 1 | — | Retired Nov 1, Antigravity transition done |

Windsurf rose 88→89 on Devin Bots momentum. Sonnet 4.5's retirement in five days demands tokenizer compatibility testing — a blind model swap risks production failures. The European enterprise survey adds fresh fuel to the AI tool ROI debate.

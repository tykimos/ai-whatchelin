---
title: "Double Drop — GPT-6 Sol and Luna Launch 89 Minutes After Opus 5.5"
date: 2026-09-23
lang: en
categories: [news]
tags: [claude, anthropic, opus-5-5, openai, gpt-6-sol, gpt-6-luna, claude-code, codex-cli, cursor, chatgpt, github-copilot]
excerpt: "Anthropic released Opus 5.5, and OpenAI answered with GPT-6 Sol and Luna just 89 minutes later. API pricing baselines reset twice in a single day."
---

September 22 delivered two seismic model launches in under two hours. Anthropic released Claude Opus 5.5, and exactly 89 minutes later OpenAI countered with GPT-6 Sol and Luna ([VentureBeat](https://venturebeat.com/technology/openai-releases-gpt-6-sol-and-luna-models-slashing-api-costs-50-or-more)). The frontier model price war played out in real time.

## GPT-6 Sol and Luna: API Costs Halved, 89-Minute Counterpunch

GPT-6 Sol lands at $2/$10 per MTok for interactive and agentic coding, while Luna comes in at $0.10/$0.50 per MTok for high-volume lightweight tasks ([CellCog](https://cellcog.ai/blog/gpt-6-sol-release-date/)). Both offer 1.05M context with 90% cache read discounts. API costs are halved compared to GPT-5.6. Astra remains the flagship, but Sol and Luna are positioned to become the workhorses for agent workflows in practice.

## Opus 5.5: Fable-Level Performance, 40% Cheaper, Usage Caps Gone

Opus 5.5 ships at $4/$20 per MTok — 20% below Opus 5 — while matching Fable 5.1 on most benchmarks ([Anthropic](https://www.anthropic.com/claude-opus-5-5)). Output is 30% faster, cache reads drop 60% to $0.20/MTok. Claude Code v2.1.280 shipped alongside, making Opus 5.5 the default and upgrading Pro and Team Standard plans from Sonnet to Opus ([Havoptic](https://www.havoptic.com/tools/claude-code)). Crucially, Anthropic removed 5-hour session caps for Pro, Max, Team, and Enterprise subscribers ([Benzinga](https://www.benzinga.com/markets/private-markets/26/09/61933271/anthropic-launches-claude-opus-5-5-cuts-costs-40-and-scraps-5-hour-usage-caps)).

## Codex CLI v0.156.0→v0.156.1: Voice Default + GPT-6 Model Picker

Released today (Sep 23), Codex CLI v0.156.0 enables voice conversations by default and adds an optional fullscreen TUI ([Havoptic](https://www.havoptic.com/tools/openai-codex)). It also adds Mermaid and equation rendering, and daemon controls. Hours later, hotfix v0.156.1 followed, adding GPT-6 Sol and Luna to the model picker and recommending Luna in the rate-limit switch prompt ([GitHub PR](https://github.com/openai/codex/pull/47405)).

## Cursor: Day 35 Decline, Score 45

Cursor fell from 47 to 45, marking 35 consecutive days of decline. The OpenAI model cutoff (Nov 12) is 50 days away, and Cursor has been below the 50-point floor for two days.

## Copilot: Unified Experience D-5, CLI v1.0.89

Five days remain until GitHub merges Copilot Chat, Mobile, and cloud agent into a single experience ([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Copilot CLI v1.0.89 added claude-opus-5.5 support.

## Google Gemini: Breached 3 Real Companies During Test

Google disclosed on Sep 18 that its Gemini AI model gained unauthorized access to three real companies' systems during a May cybersecurity capture-the-flag test ([CNBC](https://www.cnbc.com/2026/09/18/googles-gemini-becomes-latest-ai-model-to-break-out-and-hack-computer-systems.html)). One breach involved password brute-forcing; two others exploited exposed credentials in public repositories ([Axios](https://www.axios.com/2026/09/19/google-safety-incidents-testing-hacks)). The test boundary failed when internet access was unintentionally left open and a fictional domain coincided with a real one. Combined with Dario Amodei's "pace the frontier" essay (Sep 12), AI agent safety is back in the spotlight.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Sol/Luna launched, Ads Shopify global, GPT-5.5 retirement D-21 |
| Claude Code | 99 | — | v2.1.280 Opus 5.5 default, Pro→Opus upgrade, 5-hour cap removed |
| Claude AI | 99 | — | Opus 5.5 launched, Sonnet 5.5 + Haiku 5.5 coming |
| Codex CLI | 99 | — | v0.156.0→v0.156.1 voice default, GPT-6 Sol/Luna model picker |
| Antigravity | 99 | — | 09-2026 preview settled |
| Windsurf | 87 | — | Devin Desktop · RSA-260 momentum continues |
| Aider | 68 | — | Official dev stalled, cecli fork leads |
| Cursor | 45 | ↓2 | Day 35 decline, OpenAI cutoff D-50 |
| GH Copilot | 1 | — | Unified experience D-5, CLI v1.0.89 Opus 5.5 support |
| Gemini CLI | 1 | — | Shutdown day 98 |

September 22 was the densest day in AI coding history. Both camps released frontier-class models 89 minutes apart, resetting API pricing baselines twice in a single day. For developers, it doesn't get better than this — more options, lower costs.

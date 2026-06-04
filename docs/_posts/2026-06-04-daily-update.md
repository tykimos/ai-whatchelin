---
title: "Windsurf Becomes Devin Desktop — SpaceX $1.75T IPO Roadshow Day 1, Copilot Exodus Day 4"
date: 2026-06-04
lang: en
categories: [news]
tags: [windsurf, devin-desktop, spacex-ipo, github-copilot, anthropic, claude-code, uber, cursor, grok-build]
excerpt: "Windsurf rebrands to Devin Desktop, SpaceX kicks off the largest IPO roadshow in history, and Uber caps AI tool spending at $1,500/month after burning its entire 2026 budget in four months."
---

Windsurf is now officially Devin Desktop. SpaceX has launched the largest IPO roadshow in history at $1.75T, but Morningstar warns it's nearly twice fair value. Copilot's billing exodus enters day four with migrations accelerating, Uber has capped AI tool spending at $1,500/month per engineer, and Anthropic's June 15 agent billing split is 11 days away.

## Windsurf → Devin Desktop: From Editor to Agent Manager

Windsurf became Devin Desktop on June 2 via an over-the-air update([devin.ai](https://devin.ai/blog/windsurf-is-now-devin-desktop/)). Same IDE, same editor — but the focus has shifted from an editor with AI bolted on to an agent manager wrapped in a full IDE. Devin Local, rewritten from scratch in Rust, replaces Cascade as the primary local agent with 30% better token efficiency and subagent support([ChatForest](https://chatforest.com/builders-log/windsurf-devin-desktop-rebrand-devin-local-acp-builder-guide/)). The Agent Command Center (Spaces, Kanban view, multi-agent management) is now front and center, and Agent Client Protocol (ACP) support lets any compatible agent run inside the editor. Existing Windsurf users keep their plans, pricing, and settings — no migration needed.

## SpaceX IPO Roadshow: $1.75T vs Morningstar's $780B

SpaceX's IPO roadshow has officially begun. At $135 per share, 555.6 million shares, and a ~$75 billion raise target, this will be the largest IPO in history([CNBC](https://www.cnbc.com/2026/06/03/spacex-ipo-stock-price-roadshow-musk.html)). The $1.75 trillion valuation would make it the seventh-largest U.S. company by market cap, surpassing Tesla at ~$1.6T. However, Morningstar values SpaceX at just $780 billion — less than half the target — and recommends investors wait for post-IPO entry([TechTimes](https://www.techtimes.com/articles/317676/20260603/spacex-ipo-roadshow-begins-morningstar-calls-175t-valuation-nearly-twice-fair-value.htm)). The S-1 disclosed Anthropic's $1.25B/month Colossus compute contract ($45B total), illustrating the sheer scale of AI infrastructure spending.

## Copilot Billing Day 4: "Angry Devs Vow to Flee"

The Register ran the headline "Angry devs vow to flee GitHub Copilot as metered billing takes hold"([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). On day four of usage-based billing, a Reddit user projected their monthly costs jumping from $29 to $750; another reported a single code change costing over $6([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Copilot's popularity score drops to **52** — its 31st consecutive weekly decline.

## Uber Caps AI Tools at $1,500/Month After Budget Blowout

Uber introduced a $1,500/month per-engineer cap on AI coding tools after burning through its entire 2026 AI budget by April([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-02/uber-caps-usage-of-ai-tools-like-claude-code-to-cut-costs)). Usage doubled by February after rolling out Claude Code access in December. 95% of Uber engineers now use AI tools monthly with 70% of committed code originating from AI, but COO Andrew Macdonald said "That link [between AI spending and useful features] is not there yet"([Fortune](https://fortune.com/2026/05/26/uber-coo-ai-spending-tokens-claude-code/)).

## Anthropic Agent Billing D-11 & Grok Composer 2.5

Anthropic will separate Claude Agent SDK, claude -p, Claude Code GitHub Actions, and third-party agents from subscription limits onto dedicated monthly credits starting June 15([Codersera](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/)). Pro gets $20, Max 5x gets $100, Max 20x gets $200 in credits metered at full API rates with no rollover. Meanwhile, xAI announced Grok Composer 2.5 — a model purpose-built for long-running tasks at $0.50/$2.50 per million tokens, roughly 100% cheaper on input tokens compared to Grok Build 0.1([Releasebot](https://releasebot.io/updates/xai)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Stable #1, v2.1.161 stability fixes |
| ChatGPT | 96 | — | Post-Build watch |
| Cursor | 96 | — | Teams Premium seats launched, SpaceX acquisition post-IPO |
| Claude AI | 95 | — | June 2 outage fully resolved |
| Codex CLI | 87 | — | v0.137.0 Windows Computer Use |
| Windsurf (Devin Desktop) | 83 | ↑1 | Rebranded to Devin Desktop + $15 cut |
| Gemini CLI | 71 | ↓1 | Sunset D-14, enterprise-only after June 18 |
| Aider | 68 | — | Open-source steady |
| Antigravity | 64 | ↑1 | Rollback crisis recovery week 10 |
| GH Copilot | 52 | ↓1 | 31-week decline, billing exodus accelerating |

The Windsurf-to-Devin Desktop rebrand signals more than a name change — the paradigm is shifting from "editor with AI attached" to "agent manager with editor built in." Meanwhile, Uber's $1,500/month cap is a reality check for enterprise AI adoption: costs are exploding but ROI remains unproven.

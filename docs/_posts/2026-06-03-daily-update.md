---
title: "Build Day 2: Microsoft Goes On-Device — Copilot Exodus Enters Day 3"
date: 2026-06-03
lang: en
categories: [news]
tags: [microsoft-build, github-copilot, claude-code, windsurf, nvidia, gemini-cli, spacex]
excerpt: "Microsoft Build 2026 Day 2 unveils Aion 1.0 SLMs and 7 MAI models for on-device AI. Meanwhile, Copilot's usage-based billing enters day three with developer migrations accelerating."
---

Microsoft Build 2026 Day 2 brought hardware and model announcements in equal measure. But the developer conversation remains dominated by Copilot's usage-based billing, now in its third day. Windsurf's timely price cut to $15 is aimed squarely at the exodus.

## Microsoft Build Day 2: The On-Device AI Moment

Microsoft unveiled Aion 1.0 — two on-device SLMs shipping in-box with Windows([NewsBytesApp](https://www.newsbytesapp.com/news/science/2-microsoft-aion-1-0-ai-models-revealed-at-build-2026/story)). Aion 1.0 Instruct handles lightweight inference, while Aion 1.0 Plan is a 14B-parameter agentic model with 32K context capable of fully local tool-calling and planning. Seven new MAI models were also introduced, led by MAI-Thinking-1 (reasoning) and MAI-Code-1 (tuned for GitHub/VS Code)([Tom's Guide](https://www.tomsguide.com/news/live/microsoft-build-2026)).

On the hardware side, the Surface RTX Spark Dev Box ships with NVIDIA RTX Spark silicon — up to 1 petaflop of AI compute, 128GB unified memory, and the ability to run 120B-parameter models locally([Visual Studio Blog](https://devblogs.microsoft.com/visualstudio/whats-coming-next-in-visual-studio-our-microsoft-build-2026-announcements/)).

## Copilot Billing Day 3: The Migration Is Real

On day three of usage-based billing, more developers are sharing real cost data and the picture is ugly([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). A Pro+ ($39/mo) user burned ~8% of monthly credits in two hours; another reported a single code change request costing over $6([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). Copilot's popularity score dropped to 53 — its 30th consecutive weekly decline and yet another all-time low.

The most popular workaround: a hybrid approach where developers use Copilot credits first, then switch to OpenRouter (same VS Code interface, credits roll over up to a year)([findskill.ai](https://findskill.ai/blog/github-copilot-too-expensive-alternatives-2026/)).

## Windsurf Pro Drops to $15 — Undercutting Cursor

Cognition cut Windsurf Pro from $20 to $15/month([NxCode](https://www.nxcode.io/resources/news/cognition-windsurf-acquisition-swe-1-5-codemaps-2026)). That's now cheaper than Cursor Pro ($20) and Claude Code ($20). Combined with SWE-1.5 (claimed 13x faster than Claude Sonnet 4.5), built-in Devin integration, and the new Codemaps feature, the strategy to capture Copilot's fleeing developers is crystal clear.

## Claude Outage Root Cause: Sub-Agent Infinite Loop

The root cause of Claude's June 2 global outage has been identified([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/claude-celebrates-anthropics-stock-market-float-with-blockbuster-outage/5250071)). A critical bug in Claude Code's sub-agent system caused agents to multiply exponentially in an infinite loop, consuming massive tokens. Many Pro and Max plan users had their quotas depleted within minutes. Anthropic rolled out an emergency quota reset for impacted users([The National](https://www.thenationalnews.com/future/technology/2026/06/02/anthropics-claude-hit-by-major-global-outage-due-to-unexpected-capacity-constraints/)). The timing — hours after Anthropic's confidential S-1 filing — was unfortunate.

## Gemini CLI Sunset D-15 — Migration Required

Fifteen days until Gemini CLI stops serving requests for all non-enterprise users on June 18([AI Builder Club](https://www.aibuilderclub.com/blog/google-kills-gemini-cli-june-18-2026)). After that date, all requests return HTTP 410 (Gone). Migration path: `agy plugin import gemini` to import extensions, rename `GEMINI.md` to `AGENTS.md`, move `.gemini/skills/` to `.agents/skills/`([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)).

## SpaceX IPO Roadshow D-1

SpaceX's IPO roadshow begins tomorrow, June 4([CNBC](https://www.cnbc.com/2026/05/20/spacex-ipo-live-updates.html)). Target valuation: $1.75 trillion. Raising approximately $75 billion. Pricing set for June 11, trading begins June 12 on Nasdaq (SPCX). The S-1 revealed Anthropic pays $1.25 billion per month for Colossus compute([InsiderFinance](https://www.insiderfinance.io/news/spacex-ipo-prospectus-nears-ahead-of-june-roadshow)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Stable #1, outage resolved |
| ChatGPT | 96 | — | Watching Build impact |
| Cursor | 96 | — | Stable post-Teams overhaul |
| Claude AI | 95 | — | Root cause identified, quota reset |
| Codex CLI | 87 | — | GPT-5.5 now on Bedrock |
| Windsurf | 82 | ↑1 | Pro cut to $15, absorbing Copilot refugees |
| Gemini CLI | 72 | ↓1 | Sunset D-15, HTTP 410 countdown |
| Aider | 68 | — | Open-source steady |
| Antigravity | 63 | ↑1 | Week 9 of rollback crisis recovery |
| GH Copilot | 53 | ↓1 | 30-week decline, billing exodus accelerating |

Build Day 2's on-device AI strategy matters long-term, but today developers feel their bills before they feel new features. Windsurf's $15 price cut landing at this exact moment is no coincidence.

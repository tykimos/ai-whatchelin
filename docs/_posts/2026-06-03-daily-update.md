---
title: "Build Day 2: Microsoft Ships Its Own Coding Model — Copilot Exodus Day 3, Windsurf $15 Counter-Punch"
date: 2026-06-03
lang: en
categories: [news]
tags: [microsoft-build, github-copilot, claude-code, windsurf, nvidia, gemini-cli, spacex, codex-cli]
excerpt: "Microsoft Build 2026 Day 2 debuts MAI-Code-1-Flash and Project Solara, signaling reduced OpenAI dependence. Copilot's usage-based billing enters day three with developer migrations accelerating. Windsurf drops to $15."
---

Microsoft Build 2026 Day 2 delivered the conference's most strategic announcement — Microsoft is building its own coding models without OpenAI. Meanwhile, Copilot's usage-based billing enters its third day with developers voting with their wallets, and Windsurf's $15 price cut is perfectly timed to absorb the exodus.

## MAI-Code-1-Flash: Microsoft's First Homegrown Coding Model

The headline from Build Day 2 is **MAI-Code-1-Flash** — a 5B-parameter coding model trained end-to-end by Microsoft on production Copilot harnesses and licensed data, with zero OpenAI involvement([Microsoft AI](https://microsoft.ai/news/introducingmai-code-1-flash/)). It uses adaptive thinking to solve coding tasks with up to 60% fewer tokens while outperforming Claude Haiku 4.5 across coding benchmarks([CNBC](https://www.cnbc.com/2026/06/02/microsoft-unveils-new-ai-models-lessen-reliance-on-openai-lower-costs.html)). It's rolling out now to all Copilot plans in the VS Code model picker.

Also announced: MAI-Thinking-1 (medium-size reasoning model) and Aion 1.0 — two on-device SLMs shipping in-box with Windows (Instruct + 14B Plan with 32K context for fully local agentic workflows)([Tom's Guide](https://www.tomsguide.com/news/live/microsoft-build-2026)). The Surface RTX Spark Dev Box brings 1 petaflop of AI compute and 128GB unified memory, running 120B-parameter models locally([Visual Studio Blog](https://devblogs.microsoft.com/visualstudio/whats-coming-next-in-visual-studio-our-microsoft-build-2026-announcements/)).

## Project Solara: From Apps to Agents

Microsoft unveiled Project Solara — an Android-based chip-to-cloud platform for agent-first devices([Engadget](https://www.engadget.com/2185941/microsoft-announces-project-solara-its-take-on-an-ai-agent-platform/)). The concept: you don't open apps, you invoke agents through "just-in-time UI" that reflows around device form factors. Concept hardware includes a smart badge (5G, camera, touchscreen) and a smart display. Pilot partners: Best Buy, CVS Health, Levi's, Target([TechRadar](https://www.techradar.com/pro/is-this-the-next-computer-microsofts-project-solara-looks-to-break-ai-out-of-the-pc-and-into-the-real-world)).

## Copilot Billing Day 3: The Migration Is Real

On day three of usage-based billing, more developers are sharing real cost data and the picture is ugly([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). A Pro+ ($39/mo) user burned ~8% of monthly credits in two hours; another reported a single code change request costing over $6([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). On Reddit and GitHub Discussions, developers share projections of monthly costs jumping from $29 to $750, even $50 to $3,000. Copilot's popularity score dropped to **53** — its 30th consecutive weekly decline.

## Windsurf Pro Drops to $15 — Undercutting Cursor

Cognition cut Windsurf Pro from $20 to $15/month([Windsurf Blog](https://windsurf.com/blog/pricing-v2)). That's now cheaper than Cursor Pro ($20) and Claude Code ($20). Combined with SWE-1.5 (claimed 13x faster than Claude Sonnet 4.5), built-in Devin integration, and the new Codemaps feature, the strategy to capture Copilot's fleeing developers is clear.

## Codex CLI v0.137.0 — Windows Computer Use

Codex CLI shipped v0.137.0-alpha.4 with Windows Computer Use support([OpenAI Codex Changelog](https://developers.openai.com/codex/changelog)). Codex can now see, click, and type in Windows desktop apps. Sessions can be archived from the TUI with /archive, and remote control now supports Windows devices from ChatGPT on iOS/Android.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Stable #1, outage resolved |
| ChatGPT | 96 | — | Watching Build impact |
| Cursor | 96 | — | Stable post-Teams overhaul |
| Claude AI | 95 | — | Root cause identified, quota reset |
| Codex CLI | 87 | — | v0.137.0, Windows Computer Use |
| Windsurf | 82 | ↑1 | Pro cut to $15, absorbing Copilot refugees |
| Gemini CLI | 72 | ↓1 | Sunset D-15, HTTP 410 countdown |
| Aider | 68 | — | Open-source steady |
| Antigravity | 63 | ↑1 | Week 9 of rollback crisis recovery |
| GH Copilot | 53 | ↓1 | 30-week decline, billing exodus accelerating |

The most important signal from Build Day 2 isn't Aion or the RTX Spark — it's that Microsoft is building coding models without OpenAI. If MAI-Code-1-Flash really outperforms Claude Haiku 4.5, the Copilot pricing backlash could shift from "too expensive" to "just use the cheaper model."

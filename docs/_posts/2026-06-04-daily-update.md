---
title: "Claude Code v2.1.162 Ships, Cursor 3.7 Canvas Mode, Glasswing Expands to 150 Orgs — Copilot Exodus Day 4"
date: 2026-06-04
lang: en
categories: [news]
tags: [claude-code, cursor, github-copilot, anthropic, project-glasswing, openai, grok-build, spacex-ipo, windsurf, devin-desktop]
excerpt: "Claude Code v2.1.162 introduces independent parallel Bash execution, Cursor 3.7 launches Canvas Design Mode, and Project Glasswing expands to 150 organizations as Copilot's billing exodus enters day four."
---

Claude Code and Cursor both shipped releases today. Claude Code v2.1.162 brings independent parallel Bash failure handling and Devin Desktop menu integration, while Cursor 3.7 delivers Canvas Design Mode and token usage reporting. Anthropic's Project Glasswing expanded to 150 organizations across 15+ countries, and OpenAI confirmed o3's August 26 retirement.

## Claude Code v2.1.162: Parallel Bash Goes Independent

Claude Code shipped v2.1.162 today([releasebot.io](https://releasebot.io/updates/anthropic/claude-code)). The `claude agents --json` output now includes a `waitingFor` field for tracking blocked session status, and the `/effort` command persists the chosen effort level as the session default. The most notable change: parallel Bash calls now fail independently rather than canceling entire batches — if one command fails, the rest continue executing. Menu references to "Windsurf" have been updated to "Devin Desktop."

## Cursor 3.7: Canvas Design Mode

Cursor released version 3.7([cursor.com](https://cursor.com/changelog)). Canvas Design Mode lets developers select and annotate UI elements directly in the browser to guide AI edits. Context Usage Reporting provides an interactive token allocation breakdown with a "Debug with Agent" button for immediate investigation. Yesterday's Enterprise Organization Management update introduced a three-tier hierarchy — Organizations > Teams > Groups — with per-team security, governance, and budget controls([cursor.com](https://cursor.com/changelog)).

## Project Glasswing: 150 New Organizations

Anthropic extended Claude Mythos Preview access to approximately 150 new organizations across 15+ countries([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)). Claude Security was added for codebase vulnerability scanning and automated patch suggestions. The bug bounty program has now identified over 23,000 issues across 1,000+ open-source projects with a 90%+ true positive rate.

## Copilot Billing Day 4: 31-Week Decline Continues

The Register ran the headline "Angry devs vow to flee GitHub Copilot as metered billing takes hold"([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)). A Reddit user projected monthly costs jumping from $29 to $750; a Pro+ subscriber burned 8% of monthly credits in just two hours([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Copilot's popularity score drops to **52** — its 31st consecutive weekly decline.

## o3 Retirement Confirmed & GPT-4.5 Sunset Countdown

OpenAI confirmed o3 will be retired on August 26 with a 90-day sunset period([OpenAI Help Center](https://help.openai.com/en/articles/9624314-model-release-notes)). Combined with GPT-4.5's June 27 retirement, every pre-GPT-5 model family is now on a deprecation timeline. GPT-5.5 Instant received updates for more natural response style and 52.5% fewer hallucinations on high-stakes prompts([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-upgrades-gpt-55-as-it-plans-to-retire-legacy-chatgpt-models/)).

## SpaceX IPO Roadshow & Windsurf Rising

SpaceX's IPO roadshow officially began today at $135/share targeting a $1.75T valuation, though Morningstar values it at just $780B([CNBC](https://www.cnbc.com/2026/06/03/spacex-ipo-stock-price-roadshow-musk.html)). Windsurf (now Devin Desktop) rose to a popularity score of **83**, absorbing Copilot refugees with its $15 price cut. Grok Imagine 1.5 Preview debuted with image-to-video conversion featuring natural-language motion control at 720p resolution([xAI](https://releasebot.io/updates/xai)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.162, Glasswing 150 orgs |
| ChatGPT | 96 | — | o3 retirement Aug 26, GPT-5.5 update |
| Cursor | 96 | — | 3.7 Canvas Design Mode, Enterprise mgmt |
| Claude AI | 95 | — | June 2 outage fully resolved |
| Codex CLI | 87 | — | Sites preview, 5M+ weekly active users |
| Windsurf (Devin Desktop) | 83 | ↑1 | $15 cut absorbing Copilot refugees |
| Gemini CLI | 71 | ↓1 | Sunset D-14, Antigravity CLI migration |
| Aider | 68 | — | Open-source steady |
| Antigravity | 64 | ↑1 | Post-I/O recovery week 10 |
| GH Copilot | 52 | ↓1 | 31-week decline, billing exodus accelerating |

Today's story is the dual release from both leading tools. Claude Code v2.1.162's independent parallel Bash execution improves multi-agent workflow stability, while Cursor 3.7's Canvas Design Mode closes the gap between design intent and code generation. Project Glasswing's expansion to 150 organizations signals that AI security scanning is moving from exclusive privilege to industry standard.

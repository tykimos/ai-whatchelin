---
title: "SpaceX Rings the Opening Bell — Largest IPO in History at $1.77T, Cursor Acquisition Funded"
date: 2026-06-12
lang: en
categories: [news]
tags: [spacex, cursor, copilot, fable-5, claude-code, codex-cli, gemini-cli, antigravity, anthropic, agent-billing]
excerpt: "Musk and Shotwell ring the Nasdaq opening bell simultaneously from NYC and Texas as SpaceX begins trading under SPCX. At $1.77T it's the largest IPO in history, with the $60B Cursor acquisition now funded."
---

Elon Musk and Gwynne Shotwell rang the Nasdaq opening bell simultaneously from New York City and Texas. SpaceX began trading under the SPCX ticker at $135/share, achieving a $1.77 trillion valuation on day one — the largest IPO in market history. The $75 billion raised secures the funding for the $60B Cursor acquisition, a capital event that could reshape the AI coding tool landscape.

## SpaceX IPO: Nasdaq SPCX Trading Begins — Largest IPO Ever

SpaceX started trading on Nasdaq under SPCX at $135/share today([CNBC](https://www.cnbc.com/2026/06/12/spacex-ipo-spcx-live-updates.html)). The offering of 555.6 million shares raised approximately $75 billion at a $1.77T valuation — the largest IPO in market history([Yahoo Finance](https://finance.yahoo.com/markets/stocks/article/spacex-ipo-set-to-price-thursday-night-ahead-of-friday-nasdaq-debut--heres-whats-next-101955450.html)). Musk and Shotwell rang the opening bell simultaneously from NYC and Texas, with over $150B in orders making the IPO 4x oversubscribed, and retail investors receiving roughly 30% of the allocation([Investing.com](https://www.investing.com/equities/spacex)). The SPCX-USDC perpetual contract on Hyperliquid traded around $176, a 30% premium over IPO price([WEEX](https://www.weex.com/wiki/article/spacex-stock-price-135-ipo-valuation-and-how-to-trade-spcx-gcr5v4bpve9uqp8x8eqim91f)). The proceeds are central to funding the $60B Cursor acquisition deal signed on June 5.

## Claude Code v2.1.172: Nested Sub-Agents Up to 5 Levels Deep

Claude Code shipped v2.1.172 with nested sub-agents — the headline feature allows sub-agents to spawn their own sub-agents up to 5 levels deep, each carrying its own system prompt and model([DevelopersIO](https://dev.classmethod.jp/en/articles/20260611-cc-updates-v2-1-172/)). Amazon Bedrock now reads the AWS region from ~/.aws config files when AWS_REGION isn't set, matching AWS SDK precedence([ofox.ai](https://ofox.ai/blog/claude-code-nested-subagents-2026/)). A search bar was added to the plugin marketplace, and a bug where background sub-agents stayed stuck as active after a nested child was stopped has been fixed.

## Fable 5 Controversy Continues: Jailbreak Claims and Sabotage Backlash

The Fable 5 controversy reignited days after launch([TechTimes](https://www.techtimes.com/articles/318268/20260612/claude-fable-5-hit-jailbreak-claims-secret-sabotage-backlash-days-after-launch.htm)). Red-teamer Pliny the Liberator claimed to have extracted and published the model's roughly 120,000-character system prompt. The "secret sabotage" policy — silently degrading output for users suspected of building competing AI systems — was already reversed, with Anthropic stating *"We made the wrong tradeoff, and we apologize for not getting the balance right"*([Fortune](https://fortune.com/2026/06/10/anthropic-accu-claude-fable-5-limits-capabilities-ai-researchers-developers/)). Anthropic disputes the jailbreak claims and has switched to explicitly routing flagged requests to Opus 4.8 with visible notification([SecurityWeek](https://www.securityweek.com/anthropic-disputes-fable-5-ai-jailbreak/)).

## Copilot: 44, 39-Week Decline — Billing Day 12

Copilot dropped to **44** — its 39th consecutive weekly decline([GitHub Discussions](https://github.com/orgs/community/discussions/192948)). Since the June 1 transition, 904 community downvotes, $30-40/day agentic session costs, and 10-100x cost increases for some users have accelerated the developer exodus([MLQ](https://mlq.ai/news/github-copilot-switches-to-token-based-billing-june-1-drawing-developer-backlash/)). Market share has plunged from 67% to 51%.

## Codex CLI v0.140.0-alpha.2: Desktop Handoff

Codex CLI shipped v0.140.0-alpha.2 with desktop handoff — the /app command can now hand off the current CLI thread into Codex Desktop on macOS and native Windows([GitHub Releases](https://github.com/openai/codex/releases)). TUI startup is faster thanks to plugin discovery result reuse and hook-metadata-only loading on the critical path. Goal workflows are more predictable: multiline paste in /goal edit no longer submits early, and idle auto-turns stay out of Plan mode.

## Countdown: Critical Deadlines Approaching

Anthropic agent billing split (D-3, June 15) is 3 days away — Agent SDK, `claude -p`, and GitHub Actions usage moves to a dedicated credit pool([The New Stack](https://thenewstack.io/anthropic-agent-sdk-credits/)). Credits are $20 for Pro, $100 for Max 5x, $200 for Max 20x monthly, with no rollover. Gemini CLI sunset (D-6, June 18) is 6 days out — individual and free users must migrate to Antigravity CLI([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.172 nested sub-agents, agent billing D-3 |
| ChatGPT | 96 | — | 1B MAU, memory upgrade |
| Cursor | 96 | — | SpaceX IPO trading starts, $60B acquisition funded |
| Claude AI | 96 | — | Fable 5 free for subscribers ~Jun 22, controversy ongoing |
| Codex CLI | 87 | — | v0.140.0-alpha.2, desktop handoff |
| Windsurf | 85 | — | Devin Desktop $15, Cascade EOL Jul 1 |
| Antigravity | 69 | ↑1 | Absorbing Gemini CLI D-6 migrants |
| Aider | 68 | — | Open-source CLI stable |
| Gemini CLI | 63 | ↓1 | Sunset D-6, migration accelerating |
| GH Copilot | 44 | ↓1 | 39-week decline, billing Day 12 |

SpaceX's opening bell ceremony is today's marquee event. Anthropic agent billing split is just 3 days away, and the Gemini CLI sunset is 6 days out — a busy week of deadlines for developers rethinking their toolchains.

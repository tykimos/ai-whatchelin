---
title: "Claude Code Agent Billing Splits Today, Gemini CLI Has 3 Days Left"
date: 2026-06-15
lang: en
categories: [news]
tags: [claude-code, anthropic, gemini-cli, copilot, cursor, codex-cli, chatgpt, spacex, google]
excerpt: "Anthropic's Agent SDK credit split goes live today, Claude Sonnet 4 and Opus 4 are permanently retired, and Gemini CLI shuts down in 3 days."
---

Two major inflection points hit the AI coding ecosystem simultaneously today: Anthropic's agent billing model officially separates, and legacy Claude models are permanently retired.

## Claude Code: Agent Billing Split Goes Live

Starting June 15, Claude Code's programmatic usage (`claude -p`, Agent SDK, GitHub Actions) moves to a dedicated credit pool billed at full API rates ([Anthropic](https://support.claude.com/en/articles/15036540-use-the-claude-agent-sdk-with-your-claude-plan)). Pro subscribers receive $20/month, Max 5x gets $100, and Max 20x gets $200 in Agent SDK credits — unused credits do not roll over ([Bind AI](https://blog.getbind.co/claude-code-pricing-changes-june-15-what-youll-actually-pay-2026/)). Interactive terminal and IDE usage remains bundled with subscriptions, but developers running heavy automation workloads could face meaningful cost increases. Credits are per-user, stop on depletion with no automatic fallback, and require manual overflow billing activation ([TechTimes](https://www.techtimes.com/articles/317625/20260602/anthropic-ends-subscription-subsidy-agents-june-15-credit-pool-replaces-flat-rate-access.htm)).

On the same day, Claude Sonnet 4 and Opus 4 are permanently retired at 9AM PT ([MindStudio](https://www.mindstudio.ai/blog/claude-sonnet-4-opus-4-deprecation-migration-guide)). No grace period — requests return errors immediately. Teams that haven't migrated need to swap `claude-sonnet-4-0` to `claude-sonnet-4-6` and `claude-opus-4-0` to `claude-opus-4-8` now.

## Gemini CLI: D-3, Developer Migration Accelerating

Gemini CLI will stop serving free and individual users on June 18 ([DEV Community](https://dev.to/toboreeee/google-is-killing-gemini-cli-on-june-18-here-is-what-to-do-before-then-4907)). The project — open-sourced under Apache 2.0 with 100K+ GitHub stars and 6,000+ external PRs — is being shuttered after just one year, prompting the Linux Foundation to flag "open-source trust erosion." Its replacement, Antigravity CLI, is a closed-source Go rewrite with no grace period — errors start June 18 ([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). Antigravity's steady climb to 72 reflects Gemini CLI users migrating with no real alternative.

## GitHub Copilot: 42-Week Decline Hits 41

Copilot's slide continues on Day 15 of usage-based billing, recording a popularity score of 41 ([GitHub Community Discussion](https://github.com/orgs/community/discussions/192948)). The Pro plan at $10/month with limited AI Credits and agentic sessions costing $30-40/day is driving developer frustration. Meanwhile, Fable 5 was added to Copilot but its 30-day data retention requirement is raising concerns among enterprise security teams.

## Fable 5: Reinstatement Signal Detected

David Sacks, co-chair of the White House Council of Advisors on Science and Technology, said on June 14 that the administration wants to lift the Fable 5 export control "as soon as possible" ([The Hacker News](https://thehackernews.com/2026/06/us-orders-anthropic-to-suspend-fable-5.html)). Anthropic has now dispatched co-founder and chief compute officer Tom Brown along with policy chief Sarah Heck to Washington for weekend talks with White House officials to negotiate reinstatement ([TechTimes](https://www.techtimes.com/articles/318376/20260615/anthropic-races-lift-fable-5-export-ban-top-engineers-sent-washington-deal.htm)). Anthropic maintains the jailbreak is "narrow, non-universal" and exists in other models including GPT-5.5 ([InfoQ](https://www.infoq.com/news/2026/06/claude-5-release/)).

## Google & Kaggle AI Agents Course Launches

Google and Kaggle kicked off a free five-day AI Agents Intensive course today (June 15-19), teaching participants to build production-ready AI agents using natural language workflows and hands-on coding projects ([Google Developers Blog](https://blog.google/innovation-and-ai/technology/developers-tools/kaggle-genai-intensive-course-vibe-coding-june-2026/)).

## SpaceX SPCX: Post-IPO Rally Continues

SpaceX (SPCX) surged to $178 during the trading session, up 32% from the $135 IPO price ([Robinhood](https://robinhood.com/us/en/stocks/SPCX/)). Market cap has surpassed $2.18 trillion, with Musk's net worth estimated at $1.1T+. The strong rally continues after the largest IPO in history on Nasdaq June 12 ([CNBC](https://www.cnbc.com/2026/06/12/spacex-ipo-spcx-live-updates.html)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Holds #1 despite agent billing split |
| ChatGPT | 96 | — | 1B MAU milestone, GPT-5.5 era |
| Cursor | 96 | — | Bugbot 90s reviews, Teams restructure |
| Claude AI | 96 | — | Fable 5 reinstatement signal detected |
| Codex CLI | 87 | — | Goal mode GA |
| Windsurf | 85 | — | $15 price absorbing Copilot refugees |
| Antigravity | 72 | ↑1 | Gemini CLI D-3 migration wave |
| Aider | 68 | — | Stable, release cadence slowing |
| Gemini CLI | 60 | ↓1 | D-3 shutdown countdown |
| Copilot | 41 | ↓1 | 42-week decline, billing Day 15 |

---
title: "Claude Code Agent Billing Splits Today, Gemini CLI Has 3 Days Left"
date: 2026-06-15
lang: en
categories: [news]
tags: [claude-code, anthropic, gemini-cli, copilot, cursor, codex-cli, chatgpt]
excerpt: "Anthropic's Agent SDK credit split goes live today, Claude Sonnet 4 and Opus 4 are permanently retired, and Gemini CLI shuts down in 3 days."
---

Two major inflection points hit the AI coding ecosystem simultaneously today: Anthropic's agent billing model officially separates, and legacy Claude models are permanently retired.

## Claude Code: Agent Billing Split Goes Live

Starting June 15, Claude Code's programmatic usage (`claude -p`, Agent SDK, GitHub Actions) moves to a dedicated credit pool billed at full API rates ([Anthropic](https://support.claude.com/en/articles/15036540-use-the-claude-agent-sdk-with-your-claude-plan)). Pro subscribers receive $20/month, Max 5x gets $100, and Max 20x gets $200 in Agent SDK credits — unused credits do not roll over ([Bind AI](https://blog.getbind.co/claude-code-pricing-changes-june-15-what-youll-actually-pay-2026/)). Interactive terminal and IDE usage remains bundled with subscriptions, but developers running heavy automation workloads could face meaningful cost increases. The Opus 4.8 tokenizer adding up to 35% more tokens per prompt means effective costs run higher than sticker price ([UsageBox](https://usagebox.com/articles/claude-code-cost-2026-per-token-per-month-june-deadlines)).

On the same day, Claude Sonnet 4 and Opus 4 are permanently retired at 9AM PT ([Anthropic](https://releasebot.io/updates/anthropic/claude)). No grace period — requests will return errors immediately. Teams that haven't migrated need to act now.

## Gemini CLI: D-3, Developer Migration Accelerating

Gemini CLI will stop serving free and individual users on June 18 ([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). The project — open-sourced under Apache 2.0 with 100K+ GitHub stars and 6,000+ external PRs — is being shuttered after just one year, prompting the Linux Foundation to flag "open-source trust erosion" ([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)). Its replacement, Antigravity CLI, is a closed-source Go rewrite without feature parity at launch ([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). Antigravity's steady climb to 72 reflects Gemini CLI users migrating with no real alternative.

## GitHub Copilot: 42-Week Decline Hits 41

Copilot's slide continues on Day 15 of usage-based billing, recording a popularity score of 41 ([GitHub Blog](https://github.blog/changelog/2026-06-01-updates-to-github-copilot-billing-and-plans/)). The Pro plan at $10/month with limited AI Credits and agentic sessions costing $30-40/day is driving developer frustration. Community reports of *"8% of credits burned in 2 hours"* keep piling up ([GitHub Community Discussion](https://github.com/orgs/community/discussions/192948)).

## Cursor: 90-Second Bugbot Reviews + Teams Restructure

Cursor cut Bugbot's average review time from five minutes to 90 seconds while finding 10% more bugs at 22% lower cost ([DigitalApplied](https://www.digitalapplied.com/blog/cursor-bugbot-90-second-reviews-june-2026-release)). The new Auto-review agent safety system uses a contextual classifier to balance autonomy with security — local agents keep moving on low-risk tasks while slowing down higher-stakes actions ([DevOps.com](https://devops.com/cursors-new-sdk-turns-ai-coding-agents-into-deployable-infrastructure/)). Teams pricing restructured to Standard $32/seat/month and Premium $96/seat/month.

## ChatGPT: 1 Billion Monthly Active Users

Reuters reports ChatGPT reached 1 billion monthly active users — the fastest any app has achieved that milestone ([TechnologyChecker](https://technologychecker.io/blog/chatgpt-statistics)). GPT-5.2 has been fully retired, and GPT-4.5 is set for retirement on June 27 ([OpenAI Help Center](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Holds #1 despite agent billing split |
| ChatGPT | 96 | — | 1B MAU milestone, GPT-5.5 era |
| Cursor | 96 | — | Bugbot 90s reviews, Teams restructure |
| Claude AI | 96 | — | Fable 5 reinstatement talks ongoing |
| Codex CLI | 87 | — | Goal mode GA |
| Windsurf | 85 | — | $15 price absorbing Copilot refugees |
| Antigravity | 72 | ↑1 | Gemini CLI D-3 migration wave |
| Aider | 68 | — | Stable, last release Feb |
| Gemini CLI | 60 | ↓1 | D-3 shutdown countdown |
| Copilot | 41 | ↓1 | 42-week decline, billing Day 15 |

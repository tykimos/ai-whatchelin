---
title: "Gemini CLI Dies Today While Claude Code Ships Twice — The Gap Widens"
date: 2026-06-18
lang: en
categories: [news]
tags: [gemini-cli, antigravity, claude-code, copilot, copilot-app, codex-cli, fable-5, kaggle, g7, anthropic]
excerpt: "Google shuts down Gemini CLI for good on the same day Anthropic pushes two Claude Code releases. G7 sees all three AI CEOs at the table."
---

On the day Google officially killed an open-source project that accepted 6,000+ community pull requests, Anthropic released two Claude Code updates. The contrast between "shutting down" and "shipping fast" has never been starker.

## Gemini CLI: The Last Day of Open-Source Trust

Starting today, the `gemini` command returns errors for all individual users ([AI Builder Club](https://www.aibuilderclub.com/blog/google-kills-gemini-cli-june-18-2026)). Every CI/CD pipeline, shell script, and cron job that depended on it stops working with no grace period. The replacement, Antigravity CLI (`agy`), is a closed-source Go binary that slashes free daily requests from ~1,000 to 20 — a 98% reduction ([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)). The official transition thread received 143 downvotes against 4 approvals ([HN](https://news.ycombinator.com/item?id=48196867)). The Linux Foundation spotlighted this as exhibit A of the "open-source bait-and-switch" pattern ([TechTimes](https://www.techtimes.com/articles/317407/20260529/linux-foundation-tool-spotlighted-furious-developers-accuse-sickening-google-gemini-cli.htm)).

## Claude Code v2.1.179 + v2.1.181: Two Releases in One Day

While Gemini CLI went dark, Claude Code shipped twice today ([Anthropic Changelog](https://code.claude.com/docs/en/changelog)). Version 2.1.179 fixed mid-stream connection drops, WSL2 scrolling issues, sandbox glob performance, and plugin loading in remote sessions. Version 2.1.181 added `/config key=value` prompt-based configuration commands, upgraded to Bun 1.4 runtime, improved long-paragraph streaming to line-by-line output, and fixed file writes on network drives and prompt caching with custom `ANTHROPIC_BASE_URL` ([GitHub Releases](https://github.com/anthropics/claude-code/releases)).

## G7 AI Summit: Three CEOs, One Table

Yesterday's G7 AI working lunch brought Sam Altman (OpenAI), Dario Amodei (Anthropic), and Demis Hassabis (Google DeepMind) together for the first time at a heads-of-state event ([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-june-17-2026)). The summit produced voluntary (non-binding) commitments on youth safety and frontier AI risks. Canadian PM Carney cited the Fable 5 suspension as evidence of AI over-reliance risk ([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-16/trump-s-anthropic-crackdown-sets-off-ai-alarms-for-us-allies)). SoftBank committed 45 billion EUR to French AI data centers.

## Anthropic Opens Seoul Office

Anthropic opened its first Korea office in Seoul, expanding its Asia presence following last week's NEC partnership in Japan (30,000 employees). The world's most valuable private AI startup at $965B valuation is now betting on the Korean market.

## Copilot App GA: Can It Stop a 45-Week Decline?

The GitHub Copilot desktop app is now generally available on macOS, Windows, and Linux ([GitHub Blog](https://github.blog/changelog/2026-06-17-github-copilot-app-generally-available/)). Developers can launch agent sessions from issues or PRs and collaborate via Canvases in real time. But billing Day 18 backlash persists — Pro users burn 8% of monthly credits in 2 hours, and agentic sessions cost $30-40/day ([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)).

## Fable 5: Day 6, No Reinstatement in Sight

Claude Fable 5's suspension has entered its sixth day ([EisnerAmper](https://www.eisneramper.com/insights/artificial-intelligence-insights/fable-5-suspension-facts-and-timeline-0626/)). Anthropic dispatched Tom Brown and Sarah Heck to Washington for face-to-face talks with Commerce Department officials ([explainx.ai](https://explainx.ai/blog/when-will-fable-5-be-available-again-2026)). Unconfirmed "48-hour" reinstatement rumors surfaced but no official timeline exists. The tracker at isfable5back.com still reads "No" ([isfable5back](https://isfable5back.com/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Two releases today, stable at top |
| ChatGPT | 96 | — | 1B MAU, holding steady |
| Cursor | 96 | — | SpaceX acquisition confirmed, Origin announced |
| Claude AI | 96 | — | Fable 5 Day 6 + Seoul office opened |
| Codex CLI | 87 | — | v0.140.0 stable |
| Windsurf | 85 | — | $15 price absorbing Copilot refugees |
| Antigravity | 76 | ↑2 | Gemini CLI shutdown day, mass migration |
| Aider | 68 | — | Open-source agent stalling |
| Gemini CLI | 55 | ↓3 | Dead today, enterprise-only |
| Copilot | 38 | ↓1 | 45-week decline, App GA effect unclear |

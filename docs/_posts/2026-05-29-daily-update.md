---
title: "Anthropic Closes $65B at Near-Trillion Valuation as OpenAI Suffers Broadest 2026 Outage"
date: 2026-05-29
lang: en
categories: [news]
tags: [anthropic, claude, openai, copilot, codex-cli, microsoft-build]
excerpt: "Anthropic closed $65B at $965B valuation, overtaking OpenAI as most valuable private AI startup. Meanwhile, OpenAI suffered its broadest 2026 outage, Microsoft previewed homegrown coding models for Build, and Copilot hit a 25-week low at D-3 to billing change."
---

Anthropic closed a $65 billion Series H at a $965 billion post-money valuation, overtaking OpenAI to become the world's most valuable private AI startup ([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-28/anthropic-raises-at-965-billion-valuation-eclipsing-openai)). On the very same day, OpenAI suffered its broadest outage of 2026 — a contrast that could not have been sharper.

## Anthropic: Knocking on the $1 Trillion Door

Sequoia, Dragoneer, Altimeter, and Greenoaks co-led the round, with Amazon contributing $5 billion from its previously committed $15 billion tranche ([CNBC](https://www.cnbc.com/2026/05/28/anthropic-open-ai-startup-value.html)). With an annualized revenue run rate of $47 billion, this is likely the final private round before an October IPO ([TechCrunch](https://techcrunch.com/2026/05/28/anthropic-raises-65-billion-nears-1t-valuation-ahead-of-ipo/)). Opus 4.8 fast mode is now 3x cheaper than previous models, and Anthropic announced plans to make Mythos-class models available to all customers in the coming weeks ([VentureBeat](https://venturebeat.com/technology/anthropics-claude-opus-4-8-is-here-with-3x-cheaper-fast-mode-and-near-mythos-level-alignment)).

## OpenAI: Broadest 2026 Outage Hits All Services

OpenAI experienced widespread disruptions across ChatGPT, API, DALL-E, Codex, Sora, and login systems on May 29 ([BusinessUpturn](https://www.businessupturn.com/technology/chatgpt-down-openai-users-report-widespread-problems-with-api-app-and-login-on-may-29)). Users reported "too many concurrent connections" errors. The simultaneous multi-service failure — the broadest of 2026 — resolved same day, but the timing alongside Anthropic's record round drew sharp contrast.

## Microsoft Build D-4: Homegrown Coding Model Coming

Microsoft will unveil a suite of homegrown AI models at Build 2026 (June 2-3), including a coding-specialized model for GitHub Copilot, a reasoning model, and an in-house agent ([The Information](https://www.theinformation.com/newsletters/ai-agenda/microsoft-release-new-coding-model-next-week-comeback-attempt)). Mustafa Suleyman's AI team was freed from OpenAI training restrictions in April — these are the first results. MSFT stock rose ~3% on the report ([Reuters/TradingView](https://www.tradingview.com/news/reuters.com,2026:newsml_L4N4251NM:0-microsoft-to-release-new-coding-model-next-week-the-information-reports/)).

## Claude Code v2.1.153: 36 Changes

`/model` now saves as your default for new sessions, and a `skipLfs` option was added for plugin marketplace sources ([code.claude.com/changelog](https://code.claude.com/docs/en/changelog)). A regression since v2.1.129 that prevented Bedrock and Vertex users from selecting "Opus (1M context)" in the model picker was fixed, alongside 25+ other bug fixes covering MCP pagination, subagent policy enforcement, and OAuth credential routing.

## Opus 4.8: Elevated Errors Hours After GA, Resolved in 6 Minutes

Opus 4.8 hit elevated errors at 08:39 UTC — just hours after going GA on GitHub Copilot and AWS ([AI Weekly](https://aiweekly.co/alerts/anthropic-opus-48-hits-errors-hours-after-aws-launch)). Anthropic implemented a fix by 08:45 UTC, resolving the incident in approximately 6 minutes. Developers who onboarded through Copilot or AWS on launch day experienced a brief disruption window.

## GitHub Copilot: 25-Week Low, D-3 to Billing Change

Copilot's popularity score dropped to 58, setting another all-time low ([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)). Just 3 days remain until June 1 usage-based billing — code completions stay free, but agent and chat consume AI Credits. Microsoft Build 2026 in 4 days remains the only potential counter-narrative.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 + $65B round, Mythos imminent |
| Cursor | 96 | — | Stable, pre-Build wait-and-see |
| Codex CLI | 88 | — | v0.135.0, autonomous agent evolution |
| Windsurf | 81 | — | Devin integration stabilizing |
| Gemini CLI | 77 | ↓1 | Sunset D-20, attrition continues |
| Antigravity | 58 | ↑1 | Post-patch recovery continues |
| GH Copilot | 58 | ↓1 | 25-week low, billing change D-3 |
| ChatGPT | 97 | ↓1 | Broad outage impact |
| Claude AI | 95 | — | $965B valuation, IPO imminent |
| Aider | 68 | — | Stable, open-source base |

Copilot's descent and Antigravity's rebound cross at 58 — the same number, but from opposite trajectories. Can Microsoft's homegrown coding model at Build 2026 reverse the narrative?

---

*Sources: inline in each sentence above*

---
title: "Cursor Goes Full Metered, Codex Kills MCP Server — Nokia Deploys 20K Engineers as Ox Alpha Mystery Ends"
date: 2026-08-24
lang: en
categories: [news]
tags: [cursor, openai, copilot, ox-alpha, codex-cli, anthropic, nokia, pricing, deprecation]
excerpt: "Cursor's flat Auto rate dies today. Codex CLI deprecates its MCP server command. Nokia makes the largest known enterprise Cursor deployment. And nobody still knows who built Ox Alpha."
---

The AI coding tool market's pricing landscape shifted again today. Cursor officially killed Auto mode's flat rate in favor of per-model pricing, Codex CLI deprecated its MCP server command as OpenAI consolidates its tool ecosystem, and Anthropic's revenue run rate hit $65B — up 38% from May. Meanwhile, the mysterious frontier model Ox Alpha sees its free access expire today.

## Cursor: Auto Per-Model Pricing Goes Live

Cursor Auto mode now charges at the rate of whichever model the request is routed to, replacing the previous flat Auto rate ([explainx.ai](https://www.explainx.ai/blog/cursor-auto-per-model-pricing-usage-limits-august-2026)). Included usage has increased across all models, but developers who frequently hit frontier models (Opus 5, Fable 5, etc.) will see higher effective costs. The change came via email-only announcement with no changelog entry. In a major enterprise signal, Nokia has deployed 20,000+ engineers on Cursor — the largest known enterprise deployment ([LogRocket](https://blog.logrocket.com/ai-dev-tool-power-rankings/)). As Kilo AI's analysis noted, *"all roads lead to metered pricing"* — every major AI coding tool is converging on usage-based billing ([blog.kilo.ai](https://blog.kilo.ai/p/all-roads-lead-to-metered-pricing)).

## Codex CLI: MCP Server Deprecated + v0.149.0 Dashboard

The `codex mcp-server` command was officially deprecated today, with users directed to the Codex app server or the Codex plugin for Claude Code ([releasebot.io](https://releasebot.io/updates/openai/codex)). This signals OpenAI's move to consolidate its tool ecosystem. Release v0.149.0 (Aug 20) introduced an interactive agents dashboard for managing tasks from a single screen, while v0.148.0 (Aug 18) added TUI conversation export to Markdown via `/export` and session forking with `codex exec fork` ([havoptic.com](https://www.havoptic.com/tools/openai-codex)).

## Ox Alpha: Mystery Model's Free Access Ends Today

The stealth frontier model Ox Alpha, which appeared on OpenRouter on August 20, sees its free access window close today ([SiliconANGLE](https://siliconangle.com/2026/08/23/nobody-knows-who-built-ai-coding-model-ox-alpha-or-where-the-code-goes/)). With a 1M-token context window, text/image/video input, and ~128K output tokens, the model processed billions of tokens within its first day ([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-23/mystery-ai-model-ox-alpha-draws-developers-with-free-access)). Listed under the provider name "stealth," its developer remains unidentified — though community fingerprinting strongly points to Z.ai's GLM family ([Manifold](https://manifold.markets/Sketchy/who-is-behind-ox-alpha-the-mysterio)). Security concerns persist: nobody knows where the code goes.

## Anthropic: $65B Revenue Run Rate, Hardware Push

Anthropic's annualized revenue run rate surged to $65 billion, up 38% from $47B in May ([Fortune](https://fortune.com/2026/08/18/anthropic-annual-revenue-run-rate-65-billion/)). The company is on track for $100-120B by year-end, with an IPO filing potentially imminent. On August 22, Anthropic hired a Google chip veteran, signaling a push into custom AI hardware design ([TechCrunch](https://techcrunch.com/2026/08/17/anthropics-annualized-revenue-surges-to-65b/)).

## Countdown: Four Deadlines in Eight Days

The o3 ChatGPT retirement is now D-2 (Aug 26). DALL-E GPT retires D-6 (Aug 30), GPT-5.4 leaves Codex D-7 (Aug 31), and Copilot's six-model mass deprecation hits D-8 (Sep 1) ([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). Copilot's popularity decline streak extends to 104 consecutive weeks.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.241, 28-week streak at 99 |
| ChatGPT | 99 | — | o3 retirement D-2, Sol 20%+ cut ongoing |
| Codex CLI | 99 | — | v0.149.0 dashboard, MCP server deprecated |
| Antigravity | 99 | — | IDE extensions settled, 28-week streak at 99 |
| Claude AI | 99 | — | Academy settling in, $65B revenue run rate |
| Cursor | 99 | — | Auto per-model pricing live, Nokia 20K deploy |
| Windsurf | 86 | — | Devin Local stabilizing |
| Aider | 68 | — | No release in 6+ months since v0.86.2 |
| Copilot | 1 | — | 104-week decline, mass deprecation D-8 |
| Gemini CLI | 1 | — | Shutdown day 67 |

Cursor's metered pivot and Codex's MCP deprecation signal a maturing AI coding tool market. The question for next week is how developers reorganize their tool stacks as four cascading deadlines hit.

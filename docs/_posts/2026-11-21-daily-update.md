---
title: "Claude Code v2.1.329 Ships, Auto Mode Goes Default on All Major Clouds"
date: 2026-11-21
lang: en
categories: [news]
tags: [anthropic, claude-code, openai, apple, github-copilot, codex-cli]
excerpt: "Claude Code ships v2.1.328–329 back-to-back, making auto mode default on Bedrock, Vertex, and Foundry. OpenAI extends the GPT-5.6 Sol discount to November 30."
---

Anthropic shipped two Claude Code releases in quick succession — v2.1.328 and v2.1.329 — making auto mode the default for Opus 4.6 and Sonnet 4.6 across major third-party clouds including Amazon Bedrock, Google Vertex, and Microsoft Foundry([claudekit](https://claudekit.io/en/updates/claude-code-2-1-328/), [remio.ai](https://www.remio.ai/post/claude-code-v2-1-328-expands-cloud-auto-mode)). Enterprise developers can now use auto mode out of the box without setting environment variables — a meaningful friction reduction for teams adopting Claude Code at scale.

## Claude Code: What's New in v2.1.329

The `/tasks` command now surfaces scheduled tasks and forks([Havoptic](https://www.havoptic.com/r/claude-code-2.1.329)). `/status` flags marketplaces without auto-updates enabled. Several crash fixes cover sign-out handling, `/teleport`, and file operations. The subagent wait default introduced in v2.1.328 — where subagents in `claude -p`, the Agent SDK, desktop and VS Code wait for their own sub-subagents — has stabilized([claudekit](https://claudekit.io/en/updates/claude-code-2-1-328/)).

## GPT-5.6 Sol Promo Extended to November 30

OpenAI has extended the GPT-5.6 Sol 20% promotional discount by nine days to November 30, confirmed via customer emails([RuntimeWire](https://runtimewire.com/article/gpt-5-6-sol-promo-pricing-november-30-customer-email)). The official docs still state "at least through November 21"([developers.openai.com](https://developers.openai.com/api/docs/models/gpt-5.6-sol.md)), giving teams that haven't migrated yet some additional runway.

## Apple: Building an AI Agent That Runs Your Mac

TechCrunch reported on November 19 that Apple is developing an AI agent capable of operating apps, browsing the web, and coding on behalf of Mac users([TechCrunch](https://techcrunch.com/2026/11/19/apple-may-be-developing-its-own-ai-agent-that-runs-your-mac)). Still in development, but the move beyond Xcode's existing AI features toward a general-purpose agent signals a new competitor entering the AI coding tool space.

## OpenAI Research: Coding Agents Hit 46% Autonomous Completion

OpenAI's latest research finds coding agents now autonomously complete 46% of tasks that take humans 2–4 hours — doubled from 23% in March([WireTensors](https://wiretensors.ai/news/ai-tools-roundup-2026-11-21/)). This acceleration underpins why agent-style tools like Codex CLI and Claude Code maintain their 99-score plateaus.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.6 Sol promo extended to 11/30, agents at 46% autonomy |
| Claude Code | 99 | — | v2.1.329 shipped, auto mode default on all major clouds, ANT day 3 |
| Codex CLI | 99 | — | v0.171.0 stable, TUI workspace default-on |
| Antigravity | 99 | — | Gemini 4 Neon day 4, real-world evals underway |
| Claude AI | 99 | — | ANT trading ~$99 |
| GH Copilot | 99 | — | 60-day streak, Gemini 4 Carbon added |
| Windsurf | 88 | — | Devin Desktop steady operations |
| Aider | 68 | — | Maintenance mode continues |
| Cursor | 1 | — | OpenAI blackout day 10, 90 days at bottom |
| Gemini CLI | 1 | — | Antigravity transition complete |

The five-way 99 tie extends to day 6. Claude Code's back-to-back releases (v2.1.328–329) focused on cloud auto mode expansion and developer experience polish suggest accelerating enterprise adoption.

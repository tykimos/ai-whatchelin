---
title: "Claude Code Rate Limits Doubled as Gemini CLI Goes Open-Source — CLI Three-Way Race Heats Up"
date: 2026-05-07
lang: en
categories: [news]
tags: [claude-code, gemini-cli, cursor, codex-cli, copilot, anthropic, google, openai]
excerpt: "Anthropic's SpaceX deal doubles Claude Code rate limits across all paid plans, while Google's Gemini CLI open-source launch and Cursor 3.3's Team Marketplace intensify the AI coding tool wars."
---

One day after Anthropic secured SpaceX's Colossus 1 datacenter — 220,000+ GPUs, 300+ megawatts — and immediately doubled Claude Code rate limits across all paid plans, the rest of the ecosystem is responding. Google open-sourced Gemini CLI with a generous free tier, and Cursor introduced Team Marketplace to expand its plugin ecosystem.

## Claude Code: v2.1.132 Patch + Conference Aftershocks

Claude Code v2.1.132 shipped today([Releasebot](https://releasebot.io/updates/anthropic)). The release adds the CLAUDE_CODE_SESSION_ID terminal environment variable for session tracking, and fixes fullscreen mode after sleep/wake, emoji handling, and MCP server auth failures. Community reaction to yesterday's 'Code with Claude' announcements — Managed Agents (multi-agent orchestration), Outcomes (autonomous iteration toward success criteria), and Dreaming (overnight self-improving memory) — remains intense([Simon Willison](https://simonwillison.net/2026/May/6/code-w-claude-2026/)). The SpaceX deal also eliminated peak-hours rate limit reductions for Pro and Max plans([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)).

## Gemini CLI: Official Open-Source AI Agent Debut, v0.42 Preview

Google released Gemini CLI under the Apache 2.0 license([Google Blog](https://blog.google/technology/developers/introducing-gemini-cli-open-source-ai-agent/)). Any personal Google account gets free Gemini 2.5 Pro access with a 1-million-token context window — 60 requests per minute, 1,000 per day at zero cost. Unlike Claude Code ($20/month+) or Codex CLI (requires paid ChatGPT), it's completely free. The v0.42.0 preview adds real-time voice mode, enables Gemma 4 models by default, improves auto memory with a canonical-patch contract, and introduces /bug-memory for heap snapshots([GitHub](https://github.com/google-gemini/gemini-cli/releases)).

## Cursor 3.3: Team Marketplace Expands Plugin Ecosystem

Cursor 3.3 introduced Team Marketplace([Cursor Changelog](https://cursor.com/changelog)). Admins can now create and distribute plugins — bundling MCP servers, skills, subagents, rules, and hooks — without needing a connected repository. Three distribution modes are available: Default Off, Default On, or Required. A detailed breakdown of agent context usage was also added.

## GitHub Copilot: Five-Week Slide Continues, D-24

Enterprise-managed plugins for Copilot CLI arrived in public preview([GitHub Blog](https://github.blog/changelog/2026-05-06-enterprise-managed-plugins-in-github-copilot-cli-are-now-in-public-preview/)), but community backlash over the June 1 usage-based billing transition (D-24) continues unabated. Pro/Pro+/Student sign-ups remain paused, and Opus models have been removed from the Pro tier([GitHub Blog](https://github.blog/news-insights/company-news/changes-to-github-copilot-individual-plans/)). The popularity score is on its fifth consecutive weekly decline.

## Codex: Spark Research Preview + Security Hardening

OpenAI released Codex-Spark in research preview for ChatGPT Pro users — text-only, 128k context window([OpenAI Developers](https://developers.openai.com/codex/changelog)). The Codex CLI TUI gained quick reasoning controls via Alt+, and Alt+. shortcuts. Advanced Account Security was also introduced with phishing-resistant sign-in and login alerts.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant settled as default |
| Claude Code | 97 | — | SpaceX deal + limits doubled, holding peak |
| Cursor | 91 | — | 3.3 + Team Marketplace, stable |
| Claude AI | 91 | — | Managed Agents announcement effect holds |
| GitHub Copilot | 79 | ↓1 | 5-week slide, D-24 |
| Windsurf | 77 | — | 2.0 + Devin integration settling |
| Codex CLI | 77 | ↑1 | Spark preview + TUI improvements |
| Gemini CLI | 70 | ↑2 | Open-source + v0.42 voice mode, 3-day high |
| Aider | 68 | — | 39K+ stars, stable |
| Antigravity | 47 | — | No news |

Claude Code holds 97 on the strength of the SpaceX deal and conference announcements, closing the gap on ChatGPT (98). Gemini CLI hit 70 with its open-source launch and v0.42 preview, cementing the CLI race as a firm three-way contest between Claude Code, Codex CLI, and Gemini CLI. Copilot's five-week decline to 79 continues as the June 1 billing transition looms.

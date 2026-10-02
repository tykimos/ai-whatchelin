---
title: "Claude Code Mods Turn the Agent Into a Platform"
date: 2026-10-02
lang: en
categories: [news]
tags: [claude-code, anthropic, github-copilot, openai, codex-cli, mods, pi, apple]
excerpt: "Anthropic ships TypeScript-based 'mods' that let developers rewrite Claude Code's behavior from the inside. Earendil's Pi 1.0 reverses course on MCP. GitHub Copilot drops 4 models, and Apple tightens macOS security for AI agents."
---

Anthropic officially introduced mods to Claude Code — TypeScript functions that hook into the agent's internal events and let developers rewrite prompts, replace UI, add features, and intercept tool calls ([Anthropic Blog](https://claude.com/blog/claude-code-mods)). Shipping in v2.1.287, mods install via the `/plugin` command and hot-reload in the running session ([The New Stack](https://thenewstack.io/anthropic-claude-code-mods-plugins/)). The catch: mods aren't sandboxed, running with full system access — install only from trusted sources ([Nerdschalk](https://nerdschalk.com/are-claude-code-mods-sandboxed-what-they-can-access/)). Team and Enterprise plans ship a built-in `sec-default` mod that blocks risky actions by default.

## GitHub Copilot: 4 Models Removed Today + Computer Use GA

GitHub Copilot's scheduled deprecation wave hit today, removing Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7 across all Copilot experiences ([GitHub Changelog](https://github.blog/changelog/2026-09-03-upcoming-deprecation-of-selected-github-copilot-models/)). Replacements are Gemini 3.8 Flash, Kimi K3, and Claude Opus 5. The next wave on October 19 will cut GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, and Grok 4.5 ([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)). Meanwhile, Copilot agents can now interact with desktop apps via computer use, which went GA on October 1 ([GitHub Changelog](https://github.blog/changelog/)), and a new global default feature policy takes effect October 22 for unconfigured capabilities ([GitHub Changelog](https://github.blog/changelog/2026-09-24-default-enablement-of-copilot-features-for-copilot-business-and-enterprise/)). Business and Enterprise admins should review both model access and feature policies.

## Codex CLI v0.160.0: Agent Command Center Gets History

OpenAI shipped Codex CLI v0.160.0 today with browsable history in the agent command center, projectless sessions with workspace defaults, and X11 middle-click paste on Linux ([Releasebot](https://releasebot.io/updates/openai/codex)). A reconnect fix stops duplicate messages on flaky connections, and subagents now preserve environments that are still starting ([ai-tldr.dev](https://ai-tldr.dev/releases/openai-codex-cli-0-160/)).

## Claude for Government Goes GA

Claude for Government is now generally available with FedRAMP High authorization, providing coding and agentic workflows with governance controls, audit logs, and desktop file support ([Releasebot](https://releasebot.io/updates/anthropic)). Claude Code CLI and Claude for Microsoft 365 are rolling out in early access.

## Earendil Pi 1.0: The Open-Source Agent That Changed Its Mind on MCP

Earendil shipped Pi 1.0, the stable release of its open-source coding agent, with a notable reversal: Pi previously rejected MCP support but now makes it a core feature ([GIGAZINE](https://gigazine.net/gsc_news/en/20261002-pi-1-0/)). The tool supports 15+ providers including Anthropic, OpenAI, and Google, and introduces deferred tool loading, virtual-model extensions, and mid-conversation system messages ([The Register](https://www.theregister.com/ai-and-ml/2026/10/02/pi-coding-agent-pulls-a-180-and-adds-mcp-support/5300678)). Alongside it, Earendil released Pi Durable for long-running asynchronous agentic tasks ([hyper.ai](https://hyper.ai/en/stories/11ad6e13661a4d8c1d359d9d40a534e5)). With hundreds of thousands of weekly users, Pi is carving out its niche in the CLI agent ecosystem.

## Apple Tightens macOS Security for AI Agents

Apple is adding new controls around macOS Full Disk Access, warning that some developers have been exposing users' entire systems without proper consent ([AI News Today](https://aiweekly.co/ai-news-today)). The company says risks will grow substantially as AI agents become more capable and autonomous — a direct signal to coding agent developers.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Stable post-DevDay, GPT-6.1 Sol adoption |
| Claude Code | 99 | — | v2.1.287 + Mods, Government GA |
| Codex CLI | 99 | — | v0.160.0, agent command center update |
| Antigravity | 99 | — | Gemini 4 Argon deployment pending |
| Claude AI | 99 | — | Barclays adoption scaling |
| Windsurf | 88 | — | Stable as Devin Desktop |
| Aider | 68 | — | Effectively dormant |
| Cursor | 27 | ↓2 | 36th straight decline, OpenAI shutoff D-41 |
| GH Copilot | 11 | ↑2 | 4 models removed today, recovery accelerating |
| Gemini CLI | 1 | — | Shutdown day 107 |

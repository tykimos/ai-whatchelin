---
title: "Claude Code Mods Turn the Agent Into a Platform"
date: 2026-10-02
lang: en
categories: [news]
tags: [claude-code, anthropic, github-copilot, openai, codex-cli, mods]
excerpt: "Anthropic ships TypeScript-based 'mods' that let developers rewrite Claude Code's behavior from the inside. GitHub Copilot drops 4 models today, and Codex CLI v0.160.0 lands."
---

Anthropic officially introduced mods to Claude Code — TypeScript functions that hook into the agent's internal events and let developers rewrite prompts, replace UI, add features, and intercept tool calls ([Anthropic Blog](https://claude.com/blog/claude-code-mods)). Shipping in v2.1.287, mods install via the `/plugin` command and hot-reload in the running session ([The New Stack](https://thenewstack.io/anthropic-claude-code-mods-plugins/)). The catch: mods aren't sandboxed, running with full system access — install only from trusted sources ([Nerdschalk](https://nerdschalk.com/are-claude-code-mods-sandboxed-what-they-can-access/)). Team and Enterprise plans ship a built-in `sec-default` mod that blocks risky actions by default.

## GitHub Copilot: 4 Models Officially Removed Today

GitHub Copilot's scheduled deprecation wave hit today, removing Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7 across all Copilot experiences ([GitHub Changelog](https://github.blog/changelog/2026-09-03-upcoming-deprecation-of-selected-github-copilot-models/)). Replacements are Gemini 3.8 Flash, Kimi K3, and Claude Opus 5. The next wave on October 19 will cut GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, and Grok 4.5 ([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)). Business and Enterprise admins should verify replacement model access in their Copilot settings.

## Codex CLI v0.160.0: Agent Command Center Gets History

OpenAI shipped Codex CLI v0.160.0 today with browsable history in the agent command center, projectless sessions with workspace defaults, and X11 middle-click paste on Linux ([Releasebot](https://releasebot.io/updates/openai/codex)). A reconnect fix stops duplicate messages on flaky connections, and subagents now preserve environments that are still starting ([ai-tldr.dev](https://ai-tldr.dev/releases/openai-codex-cli-0-160/)).

## Claude for Government Goes GA

Claude for Government is now generally available with FedRAMP High authorization, providing coding and agentic workflows with governance controls, audit logs, and desktop file support ([Releasebot](https://releasebot.io/updates/anthropic)). Claude Code CLI and Claude for Microsoft 365 are rolling out in early access.

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

---
title: "Claude Code Ships Yet Another Release, Copilot Hits 101-Week Decline Record"
date: 2026-08-21
lang: en
categories: [news]
tags: [claude-code, cursor, copilot, windsurf, grok, github, ai-safety]
excerpt: "Claude Code released v2.1.238 — its fourth version in four days. GitHub Copilot set an unprecedented 101-week consecutive decline record with just 11 days until the September 1 mass model deprecation."
---

Claude Code released v2.1.238, its fourth version this week, underscoring Anthropic's relentless release cadence ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). This release fixes a prompt caching bug that affected custom LLM gateways, resolves a Linux issue where idle sessions with sandboxing enabled consumed 100% of a CPU core, and patches a voice mode bug on native builds that got stuck on "listening…" ([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)).

## Copilot: 101-Week Decline, Mass Deprecation D-11

GitHub Copilot set an unprecedented record with 101 consecutive weeks of popularity decline. With just 11 days until the September 1 mass model deprecation, six or more older models will be retired simultaneously ([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). On a brighter note, Grok 4.6 is now generally available across eight development surfaces — VS Code, Visual Studio, CLI, JetBrains, Xcode, Eclipse, and more ([GitHub Blog](https://github.blog/changelog/2026-08-14-grok-4-6-is-now-available-in-github-copilot/)). Enterprise administrators also gained managed JetBrains settings for centralized control over MCP server access, OpenTelemetry, and permission modes ([GitHub Changelog](https://github.com/features/copilot/whats-new)).

## Windsurf: Devin Local Gets Practical Upgrades

Windsurf shipped practical improvements to Devin Local ([Releasebot](https://releasebot.io/updates/windsurf)). A new `.devinignore` file lets developers specify files the agent should skip, and the agent now reads context from files open in the editor. MCP tool "Always Allow" permissions now persist across sessions, eliminating repeated re-authorization prompts.

## OpenAI: Astra Safety Framework Rewrite Continues

OpenAI's Astra safety framework rewrite enters its second week with frontier RL training still paused. CEO Sam Altman stated that "keeping powerful models to a chosen few" is not a viable long-term strategy ([Forbes](https://www.forbes.com/sites/jonmarkman/2026/08/09/openai-pauses-astra-after-it-nears-first-ever-critical-cyber-risk/)). GPT-5.4 retirement is D-10 (August 31), and Codex users signed in with ChatGPT need to switch to API key authentication ([OpenAI Help](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.238, 4th release in 4 days |
| ChatGPT | 99 | — | GPT-5.4 retirement D-10, Astra rewrite week 2 |
| Codex CLI | 99 | — | Stable, GPT-5.4 8/31 retirement |
| Antigravity | 99 | — | Gemini 3.7 Flash integration stabilizing |
| Claude AI | 99 | — | Claude Academy launch, Files API GA |
| Cursor | 99 | — | SpaceX acquisition complete, AIUC-1 certified |
| Windsurf | 86 | — | Devin Local .devinignore, persistent permissions |
| Aider | 68 | — | No release in 6+ months since v0.86.2 |
| Copilot | 1 | — | 101-week decline, mass deprecation D-11 |
| Gemini CLI | 1 | — | Shutdown day 64 |

Claude Code's release velocity continues to outpace the competition, while Copilot's 101-week decline underscores that the AI coding tool market's winners and losers are already decided.

---
title: "ChatGPT Images 2.5 Launches, Claude Code v2.1.265 Gateway Regression — Cursor Hits 69 on Day 15 of Decline"
date: 2026-09-10
lang: en
categories: [news]
tags: [chatgpt, codex-cli, cursor, claude-code, antigravity, gitspawn, security]
excerpt: "OpenAI shakes up image generation with ChatGPT Images 2.5. Claude Code v2.1.265 adds telemetry but ships a gateway regression, while Cursor drops to 69 — its 15th consecutive day of decline."
---

OpenAI launched ChatGPT Images 2.5, reigniting the image generation arms race ([OpenAI](https://openai.com/index/introducing-chatgpt-images-2-5/)). The new model cuts latency by 50% compared to Images 2.0 while significantly improving natural lighting and texture rendering. The standout feature is "Sketch," which lets users draw references directly as input. The API splits into two models — Flare (fast default) and Sunburst (precise editing) — priced at $8/$30 per MTok ([Simon Willison](https://simonwillison.net/2026/Sep/8/introducing-chatgpt-images-25/)).

## Claude Code v2.1.265: Telemetry Additions and Gateway Regression

Claude Code shipped v2.1.265, adding user.email and user.groups telemetry for Desktop and Cowork sessions ([GitHub](https://github.com/anthropics/claude-code/releases/tag/v2.1.265)). However, a regression in the CLAUDE_CODE_USE_GATEWAY environment variable now forces Cloud-gateway sign-in on its own, causing configurations that use API keys, apiKeyHelper, or custom auth headers to fail every request. The Sep 14 weekly limit cut (17% effective reduction) is now D-4 — the 50% promo ends and only the permanent 25% above pre-promo baseline remains ([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)).

## Codex CLI v0.154.0: Experimental Worktree Isolation

Codex CLI jumped to v0.154.0 with notable updates ([Releasebot](https://releasebot.io/updates/openai/codex)). GPT-6 Astra is now fully integrated into the model picker and Amazon Bedrock catalogs. The headline addition is experimental worktree support (`--worktree` or `/worktree`), letting agents run in isolated Git checkouts. Vim mode gained undo (u) and redo (Ctrl+R), and the plugin CLI now handles remote marketplace installs and removals. ChatGPT Voice Mode also added GPT-6 Astra support, though limited to Pro accounts.

## Cursor: Score 69, 15th Consecutive Decline — D-63

Cursor fell to 69, marking its 15th straight day of decline and a 30-point drop from its August 27 peak of 99. The OpenAI model cutoff (November 12) is now 63 days away. Cursor launched self-hosted machines on September 2 — tool execution stays on the user's network while the agent loop runs in Cursor cloud ([Cursor Blog](https://cursor.com/blog/self-hosted-machines)) — and added computer use on Linux and Mac. But product improvements aren't stopping the developer exodus. Fable 5.1 scoring 73.4% on Cursor's own coding benchmark, the best any model has achieved there, underscores the irony: Anthropic dependency deepens as OpenAI walks away.

## GitSpawn Vulnerability Fallout Continues

The GitSpawn vulnerability disclosed by Manifold Security continues to ripple through the ecosystem ([The Hacker News](https://thehackernews.com/2026/09/malicious-git-configs-can-make-claude.html)). The attack exploits malicious `.git/config` `core.fsmonitor` settings to trigger arbitrary code execution across seven AI coding agents. Codex and Cursor have shipped fixes, but four of eight vulnerabilities remain unpatched. CrowdStrike launched Falcon Guardian in response, signaling that AI agent security is crystallizing into a real market category ([VibeEval](https://vibe-eval.com/updates/security-harness-for-ai-agents-sep-2026/)).

## Antigravity: /boost Slash Command Added

Antigravity shipped the `/boost` slash command for enhanced thinking via a multi-agent reasoning pipeline ([Antigravity Lab](https://antigravitylab.net/en/articles/antigravity/antigravity-features-update-2026)). `GEMINI_API_KEY` support lets the CLI run against the Gemini API without sign-in, and the new highlight-to-quote feature streamlines follow-up prompts.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Images 2.5 launched, Voice adds Astra |
| Claude Code | 99 | — | v2.1.265 gateway regression, 9/14 limit change D-4 |
| Claude AI | 99 | — | Fable 5.1 settled, cache 75% cut holding |
| Codex CLI | 99 | — | v0.154.0, worktree experiment |
| Antigravity | 99 | — | /boost command, GEMINI_API_KEY |
| Windsurf | 87 | — | Cognition $48B momentum holding |
| Cursor | 69 | ↓2 | 15th consecutive decline, self-hosted added |
| Aider | 68 | — | No release since v0.86.2 |
| GH Copilot | 1 | — | Floor, unified relaunch 9/28 D-18 |
| Gemini CLI | 1 | — | Shutdown Day 84, replaced by Antigravity |

The Claude Code v2.1.265 gateway regression is hitting LLM proxy users immediately. ChatGPT Images 2.5 and Codex CLI worktree support show OpenAI pushing a dual "coding + creative" strategy. Cursor's 30-point slide lays bare the market-sentiment damage from the post-SpaceX OpenAI breakup — with Claude Code's 9/14 limit adjustment and Copilot's 9/28 relaunch approaching, the developer tool reshuffling will only accelerate.

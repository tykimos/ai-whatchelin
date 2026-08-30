---
title: "DALL-E GPT Exits, Copilot D-1, Cursor Slides to 91 — September Will Reshape AI Coding"
date: 2026-08-30
lang: en
categories: [news]
tags: [chatgpt, dall-e, copilot, cursor, openai, claude-code, anthropic, codex, grok]
excerpt: "DALL-E GPT is officially removed from ChatGPT today. Copilot's September 1 cliff is 24 hours away. Cursor drops to 91 as the OpenAI breakup continues. Grok CLI breaks into the top 5."
---

The official DALL-E GPT has been permanently removed from ChatGPT today, August 30 ([Inc](https://www.inc.com/jelinda-montes/dall-e-gpt-shuts-down-august-30-download-your-images-before-the-official-tool-disappears-tomorrow/91396233)). OpenAI is pushing ChatGPT Images (gpt-image-1 and gpt-image-1-mini) as the replacement, available across all tiers including the free plan ([Notebookcheck](https://www.notebookcheck.net/DALL-E-leaves-ChatGPT-on-August-30-download-your-images-first.1360522.0.html)). Custom GPTs with Image Generation enabled are unaffected.

## Copilot: D-1 — Credit Cuts, Model Purge, Sign-ups Reopen in 24 Hours

Twenty-four hours until the September 1 cliff. Business promotional credits drop from 3,000 to 1,900 (37% cut), and Enterprise from 7,000 to 3,900 (44% cut) ([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Six models — including Gemini 3.1 Pro, Claude Opus 4.5/4.6, Claude Sonnet 4.5/4.6, and Raptor mini — are deprecated across all Copilot experiences ([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Starting no earlier than September 28, Copilot Chat on github.com, Copilot Chat in GitHub Mobile, and GitHub Copilot cloud agent will relaunch as a single unified Copilot experience ([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). The August 28 Visual Studio update lets org/enterprise owners publish custom agents across repositories, and the Copilot Slack integration (@GitHub) entered public preview for agentic coding tasks ([GitHub Blog](https://github.blog/changelog/2026-08-28-github-copilot-in-visual-studio-august-update-2/)).

## Cursor: Drops to 91 — Second Day of OpenAI Breakup Fallout

Yesterday's Bloomberg report on OpenAI terminating its Cursor partnership continues to ripple through the industry ([The Coin Republic](https://www.thecoinrepublic.com/2026/08/30/openai-news-openai-dumps-cursor-after-spacex-deal-sets-november-cutoff/)). With 74 days until GPT model access is cut on November 12, Cursor is pivoting to Grok 4.6 and Anthropic Claude, but the second trust crisis — following the Aur0ra ransomware incident — keeps dragging the score down. Cursor CEO Michael Truell downplayed the impact, saying "OpenAI models serve about 5% of Cursor user traffic," though he confirmed the company is in talks with OpenAI to resolve the dispute ([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). Anthropic co-founder Tom Brown immediately pledged to "continue to increase compute to support Claude models in Cursor" ([WCCFTech](https://wccftech.com/anthropic-pounces-as-openai-abandons-spacexs-cursor-vowing-to-increase-claude-compute-even-as-openai-cites-contract-distrust/)).

## Claude Code: Lighter Binary, Token Visibility + September 14 Limit Change

Claude Code's latest update starts the CLI before the sandbox loads, improving perceived startup speed ([explainx.ai](https://explainx.ai/blog/claude-code-weekly-update-faster-startup-token-visibility-august-2026)). The Linux build has been trimmed to approximately 75 MB, and token details have been added to /cost, /usage, and /tasks commands ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Sonnet 5's $2/$10 pricing has been confirmed permanent, stabilizing developer cost expectations ([Enterprise DNA](https://enterprisedna.co/resources/news/anthropic-claude-sonnet-5-pricing-permanent-reversal-august-2026/)). Meanwhile, Anthropic announced the current 50% promotional limit boost will end on September 14, replaced by a permanent 25% increase ([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)). That's effectively a 17% cut from current levels, though it's still 25% above pre-promotion baselines ([Notebookcheck](https://www.notebookcheck.net/Anthropic-announces-a-25-increase-to-Claude-Code-limits-but-there-s-a-17-catch.1382735.0.html)).

## Codex: Appshots + v0.151.0 New Features

Codex introduced Appshots on macOS, letting users attach an app window to a Codex thread via hotkey — capturing both a screenshot and available text for instant visual context ([Releasebot](https://releasebot.io/updates/openai/codex)). The v0.151.0 release adds a configurable grace period for discovering tools from optional MCP servers and a new `--approve-for-me` CLI flag for auto-reviewed approvals ([Havoptic](https://www.havoptic.com/tools/openai-codex)).

## Grok CLI: Breaks Into Top-5 CLI Agent Rankings

The free, open-source Grok CLI has displaced Antigravity in the top-5 CLI agent rankings this month ([Pinggy](https://pinggy.io/blog/top_cli_based_ai_coding_agents/)). Powered by Grok 4.6, it ships with Git workflows, web search, code search, and MCP server support (Linear, Sentry, Grafana) — signaling the SpaceX-Cursor ecosystem's expansion beyond the IDE into the terminal.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | CLI lighter, Sept 14 limit change coming, stable at top |
| ChatGPT | 99 | — | DALL-E GPT exits today, ChatGPT Images takes over |
| Codex CLI | 99 | — | Appshots, v0.151.0, --approve-for-me |
| Antigravity | 99 | — | Version control improvements, IDE extensions stable |
| Claude AI | 99 | — | Sonnet 5 pricing permanent, Cursor compute pledge |
| Cursor | 91 | ↓2 | OpenAI shutoff D-74, second day of decline |
| Windsurf | 86 | — | Devin Desktop stable, plugin improvements |
| Aider | 68 | — | 44K+ stars, maintenance mode |
| Copilot | 1 | — | D-1: credit cuts + model purge + sign-ups reopening |
| Gemini CLI | 1 | — | Shutdown day 73 |

With September 1 just 24 hours away, the AI coding tool market is about to reset. Copilot faces effective reinvention through credit cuts and model deprecations, while Cursor accelerates its multi-model pivot to Anthropic and xAI after the OpenAI breakup. Grok CLI's rise shows the SpaceX-Cursor ecosystem expanding beyond the IDE into the terminal. For developers, the takeaway is clear: vendor-locked workflows are no longer safe.

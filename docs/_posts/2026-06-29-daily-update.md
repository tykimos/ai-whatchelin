---
title: "GPT-5.6 Caught Running Secretly on Codex, Cursor Ships iOS App"
date: 2026-06-29
lang: en
categories: [news]
tags: [openai, gpt-5.6, cursor, spacex, anthropic, fable-5, claude-code, copilot, antigravity]
excerpt: "OpenAI silently deployed GPT-5.6 to Codex users before its official preview opened. Cursor launches its first iOS app after the SpaceX acquisition. Fable 5 remains suspended at Day 17."
---

OpenAI silently deployed GPT-5.6 Sol to some Codex users before the model's official limited preview was even announced to partners, developers discovered today via a hidden system-prompt parameter ([TechTimes](https://www.techtimes.com/articles/319297/20260629/openai-silently-rolled-gpt-56-some-codex-users-hidden-prompt-exposes-swap.htm)). The revelation raises fundamental questions about how transparently AI vendors communicate model changes to paying users.

## OpenAI: GPT-5.6 Secret Deployment and the "Juice Value" Controversy

OpenAI announced on June 26 that GPT-5.6 would be available only to roughly 20 government-vetted partner organizations ([OpenAI](https://openai.com/index/previewing-gpt-5-6-sol/)). But developers detected the model running beneath their Codex sessions by checking for a 353,000-token context window and a hidden "Juice value" of 128 via the `/status` command ([TechTimes](https://www.techtimes.com/articles/319297/20260629/openai-silently-rolled-gpt-56-some-codex-users-hidden-prompt-exposes-swap.htm)). GPT-5.6 introduces a Sol/Terra/Luna tiering system, with Sol offering an ultra mode for parallel subagent execution ([9to5Mac](https://9to5mac.com/2026/06/26/openai-upgrading-chatgpt-and-codex-with-new-gpt-5-6-models-in-limited-release/)). Meanwhile, GPT-4.5 was officially retired from ChatGPT on June 27 ([OpenAI Help](https://help.openai.com/en/articles/9624314-model-release-notes)).

## Cursor: First iOS App Launches on App Store Post-SpaceX Acquisition

Cursor released its first iPhone and iPad app on the App Store ([9to5Mac](https://9to5mac.com/2026/06/29/cursor-releases-iphone-and-ipad-app-following-recent-acquisition-by-spacex/)). The app — Cursor's first major product release since SpaceX's $60B acquisition agreement — enables launching coding agents remotely, reviewing screenshots and videos of changes, annotating images for visual feedback, inspecting diffs and merging PRs, and voice conversations with agents. It's designed as a remote agent management layer, not a mobile coding environment.

## Fable 5: Day 17 Suspended, "This Week" Restoration Still Pending

Fable 5 remains fully suspended on Day 17 for all general users. Axios reported June 27 that reinstatement could come "as soon as this week," but the Pentagon and NSA still need to give final approval ([Axios](https://www.axios.com/2026/06/27/anthropic-fable-5-return-soon)). Only Mythos 5 has been partially restored for Annex A US entities. Austria sent a formal letter to the EU Commission urging European AI sovereignty in direct response to the Fable 5 ban ([Jerusalem Post](https://www.jpost.com/business-and-innovation/tech-and-start-ups/article-900712)).

## Claude Code v2.1.193 — /rewind, Shell Mode, MCP Auth

The latest Claude Code release adds `/rewind` to resume conversations from before `/clear`, `claude mcp login/logout` for shell-based MCP authentication, and automatic responses to command output in shell mode ([Anthropic](https://code.claude.com/docs/en/whats-new)). Background subagents now surface permission prompts in the main session instead of auto-denying, and CPU/memory usage during streaming has been reduced.

## Copilot Hits 27 on 55th Consecutive Week of Decline

GitHub Copilot dropped to 27, marking its 55th consecutive week of decline. Day 29 of usage-based billing means a full month has passed since the switch, with agentic sessions still costing $30-40 per day ([GitHub Discussions](https://github.com/orgs/community/discussions/197089)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.193 /rewind, MCP auth, CPU optimization |
| ChatGPT | 97 | — | GPT-5.6 secret deployment detected, GPT-4.5 retired |
| Claude AI | 96 | — | Fable 5 D17, EU AI sovereignty debate triggered |
| Cursor | 96 | — | iOS app launched on App Store |
| Codex CLI | 88 | — | GPT-5.6 Sol secretly deployed to some users |
| Antigravity | 87 | ↑1 | 11-week streak, absorbing Gemini CLI migration |
| Windsurf | 85 | — | Cascade EOL in 2 days (Jul 1) |
| Aider | 68 | — | Open-source stable |
| Gemini CLI | 30 | ↓2 | Shutdown Day 12, enterprise-only floor |
| Copilot | 27 | ↓1 | 55-week decline, billing Day 29 |

The GPT-5.6 secret deployment opens a new chapter in AI vendor transparency debates. The practice of swapping models without notifying paying users — combined with Copilot's ongoing billing backlash — signals that developer trust is becoming the defining competitive variable in the coding tools market.

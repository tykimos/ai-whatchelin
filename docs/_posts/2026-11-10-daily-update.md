---
title: "Cursor's OpenAI Cutoff D-2 — Copilot Lands in JetBrains Air and Xcode"
date: 2026-11-10
lang: en
categories: [news]
tags: [cursor, openai, github-copilot, claude-code, anthropic, gemini-cli]
excerpt: "OpenAI's model cutoff for Cursor is two days away. Meanwhile, Copilot expands into JetBrains Air, Xcode, and ships GPT-6.1 Terra."
---

Cursor's reckoning is nearly here. With OpenAI's model cutoff confirmed for November 12, GitHub Copilot isn't just absorbing the vacuum — it's expanding aggressively into JetBrains Air and Xcode while adding GPT-6.1 Terra to its arsenal.

## Cursor: OpenAI Cutoff D-2, Day 77 at Bottom

OpenAI's complete termination of Cursor's model access is now just two days away, set for November 12 ([InfoWorld](https://www.infoworld.com/article/4216503/cursor-customers-will-lose-access-to-openai-coding-models-in-november.html)). The contract clause was triggered by SpaceX's $60 billion acquisition of Anysphere. Cursor's co-founder noted that OpenAI models account for only about 5% of total traffic ([The New Stack](https://thenewstack.io/openai-cuts-cursor-spacex/)), but the psychological impact runs deeper — the tool has been pinned at a popularity score of 1 for 77 consecutive days.

## GitHub Copilot: JetBrains Air, Xcode, and GPT-6.1 Terra

A big week for Copilot's reach. On November 3, GitHub shipped Copilot as a selectable agent inside JetBrains Air, using the Agent Client Protocol (ACP) to run tasks locally or in the cloud ([GitHub Blog](https://github.blog/changelog/2026-11-03-github-copilot-is-now-available-in-jetbrains-air)). The next day, Copilot landed in Xcode's native coding assistant as a public preview, with GA expected alongside Xcode 27.3 in December ([GitHub Blog](https://github.blog/changelog/2026-11-06-github-copilot-weekly-releases-november-2)). The weekly release also introduced Agent Merge, letting Copilot auto-merge PRs once all required checks pass.

On the model front, Copilot CLI v1.0.106 added GPT-6.1 Terra to the model picker ([GitHub Blog](https://github.blog/changelog/2026-10-26-gpt-6.1-terra-in-github-copilot)). Terra is optimized for everyday agentic coding at lower cost than Sol, available on Pro, Pro+, Max, Business, and Enterprise plans ([Visual Studio Magazine](https://visualstudiomagazine.com/articles/2026/10/28/github-copilot-adds-gpt-6-1-terra-for-lower-cost-agentic-coding.aspx)). Copilot's popularity has now risen for 46 consecutive days, absorbing Cursor's lost market share.

## Claude Code: v2.1.319 Brings Auto Mode

Claude Code v2.1.319 shipped with a new Auto Mode ([claudekit](https://claudekit.io/en/updates/claude-code-2-1-319/)). When telemetry is disabled behind an LLM gateway, calls the server can't inspect are now handled via server-side approval rather than the built-in classifier. The release also adds MCP task support in the terminal and gateway management features ([labmemo](https://labmemo.com/claude-code-v2-1-319-auto-mode-gateway-mcp-task-2026-11/)). This comes as the fallout from last week's credential leak report (2,539 secrets across 1,994 public repos) continues.

## Anthropic: IPO Pricing D-3

Anthropic's Nasdaq (ANT) IPO pricing is expected on November 13. The simultaneous launch of Fable 5.2 and Mythos 5.2 with a 20% price cut, paired with METR's RSI warning about covert capabilities, creates a complex backdrop for investors ([TechCrunch](https://techcrunch.com/2026/11/09/anthropic-releases-new-mythos-and-fable-models-amid-rsi-concerns/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Stabilizing after degradation |
| Claude Code | 99 | — | v2.1.319 Auto Mode shipped |
| Codex CLI | 99 | — | Stable |
| Antigravity | 99 | — | Stable |
| Claude AI | 99 | — | IPO pricing D-3 |
| GH Copilot | 89 | ↑2 | 46-day streak; JetBrains Air, Xcode, Terra |
| Windsurf | 88 | — | Stable |
| Aider | 68 | — | Maintenance mode |
| Cursor | 1 | — | OpenAI cutoff D-2, day 77 at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition complete |

With Cursor's OpenAI cutoff just 48 hours away, the AI coding tool landscape is at an inflection point. Copilot's triple expansion — JetBrains Air, Xcode, and Terra — signals Microsoft's play for the post-Cursor vacuum, while Claude Code pushes security improvements amid last week's credential leak fallout.

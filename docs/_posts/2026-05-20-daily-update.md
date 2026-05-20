---
title: "Antigravity 2.0 Nukes Its Own Code Editor the Day After Launch — Half of I/O Gains Evaporate"
date: 2026-05-20
lang: en
categories: [news]
tags: [antigravity, google-io, managed-agents, code-with-claude, copilot, gemini-cli, cursor]
excerpt: "The day after Google I/O, Antigravity's auto-update wiped out developer environments — terminals, editors, and file explorers vanished. Forums erupted while I/O Day 2's Managed Agents API and Code with Claude London Extended quietly built the future."
---

Yesterday, Antigravity posted the largest single-day jump in WhatChelin history (+14). Today it's in the headlines for the exact opposite reason: Google's automatic update destroyed the code editor, and forums are overflowing with developers calling it "non-technical people shipping code to production."

## Antigravity 2.0: A Historic Own Goal

When developers opened Antigravity after the May 19 auto-update, terminals, file explorers, and editing tools were gone ([Techloy](https://www.techloy.com/why-googles-antigravity-2-0-ai-update-has-developers-furious/)). Google split the app into three separate downloads — **Antigravity 2.0** (agent orchestration), **Antigravity IDE** (coding), and **Antigravity CLI** (terminal) — but the old config path (`\Roaming\Antigravity`) doesn't match the new one (`\Roaming\Antigravity IDE`), wiping extensions and settings ([PiunikaWeb](https://piunikaweb.com/2026/05/20/fix-google-antigravity-2-0-missing-ide-error/)). Reddit and Google AI Developers forums were flooded within hours. Many developers are rolling back to v1.23.2 and disabling auto-updates entirely ([Google AI Developers Forum](https://discuss.ai.google.dev/t/whats-with-antigravity-2-0/145451)).

## Google I/O Day 2: Managed Agents API + Chrome DevTools for Agents

The real developer sessions kicked off today. **Managed Agents in the Gemini API** provisions a fully sandboxed agent with the Antigravity harness via a single API call ([Google Developers Blog](https://developers.googleblog.com/all-the-news-from-the-google-io-2026-developer-keynote/)). **Chrome DevTools for agents** automates quality audits and emulates real-world user experiences, while **WebMCP** proposes an open web standard for agent-accessible tools ([Google I/O](https://io.google/2026/explore/technical-session-2)). The Antigravity SDK enables self-hosted deployments, and a new **Migration Agent** converts React Native/iOS code to native Kotlin.

## Code with Claude London Extended

Anthropic is running Day 2 in London exclusively for indie developers and early-stage founders ([claude.com](https://claude.com/code-with-claude/london-extended)). Demos, office hours, and laptops-open workshops from the Applied AI team run all day. Yesterday's **Claude Code v2.1.144** — with /resume for background sessions, MCP tunnels, and self-hosted sandboxes — gets hands-on testing in real-world projects.

## Copilot: 16-Week Slide Continues, D-12

GitHub Copilot dropped to 67, marking its **16th consecutive weekly decline**. Twelve days remain until usage-based billing on June 1 — code completions and Next Edit suggestions stay free, but Chat, CLI, Cloud Agent, Spaces, and Spark all consume AI Credits ([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). The community continues to criticize the Pro+ structure where $39/mo includes only $39 in credits — effectively "pay the same, get less."

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | Musk verdict cleared legal uncertainty |
| Claude Code | 98 | — | CwC London Extended, v2.1.144 |
| Cursor | 96 | — | Composer 2.5 settling in, xAI partnership buzz |
| Claude AI | 93 | — | CwC London Extended, agent metering D-26 |
| Gemini CLI | 86 | ↑1 | I/O Day 2 Managed Agents API unveiled |
| Codex CLI | 84 | — | Dell partnership steady |
| Windsurf | 81 | — | Devin Review/Terminal GA |
| Aider | 68 | — | Stable, 41.6K GitHub stars |
| GitHub Copilot | 67 | ↓1 | 16-week slide, new all-time low |
| Antigravity | 58 | ↓4 | Auto-update fiasco erases half of I/O surge |

## Anthropic Acquires Stainless for $300M+

Anthropic confirmed its acquisition of Stainless, the developer tools company behind every official Claude SDK as well as SDKs for OpenAI, Google DeepMind, Cloudflare, Perplexity, and Groq ([Anthropic](https://www.anthropic.com/news/anthropic-acquires-stainless)). Stainless will wind down its hosted SDK generator; existing customers retain ownership of already-generated SDKs. Anthropic now controls the model (Claude), the connectivity standard (MCP), and the SDK toolchain — a vertical integration play for the agent era ([The Register](https://www.theregister.com/ai-ml/2026/05/20/anthropics-stainless-steal-tightens-grip-on-ai-dev-tooling/5243053)).

## Cursor Now Available in Jira

Cursor is now available inside Jira ([Cursor Changelog](https://cursor.com/changelog/05-19-26)). Assign work items to Cursor or @mention it in a comment to spin up a cloud agent that reads the ticket context, builds the fix, and posts a PR link back to Jira. Requires Jira Commercial Cloud with Rovo.

Today's theme is the **paradox of execution**. Antigravity posted its biggest-ever day just 24 hours ago, then lost trust with a single botched auto-update. "A good announcement" and "a good launch" aren't the same thing. Anthropic's Stainless acquisition sends the opposite message — lock down the infrastructure before the announcement. Meanwhile, Gemini CLI quietly climbed to 86 on Managed Agents API excitement, overtaking Codex CLI (84).

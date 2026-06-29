---
title: "Fable 5 Still Locked at Day 17 as Anthropic Sunsets Opus 4.7 Fast Mode"
date: 2026-06-29
lang: en
categories: [news]
tags: [anthropic, fable-5, claude-code, opus-4.7, copilot, antigravity, windsurf, spacex]
excerpt: "Fable 5 remains suspended on Day 17 while Anthropic begins deprecating Opus 4.7 fast mode. Copilot drops to 27 on its 55th consecutive week of decline, and Antigravity hits 87 on an 11-week streak."
---

Anthropic is under pressure on multiple fronts. Fable 5 remains fully suspended on Day 17 for all general users, while Opus 4.7 fast mode was officially deprecated on June 25 with complete removal set for July 24 ([Anthropic Docs](https://platform.claude.com/docs/en/build-with-claude/fast-mode)). Developers using fast mode must migrate to Opus 4.8 — which is also significantly cheaper at $10/$50 per MTok versus Opus 4.7's $30/$150.

## Fable 5: "This Coming Week" Report, But Still No Movement

Axios reported on June 27 that the Trump administration is "close" to restoring Fable 5, potentially "as soon as this week" ([Axios](https://www.axios.com/2026/06/27/anthropic-fable-5-return-soon)). Commerce Secretary Lutnick's June 26 letter cleared Mythos 5 for Annex A entities (approved US institutions) only, but Fable 5 remains blocked for all consumers, API developers, Claude Code users, and international subscribers ([Fortune](https://fortune.com/2026/06/27/anthropic-mythos-5-ai-model-us-commerce-department-clearance-fable/)). The July 8 identity verification policy (government ID + selfie) is emerging as the key pathway for US-only restoration.

## Claude Code v2.1.193 — Streamlined MCP Authentication

The latest Claude Code release adds `claude mcp login`/`logout` commands for authenticating MCP servers directly from the shell ([Anthropic](https://code.claude.com/docs/en/whats-new)). Shell mode now automatically responds to command output (like explanations for `npm test` without a second prompt), and `/rewind` can resume conversations from before `/clear` was run. Team and Enterprise plans also gain Trusted Devices for remote control, requiring device verification before accessing remote Claude Code sessions ([Anthropic](https://www.anthropic.com/news)).

## Copilot Hits 27 on 55th Consecutive Week of Decline

GitHub Copilot dropped to 27, marking its 55th consecutive week of decline. Day 29 of usage-based billing means a full month has passed since the switch, with agentic sessions still costing $30-40 per day and driving developers away ([GitHub Discussions](https://github.com/orgs/community/discussions/197089)). The JetBrains Developer Ecosystem Survey puts Copilot at 29% market share, with Cursor and Claude Code each at 18% and closing fast ([NxCode](https://www.nxcode.io/resources/news/github-copilot-getting-worse-2026-developers-switching)).

## Windsurf Cascade EOL D-2 — Migration Deadline Looming

Windsurf's legacy local AI agent Cascade shuts down on July 1. CI pipelines and automation scripts that call Cascade directly must be migrated to Devin Local within the next two days. Devin Local, a Rust rewrite, claims 30% token savings over its predecessor.

## SPCX Correction Continues — Down 32% From ATH

SpaceX (SPCX) is trading at ~$153, down 32% from its June 16 all-time high of $225 ([Yahoo Finance](https://finance.yahoo.com/quote/SPCX/)). The $60B Cursor acquisition agreement remains on track for a Q3 close.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.193 MCP auth, shell mode improvements |
| ChatGPT | 97 | — | GPT-5.6 limited preview continues, GA "coming weeks" |
| Claude AI | 96 | — | Fable 5 D17, Opus 4.7 fast deprecation begins |
| Cursor | 96 | — | SpaceX $60B acquisition on track for Q3 |
| Codex CLI | 88 | — | GPT-5.6 available to preview orgs via Codex |
| Antigravity | 87 | ↑1 | 11-week streak, absorbing Gemini CLI migration |
| Windsurf | 85 | — | Cascade EOL in 2 days (Jul 1) |
| Aider | 68 | — | Open-source stable |
| Gemini CLI | 30 | ↓2 | Shutdown Day 12, enterprise-only floor |
| Copilot | 27 | ↓1 | 55-week decline, billing Day 29 |

Antigravity's 11-week streak stands out — steadily absorbing Gemini CLI migration demand to reach 87, with a 90+ score possible by mid-July at this pace. Meanwhile, Copilot's month-long free fall since usage-based billing confirms a fundamental shift in the coding tools market.

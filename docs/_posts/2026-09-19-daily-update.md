---
title: "Claude Code Embraces Codex Compatibility With AGENTS.md Support — Cursor Hits 30-Day Decline"
date: 2026-09-19
lang: en
categories: [news]
tags: [claude-code, cursor, openai, codex-cli, antigravity, agents-md]
excerpt: "Claude Code v2.1.277 adds AGENTS.md reading, establishing cross-tool compatibility with Codex CLI projects. Cursor drops to 53 on its 30th consecutive day of decline."
---

Claude Code shipped v2.1.277 today with official AGENTS.md file support — when a project has no CLAUDE.md, the agent now automatically reads AGENTS.md as project instructions ([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). This effectively makes Claude Code compatible with OpenAI Codex CLI's project configuration format, marking the first official interoperability move between terminal-based coding agents. For developers juggling multiple tools, switching just got significantly easier.

## Claude Code: AGENTS.md Support Bridges the Codex Ecosystem

The headline feature in v2.1.277 is AGENTS.md compatibility ([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). Auto mode for Claude API, Enterprise, and Bedrock/Vertex/Foundry/gateway users now defaults to the server-side classifier, eliminating classifier overhead charges. The update also introduces `CLAUDE_GATEWAY_PROXY_IS_EGRESS_BOUNDARY` for gateway proxies and an optional headers map for upstream static headers. Background task notification improvements and session hang prevention round out the stability fixes.

## Cursor: 53 Points, 30 Consecutive Days of Decline — 50-Floor Approaching

Cursor dropped to 53, marking exactly 30 consecutive days of decline since the SpaceX acquisition closed on August 14 ([TechCrunch](https://techcrunch.com/2026/08/15/spacex-officially-closes-its-cursor-acquisition/)). With 54 days until OpenAI's November 12 model access cutoff, the 50-point psychological floor is now just days away. Cursor Projects beta (a coordinator agent delegating to thousands of subagents) launched on September 10 but has failed to arrest the slide. OpenAI cites Musk-owned companies' history of contract violations as grounds for termination ([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)), while Cursor maintains that OpenAI models represent only 5% of its traffic.

## OpenAI Codex CLI: GPT-5.5 Retirement D-25, Sol Migration Accelerates

GPT-5.5 retires from ChatGPT and Codex on October 14 across all plans ([OpenAI Deprecations](https://developers.openai.com/api/docs/deprecations)). Migration to GPT-5.6 Sol (gpt-5.6-sol) is now urgent — workspace defaults, custom agents, and scripts all need updating. Sol's API pricing was cut 20%+ on August 21 (input $5 to $4, output $30 to $20), with the promotion running through November 21 ([OpenAI](https://openai.com/index/gpt-5-6/)).

## Antigravity: v2.13.0 Stabilized, IDE Extensions Maturing

Google Antigravity v2.13.0 (September 14) delivered a new Documents section, C++/Python/Protobuf syntax highlighting, file pill hover tooltips, and a built-in Guide skill, along with 16 improvements and 16 bug fixes ([Antigravity Blog](https://antigravity.google/blog/google-io-2026)). IDE extensions across VS Code, JetBrains, Zed, and Visual Studio are entering their stabilization phase.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Word add-in, Astra for Law stable |
| Claude Code | 99 | — | v2.1.277, AGENTS.md interop |
| Claude AI | 99 | — | R&D 26% leadership, self-improvement ongoing |
| Codex CLI | 99 | — | GPT-5.5→Sol migration D-25 |
| Antigravity | 99 | — | v2.13.0 stabilized |
| Windsurf | 87 | — | Devin Desktop stable phase |
| Aider | 68 | — | 44K stars, steady releases |
| Cursor | 53 | ↓2 | Day 30 decline, 50-floor imminent |
| GH Copilot | 1 | — | Unified experience D-9 (Sep 28) |
| Gemini CLI | 1 | — | Shutdown day 94 |

Interoperability between terminal agents has begun. Claude Code's AGENTS.md support signals coexistence over competition, and for developers, it means lower switching costs across the tools they rely on.

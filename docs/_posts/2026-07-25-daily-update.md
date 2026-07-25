---
title: "Claude Opus 5 Drops — Doubles Frontier-Bench, MCP Goes Stateless"
date: 2026-07-25
lang: en
categories: [news]
tags: [anthropic, claude, opus-5, claude-code, mcp, antigravity, github-copilot, kiro, huawei]
excerpt: "Anthropic launches Claude Opus 5 with 2x Frontier-Bench performance at the same price, while the MCP stateless architecture RC signals breaking changes across the entire ecosystem."
---

Anthropic launched Claude Opus 5 yesterday, shaking up the AI coding tool landscape once again. The model doubles Opus 4.8 on Frontier-Bench v0.1 while keeping pricing at the same $5/$25 per MTok([Fortune](https://fortune.com/2026/07/24/anthropic-debuts-claude-opus-5-with-feature-that-lets-users-toggle-between-cost-and-capability/)). Simultaneously, the largest MCP protocol overhaul RC dropped, making the final week of July a seismic one for the entire AI development ecosystem.

## Claude Opus 5: Same Price, Double the Performance

Opus 5 ships with a 1M-token context window, 128K max output, and thinking enabled by default([9to5Mac](https://9to5mac.com/2026/07/24/anthropic-upgrades-claude-with-new-opus-5-model-details-here/)). The standout feature is a per-request low/medium/high effort toggle — save costs on simple tasks, pour full power into complex ones. It surpasses Fable 5 on OSWorld 2.0 at one-third the cost. Available immediately across Claude API, Amazon Bedrock, Google Cloud, Microsoft Foundry, claude.ai, Claude Code, and Claude Cowork.

## Claude Code v2.1.219: Opus 5 Now Default

Claude Code updated to v2.1.219 with Opus 5 set as the default Opus model([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Subagents can now nest up to depth 3, enabling more complex multi-agent workflows. A new `sandbox.network.strictAllowlist` setting blocks non-approved hosts. Opus 4.7 is fully retired from fast mode — only Opus 5 and Opus 4.8 remain.

## MCP 2026-07-28 RC: The Stateless Revolution

The largest revision in MCP history went live as a release candidate([The Register](https://www.theregister.com/devops/2026/07/23/model-context-protocol-prepares-to-break-with-its-stateful-past/5276722)). Session state, the initialize handshake, and protocol-level sessions are all eliminated — every request becomes self-contained. New additions include server-rendered UIs (MCP Apps), long-running Tasks, and tighter OAuth/OIDC authorization. Final release targets July 28, with breaking changes that demand immediate attention from MCP server operators([Developers Digest](https://www.developersdigest.tech/blog/mcp-2026-07-28-breaking-changes)).

## Antigravity CLI v1.1.6-v1.1.7: Two Releases in One Day

Antigravity CLI shipped two releases in a single day([Antigravity Changelog](https://antigravity.google/changelog)). v1.1.6 adds custom agents in Markdown format (`agent.md`) and progressive streaming for `/codesearch`. v1.1.7 improves permission prompts for compound shell commands and fixes CJK clipboard copying on Windows.

## GitHub Copilot: Opus 5 Day-One, Decline Continues

GitHub Copilot added Opus 5 on launch day across Pro/Pro+/Max/Business/Enterprise plans([GitHub Changelog](https://github.blog/changelog/2026-07-24-claude-opus-5-is-now-available-in-github-copilot/)). Gemini 2.5 Pro and Gemini 3 Flash will be removed from Copilot on July 31. Despite the new model addition, the 77-week decline continues — all eyes on whether the GitHub Models transition (July 30) can spark a turnaround.

## Kiro: RCE Vulnerability Disclosed

A remote code execution flaw was discovered in AWS's Kiro IDE([The Hacker News](https://thehackernews.com/2026/07/aws-kiro-flaw-let-poisoned-web-page.html)). A poisoned web page could rewrite Kiro's MCP config and execute arbitrary code. Users should update to v1.0.165 or later immediately.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 default, v2.1.219 shipped |
| ChatGPT | 99 | — | GPT-5.6 Sol stable, Codex teaser unconfirmed |
| Antigravity | 99 | — | Two releases in one day (v1.1.6-v1.1.7) |
| Claude AI | 99 | ↑1 | Opus 5 launch, 98→99 |
| Cursor | 97 | — | Router adoption expanding, cost savings confirmed |
| Codex CLI | 91 | — | "Codexy" tease, no official announcement |
| Windsurf | 85 | — | Devin Desktop stable operations |
| Aider | 68 | — | No major updates |
| Copilot | 1 | — | 77-week decline, Opus 5 added but floor holds |
| Gemini CLI | 1 | — | Consumer access closed 37 days |

Opus 5 and the MCP stateless overhaul define this week. Opus 5 delivering double the performance at the same price solidifies Anthropic's value-for-money lead, while MCP's breaking changes demand immediate action from every server operator before the July 28 final release.

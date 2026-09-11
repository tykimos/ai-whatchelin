---
title: "Cursor Bets on Multi-Agent 'Projects' to Reverse 16-Day Slide"
date: 2026-09-11
lang: en
categories: [news]
tags: [cursor, claude-code, codex-cli, anthropic, openai, chatgpt]
excerpt: "Cursor unveiled Projects, a coordinator agent orchestrating thousands of subagents, as its stock continues a 16-day slide. Claude Code v2.1.268 and Codex CLI also shipped major updates."
---

Cursor just played its biggest card since the SpaceX acquisition. The 'Projects' beta, which began rolling out yesterday (Sep 10), introduces a coordinator agent that delegates tasks to thousands of subagents while maintaining context across months of work, all running in the cloud ([Cursor Blog](https://cursor.com/blog)). It subscribes to external signals — Slack threads, PR events, schedules — and Cursor's internal data shows primary Projects users merge six times more PRs ([Releasebot](https://releasebot.io/updates/cursor)). Whether this reverses the 16-day decline from 99 to 68 is the question of the week.

## Cursor: Self-Hosted Machines + Projects, a Two-Pronged Counterattack

Combined with Self-Hosted Machines (launched Sep 2), Cursor now offers a hybrid architecture where the agent loop and inference run in Cursor's cloud while tool execution stays on the user's network ([Cloudflare Changelog](https://developers.cloudflare.com/changelog/post/2026-09-02-cursor-cloud-agents/)). Eight sandbox backends are supported: Lambda, Cloudflare, Coder, Daytona, E2B, Modal, Namespace, and Vercel. With the OpenAI model cutoff (Nov 12) now 62 days away, Cursor is betting that product innovation can outrun sentiment-driven attrition.

## Claude Code v2.1.268: Gateway Pricing Parity, Enhanced Plugin Management

Today's v2.1.268 release brings gateway pricing parity for signed-in clients and adds a `gatewayInternalNetworks` admin setting for access control ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Plugin management commands (install, uninstall, update, enable, disable) now output JSON, enabling automation pipeline integration. The HTTP 400 regression introduced in v2.1.265 affecting third-party endpoints has been fixed. The September 14 weekly limit cut (17% effective reduction) is now just D-3 ([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)).

## Codex CLI: GPT-6 Astra Integration, Worktree Sessions Go Experimental

Yesterday's major Codex CLI update integrated GPT-6 Astra into the model picker and Amazon Bedrock ([Gradually.ai](https://www.gradually.ai/en/changelogs/codex-cli/)). The experimental `--worktree` flag enables isolated Git checkouts, and a new inline Q&A feature lets developers ask questions while Codex continues working. OpenAI also launched the Agents API public beta on the same day, exposing the managed Codex harness — sessions, orchestration, context compaction, and recovery — to third-party developers.

## Anthropic: Threat Report and Enterprise Smart Reports Drop Together

Anthropic published its September threat intelligence report today, disclosing that Claude Code was used to build autonomous drone swarm kill software ([Anthropic](https://www.anthropic.com/threat-intelligence-report-september-2026)). The report's starkest line: newer Claude models "can no longer be assumed below the threshold for meaningful bioweapons assistance" — a first for any major AI company ([TechTimes](https://www.techtimes.com/articles/327308/20260911/anthropic-threat-report-ai-models-near-bioweapons-threshold-drone-kill-software-emerges.htm)). Meanwhile, Claude Enterprise Smart Reports quietly launched in beta, analyzing team usage patterns, costs, and friction points to surface reusable shared skills ([Releasebot](https://releasebot.io/updates/anthropic/claude)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Astra 1-week GA, Deep Research expansion |
| Claude Code | 99 | — | v2.1.268, threat report, 9/14 limit cut D-3 |
| Claude AI | 99 | — | Enterprise Smart Reports beta |
| Codex CLI | 99 | — | GPT-6 Astra integration, worktree experiment, Agents API beta |
| Antigravity | 99 | — | /boost stable, GEMINI_API_KEY support |
| Windsurf | 87 | — | Cognition $47B valuation momentum |
| Cursor | 68 | ↑1 | Projects beta: first uptick in 16-day decline |
| Aider | 68 | — | No release since v0.82.0 |
| GH Copilot | 1 | — | Floor, October triple reset D-17 |
| Gemini CLI | 1 | — | Shutdown Day 85, replaced by Antigravity |

Whether Cursor Projects becomes a real turning point or merely slows the bleed depends on next week. Without resolution of the OpenAI model cutoff — the structural headwind — product innovation alone may not be enough to fully reverse sentiment.

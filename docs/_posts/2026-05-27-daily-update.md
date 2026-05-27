---
title: "Anthropic Closes $30B+ at $900B Valuation — Claude Code v2.1.152 Ships Auto-Fix"
date: 2026-05-27
lang: en
categories: [news]
tags: [anthropic, claude-code, github-copilot, copilot-studio, spacex, gemini-api, grok-build, claude-mythos]
excerpt: "Anthropic surpasses OpenAI as the world's most valuable private AI startup after closing its $30B+ round. Claude Code v2.1.152 introduces code review auto-fix, and Managed Agents gain self-hosted sandboxes."
---

Anthropic closed its $30 billion-plus funding round at a $900B+ pre-money valuation, surpassing OpenAI to become the world's most valuable private AI startup ([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-22/anthropic-to-close-over-30-billion-round-as-soon-as-next-week)). Sequoia Capital, Dragoneer, Altimeter Capital, and Greenoaks Capital Partners co-led with roughly $2 billion each, with Microsoft and NVIDIA also participating ([Yahoo Finance](https://finance.yahoo.com/sectors/technology/articles/anthropic-set-close-30-billion-203545596.html)). An October 2026 IPO is expected, with Wilson Sonsini hired to prepare the listing.

## Claude Code v2.1.152: Code Review Auto-Fix

Claude Code shipped v2.1.152 with `/code-review --fix`, which applies review findings directly to your working tree ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Skills can now declare `disallowed-tools` in frontmatter, `/reload-skills` refreshes skills mid-session, and `SessionStart` hooks fire on session launch. The release also fixes terminal styling degradation in long sessions.

## Claude Managed Agents: Self-Hosted Sandboxes + MCP Tunnels

Two major enterprise features landed for Managed Agents ([claude.com](https://claude.com/blog/claude-managed-agents-updates)). Self-hosted sandboxes (public beta) let tool execution run on your own infrastructure or managed providers like Cloudflare, Daytona, Modal, or Vercel. MCP tunnels (research preview) enable agents to reach MCP servers inside private networks without public endpoints, with end-to-end encryption ([InfoQ](https://www.infoq.com/news/2026/05/claude-mcp-tunnels/)).

## GitHub Copilot: 23-Week Slide Hits 60

Copilot's popularity score dropped to 60 — its all-time low and 23rd consecutive week of decline ([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)). With 5 days until June 1 usage-based billing, agent and chat features will consume AI Credits while code completions remain unlimited. GitHub shipped targeted model rules in public preview, letting enterprise admins control which models are available per org ([GitHub Changelog](https://github.blog/changelog/2026-05-26-target-copilot-models-to-organizations-with-model-rules/)).

## Copilot Studio: First GA Computer-Use Agents

Microsoft's Copilot Studio made computer-using agents generally available across all commercial Power Platform geographies ([Microsoft Copilot Blog](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/new-and-improved-computer-using-agents-a-new-workflows-experience-and-real-time-voice-experiences/)). The agents interact with desktop and web apps through the UI — clicking, typing, and navigating like a human. Ships with OpenAI CUA and Claude Sonnet 4.5 as production models — the first platform with contractual GA for computer-use agents.

## SpaceX IPO: Largest Ever on Track

SpaceX is targeting a $1.75 trillion valuation and $75 billion raise — potentially the largest IPO in history ([CNBC](https://www.cnbc.com/2026/05/20/spacex-ipo-live-updates.html)). Roadshow begins June 4, pricing set for June 11, trading starts June 12 on Nasdaq (SPCX). Goldman Sachs leads underwriting. The S-1 filing confirmed Anthropic pays $1.25 billion monthly for Colossus compute.

## Gemini API: Breaking Change, June 8 Deadline

The Gemini Interactions API replaced `outputs` with a new `steps` array and introduced a polymorphic `response_format` ([Google AI for Developers](https://ai.google.dev/gemini-api/docs/interactions-breaking-changes-may-2026)). The new schema became the default on May 26; legacy support via `Api-Revision: 2026-05-07` header ends June 8. Developers must migrate immediately.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 98 | — | v2.1.152 + Managed Agents boost |
| ChatGPT | 98 | — | GPT-5.5 Instant momentum |
| Cursor | 96 | — | Composer 2.5 holding steady |
| Claude AI | 94 | — | $900B+ round closed |
| Codex CLI | 88 | — | 5-week high plateau |
| Windsurf | 81 | — | Post-outage stable |
| Gemini CLI | 80 | ↓1 | Sunset D-22, API breaking change |
| Aider | 68 | — | Stable |
| GH Copilot | 60 | ↓1 | 23-week slide, all-time low |
| Antigravity | 56 | ↑1 | 4-day recovery post-rollback |

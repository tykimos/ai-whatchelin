---
title: "Cursor Breaks Below 50 — Day 32 of Decline as Claude Code Adds AGENTS.md Support"
date: 2026-09-21
lang: en
categories: [news]
tags: [cursor, claude-code, antigravity, codex-cli, github-copilot, chatgpt, aider]
excerpt: "Cursor drops to 49 after 32 consecutive days of decline since SpaceX's acquisition closed. Meanwhile Claude Code adds AGENTS.md support, ChatGPT ships Word integration, and Copilot gains a Sentry canvas."
---

Cursor has broken through the 50-point floor. After 32 consecutive days of decline since the SpaceX acquisition closed on August 14, it hit 49 — entering the 40s for the first time ([CNBC](https://www.cnbc.com/2026/06/16/spacex-spcx-cursor-acquisition-ipo.html)). With 52 days left until OpenAI's November 12 model access cutoff, the Plugin4Shell non-patch and sandbox escape CVE-2026-48124 continue to weigh on sentiment.

## Cursor: Projects Beta Plays the Comeback Card, but the Score Keeps Falling

Cursor launched Projects in beta on September 10, bringing a cloud coordinator that delegates work to thousands of subagents ([AI Weekly](https://aiweekly.co/alerts/cursor-ships-projects-beta-with-delegating-coordinator-agent)). The coordinator keeps running when the developer's laptop is closed, decoupling agent throughput from human availability ([Pondero](https://pondero.ai/news/2026-09-11-cursor-projects/)). Cursor claims engineers using Projects as their primary workflow merged six times as many pull requests ([Technobezz](https://www.technobezz.com/news/cursor-projects-cloud-agents-beta)). Yet amid the SpaceX acquisition uncertainty and compounding security issues, the score slid to 49.

## Claude Code: AGENTS.md Support and Server-Side Auto Mode

Claude Code v2.1.277 added AGENTS.md support — in projects without a CLAUDE.md, Claude Code now reads AGENTS.md instead ([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). Follow-up release v2.1.278 switched auto mode for Claude API and Enterprise users to a server-side classifier by default, eliminating classifier overhead costs ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Custom request headers for LLM gateways were also added.

## Antigravity: antigravity-preview-09-2026 Generation Shift

Google released antigravity-preview-09-2026 on September 17, replacing and deprecating the May build ([Releasebot](https://releasebot.io/updates/google/antigravity)). Breaking changes include PascalCase parameters replacing snake_case and line-range edits replacing full file rewrites ([GitHub PR #83](https://github.com/google-gemini/gemini-skills/pull/83)). The May build retires on October 5 ([Creators Toolbox](https://creatorstoolbox.com/blog/google-gemini-antigravity-agent-09-2026)).

## ChatGPT: Microsoft Word Sidebar Goes Live

ChatGPT shipped Microsoft Word integration, letting users draft from notes, summarize documents, revise selected text, and adjust formatting from the ChatGPT sidebar ([ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). Available on all plans including Free.

## GitHub Copilot: Sentry Canvas and Unified Experience D-7

A new Sentry canvas in the GitHub Copilot app lets developers review production crash errors and stack traces, investigate causes, and prepare pull requests — all from the Copilot interface ([GitHub Changelog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)). Auto model selection now offers three tiers: efficiency, balance, and intelligence. The unified experience launches in 7 days (September 28), and a mass model retirement on October 2 will remove Gemini 3.5/3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7 ([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)).

## Aider: Development Stalls, Community Fork cecli Takes the Torch

Official Aider development has visibly stalled — no tagged release since August 2025, one PyPI patch in February 2026, and 500+ open pull requests piling up ([shortlisted.tools](https://shortlisted.tools/products/aider)). The community fork cecli (formerly Aider CE) has stepped in with weekly releases and an added agent mode, effectively becoming the successor.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Word integration launched, GPT-5.5 retirement D-23 |
| Claude Code | 99 | — | v2.1.278, AGENTS.md support + server-side auto mode |
| Claude AI | 99 | — | Fable 5.1 frontier holds |
| Codex CLI | 99 | — | v0.154.0, GPT-5.3 Spark retired |
| Antigravity | 99 | — | 09-2026 preview build generation shift |
| Windsurf | 87 | — | Devin Desktop · RSA-260 buzz continues |
| Aider | 68 | — | Official dev stalled, cecli fork leads |
| Cursor | 49 | ↓2 | Day 32 decline, first break below 50 |
| GH Copilot | 1 | — | Unified experience D-7, Sentry canvas added |
| Gemini CLI | 1 | — | Shutdown day 96 |

Cursor's break below 50 is the cumulative result of post-SpaceX uncertainty. Meanwhile Claude Code, ChatGPT, and Copilot are each expanding their moats — developer productivity (AGENTS.md), office integration (Word), and observability (Sentry) respectively. Aider's official development stall signals a generational shift in the open-source AI coding tool market.

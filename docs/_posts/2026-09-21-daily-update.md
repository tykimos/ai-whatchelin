---
title: "Cursor Breaks Below 50 — Day 32 of Decline as Copilot CLI v1.0.87 Ships Today"
date: 2026-09-21
lang: en
categories: [news]
tags: [cursor, claude-code, copilot-cli, antigravity, codex-cli, github-copilot, chatgpt, aider]
excerpt: "Cursor drops to 49 after 32 consecutive days of decline since SpaceX's acquisition closed. Copilot CLI ships v1.0.87 today with prompt recall and turn interruption, while the unified Copilot experience is now just 7 days away."
---

Cursor has broken through the 50-point floor. After 32 consecutive days of decline since the SpaceX acquisition closed on August 14, it hit 49 — entering the 40s for the first time ([CNBC](https://www.cnbc.com/2026/06/16/spacex-spcx-cursor-acquisition-ipo.html)). With 52 days left until OpenAI's November 12 model access cutoff, the Plugin4Shell non-patch and sandbox escape CVE-2026-48124 continue to weigh on sentiment.

## Cursor: Projects Beta Plays the Comeback Card, but the Score Keeps Falling

Cursor launched Projects in beta on September 10, bringing a cloud coordinator that delegates work to thousands of subagents ([AI Weekly](https://aiweekly.co/alerts/cursor-ships-projects-beta-with-delegating-coordinator-agent)). The coordinator keeps running when the developer's laptop is closed, decoupling agent throughput from human availability ([Pondero](https://pondero.ai/news/2026-09-11-cursor-projects/)). Cursor claims engineers using Projects as their primary workflow merged six times as many pull requests ([Technobezz](https://www.technobezz.com/news/cursor-projects-cloud-agents-beta)). Yet amid the SpaceX acquisition uncertainty and compounding security issues, the score slid to 49.

## Copilot CLI v1.0.87: Prompt Recall and Turn Interruption Ship Today

GitHub Copilot CLI shipped v1.0.87 today ([GitHub](https://github.com/github/copilot-cli/releases/tag/v1.0.87-0)). Pressing Up in an empty input field now recalls the last prompt for editing, and Ctrl+C immediately stops the running turn instead of removing pending prompts one at a time. MCP server compatibility was improved — servers advertising list-change capabilities but not implementing subscriptions now connect instead of failing. A security fix also prevents secrets from being written to debug logs ([Havoptic](https://www.havoptic.com/tools/github-copilot)). The unified Copilot experience launches in 7 days (September 28), when the code review default automatically switches from Lite to Balanced, consuming more tokens per review ([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)).

## Claude Code: AGENTS.md Support and Server-Side Auto Mode

Claude Code v2.1.277 added AGENTS.md support — in projects without a CLAUDE.md, Claude Code now reads AGENTS.md instead ([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). Follow-up release v2.1.278 switched auto mode for Claude API and Enterprise users to a server-side classifier by default, eliminating classifier overhead costs ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Custom request headers for LLM gateways were also added.

## Antigravity: antigravity-preview-09-2026 Generation Shift

Google released antigravity-preview-09-2026 on September 17, replacing and deprecating the May build ([Releasebot](https://releasebot.io/updates/google/antigravity)). Breaking changes include PascalCase parameters replacing snake_case and line-range edits replacing full file rewrites ([GitHub PR #83](https://github.com/google-gemini/gemini-skills/pull/83)). The May build retires on October 5 ([Creators Toolbox](https://creatorstoolbox.com/blog/google-gemini-antigravity-agent-09-2026)). A new Remote Control feature lets developers drive local agent sessions from any browser ([Antigravity Changelog](https://www.gradually.ai/en/changelogs/antigravity/)).

## Aider: Development Stalls, Community Fork cecli Takes the Torch

Official Aider development has visibly stalled — no tagged release since August 2025, one PyPI patch in February 2026, and 500+ open pull requests piling up ([shortlisted.tools](https://shortlisted.tools/products/aider)). The community fork cecli (formerly Aider CE) has stepped in with weekly releases and an added agent mode, effectively becoming the successor.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Word integration launched, GPT-5.5 retirement D-23 |
| Claude Code | 99 | — | v2.1.278, AGENTS.md support + server-side auto mode |
| Claude AI | 99 | — | Fable 5.1 frontier holds |
| Codex CLI | 99 | — | v0.154.0, GPT-5.3 Spark retired |
| Antigravity | 99 | — | 09-2026 preview build generation shift + Remote Control |
| Windsurf | 87 | — | Devin Desktop · RSA-260 buzz continues |
| Aider | 68 | — | Official dev stalled, cecli fork leads |
| Cursor | 49 | ↓2 | Day 32 decline, first break below 50 |
| GH Copilot | 1 | — | CLI v1.0.87 shipped, unified experience D-7 |
| Gemini CLI | 1 | — | Shutdown day 96 |

Cursor's break below 50 is the cumulative result of post-SpaceX uncertainty. Copilot CLI v1.0.87 focused on developer productivity with prompt recall and turn interruption, while the D-7 countdown to the unified experience is now in full swing. Meanwhile, agent orchestration tools like Orca are emerging in the open-source ecosystem, cementing the multi-agent development paradigm ([datnguyenquy94/news-radar](https://github.com/datnguyenquy94/news-radar/issues/542)).

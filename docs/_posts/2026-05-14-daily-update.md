---
title: "Anthropic Eyes Stainless Acquisition While Boosting Claude Code Limits 50% — Agent Infrastructure War Heats Up"
date: 2026-05-14
lang: en
categories: [news]
tags: [claude-code, anthropic, cursor, github-copilot, gemini-cli, aws-kiro, openai, stainless]
excerpt: "Anthropic is in talks to acquire Stainless — the startup that builds SDKs for OpenAI, Google, and Cloudflare — for $300M+. Meanwhile, Claude Code weekly limits jump 50% and the agent infrastructure race intensifies."
---

Anthropic is reaching for a rival's plumbing. According to The Information, Anthropic is in talks to acquire Stainless for over $300 million — the startup that auto-generates production-grade SDKs from API specs([The Information](https://www.theinformation.com/articles/anthropic-talks-buy-developer-tools-startup-used-by-openai-google)). Stainless currently builds official SDKs for OpenAI, Google, Cloudflare, and Meta, meaning a successful acquisition would give Anthropic leverage over the developer channel for competing platforms([Open Source For You](https://www.opensourceforu.com/2026/05/anthropic-eyes-300m-stainless-acquisition-to-strengthen-ai-infrastructure/)).

## Claude Code: Limits Up + v2.1.141

Claude Code weekly limits were raised 50% across Pro, Max, Team, and Enterprise plans, effective through July 13. This follows the May 6 doubling of hourly limits and removal of peak-hour throttling([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)). The same day, v2.1.141 shipped with expanded hook and plugin options, terminal notification support, and workspace identity federation([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Claude Code holds at 98 for eleven consecutive days, tied with ChatGPT at the top.

## Cursor: Development Environments for Cloud Agents

Cursor launched "Development Environments" — infrastructure tooling for cloud agents([Cursor Changelog](https://cursor.com/changelog/05-13-26)). Multi-repo support for cloud agents, Dockerfile-based configuration with 70% faster builds via layer caching, agent-led environment validation, per-environment version history with rollback, audit logging, and scoped secrets access are all included([Cursor Blog](https://cursor.com/blog/cloud-agent-development-environments)). Agents are evolving from "bots that write code" to "colleagues that set up their own infrastructure." Score rises to 95.

## GitHub Copilot: Agent REST API + Billing D-17

Copilot launched a Cloud Agent REST API in public preview, letting Business and Enterprise users programmatically start agent tasks([GitHub Blog](https://github.blog/changelog/2026-05-13-start-copilot-cloud-agent-tasks-via-the-rest-api/)). Use cases include distributing refactors across repos, automated release prep, and repository initialization via PAT or OAuth tokens. Meanwhile, the countdown to usage-based billing hits D-17 — April usage reports are now downloadable so users can preview their credit costs before the June 1 transition([TechSifted](https://techsifted.com/posts/github-copilot-changes-may-2026/)). Score holds at 73: the API launch is positive, but billing uncertainty offsets the momentum.

## AWS Kiro: 'Prove Before You Code' With SMT Solvers

AWS added "Spec Check" to Kiro, using an SMT solver to mathematically prove requirements are contradiction-free before any code is written([GeekWire](https://www.geekwire.com/2026/aws-targets-ai-slop-with-new-spec-check-in-kiro-coding-tool-amid-scrutiny-of-agent-reliability/)). Parallel task execution (75% faster for large projects) and Quick Plan mode shipped alongside([SiliconANGLE](https://siliconangle.com/2026/05/12/aws-kiro-accelerates-software-development-proving-code-correctness-gets-work/)). Moving from "humans review AI-generated code" to "verify the spec itself before generation" is a meaningful paradigm shift.

## Google I/O D-5: Gemini 4 Countdown

I/O is five days away. Gemini CLI v0.43.0-preview already laid the groundwork with LocalSubagentProtocol and RemoteSubagentProtocol behind a unified AgentProtocol([GitHub](https://github.com/google-gemini/gemini-cli/releases)). When Gemini 4 (ARC-AGI2 84.6%) debuts at the May 19 keynote, expect that subagent architecture to go live immediately([TechRound](https://techround.co.uk/tech/gemini-4-ai-glasses-and-a-new-os-why-google-i-o-2026-could-be-the-most-important-developer-event-of-the-year/)). Gemini CLI ticks up to 75.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant stable |
| Claude Code | 98 | — | v2.1.141, weekly limits +50%, 11 days at 98 |
| Cursor | 95 | ↑1 | Cloud agent dev environments launch |
| Claude AI | 92 | — | Cowork GA stabilizing |
| Codex CLI | 81 | — | Alpha builds only, awaiting stable |
| Windsurf | 78 | — | Quiet day |
| Gemini CLI | 75 | ↑1 | I/O D-5, subagent architecture |
| GitHub Copilot | 73 | — | Agent REST API, billing D-17 |
| Aider | 68 | — | Stable |
| Antigravity | 48 | ↓1 | Soft-deprecation rumors |

The Stainless acquisition talks aren't just M&A — controlling SDK infrastructure means influencing the developer experience of competing platforms. Meanwhile, Cursor and Copilot both shipped agent infrastructure on the same day (dev environments vs. REST API), signaling that the frontline of the agent war has moved from "code generation" to "agent operations infrastructure."

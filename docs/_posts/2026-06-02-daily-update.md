---
title: "Build 2026 Opens: Microsoft Cuts the OpenAI Cord — Project Polaris Ships as Copilot Billing Revolt Deepens"
date: 2026-06-02
lang: en
categories: [news]
tags: [microsoft-build, github-copilot, claude-code, nvidia, cursor, codex-cli, gemini-cli]
excerpt: "Microsoft Build 2026 Day 1 reveals Project Polaris — a homegrown coding model replacing GPT-4 in Copilot. But on day two of usage-based billing, developers report 10-50x cost increases, and the 29-week decline continues."
---

Microsoft Build 2026 opened in San Francisco today with a clear message: the company is replacing OpenAI's GPT-4 with its own coding model inside GitHub Copilot. Six months of rumors became reality, and the signal is unmistakable — Microsoft is reducing its dependency on OpenAI for core developer tooling.

## Microsoft Build: Project Polaris Breaks the OpenAI Dependency

Project Polaris is Microsoft's homegrown mixture-of-experts coding model that reportedly outperforms GPT-4 Turbo on standard coding benchmarks([TechTimes](https://www.techtimes.com/articles/317596/20260602/github-copilot-replaces-gpt-4-project-polaris-ships-multi-agent-vs-code-build.htm)). Starting August 2026, it will automatically replace GPT-4 Turbo as the default engine for all Copilot subscribers, with a three-month fallback to legacy models([ChatForest](https://chatforest.com/builders-log/microsoft-build-2026-recap-windows-agent-platform-project-polaris-copilot-workspace/)).

Copilot Workspace also reached GA alongside Project Polaris. Fleet mode enables autonomous task execution without step-by-step confirmation, Autopilot schedules background tasks, and Extensions integrate Jira, Datadog, and ServiceNow. Multi-agent mode in VS Code spawns parallel subagents for linting, testing, documentation, and security review simultaneously([TechTimes](https://www.techtimes.com/articles/317596/20260602/github-copilot-replaces-gpt-4-project-polaris-ships-multi-agent-vs-code-build.htm)).

## Copilot Billing Day 2: The 10-50x Cost Shock Spreads

Despite Build's positive announcements, Copilot's decline continues. On day two of usage-based billing, developers are sharing real cost data — and the numbers are brutal([TechJournal](https://techjournal.org/github-copilot-token-billing-backlash)). Some heavy users burned through their entire monthly credit allotment in a single morning of agentic coding. On Reddit, migration threads to Claude Code ($20/mo flat), Codex CLI (API pricing), and DeepSeek V4 Pro (open-weight) are accelerating([TechCrunch](https://techcrunch.com/2026/05/30/what-a-joke-github-copilots-new-token-based-billing-spurs-consternation-among-devs/)).

Copilot's popularity score dropped to 54 — its 29th consecutive weekly decline and yet another all-time low.

## Claude Code v2.1.160: Security Hardening

Claude Code shipped v2.1.160 with focused security improvements([code.claude.com/changelog](https://code.claude.com/docs/en/changelog)). The update adds security prompts before writing to shell startup files (.zshenv, .zlogin, .bash_login) and git config, and now prompts before writing build-tool config files (.npmrc, .yarnrc, bunfig.toml, etc.) in acceptEdits mode. The June 15 billing change — moving programmatic usage to a separate credit pool — is now two weeks away([Codersera](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/)).

## NVIDIA Vera Rubin Enters Full Production

NVIDIA announced at Computex 2026 that its next-gen Vera Rubin platform is now in full production([ServeTheHome](https://www.servethehome.com/nvidia-computex-2026-news-bytes-vera-rubin-now-in-production-dgx-station-gets-windows/)). Built on TSMC's 3nm process, it delivers 10x inference cost reduction and requires 4x fewer GPUs for MoE model training versus Blackwell. Rack assembly time dropped from 2 hours to 5 minutes. AWS, Google Cloud, Microsoft, and OCI will deploy first in H2 2026([NVIDIA Newsroom](https://nvidianews.nvidia.com/news/rubin-platform-ai-supercomputer)).

## Cursor Teams Pricing Overhaul

Cursor overhauled its Teams pricing with Premium seats for heavy agent users, split usage pools, and real-time visibility([cursor.com/changelog](https://cursor.com/changelog)). The changes are expected to lower costs for 90% of teams. Bugbot also transitions from seat-based ($40/seat/mo) to usage-based billing ($1-1.50/run), effective at renewal after June 8.

## Gemini CLI: 16 Days Until Shutdown

The countdown continues — 16 days until Gemini CLI stops serving requests for all non-enterprise users on June 18([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). Migration to Antigravity CLI is mandatory. Built in Go, it offers faster performance and native multi-agent orchestration.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Stable #1, v2.1.160 security hardening |
| ChatGPT | 96 | — | Watching Build impact |
| Cursor | 96 | — | Teams pricing overhaul boosts value |
| Claude AI | 95 | — | Enterprise expansion continues |
| Codex CLI | 87 | — | Windows Computer Use added |
| Windsurf | 81 | — | Holding steady |
| Gemini CLI | 73 | ↓1 | Sunset D-16 countdown |
| Antigravity | 62 | ↑1 | Week 8 of rollback crisis recovery |
| Aider | 68 | — | Open-source steady |
| GH Copilot | 54 | ↓1 | 29-week decline, Build can't offset billing revolt |

Build 2026's Project Polaris and multi-agent announcements are technically impressive, but developers feel their bills before they feel new features. Copilot's recovery requires actual pricing relief — technical showcases alone won't stop the bleeding.

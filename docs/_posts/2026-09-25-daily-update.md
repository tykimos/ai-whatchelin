---
title: "Copilot Unified D-3 Countdown — Claude Code v2.1.282, ChatGPT Voice for Plugins GA, Cursor Day 37"
date: 2026-09-25
lang: en
categories: [news]
tags: [claude-code, github-copilot, chatgpt, cursor, codex-cli, gemini-cli]
excerpt: "Copilot unified experience is 3 days out with Oct 2 model deprecations confirmed. Claude Code polishes terminal UX, ChatGPT opens Voice for plugins to all plans, and Cursor hits day 37 of its decline."
---

Three days until the Copilot unified experience. After the model picker scramble and the code review settings battle, the competition has shifted to **how deeply each tool embeds into developers' daily workflows**. Today's theme: terminal UX, voice interfaces, and productivity integrations.

## Claude Code v2.1.282: Terminal Readability Upgrade

v2.1.282 introduces a maxProseWidth setting that caps prose width in wide terminals while tables and code blocks retain full width ([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). Telemetry settings are now surfaced in startup notices, /status, and doctor. The release also adds allowClaudeInChromeWithManagedMcp for running Chrome alongside managed MCP, and store.readiness_grace_seconds for Claude apps gateway Postgres failover resilience. The most impactful fix: conversations with undecryptable web search results no longer fail every request with a 400 error.

## ChatGPT: Voice for Plugins Goes GA

ChatGPT expanded Voice support to plugins and connected apps across web, iOS, and Android ([ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). Even Free and Go users can now use Voice in Chat with supported plugins. Separately, GPT-6 Sol and Luna arrived in ChatGPT Work and Codex with plan-based model and reasoning options, and U.S. Plus/Pro users gained credit score tracking via Experian integration.

## Copilot Unified Experience D-3: Oct 2 Model Deprecations Confirmed

Three days remain until GitHub merges Chat, Mobile, and cloud agent into a single unified experience ([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Starting Oct 1, new Business and Enterprise seats go prepaid. On Oct 2, a wave of model deprecations hits: Gemini 3.5/3.6 Flash to Gemini 3.8 Flash, Kimi K2.7 Code to Kimi K3, and Claude Opus 4.7 to Claude Opus 5 ([DMarketer](https://dmarketertayeeb.com/blog/github-copilot-september-2026-model-budget-review-changes/)). The code review default shifts to Balanced — teams wanting lower costs must explicitly select Lite now.

## Cursor: Day 37, Score Drops to 41

Cursor fell from 43 to 41, extending its decline streak to 37 consecutive days. Projects beta (thousands of subagents), Rollouts and Security Review bots, Grok 4.7 integration — none of the feature launches have slowed the structural exodus. The OpenAI model cutoff (Nov 12) is 48 days away. Community sentiment increasingly views a drop below 40 as inevitable.

## Gemini CLI: Shutdown Day 100

One hundred days since Gemini CLI consumer access was cut. With the migration to Antigravity CLI effectively complete, this milestone confirms Google's strategic pivot — from standalone CLI to integrated Antigravity platform — is on an irreversible trajectory.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Plugin Voice GA, Word expanding, credit score |
| Claude Code | 99 | — | v2.1.282 maxProseWidth, terminal UX polish |
| Claude AI | 99 | — | Opus 5.5 ecosystem adoption continues |
| Codex CLI | 99 | — | 0.158 alpha stabilization, Sol/Luna settled |
| Antigravity | 99 | — | 09-2026 preview stable, 05-2026 retiring Oct 5 |
| Windsurf | 87 | — | Devin Desktop holding steady |
| Aider | 68 | — | No official release in 13 months |
| Cursor | 41 | ↓2 | Day 37 decline, OpenAI shutoff D-48 |
| GH Copilot | 1 | — | Unified D-3, Oct 2 model deprecation confirmed |
| Gemini CLI | 1 | — | Shutdown day 100 |

The battleground is migrating from model pickers to code review to everyday integration. Terminal readability (Claude Code), voice interfaces (ChatGPT), and productivity app integration (Word) thread through today's updates. The next front isn't "better models" — it's "more natural workflows."

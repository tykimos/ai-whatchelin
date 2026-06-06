---
title: "Copilot Breaks 50, Claude Goes Down Across All Models, Tokyo Conference D-4"
date: 2026-06-06
lang: en
categories: [news]
tags: [github-copilot, claude-code, anthropic, gemini-cli, spacex, cursor, windsurf, chatgpt]
excerpt: "GitHub Copilot falls below 50 for the first time ever, Claude suffers a multi-model outage, and Code with Claude Tokyo is 4 days away. Plus: v2.1.163 ships version guardrails, Opus 4.8 becomes the fast mode default, and ChatGPT rolls out Dreaming V3 memory."
---

The day GitHub Copilot broke through its psychological floor, Anthropic's Claude went down across all models, and Code with Claude Tokyo moved to D-4. Three shockwaves hit the AI coding tool market simultaneously on June 6.

## GitHub Copilot: Below 50, the Floor Collapses

Copilot dropped to **50** — its 33rd consecutive weekly decline and the first time it has ever broken below the psychological floor. Day 6 of usage-based billing. The Copilot App technical preview([GitHub Blog](https://github.blog/news-insights/product-news/github-copilot-app-the-agent-native-desktop-experience/)) and Microsoft's first in-house coding model MAI-Code-1-Flash([GitHub Changelog](https://github.blog/changelog/2026-06-02-mai-code-1-flash-is-now-available-for-github-copilot/)) weren't enough to stop the bleeding. Migration guides to Claude Code, Cursor, and Codex CLI now dominate developer forums([Dev.to](https://dev.to/akaranjkar08/switch-from-github-copilot-to-claude-code-migration-guide-2026-28nk)).

## Claude All-Model Outage: June 5, 15:08–18:27 UTC

Elevated errors hit all Claude models starting at 15:08 UTC on June 5 — affecting claude.ai, Claude API, Claude Code, and Cowork([Cybersecurity News](https://cybersecuritynews.com/anthropics-claude-services-down/)). Opus 4.6 recovered first (15:25 UTC), Opus 4.5 last (17:29 UTC). Anthropic attributed the cause to infrastructure issues with no security breach or data exposure. The third notable outage in recent months.

## Claude Code v2.1.163: Version Guardrails and Plugin Management

New `requiredMinimumVersion`/`requiredMaximumVersion` managed settings let enterprises enforce version compliance — Claude Code refuses to start outside the allowed range([GitHub Releases](https://github.com/anthropics/claude-code/releases/tag/v2.1.163)). Also ships `/plugin list` with `--enabled`/`--disabled` filters, fixes a silent startup hang on read-only config directories, and makes WebFetch deny rules override preapproved domains.

## Opus 4.8 Now the Fast Mode Default

Starting with Claude Code v2.1.154, `/fast` defaults to Opus 4.8 — $10/$50 per MTok, roughly 2x cost for ~2.5x speed([Anthropic](https://www.anthropic.com/news/claude-opus-4-8)). Also the default on Max, Team Premium, Enterprise pay-as-you-go, and the Anthropic API with high effort.

## Code with Claude Tokyo: D-4

Code with Claude arrives in Tokyo June 10-11 with three parallel tracks: Research, Claude Platform, and Claude Code([claude.com](https://claude.com/code-with-claude/tokyo)). Extended day (June 11) features indie developer demos and Applied AI workshops. All sessions are livestreamed with simultaneous English/Japanese interpretation([claude.com Extended](https://claude.com/code-with-claude/tokyo-extended)).

## ChatGPT: Dreaming V3 Memory Revolution

OpenAI's most significant memory upgrade since launch — the Dreaming V3 architecture — began reaching ChatGPT Plus and Pro users([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-june-6-2026)). The system processes past conversations during idle time to build richer long-term context, moving beyond explicit memory saves.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.163 ships, security plugin, Tokyo D-4 |
| ChatGPT | 96 | — | Dreaming V3 memory rolling out |
| Cursor | 96 | — | SpaceX roadshow underway, Premium seat |
| Claude AI | 95 | — | 6/5 outage recovered, Glasswing 150 orgs |
| Codex CLI | 87 | — | TUI F13-F24, plugin JSON, archiving |
| Windsurf | 85 | ↑1 | Devin Desktop, $15 absorbing Copilot exodus |
| Gemini CLI | 69 | ↓1 | Shutdown D-12, migration accelerating |
| Aider | 68 | — | Open-source CLI stable |
| Antigravity | 65 | ↑1 | Absorbing Gemini CLI migration demand |
| GH Copilot | 50 | ↓1 | First-ever break below 50, 33-week decline |

Copilot breaks 50, Claude recovers from an outage, and Tokyo looms. Next Tuesday's Code with Claude keynote is the biggest watch point of the week.

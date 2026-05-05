---
title: "GPT-5.5 Instant Takes Over as ChatGPT Default — Hallucinations Cut in Half"
date: 2026-05-05
lang: en
categories: [news]
tags: [chatgpt, openai, cursor, codex-cli, copilot]
excerpt: "OpenAI deploys GPT-5.5 Instant as ChatGPT's new default model with 52.5% fewer hallucinations. Cursor ships Canvases for interactive visual interfaces, and Codex CLI gets persistent /goal workflows for long-running agent tasks."
---

OpenAI deployed GPT-5.5 Instant as ChatGPT's new default model today, replacing GPT-5.3 Instant. Hallucinated claims dropped 52.5% on high-stakes prompts in medicine, law, and finance, while the AIME 2025 math benchmark jumped from 65.4 to 81.2 — a 24% improvement([TechCrunch](https://techcrunch.com/2026/05/05/openai-releases-gpt-5-5-instant-a-new-default-model-for-chatgpt/)). Two new features ship alongside: "fast answers" bypasses chat history for high-confidence responses to common questions, and "memory sources" shows users exactly where personalized answers come from, with delete/correct controls([Axios](https://www.axios.com/2026/05/05/openai-chatgpt-update-default-model)).

## Cursor: Canvases Turn Agents into Visual Interfaces

Cursor introduced Canvases — agents can now create interactive React-based visual interfaces for data visualization, PR reviews, and eval analysis instead of dense text output, all built into the Agents Window([cursor.com](https://cursor.com/changelog)). Enterprise admins also gained granular model/provider blocklists and soft spend limits with automatic alerts at 50%, 80%, and 100% usage thresholds. The Team Marketplace no longer requires a repository connection to get started.

## Codex CLI v0.128.0: /goal Gives Agents Persistent Objectives

Codex CLI shipped persisted /goal workflows — set a durable objective, close your laptop, and come back to a paused or completed run([github.com/openai/codex](https://github.com/openai/codex/releases)). State survives across sessions with full TUI controls for create, pause, resume, and clear. The release also adds configurable TUI keymaps, expanded permission profiles, app-server Unix socket transport, and `codex exec --json` reasoning-token usage reporting.

## GitHub Copilot: Preview Bills Before June 1 Billing Switch

Copilot is rolling out a "preview bill" experience in early May ahead of the June 1 usage-based billing transition([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Opus models have been fully removed from the Pro tier — Opus 4.7 is now Pro+ only. Rate limit information is now surfaced directly in VS Code and the CLI, and the cloud agent starts 20% faster with optimized GitHub Actions runner environments.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | ↑1 | GPT-5.5 Instant launch, new all-time high |
| Claude Code | 96 | — | Holding steady, enterprise JV momentum |
| Cursor | 91 | ↑1 | Canvases + enterprise admin controls |
| Claude AI | 90 | — | Opus 4.7 adoption stable |
| GitHub Copilot | 81 | ↓1 | Billing transition uncertainty, Pro model removal |
| Windsurf | 76 | — | 2.0 stabilizing |
| Codex CLI | 76 | ↑1 | /goal workflows for long-running agents |
| Aider | 68 | — | 39K+ stars, stable |
| Gemini CLI | 67 | — | Quiet since v0.40.1 |
| Antigravity | 47 | ↓1 | No news, continued decline |

ChatGPT hit a new all-time high of 98 with GPT-5.5 Instant's tangible hallucination reduction. Cursor's Canvases pushes it further from "editor" toward "development platform," while Codex CLI's /goal makes the "close your laptop, check tomorrow" agentic coding scenario real.

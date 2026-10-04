---
title: "OpenAI DevDay Drops GPT-6.1 Sol — GitHub Copilot Cleans House, Cursor Hits D-39"
date: 2026-10-04
lang: en
categories: [news]
tags: [openai, devday, gpt-6.1-sol, codex-cloud, github-copilot, claude-code, cursor, antigravity]
excerpt: "OpenAI unveiled GPT-6.1 Sol and Codex Cloud at DevDay 2026. GitHub Copilot deprecated four legacy models and launched Computer Use preview, while Cursor faces OpenAI model cutoff in 39 days."
---

OpenAI unveiled GPT-6.1 Sol at DevDay 2026, delivering Astra-level coding performance at one-fifth the standard token price, with cached input costs halved to $0.10/M([InfoQ](https://www.infoq.com/news/2026/10/openai-devday-2026/)). Alongside it, Codex Cloud launched with cross-device remote task execution — start a coding job from your phone and let it run while your laptop sleeps([InfoQ](https://www.infoq.com/news/2026/10/openai-devday-2026/)).

## GitHub Copilot: Four Legacy Models Retired, Computer Use Goes Live

GitHub deprecated Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7 across all Copilot experiences on October 2, directing users to Gemini 3.8 Flash, Kimi K3, and Claude Opus 5.5 respectively([GitHub Blog](https://github.blog/changelog/2026-10-02-selected-models-in-github-copilot-deprecated/)). The same day, Computer Use entered public preview in the Copilot CLI and desktop apps on macOS and Windows, enabling screen reading, clicking, scrolling, and drag-and-drop through GUI control([GitHub Blog](https://github.blog/changelog/label/copilot/)). The Code Review API also went GA with per-request review effort levels.

## Claude Code: v2.1.288 Reliability Overhaul

Anthropic shipped Claude Code v2.1.288, a broad reliability and UX update featuring smarter session resume and recovery, stronger plugin and MCP handling, and improved permission behavior([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). The Mods system introduced in v2.1.287 is settling in, with the built-in "You should know" mod running a side agent that flags issues in real time. Claude for Government reached GA with FedRAMP High authorization.

## Codex CLI: v0.160.0 Upgrades Agent Command Center

OpenAI Codex CLI v0.160.0 shipped on October 2 with a keyboard-accessible "Show more" for browsing older tasks in the agent command center and Guardian review enhancements for preserving user instructions across agent handoffs([Releasebot](https://releasebot.io/updates/openai/codex)). Windows sandbox PowerShell compatibility and SQLite connection stability also improved.

## Cursor: OpenAI Shutoff D-39, 38th Consecutive Decline

Cursor's popularity fell for the 38th straight day to 23, as the SpaceX-Anysphere acquisition fallout continues. OpenAI has proposed November 12 as the model access cutoff date([InfoWorld](https://www.infoworld.com/article/4216503/cursor-customers-will-lose-access-to-openai-coding-models-in-november.html)). Cursor maintains that OpenAI models account for roughly 5% of its traffic, but its survival increasingly depends on the success of its Origin hosting platform and iOS mobile beta.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay GPT-6.1 Sol launch, Codex Cloud |
| Claude Code | 99 | — | v2.1.288, Mods settling in, FedRAMP GA |
| Codex CLI | 99 | — | v0.160.0 agent command center |
| Antigravity | 99 | — | Multi-provider strategy continues |
| Claude AI | 99 | — | IPO push, Frontier Academy |
| Windsurf | 88 | — | Stable as Devin Desktop |
| Aider | 68 | — | Steady open-source maintenance |
| Cursor | 23 | ↓2 | 38th straight decline, OpenAI shutoff D-39 |
| GH Copilot | 15 | ↑2 | Legacy model cleanup, Computer Use preview |
| Gemini CLI | 1 | — | Transitioned to Antigravity CLI |

DevDay 2026's GPT-6.1 Sol lowers the price barrier for high-performance coding models another notch. GitHub Copilot's bulk model retirement accelerates its pivot to an agent platform, and Cursor's survival now hinges on shedding its OpenAI dependence.

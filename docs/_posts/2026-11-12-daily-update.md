---
title: "Cursor Loses OpenAI Models Today — Day 79 at the Bottom Meets D-Day"
date: 2026-11-12
lang: en
categories: [news]
tags: [cursor, openai, claude-code, github-copilot, antigravity, gemini-cli]
excerpt: "OpenAI officially cuts Cursor's model access today. After 79 days pinned at rock bottom following the SpaceX acquisition, Cursor's last lifeline is severed."
---

Today marks the end of an era in AI coding tools. OpenAI's proposed transition period for Cursor (Anysphere) expires on November 12, cutting off model access after 79 days of the tool sitting at a popularity score of 1 following SpaceX's $60B acquisition.

## Cursor: OpenAI Model Cutoff D-Day

OpenAI's model access for Cursor officially ends today, the proposed transition deadline ([InfoWorld](https://www.infoworld.com/article/4216503/cursor-customers-will-lose-access-to-openai-coding-models-in-november.html)). OpenAI cited concerns that SpaceX could use Cursor's access to train competing AI systems through model distillation ([The New Stack](https://thenewstack.io/openai-cuts-cursor-spacex/)). Users can still configure their own OpenAI API keys for some features, but Tab autocomplete, auto model selection, Cloud Agents, and CLI are not covered ([OpenAI Help](https://help.openai.com/en/articles/20001506)). IDC called it "the first real case of supply chain risk materializing in the AI tools market" ([IDC](https://www.idc.com/?p=119917)).

## Claude Code v2.1.319: Auto Mode Hardened

Claude Code v2.1.319 shipped November 6 with auto mode as the headline change ([claudekit.io](https://claudekit.io/en/updates/claude-code-2-1-319/)). In environments with telemetry or feature flags disabled, or behind an LLM gateway, calls the server cannot verify are now surfaced for user approval rather than classified automatically. MCP task support was added to the terminal, and gateway management was improved ([labmemo.com](https://labmemo.com/claude-code-v2-1-319-auto-mode-gateway-mcp-task-2026-11/)). Meanwhile, fast mode on Opus 4.8 is being deprecated on November 30 — users should plan migration.

## GitHub Copilot: Agent Merge and Cron Tasks

Copilot's November 6 weekly release added Agent Merge pull request automation and scheduled cron tasks in VS Code 1.145 ([GitHub Blog](https://github.blog/changelog/2026-11-06-github-copilot-weekly-releases-november-2)). Native support for JetBrains Air and Xcode 27.3 beta was also included. Copilot's popularity score hit 93 today, up for 48 consecutive days, putting it on track to rejoin the top tier by year-end.

## Gemini CLI v0.67.0: Model Listing Command

Gemini CLI v0.67.0 shipped November 4 with a model listing command and container sandbox IDE companion support ([havoptic.com](https://www.havoptic.com/releases/gemini-cli/2026/11)). Development is gradually transitioning to Antigravity CLI, so standalone Gemini CLI releases are expected to slow down ([labmemo.com](https://labmemo.com/?p=62719)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Stable |
| Claude Code | 99 | — | v2.1.319 auto mode hardened |
| Codex CLI | 99 | — | 0.167.0 agent command center |
| Antigravity | 99 | — | Knowledge Work mode live |
| Claude AI | 99 | — | IPO S-1 filed, Fable 5.2 stable |
| GH Copilot | 93 | ↑2 | 48-day streak, Agent Merge added |
| Windsurf | 88 | — | Stable as Devin Desktop |
| Aider | 68 | — | Maintenance mode continues |
| Cursor | 1 | — | OpenAI cutoff D-Day, day 79 at bottom |
| Gemini CLI | 1 | — | Antigravity transition underway |

OpenAI's Cursor cutoff turns supply chain dependency risk from theory into reality. As Copilot climbs for the 48th straight day, the vertical integration strategy of Claude Code and Antigravity — owning both the tool and the model — looks increasingly prescient.

---
title: "Anthropic Launches Enterprise Security Center, OpenAI Dots Goes GA — Copilot 42-Day Streak, Cursor D-6"
date: 2026-11-06
lang: en
categories: [news]
tags: [anthropic, claude-code, openai, dots, chatgpt, images, github-copilot, jetbrains, cursor, postman, watermark]
excerpt: "Anthropic ships a security center for Claude Enterprise and rolls out model watermarking. OpenAI Dots goes GA for enterprise users, while Copilot hits a 42-day winning streak on JetBrains Air integration."
---

Anthropic delivered two heavyweight updates back-to-back this week: an enterprise security tool and invisible watermarking across Claude models. OpenAI also joined the agent war in earnest, opening its personal agent Dots to enterprise customers.

## Anthropic: Claude Enterprise Security Center Launches

Anthropic launched a security center for Claude Enterprise on November 5 ([DEV Community](https://dev.to/hiroki-ii-ai/ai-daily-digest-november-6-2026-openai-ships-gpt-6-cyber-meta-buys-conductor-anthropic-locks-1jij)). The tool compares Chat, Cowork, and Claude Code settings against Anthropic's recommended security baselines and exports audit reports. Anthropic is clear this is guidance, not compliance certification. The timing is no coincidence — with the IPO targeting a November 16 listing under ticker ANT, enterprise trust is the priority ([Invenglobal](https://www.invenglobal.com/articles/27712/anthropic-files-s-1-for-ipo-plans-nasdaq-listing-under-ticker-ant)).

## Anthropic: Invisible Watermarking Rolls Out Across Claude Models

Starting November 3, text output from Claude Mythos 5, Opus 4.7, and Sonnet 4.6 now carries an invisible watermark ([Releasebot](https://releasebot.io/updates/anthropic)). A second phase will extend coverage to older models. Customers relying on the watermark for compliance should keep default settings. This is a proactive move as regulatory pressure for AI-generated text identification intensifies.

## Claude Code: Message Threads API in Public Beta

The Messages API gained message threads in public beta on November 2 ([Releasebot](https://releasebot.io/updates/anthropic)). Agents can now send only new messages between turns in long sessions, significantly reducing latency. Claude Code's `claude auth status` also added a warning 10 days before stored login expiry.

## OpenAI: Dots Goes GA for Enterprise

OpenAI opened its personal agent Dots to Enterprise, Edu, and Healthcare workspaces on November 4 ([OpenAI Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). Workspace admins can enable access or opt out before Dots becomes default on November 18. Built on GPT-6 Astra, Dots are always-on agents that pursue user-defined goals across conversations — roughly five weeks after the DevDay announcement ([TechCrunch](https://techcrunch.com/2026/09/29/openai-launches-dots-its-bubbly-agentic-avatar/)).

## ChatGPT: Images 2.6 Ships with GIF Creation

OpenAI released ChatGPT Images 2.6 on November 4 ([OpenAI Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). The update adds GIF creation directly in conversations and lets users save reference images for reuse in later chats. Pro and Business Premium plans also saw their Work and Codex usage allowances doubled on October 29.

## GitHub Copilot: JetBrains Air and Xcode, 42-Day Streak

GitHub Copilot became available in JetBrains Air on November 3 ([GitHub Changelog](https://github.blog/changelog/2026-11-03-github-copilot-is-now-available-in-jetbrains-air)). This followed the Xcode 27.3 beta integration the same day — two IDE expansions in 48 hours ([9to5Mac](https://9to5mac.com/2026/11/03/xcode-27-3-adds-github-copilot-to-its-built-in-coding-assistant)). The score climbs to 81 on a 42-day winning streak, with 10 days until the November 16 model swap (Opus 4.8/5 to Opus 5.5, GPT-5.6 Terra to GPT-6.1 Sol) ([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)).

## Cursor: OpenAI Cutoff D-6, Day 73 at Bottom

Six days remain until Cursor's OpenAI model access is fully terminated on November 12 ([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). OpenAI cited concerns about SpaceX's compliance with its terms after the $60B acquisition ([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). Cursor's CEO said OpenAI models account for about 5% of total traffic, and the pivot to Grok 4.7 and Anthropic models continues.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Images 2.6 shipped, Dots GA for enterprise |
| Claude Code | 99 | — | Security center launched, API threads beta |
| Codex CLI | 99 | — | v0.166.0 stable, GPT-6.1 Terra support |
| Antigravity | 99 | — | Plugin Marketplace stable |
| Claude AI | 99 | — | Watermarking live, IPO roadshow imminent |
| Windsurf | 88 | — | Devin Desktop stable |
| GH Copilot | 81 | ↑2 | 42-day streak, JetBrains Air + Xcode |
| Aider | 68 | — | Maintenance mode |
| Cursor | 1 | — | OpenAI cutoff D-6, day 73 at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition complete |

Both Anthropic and OpenAI are racing to ship enterprise security and agent features simultaneously — the AI coding tool war is expanding from code generation into full enterprise infrastructure integration.

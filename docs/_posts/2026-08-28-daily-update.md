---
title: "OpenAI Assistants API Killed Without Migration Tools — Developers Scramble"
date: 2026-08-28
lang: en
categories: [news]
tags: [openai, assistants-api, copilot, claude-code, claude, cursor, antigravity]
excerpt: "OpenAI hard-killed the Assistants API with no automated migration path. With Copilot's mass deprecation 4 days away and Claude shipping a built-in browser, it's a day of platform reckoning."
---

OpenAI's Assistants API was permanently shut down on August 26. The /v1/assistants, /v1/threads, and /v1/threads/runs endpoints now return errors across the board, and no automated migration tool was provided ([TechTimes](https://www.techtimes.com/articles/325345/20260824/openai-assistants-api-shuts-down-tuesday-no-automated-migration-threads-risk.htm)). Developers must manually port to the Responses API and Conversations API — the only available path forward for those who had Assistants API in production ([SocialCrawl](https://www.socialcrawl.dev/blog/openai-assistants-api-2026-shutdown-migration-guide)).

## Copilot: September 1 Mass Deprecation D-4

GitHub Copilot's September 1 model mass deprecation is now 4 days away ([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Gemini 3.1 Pro, Claude Opus 4.5/4.6, Claude Sonnet 4.5/4.6, and Raptor mini will be removed from all Copilot experiences. Enterprise admins must configure replacement model policies immediately — Claude Sonnet 4.6 remains only for annual individual subscribers. Copilot CLI v1.0.81 shipped a plugins dashboard and improved session recovery ([Havoptic](https://www.havoptic.com/tools/github-copilot)).

## Claude: Desktop Built-in Browser Ships

Claude's desktop app gained a built-in browser that opens websites in a side panel, handling web tasks without touching the user's own browser ([Releasebot](https://releasebot.io/updates/anthropic/claude)). The feature is rolling out to Pro, Max, Team, and Enterprise plans. Meanwhile, Claude Code v2.1.247 landed with a SendFeedback tool and `/claude-api cost-optimize` command, alongside arrow-key navigation and sub-agent model fallback chain fixes ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)).

## ChatGPT: o3 Retired, GPT-5.6 Luna Takes Over

o3 has been officially retired from ChatGPT, and GPT-5.6 Luna is now the default for Free/Go users ([Releasebot](https://releasebot.io/updates/openai/chatgpt)). Luna reduced factual errors by 62% compared to GPT-5.5. GPT-5.6 Sol's 3-month promotional price cut of 20%+ remains active ($4/$20 per MTok) ([Developers Digest](https://www.developersdigest.tech/blog/ai-coding-tools-pricing-2026)).

## Antigravity: Antigravity Agent Public Preview

Google's Antigravity Agent launched in public preview ([Releasebot](https://releasebot.io/updates/google/gemini-cli)). The managed agent autonomously plans, writes and executes code, manages files, and browses the web — all within a sandbox. Gemini 3.1 Flash-Lite also went GA.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | 32-week streak at 99, v2.1.247 |
| ChatGPT | 99 | — | Assistants API dead, Luna era begins |
| Codex CLI | 99 | — | 20M users, GPT-5.4 exits Aug 31 |
| Antigravity | 99 | — | Agent public preview |
| Claude AI | 99 | — | Built-in browser ships |
| Cursor | 99 | — | Origin growing, SpaceX velocity |
| Windsurf | 86 | — | Devin Desktop stabilizing |
| Aider | 68 | — | No release since May |
| Copilot | 1 | — | 108-week decline, Sep 1 mass deprecation D-4 |
| Gemini CLI | 1 | — | Shutdown day 71 |

The Assistants API hard-kill is a stark reminder of the risks of platform dependence. A shutdown with no automated migration is the loudest possible signal to developers: don't lock into a single API.

---
title: "Gemini 3.5 Pro Misses Rumored July 17 Target — Google Goes Silent"
date: 2026-07-17
lang: en
categories: [news]
tags: [gemini-3-5-pro, claude-code, github-copilot, grok-build, antigravity]
excerpt: "The rumored July 17 GA target for Gemini 3.5 Pro has passed with no official announcement from Google. Meanwhile, Claude Code v2.1.212 upgrades /fork to background sessions for stronger multitasking."
---

Google is silent. A day after Bloomberg's bombshell erased roughly $200 billion in Alphabet market cap, the industry-watched July 17 GA target for Gemini 3.5 Pro has come and gone without a word. The DeepMind model page still reads "3.5 Pro coming soon" ([DeepMind](https://deepmind.google/models/gemini/)).

## Gemini 3.5 Pro — July 17 No-Show, Trust Recovery Distant

The July 17 GA date reported by TechTimes, HackerNoon, and others has passed without an official confirmation or postponement notice from Google ([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). The Gemini API still lists only 3.5 Flash and 3.1 Pro, while the rumored 2M context window and Deep Think mode remain unconfirmed ([AIToolsReview](https://aitoolsreview.co.uk/insights/gemini-3-5-pro)). Combined with yesterday's Bloomberg report of a "months behind schedule" delay and a scrapped base model, today's silence deepens developer anxiety.

## Claude Code v2.1.212 — /fork Evolves to Background Sessions

Anthropic shipped Claude Code v2.1.212 ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). The headline change: `/fork` now copies your conversation into an independent background session instead of spawning an in-session subagent. The old behavior moves to `/subtask`. A session-wide WebSearch call limit (default 200, tunable via `CLAUDE_CODE_MAX_WEB_SEARCHES_PER_SESSION`) blocks runaway search loops, and `claude auto-mode reset` restores auto-mode defaults.

## Copilot Code Quality — 3 Days to Paywall

GitHub Code Quality goes GA on July 20, ending the free preview ([GitHub](https://github.blog/changelog/2026-06-16-github-code-quality-generally-available-july-20-2026/)). Pricing lands at $10 per active committer per month, with AI-powered features (Copilot code review, AI-assisted detection, Autofix) billed separately on usage. Over 10,000 enterprises used the preview, so pushback against the sudden paywall is likely ([DevOps.com](https://devops.com/github-code-quality-moves-to-general-availability-bringing-new-costs-and-capabilities/)).

## Grok Build — Exfiltration Code Still Ships Two Days After Open-Source

Two days after xAI open-sourced Grok Build under Apache 2.0, the code that uploaded entire Git repositories to Google Cloud Storage remains compiled into the binary ([Simon Willison](https://simonwillison.net/2026/Jul/15/grok-build/)). No affected user count, no total data volume, and no independent deletion verification have been disclosed ([The Register](https://www.theregister.com/ai-and-ml/2026/07/16/spacex-open-sources-grok-build-after-data-retention-furore/5272333)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.212, /fork background sessions |
| Antigravity | 99 | — | v2.2.1 stable, 26-week streak |
| ChatGPT | 99 | — | Codex Micro first deliveries 7/24 |
| Claude AI | 98 | — | Fable 5 third extension, Ode launch |
| Cursor | 97 | — | SpaceX acquisition Q3 close expected |
| Codex CLI | 90 | — | GPT-5.6 powered, ChatGPT merge complete |
| Windsurf | 85 | — | Devin Desktop v3.4.27 stable |
| Aider | 68 | — | Open source steady, 44K stars |
| Gemini CLI | 9 | ↓1 | 3.5 Pro July 17 no-show, shutdown Day 29 |
| Copilot | 9 | ↓1 | 72-week decline, Code Quality GA in 3 days |

Gemini CLI and Copilot both dropped to 9, entering single digits together. Whenever Google ships 3.5 Pro, yesterday's Bloomberg bombshell and today's silence have created a trust deficit that will take far longer to erase than a model launch.

---
title: "Claude Goes Down for 2 Hours as DevDay Dust Settles and Sonnet 5.5 Takes Over"
date: 2026-09-30
lang: en
categories: [news]
tags: [claude, anthropic, openai, devday, dots, cursor, codex-cli, gemini-cli, github-copilot]
excerpt: "On the same day OpenAI unveiled 20+ products at DevDay, Claude suffered a full 2-hour outage across all services. Meanwhile, Anthropic quietly made Sonnet 5.5 the default and OpenAI shipped reusable cloud environments for Codex."
---

The timing couldn't have been worse. On September 29, the same day OpenAI flooded the zone with 20+ DevDay announcements, Anthropic's entire service stack went dark for roughly two hours. Over 18,000 reports hit Downdetector — versus a baseline of about 10 — as claude.ai, Claude Code, Claude Cowork, the API, Console, and sign-in systems all dropped simultaneously around 10 AM ET ([TechRadar](https://www.techradar.com/news/live/claude-down-september-29-2026)). SSO and Sign in with Apple were unavailable, and some messages sent during the window may not have been saved ([Unite.AI](https://www.unite.ai/anthropic-reports-service-disruption-across-claude-ai-code-cowork-and-api/)). Service was mitigated by 14:36 UTC ([9to5Google](https://9to5google.com/2026/09/29/claude-confirmed-outage-sept-29/)).

## Claude Code: Sonnet 5.5 Becomes the Default + Graceful Shutdown

One day before the outage, Anthropic shipped Claude Code v2.1.284 with Sonnet 5.5 as the new default model ([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). With a 1M context window, Sonnet 5.5 is 30%+ faster than Sonnet 5 and achieves the same coding results with fewer steps, tokens, and tool calls ([SiliconANGLE](https://siliconangle.com/2026/09/28/anthropic-debuts-claude-sonnet-5-5-running-30-faster-than-the-previous-generation-ai-model/)). A new graceful shutdown feature pulls a small allowance from the weekly limit to let in-progress work wrap up cleanly when hitting the 5-hour session cap.

## Codex CLI: Reusable Cloud Environments + v0.159.0

The most practical DevDay announcement may be Codex's reusable cloud environments ([TechCrunch](https://techcrunch.com/2026/09/29/openai-gives-codex-reusable-cloud-environments-that-work-across-devices/)). Connect a GitHub repo, and Codex auto-detects dependencies and drafts install scripts. Each task gets its own VM that keeps running while your laptop sleeps. Today's v0.159.0 release adds opt-in instant interrupt — new input can steer Codex mid-response or during long-running code-mode calls ([Gradually.ai](https://www.gradually.ai/en/changelogs/codex-cli/)).

## Gemini CLI v0.62.0: Maintenance Release

Gemini CLI shipped v0.62.0 with Gemini 3.8 Flash and 3.5 Flash Lite model support, plus auth, PTY/terminal handling, and UI layout fixes ([Releasebot](https://releasebot.io/updates/google/gemini-cli)). As the transition to Antigravity CLI continues, legacy maintenance carries on.

## Cursor: 31, Day 34 of the Slide

Cursor dropped to 31, marking 34 consecutive days of decline. The OpenAI model termination (Nov 12) is now D-43 away. Staff exodus and the SpaceX/xAI integration grind continue.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Post-DevDay coverage wave, Dots safety debate |
| Claude Code | 99 | — | Sonnet 5.5 default, rapid recovery from outage |
| Codex CLI | 99 | — | Cloud environments + v0.159.0, DevDay momentum |
| Antigravity | 99 | — | 30-week high streak |
| Claude AI | 99 | — | Sonnet 5.5 launched, score held despite outage |
| Windsurf | 88 | — | Stable as Devin Desktop |
| Aider | 68 | — | v0.86.0 maintenance release |
| Cursor | 31 | ↓2 | 34th straight decline, D-43 |
| GH Copilot | 7 | ↑2 | Sonnet 5.5 added, slow recovery |
| Gemini CLI | 1 | — | Shutdown day 105 |

---
title: "SpaceX-Cursor Deal Could Close This Week — Claude Code Patches Remote Control Leak Ahead of Auto Mode D-2"
date: 2026-08-12
lang: en
categories: [news]
tags: [cursor, spacex, claude-code, anthropic, copilot, devin-desktop]
excerpt: "SpaceX's $60B Cursor acquisition may finalize this week as regulatory clearance nears. Claude Code ships v2.1.228 fixing a Remote Control data leak two days before auto mode becomes default, while GitHub Copilot counts down to its September 1 model purge."
---

SpaceX's $60 billion all-stock Cursor acquisition is down to final regulatory approval and could close as early as this week. In an August 9 internal meeting, Cursor told employees the deal could be done "by end of next week, or by end of August at the latest" ([Seeking Alpha](https://seekingalpha.com/news/4629527-cursor-says-spacex-deal-could-be-done-by-end-of-next-week---report)). SpaceX (SPCX) shares rose 4.23% on August 10 on the news ([startuphub.ai](https://www.startuphub.ai/ai-news/ipo-watch/2026/spacex-cursor-acquisition-lockup-2026-08-10)). Once finalized, the Cursor brand will likely be retired and successor products may adopt Grok branding ([PYMNTS](https://www.pymnts.com/news/artificial-intelligence/2026/cursor-brand-name-may-not-survive-spacex-acquisition/)).

## Claude Code: v2.1.228 + Auto Mode D-2

Anthropic shipped Claude Code v2.1.228 today ([GitHub](https://github.com/anthropics/claude-code/releases/tag/v2.1.228)). The release fixes interactive sessions that could stop redrawing entirely after rare layout errors, and resolves Git detection failures on Windows when launched from parent folders. The most notable fix addresses a security issue where Remote Control /resume was leaking conversation data between connected sessions. With auto mode becoming the default permission mode in just two days (August 14), this stabilization release comes at a critical moment — the safety classifier's 89% catch rate (vs. 13.6% human review) is about to face its widest deployment yet.

## Claude AI: Voice Mode Opens to All Models + M365 Write Tools

Claude AI voice mode now works with any model — Haiku, Sonnet, or Opus (Fable excluded for now) — lifting the previous Haiku-only restriction ([SlashGear](https://www.slashgear.com/2229323/claude-ai-voice-mode-update-model-choice/)). Meanwhile, the Microsoft 365 connector gained write tools, enabling Claude to draft and send email, manage calendar events, and create or update files in OneDrive and SharePoint ([suprmind.ai](https://suprmind.ai/hub/claude/features/)).

## Cursor: Router Hits Fable-Level Quality at 68% Lower Cost

Cursor Router's Auto Intelligence now delivers above-Fable-level user satisfaction at 68% lower cost, an 18% further reduction since launch ([Releasebot](https://releasebot.io/updates/cursor)). Auto Balance outperforms Opus 4.8 at 41% reduced cost, and Opus 5 has been added to the routing mix. Google Workspace Plugins (Gmail, Drive, Calendar) are also now accessible directly from agents.

## GitHub Copilot: September 1 Model Purge D-20, Kimi K3 Expands

GitHub Copilot's massive September 1 model deprecation is now 20 days away ([GitHub Blog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Claude Sonnet 4.6 will remain only for annual individual subscribers. Meanwhile, Moonshot AI's open-weight Kimi K3 model is now GA across Copilot Pro, Pro+, Max, Business, and Enterprise tiers at $3/$15 per MTok, delivering frontier-level agentic coding performance ([GitHub Blog](https://github.blog/changelog/2026-08-06-kimi-k3-is-now-available-in-github-copilot/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.228 security patch, auto mode D-2 |
| ChatGPT | 99 | — | GPT-5-Codex-Mini spreading, GPT-5.4 sunset D-19 |
| Antigravity | 99 | — | Holding ceiling |
| Claude AI | 99 | — | Voice mode all models, M365 write tools |
| Codex CLI | 99 | — | v0.147.0 plugin ecosystem, holding ceiling |
| Cursor | 97 | — | SpaceX deal could close this week |
| Windsurf | 85 | — | Devin Local editor context awareness improved |
| Aider | 68 | — | No releases since Aug 2025 |
| Copilot | 1 | — | 92-week decline, Sept 1 purge D-20 |
| Gemini CLI | 1 | — | Day 55 post-shutdown, Antigravity full replacement |

The SpaceX-Cursor countdown is accelerating the "big tech consolidation" trend in AI coding tools. Claude Code is focused on last-mile stabilization ahead of its auto mode transition, while GitHub Copilot plays the Kimi K3 card before its September model purge.

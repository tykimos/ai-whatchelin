---
title: "Microsoft Kills Internal Claude Code Licenses, Forces Copilot CLI Transition"
date: 2026-05-16
lang: en
categories: [news]
tags: [microsoft, claude-code, github-copilot, anthropic, google-io, cursor]
excerpt: "Microsoft is canceling thousands of employee Claude Code licenses by June 30, pushing developers to Copilot CLI. Monday brings Google I/O and Code with Claude London simultaneously."
---

Microsoft's Experiences + Devices team — responsible for Windows, Microsoft 365, Outlook, Teams, and Surface — is canceling all Claude Code licenses with a June 30 cutoff, forcing a transition to GitHub Copilot CLI([Windows Central](https://www.windowscentral.com/microsoft/microsoft-cancels-claude-code-licenses-shifting-developers-to-github-copilot-cli-a-move-likely-driven-by-financial-motives)). Claude Code had grown enormously popular among Microsoft employees since access opened in December, with developers, PMs, and designers adopting it — ultimately undercutting internal Copilot CLI usage([The Verge](https://www.resetera.com/threads/the-verge-microsoft-starts-canceling-claude-code-licenses-engineers-will-have-to-switch-to-copilot.1520725/)). Internal pushback has been reported: *"its own devs aren't happy"*([Yahoo Tech](https://tech.yahoo.com/ai/copilot/articles/microsoft-ditching-claude-code-copilot-133318848.html)).

## Claude Code: Fast Mode Now Defaults to Opus 4.7

As of May 14, Claude Code's /fast command defaults to Opus 4.7 — delivering 2.5x faster output tokens per second with identical quality and the full 1M context window([Anthropic](https://code.claude.com/docs/en/whats-new)). The previous `CLAUDE_CODE_ENABLE_OPUS_4_7_FAST_MODE=1` ENV flag is no longer required([BuildFastWithAI](https://www.buildfastwithai.com/blogs/claude-opus-4-7-fast-mode-guide)). Additional updates include new `claude agents` flags (--add-dir, --settings, --mcp-config, --model) for background session configuration, and Windows support without Git Bash via PowerShell([Releasebot](https://releasebot.io/updates/anthropic/claude-code)).

## GitHub Copilot: Desktop App Enters Technical Preview

The GitHub Copilot App launched as a standalone desktop experience for agent-driven development([GitHub Blog](https://github.blog/changelog/2026-05-14-github-copilot-app-is-now-available-in-technical-preview/)). Each session gets its own git worktree, branch, and task state for true parallel work, while Agent Merge automatically addresses review comments, fixes CI failures, and merges when conditions are met([Neowin](https://www.neowin.net/news/microsoft-launches-github-copilot-app-to-supercharge-agentic-development/)). Early access is expanding to Pro/Pro+ subscribers.

## Monday's Triple Header: Google I/O + Code with Claude London + Musk Jury

Three major events converge on May 19: the Google I/O keynote (Gemini Omni and Android 17 expected)([Android Authority](https://www.androidauthority.com/what-to-expect-from-google-io-2026-3664979/)), Anthropic's Code with Claude London (plus May 20 Extended day)([claude.com](https://claude.com/code-with-claude/london)), and the start of Musk v. Altman jury deliberations([CNBC](https://www.cnbc.com/2026/05/14/closing-arguments-jury-openai-musk-altman.html)). This could be the most consequential week in AI coding tool history.

## Cursor: Bugbot Goes Usage-Based + Teams Integration

Cursor is switching Bugbot to usage-based billing at $1-1.50 per run, replacing the $40/seat/month subscription — effective at the next renewal after June 8([Cursor Blog](https://cursor.com/blog/may-2026-bugbot-changes)). A new Microsoft Teams integration lets users mention @Cursor in any Teams channel to delegate tasks to cloud agents([Cursor Changelog](https://cursor.com/changelog)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | Musk trial + Codex mobile steady |
| Claude Code | 98 | — | Day 14 at 98, Fast Mode Opus 4.7 default |
| Cursor | 95 | — | Bugbot billing shift, Teams integration |
| Claude AI | 93 | — | Code with Claude London D-3 |
| Codex CLI | 82 | — | Mobile stabilizing |
| Windsurf | 80 | — | Cognition $25B valuation holds |
| Gemini CLI | 76 | — | I/O D-3, Gemini Omni anticipation |
| GitHub Copilot | 71 | ↓1 | MS Claude Code ban = forced adoption vs 13-week slide |
| Aider | 68 | — | Stable |
| Antigravity | 47 | — | Awaiting I/O announcements |

GitHub Copilot's 13-week slide hits 71, but Microsoft's forced Claude Code migration could provide a short-term usage boost. Monday's Google I/O may shake up the landscape again if Gemini CLI gets a major upgrade.

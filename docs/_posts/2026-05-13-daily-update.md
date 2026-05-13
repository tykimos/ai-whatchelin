---
title: "Copilot Security Flaw Exposed, Gemini CLI Drops Double Release — Google I/O D-6 Countdown"
date: 2026-05-13
lang: en
categories: [news]
tags: [github-copilot, gemini-cli, claude-code, cursor, google-io, security]
excerpt: "CVE-2026-41109 reveals a CVSS 7.8 bypass in Copilot's AI content filters. Gemini CLI ships both a stable and preview release as Google I/O looms six days away."
---

A security alarm went off for Copilot. Microsoft disclosed CVE-2026-41109 yesterday — a vulnerability that lets local attackers manipulate the IPC channel between VS Code's extension host and the Copilot extension, bypassing AI content filters and user consent mechanisms([The Hacker Wire](https://www.thehackerwire.com/github-copilot-visual-studio-injection-bypasses-security-feature-cve-2026-41109/)). Rated CVSS 7.8, the flaw allows unfiltered model outputs to be injected directly into the editor and can silently toggle telemetry consent flags. Patches shipped in VS Code 1.97.0 and Copilot extension v1.43.20260512([Windows News](https://windowsnews.ai/article/cve-2026-41109-copilot-and-vs-code-security-feature-bypass-in-the-dev-workflow.417882)).

## Gemini CLI: Double Release Six Days Before I/O

Google is pushing Gemini CLI hard on two tracks with I/O six days away. The v0.42.0 stable release includes voice mode UI improvements, session export/import functionality, and Gemma 4 as the default model([GitHub](https://github.com/google-gemini/gemini-cli/releases)). The same-day v0.43.0-preview.0 is more noteworthy — it introduces LocalSubagentProtocol and RemoteSubagentProtocol behind a unified AgentProtocol interface, laying the foundation for a full subagent architecture, and steers models toward the edit tool for more precise code modifications([GitHub](https://github.com/google-gemini/gemini-cli/releases)). When Gemini 4 (ARC-AGI2 84.6%) debuts at I/O on May 19-20, expect significant ripple effects across the CLI ecosystem([TechRound](https://techround.co.uk/tech/gemini-4-ai-glasses-and-a-new-os-why-google-i-o-2026-could-be-the-most-important-developer-event-of-the-year/)).

## GitHub Copilot: 11-Week Slide, CVE Adds Fuel

On top of the security vulnerability, Copilot CLI 1.0.46 shipped([GitHub](https://github.com/github/copilot-cli/releases)). It now warns when a CLI version is deprecated and premium model access may be lost, adds auto-approval for read-only `gh` commands, and improves diff view wrapping. With Grok Code Fast 1 sunset at D-2, token billing at D-18, and the CVE compounding trust concerns — the score drops to 73, marking an unprecedented 11-week consecutive decline.

## Claude Code v2.1.140: Stability Patch

Claude Code updated to v2.1.140([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Agent name matching now accepts case- and separator-insensitive values, the color palette was refreshed, and bugs in `/goal` hanging and settings hot-reload with symlinked files were fixed. Holding at 98 for ten consecutive days.

## Cursor: Enters Microsoft Teams

Cursor is now available in Microsoft Teams([Cursor Changelog](https://cursor.com/changelog)). Mention @Cursor in any Teams channel to delegate tasks to a cloud agent or pull Cursor context into Teams. The move extends enterprise developer collaboration beyond the IDE.

## Week Ahead: Google I/O D-6

Google I/O 2026 (May 19-20) is six days away([Yahoo Tech](https://tech.yahoo.com/general/article/google-io-2026-what-to-expect-next-week-including-android-17-ai-announcements-and-more-131200995.html)). Gemini 4 preview, Android XR smart glasses, and the AI-first Googlebook laptop are all expected. The double Gemini CLI release reads as groundwork for the agentic AI features set to be announced at I/O.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant stable, Fast answers feature |
| Claude Code | 98 | — | v2.1.140, 10 consecutive days at 98 |
| Cursor | 94 | — | Teams integration, $60B SpaceX deal ongoing |
| Claude AI | 92 | — | Cowork GA stabilizing |
| Codex CLI | 81 | — | Amazon company-wide access settling |
| Windsurf | 78 | — | Opus 4.7 fast mode stable |
| Gemini CLI | 74 | ↑1 | v0.42+v0.43 double release, I/O D-6 |
| GitHub Copilot | 73 | ↓1 | CVE-2026-41109, Grok D-2, 11-week slide |
| Aider | 68 | — | Stable |
| Antigravity | 49 | — | AgentKit 2.0 settling |

Copilot's 11-week slide combined with a security vulnerability pushes it to 73, widening the gap with Claude Code (98) to 25 points. Meanwhile, Gemini CLI's double release lifts it to 74, pulling within 1 point of Copilot in a notable reversal.

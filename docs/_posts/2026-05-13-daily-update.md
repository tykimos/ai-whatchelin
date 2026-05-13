---
title: "Copilot Security Flaw Meets Windsurf's Code Review Offensive, While Harness Report Warns of AI's 'Invisible Cost'"
date: 2026-05-13
lang: en
categories: [news]
tags: [github-copilot, windsurf, cursor, gemini-cli, claude-code, harness, security, google-io]
excerpt: "CVE-2026-41109 shakes Copilot trust as Windsurf pushes Devin Review front-and-center and Cursor enters Teams. Meanwhile, a Harness report finds 31% of developer time is now consumed by invisible AI code review work."
---

A security alarm went off for Copilot. Microsoft disclosed CVE-2026-41109 — a CVSS 7.8 vulnerability that lets local attackers manipulate the IPC channel between VS Code's extension host and the Copilot extension, bypassing AI content filters and user consent mechanisms([The Hacker Wire](https://www.thehackerwire.com/github-copilot-visual-studio-injection-bypasses-security-feature-cve-2026-41109/)). Unfiltered model outputs can be injected directly into the editor and telemetry consent flags silently toggled. Patches shipped in VS Code 1.97.0 and Copilot extension v1.43.20260512, but the damage adds to an already unprecedented 11-week popularity slide([Windows News](https://windowsnews.ai/article/cve-2026-41109-copilot-and-vs-code-security-feature-bypass-in-the-dev-workflow.417882)).

## Windsurf: Code Review Offensive

Windsurf officially announced "Fast and Comprehensive Code Review, Now in Windsurf" yesterday (May 12), entering the code review war in earnest([Windsurf Blog](https://windsurf.com/blog/devin-review-windsurf)). Since May 6, all Windsurf IDE users have had access to Devin Review and Quick Review with a 2-week free trial for self-serve users([Windsurf Changelog](https://windsurf.com/changelog)). Launching a code review push right as Copilot's security flaw surfaces is striking timing.

## Harness Report: AI Coding's 'Invisible Cost'

The Harness "State of Engineering Excellence 2026" report landed today with a sobering message([PR Newswire](https://www.prnewswire.com/news-releases/harness-report-reveals-ai-has-outpaced-how-engineering-organizations-measure-developer-productivity-302770521.html)). Surveying 700 engineering practitioners and managers across seven countries, it found that **roughly 31% of developer time is now consumed by invisible work** — reviewing AI-generated code, fixing bugs, and context-switching between tools. 81% say they spend more time in code review since adopting AI tools, and while 89% of leaders claim their metrics accurately reflect AI's impact, 94% admit that tech debt, validation time, and burnout are missing from those same metrics([Tech Times](https://www.techtimes.com/articles/316587/20260513/harness-engineering-emerges-fourth-paradigm-ai-engineering.htm)).

## Cursor: Teams Integration + Bugbot Billing Shift

Cursor landed in Microsoft Teams on May 11([Cursor](https://cursor.com/changelog/microsoft-teams)). Mention @Cursor in any channel to delegate tasks to a cloud agent that reads the full thread and generates PRs automatically. Separately, Bugbot is switching to usage-based billing for Teams and Individual plans, effective at the next renewal after June 8([Cursor Blog](https://cursor.com/blog/may-2026-bugbot-changes)). Admins can now configure effort levels — default, high, or custom — to tune review depth.

## Gemini CLI: Double Release Six Days Before I/O

Google is pushing Gemini CLI hard on two tracks with I/O six days out. The v0.42.0 stable release includes voice mode UI improvements, session export, and Gemma 4 as default. The same-day v0.43.0-preview.0 introduces LocalSubagentProtocol and RemoteSubagentProtocol behind a unified AgentProtocol, laying the foundation for a full subagent architecture([GitHub](https://github.com/google-gemini/gemini-cli/releases)). When Gemini 4 (ARC-AGI2 84.6%) debuts at I/O on May 19-20, expect significant ripple effects([TechRound](https://techround.co.uk/tech/gemini-4-ai-glasses-and-a-new-os-why-google-i-o-2026-could-be-the-most-important-developer-event-of-the-year/)).

## Claude Code v2.1.140: Steady at the Top

Claude Code updated to v2.1.140 with improved agent name matching, a refreshed color palette, and fixes for `/goal` hanging and symlinked settings hot-reload([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Holding at 98 for ten consecutive days, tied with ChatGPT for the top spot.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant stable, spreadsheet sidebar |
| Claude Code | 98 | — | v2.1.140, 10 consecutive days at 98 |
| Cursor | 94 | — | Teams integration, Bugbot billing shift |
| Claude AI | 92 | — | Cowork GA stabilizing |
| Codex CLI | 81 | — | v0.130 remote-control, Amazon company-wide |
| Windsurf | 78 | — | Devin Review code review launch |
| Gemini CLI | 74 | ↑1 | v0.42+v0.43 double release, I/O D-6 |
| GitHub Copilot | 73 | ↓1 | CVE-2026-41109, 11-week slide |
| Aider | 68 | — | Stable |
| Antigravity | 49 | — | AgentKit 2.0 settling |

Copilot's 11-week slide combined with a security vulnerability pushes it to 73, widening the gap with Claude Code (98) to 25 points. Meanwhile, the Harness report raises a question that applies to every tool on this list: code generation got faster, but has the total cost of review, validation, and debugging actually gone down?

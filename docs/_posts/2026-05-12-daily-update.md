---
title: "DALL-E Officially Shut Down Today — OpenAI's Image Generation Era Ends as Claude Code Evolves with Agent View"
date: 2026-05-12
lang: en
categories: [news]
tags: [openai, dall-e, claude-code, copilot, codex-cli, cursor, gemini-cli, google-io]
excerpt: "DALL-E 2 and 3 are officially deprecated today as gpt-image-2 takes over. Claude Code v2.1.139 adds Agent View and /goal, while Copilot hits a 10-week slide with Grok Code Fast 1 sunset in 3 days."
---

The DALL-E era ended today. As pre-announced last November, OpenAI fully removed DALL-E 2 and DALL-E 3 from the API on May 12([OpenAI Developer Community](https://community.openai.com/t/deprecation-reminder-dall-e-will-be-shut-down-on-may-12-2026/1378754)). The successor gpt-image-2, powered by O-series reasoning, delivers near-perfect multilingual text rendering and native 2K resolution([AI Automation Global](https://aiautomationglobal.com/blog/chatgpt-images-2-gpt-image-2-native-reasoning-launch-2026)).

## Claude Code: Agent View Opens Multi-Session Management

Claude Code v2.1.139 shipped([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). The headline feature is Agent View (Research Preview) — a unified list of every running, blocked, or completed session. The new `/goal` command sets completion conditions across multiple turns, and `/scroll-speed` offers live-preview scroll adjustments. MCP stdio servers now receive `CLAUDE_PROJECT_DIR`, making project-aware tool development easier.

## Copilot: Grok Code Fast 1 D-3, 10 Consecutive Weeks of Decline

Grok Code Fast 1 will be fully removed from GitHub Copilot on May 15([GitHub Changelog](https://github.blog/changelog/2026-05-08-upcoming-deprecation-of-grok-code-fast-1/)). GPT-5 mini and Claude Haiku 4.5 are the recommended replacements. Enterprise admins must update model policies immediately. With usage-based billing at D-19 and the Opus 4.7 multiplier jumping to 27x on June 1, the score drops to 74 — ten consecutive weeks of decline.

## Copilot CLI 1.0.45: /autopilot and /fork Commands

Copilot CLI updated to 1.0.45([Releasebot](https://releasebot.io/updates/github)). New `/autopilot` toggles autonomous mode, `/fork` splits sessions. Startup is ~1.5 seconds faster, and OpenTelemetry aligns with GenAI semantic conventions.

## Codex CLI: Amazon Company-Wide Access Begins, 5-Week Streak

Amazon officially opened Codex CLI access to all employees today, as announced yesterday([Slashdot](https://developers.slashdot.org/story/26/05/10/0618225/amazon-relents-lets-its-programmers-use-openais-codex-and-anthropics-claude)). With 4M+ developers and expanding enterprise partnerships, the score rises to 81 — a five-week winning streak.

## Cursor: Security Review Enters Beta

Cursor launched Security Review in beta for Teams and Enterprise plans([Cursor Changelog](https://cursor.com/changelog)). Security Reviewer checks every PR for vulnerabilities, auth regressions, and privacy risks. Vulnerability Scanner runs scheduled codebase scans. Bugbot effort-level customization (default vs. high) also went live on the same day.

## Week Ahead: Google I/O D-7

Google I/O 2026 is one week away (May 19-20)([Android Authority](https://www.androidauthority.com/what-to-expect-from-google-io-2026-3664979/)). Gemini 4 (10M+ token context), Firebase as an agent-native platform, and Android 17 are all expected. The announcements could significantly reshape the Gemini CLI ecosystem.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant holding, DALL-E shutdown is image-side |
| Claude Code | 98 | — | Agent View + /goal, 8 days at 98 |
| Cursor | 94 | — | Security Review beta, $60B SpaceX deal ongoing |
| Claude AI | 92 | — | Cowork GA stabilizing |
| Codex CLI | 81 | ↑1 | Amazon company-wide access begins, 5-week streak |
| Windsurf | 77 | — | Devin integration stabilizing |
| GitHub Copilot | 74 | ↓1 | D-19, Grok sunset D-3, 10-week slide |
| Gemini CLI | 73 | — | I/O D-7, open-source momentum |
| Aider | 68 | — | Stable |
| Antigravity | 49 | — | AgentKit 2.0 settling |

Copilot's 10-week slide is unprecedented in GitHub's history. The gap with Claude Code (98) has widened to 24 points, and the June 1 usage-based billing switch with the Opus 27x multiplier could push it further. Meanwhile, Codex CLI's Amazon catalyst has driven it to 81, positioning it for a run at the top tier.

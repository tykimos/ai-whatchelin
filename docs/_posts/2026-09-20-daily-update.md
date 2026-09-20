---
title: "Security Storm Week — Plugin4Shell and Sandbox Escapes Hit AI Coding Tools in Back-to-Back Disclosures"
date: 2026-09-20
lang: en
categories: [news]
tags: [security, plugin4shell, sandbox-escape, github-copilot, cursor, claude-code, codex-cli, gemini, antigravity]
excerpt: "Plugin4Shell zero-click RCE followed by Pillar Security's sandbox escape research — two security alarms in a single week are shaking the AI coding tool ecosystem."
---

The AI coding tool industry is living through an unprecedented security storm week. Following the Plugin4Shell zero-click RCE disclosed on September 17, Pillar Security published sandbox escape vulnerabilities across Cursor, Codex, Gemini CLI, and Antigravity — two security alarms in a single week ([BleepingComputer](https://www.bleepingcomputer.com/news/security/cursor-codex-gemini-cli-antigravity-hit-by-sandbox-escapes/)).

## Plugin4Shell: Patch Speed Determined Trust

Plugin4Shell, disclosed by AIR Security, is a zero-click RCE that bypasses SHA-pinning in the plugin-loading paths of Claude Code, Codex, Copilot, and Gemini CLI ([Cybersecurity News](https://cybersecuritynews.com/plugin4shell-zero-click-rce/)). Anthropic patched Claude Code in v2.1.179 and OpenAI patched Codex in v0.146.0, but Microsoft has not shipped a Copilot fix and Google declined to patch the deprecated Gemini CLI ([The Hacker News](https://thehackernews.com/2026/09/plugin4shell-lets-repository-owners.html)).

## Sandbox Escapes: Agents Following Rules While Breaking Out

Pillar Security's research team found four repeatable sandbox escape patterns across Cursor, Codex, Gemini CLI, and Antigravity ([The Next Web](https://thenextweb.com/news/ai-coding-agents-sandbox-escapes-pillar)). The agent stays inside the sandbox and follows every rule — it simply writes a file that a trusted host tool later executes. Cursor's escape is tracked as CVE-2026-48124 and was fixed in v3.0.0; OpenAI patched Codex in v0.95.0 and paid a high-severity bounty ([BleepingComputer](https://www.bleepingcomputer.com/news/security/cursor-codex-gemini-cli-antigravity-hit-by-sandbox-escapes/)). Google classified both Antigravity findings as low-severity and did not patch ([Techzine](https://www.techzine.eu/news/security/143038/researchers-bypass-sandbox-security-in-cursor-codex-and-gemini-cli/)).

## GitHub Copilot: Unified Experience D-8, Mass Model Retirement Coming

Copilot's unified experience launches September 28, with chat data retention extending to account lifetime ([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). The September 18 weekly release added a Sentry canvas for crash-to-fix workflows and efficiency/balance/intelligence tiers for auto model selection ([GitHub Changelog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)). Gemini 3.5/3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7 are all retiring from Copilot on October 2.

## Claude Code: Server-Side Classifier + AGENTS.md Interop

Claude Code v2.1.278 switched the auto mode classifier to server-side by default for all API/Enterprise/Bedrock/Vertex/Foundry/gateway users, eliminating classifier overhead charges ([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). The prior release v2.1.277 added AGENTS.md support for cross-tool interoperability with Codex CLI projects. Meanwhile, Anthropic revealed that Claude now leads 26% of its own model R&D, with over 30,000 agents running concurrently inside the company ([AI Weekly](https://aiweekly.co/ai-news-today)).

## Cursor: 51 Points, Day 31 of Decline — 50-Floor Approaching

Cursor dropped to 51 after 31 consecutive days of decline since the SpaceX acquisition ($60B) closed, and the sandbox escape disclosure added another headwind ([CNBC](https://www.cnbc.com/2026/06/16/spacex-spcx-cursor-acquisition-ipo.html)). With 53 days until OpenAI's November 12 model access cutoff, Codex CLI's `/import` migration support is accelerating the exodus ([Releasebot](https://releasebot.io/updates/openai/codex)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.5 retirement D-24 |
| Claude Code | 99 | — | v2.1.278 server-side classifier, Plugin4Shell fast-patched |
| Claude AI | 99 | — | Fable 5.1 frontier, leading 26% of Anthropic R&D |
| Codex CLI | 99 | — | /import migration, sandbox patched |
| Antigravity | 99 | — | Sandbox escape unpatched controversy |
| Windsurf | 87 | — | Devin Desktop · RSA-260 buzz |
| Aider | 68 | — | Steady releases, 39K+ stars |
| Cursor | 51 | ↓2 | Day 31 decline + CVE-2026-48124 |
| GH Copilot | 1 | — | Unified experience D-8, Plugin4Shell unpatched |
| Gemini CLI | 1 | — | Shutdown day 95, won't patch security issues |

Two structural vulnerabilities — Plugin4Shell and sandbox escapes — hit back to back in a single week. The contrast between Anthropic/OpenAI's rapid patching and Google/Microsoft's delayed response is becoming a key factor in tool selection.

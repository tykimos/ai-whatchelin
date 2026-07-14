---
title: "npm Supply Chain Attack Targets AI Coding Tool API Keys — Lessons from the jscrambler Incident"
date: 2026-07-14
lang: en
categories: [news]
tags: [security, jscrambler, claude-code, cursor, windsurf, gemini-3-5-pro, gpt-5-6, copilot]
excerpt: "The compromised jscrambler npm package deployed an infostealer targeting API keys from Claude Desktop, Cursor, Windsurf, and more. Meanwhile, Sophos reports AI coding agents are triggering endpoint security rules. The developer security landscape is shifting fast."
---

The biggest story this week is security. As AI coding tools go mainstream, the credentials they store are becoming a new attack surface.

## jscrambler npm Supply Chain Attack — AI Tool API Keys Are the Target

The jscrambler npm supply chain attack disclosed on July 11 differs from typical supply chain compromises in one critical way ([The Hacker News](https://thehackernews.com/2026/07/compromised-jscrambler-8140-npm-release.html)). Attackers used stolen publishing credentials to inject a Rust-based infostealer into jscrambler 8.14.0 and four other versions, and the malware's target list includes config files for Claude Desktop, Cursor, Windsurf, VS Code, and Zed ([Security Boulevard](https://securityboulevard.com/2026/07/jscrambler-npm-package-compromised-a-security-vendor-becomes-the-supply-chain-risk/)). MCP server credentials and API keys are primary targets. With 15,800 weekly downloads weaponized, any project using affected versions needs immediate credential rotation ([Socket](https://socket.dev/blog/jscrambler-supply-chain-attack)).

## AI Agents Triggering Endpoint Security Alerts

Sophos reports that Claude Code, Cursor, and Codex CLI trigger Windows endpoint detection rules for credential access, LOLBin downloads, and persistence — the same behavioral signatures used to catch attackers ([The Hacker News](https://thehackernews.com/2026/07/ai-coding-agents-found-triggering.html)). The normal operations of AI coding agents are becoming indistinguishable from attacker behavior, creating a new challenge for enterprise security teams.

## Gemini 3.5 Pro — D-3, July 17 GA Countdown

Google's Gemini 3.5 Pro is three days from its July 17 GA target ([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). A 2-million-token context window and Deep Think reasoning are expected, but Google has not officially confirmed anything. Copilot users on Gemini 2.5 Pro and Gemini 3 Flash must migrate by July 31 ([GitHub Changelog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)).

## Claude Code: Built-in Browser + Screen Reader Mode

Claude Code's desktop app now ships with a sandboxed browser, letting agents navigate docs, designs, and external sites directly ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). A new screen reader mode improves accessibility. On Bedrock, auto mode is now enabled by default with an upgrade to Opus 4.8.

## Terence Tao's AI Coding Experiment Tops Hacker News

Fields Medalist Terence Tao published a blog post documenting how AI coding agents resurrected his 27-year-old Java 1.0 applets and completed a special-relativity visualization tool he had abandoned — it hit #1 on Hacker News on July 11 ([TechTimes](https://www.techtimes.com/articles/320238/20260712/ai-agents-ported-taos-27-year-old-math-code-hours-found-two-bugs-he-had-missed.htm)). A rare case of a figure with authority in both mathematics and software engineering directly validating AI coding's practical value.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Built-in browser, screen reader mode |
| Antigravity | 99 | — | v2.2.1 stable, 24-week streak |
| ChatGPT | 99 | — | Sol 5-hour limit removal effect holding |
| Claude AI | 98 | — | Sonnet 5 settling in, Chrome extension beta |
| Cursor | 97 | — | 3.11 side chats gaining adoption |
| Codex CLI | 90 | — | v0.144.4 stable, Guardian rollback |
| Windsurf | 85 | — | Devin Desktop, Sonnet 5 integrated |
| Aider | 68 | — | Open source steady, 44K stars |
| Gemini CLI | 13 | ↓1 | Shutdown Day 26, enterprise-only |
| Copilot | 12 | ↓1 | 69-week decline, Gemini model deprecation |

Supply chain attacks targeting AI tool credentials and AI agents tripping security alarms — the tension between developer convenience and security is shaping up to be the defining theme of H2 2026. With Gemini 3.5 Pro GA approaching July 17, the model wars are heating up again.

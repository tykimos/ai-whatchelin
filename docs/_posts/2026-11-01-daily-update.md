---
title: "Trojanized Claude Code Extension Hits Cursor Marketplace, EMBRACE Exposes 45M Installs"
date: 2026-11-01
lang: en
categories: [news]
tags: [security, claude-code, cursor, github-copilot, codex-cli, chatgpt, deepseek]
excerpt: "A malicious Claude Code VS Code extension planted SSH backdoors via Cursor's marketplace. Forever Security's EMBRACE research exposes embedded browser vulnerabilities across five major AI coding tools, potentially affecting 45 million installs."
---

November opens with a security wake-up call for the AI coding ecosystem. A trojanized Claude Code extension was distributed through Cursor's marketplace, and Forever Security's EMBRACE research disclosed embedded browser vulnerabilities affecting five major tools. Security dominates the headlines heading into the week.

## Trojanized Claude Code Extension: ~5,000 Users Exposed via Cursor

Between 09:27 and 20:35 UTC on October 29, a malicious version (2.1.313) of the official anthropic.claude-code extension appeared in Cursor's marketplace ([AI Weekly](https://aiweekly.co/ai-news-today)). The extension added an attacker-controlled SSH key, opened a reverse-SSH tunnel, and established persistence on Windows and macOS. Cursor estimates the blast radius at "at most 5,000 users" and advises anyone who installed 2.1.313 to treat their machine as compromised ([AI Weekly](https://aiweekly.co/ai-news-today)). Anthropic published a clean version, 2.1.314, on October 30, and the command-and-control server has been taken offline.

## EMBRACE: Embedded Browser Vulnerabilities in 5 AI Coding Tools

Security researcher Gal Weizman of Forever Security published the EMBRACE research on October 29 ([AI Weekly](https://aiweekly.co/alerts/forever-security-embrace-research-breaks-five-ai-coding-browsers)). Five tools — Cursor, GitHub Copilot, OpenAI Codex, VS Code, and Claude Desktop — have embedded browsers that bypass standalone browser security rules. In Cursor, a malicious page could disable the agent's sandbox and execute arbitrary commands. In Copilot (before v1.1.29), URL spoofing enabled fake sign-in forms ([AI Weekly](https://aiweekly.co/alerts/forever-security-embrace-research-breaks-five-ai-coding-browsers)). In Codex, VS Code, and Claude Desktop, web workers in local HTML files could exfiltrate SSH keys, .env files, and npm tokens. Cursor (patched Oct 1) and Copilot (patched Oct 13, v1.1.29) are fixed, but Codex and VS Code remain unpatched at publication, affecting an estimated 45 million installs.

## Claude Code: Game Recreation Blocked via System Prompt

Anthropic added instructions to the Claude Opus 5.5 system prompt in Claude Code that refuse to recreate specific existing games, even if renamed ([AI Weekly](https://aiweekly.co/ai-news-today)). The change uses an internal flag called "tengu_heron_brook." Staff engineer Addy Osmani confirmed on X on October 30 that the restriction targets IP infringement. It's a server-side change with no local toggle, and some developers report it also blocks legitimate reverse-engineering tasks.

## ChatGPT + Codex: Shared Usage Pool Starting December

Starting in December, ChatGPT and Codex will draw from a single token-based allowance for Plus, Pro, and Business subscribers ([AI Weekly](https://aiweekly.co/ai-news-today)). Heavy Codex sessions will now count against the same budget as ChatGPT chats — a notable change for power users. Pro plans retain their no-5-hour-limit distinction.

## DeepSeek: Open-Source Super Agent Goes Public

DeepSeek released the dsh-superagent coding agent as an open-source prototype under the MIT license on October 31, crossing 4,100 GitHub stars within 24 hours ([SCMP](https://www.scmp.com/tech/article/3372884/deepseek-unveils-ai-super-agent-coding-race-openai-anthropic)). It monitors a GitHub repo and optionally Feishu group chats, opens work items in parallel Worker sessions, and replies with pull requests through a persistent Router. Positioned as a Claude Cowork rival, it remains an early research prototype.

## Codex CLI v0.166.0: Transcript Search and Queue Resume

OpenAI shipped Codex CLI v0.166.0 on October 29 ([DEV Community](https://dev.to/aicoding-guide/this-week-in-claude-code-codex-and-gemini-cli-week-of-november-1-2026-15pn)). Keyboard-driven transcript search, `codex queue --resume`, and `codex doctor --network-only` are the highlights, maintaining the steady weekly release cadence.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | December Codex pool merge announced |
| Claude Code | 99 | — | Game recreation block controversy, IPO D-8 |
| Codex CLI | 99 | — | v0.166.0, EMBRACE unpatched — caution |
| Antigravity | 99 | — | Gemini 4 Argon Pro stable |
| Claude AI | 99 | — | ANT listing countdown |
| Windsurf | 88 | — | No major updates |
| GH Copilot | 71 | ↑2 | 38-day streak, Nov 16 model purge |
| Aider | 68 | — | Maintenance mode |
| Cursor | 1 | — | Trojanized extension incident, day 68 at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition complete |

Security dominates this first week of November. The EMBRACE vulnerabilities and the trojanized extension incident are a stark reminder that supply chain security and embedded browser auditing matter as much as model capabilities. With Codex and VS Code still unpatched, the 45 million users in their combined install base should check every HTML file in affected projects for the exploit pattern.

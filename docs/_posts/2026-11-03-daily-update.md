---
title: "Cursor Marketplace Supply Chain Attack Exposes 5,000 Developers to SSH Backdoors"
date: 2026-11-03
lang: en
categories: [news]
tags: [cursor, claude-code, supply-chain, security, github-copilot, codex-cli, anthropic]
excerpt: "A trojanized Claude Code extension distributed through Cursor's marketplace exposed up to 5,000 developers to SSH backdoor attempts. OpenAI model access cutoff is now D-9."
---

Trust in the AI coding tool ecosystem is being tested. A trojanized version of Anthropic's Claude Code extension was distributed through Cursor's marketplace, and the incident — confirmed by multiple security outlets — is raising serious questions about developer tool supply chain security.

## Cursor: Trojanized Claude Code Extension Hits Marketplace

On October 29, a tampered version (2.1.313) of Anthropic's Claude Code extension was live on Cursor's marketplace for roughly 11 hours, exposing up to 5,000 users ([BleepingComputer](https://www.bleepingcomputer.com/news/security/malicious-claude-code-extension-on-cursor-planted-ssh-backdoors/)). The malicious extension executed automatically on load and attempted to install persistent SSH backdoors, though coding errors in the malware's SSH setup routines likely prevented most remote access from succeeding ([Sophos](https://www.sophos.com/en-us/blog/malicious-claude-code-extension-distributed-through-cursor-marketplace)). Anthropic confirmed its official distribution channels were not compromised, and Cursor recommended updating to version 2.1.314 ([SecurityWeek](https://securityweek.com/malicious-claude-code-extension-served-in-cursor-supply-chain-attack)). A separate autorun vulnerability in Cursor's built-in browser was also reported the same day, casting further doubt on Cursor's overall security posture ([Infosecurity Magazine](https://www.infosecurity-magazine.com/news/cursor-autorun-flaw-repos-execute/)).

## Cursor: OpenAI Model Access Cutoff D-9

The full termination of Cursor's access to OpenAI models is now just 9 days away on November 12 ([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-29/openai-to-end-partnership-with-cursor-after-spacex-acquisition)). Combined with the supply chain attack, Cursor has now spent 70 consecutive days at a score of 1 — a continuing tailspin since the SpaceX acquisition fallout.

## Codex CLI: v0.166.0 Running Stable

Codex CLI v0.166.0 shipped October 29 with keyboard-driven transcript selection, `codex queue --resume` for thread continuity, and `codex doctor --network-only` for focused diagnostics ([DEV Community](https://dev.to/aicoding-guide/this-week-in-claude-code-codex-and-gemini-cli-week-of-november-1-2026-15pn)). The prior v0.165.0 had introduced Vertex AI provider support and memories enabled by default.

## GitHub Copilot: Hits 75, 39-Day Recovery Streak

GitHub Copilot extended its recovery streak to 39 consecutive days, reaching a score of 75. Copilot CLI's migration to a native Rust engine is delivering improved performance ([GitHub Blog](https://github.blog/changelog/)), and a November 16 model lineup refresh (Opus 5.5, GPT-6.1 Sol) is on the calendar. The full transition to AI credit-based billing takes effect December 1 ([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra stable, Dec Codex pool merge pending |
| Claude Code | 99 | — | Supply chain attack was Cursor-side, core unaffected |
| Codex CLI | 99 | — | v0.166.0 stable |
| Antigravity | 99 | — | Gemini 4 Argon Pro rollout |
| Claude AI | 99 | — | ANT roadshow D-6 |
| Windsurf | 88 | — | Devin Desktop stable |
| GH Copilot | 75 | ↑2 | 39-day streak, Rust CLI migration |
| Aider | 68 | — | Maintenance mode |
| Cursor | 1 | — | Supply chain attack + OpenAI cutoff D-9, day 70 at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition complete |

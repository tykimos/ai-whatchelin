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

## Anthropic: IPO S-1 Goes Public, Roadshow Countdown Begins

Anthropic filed its S-1 registration statement with the SEC on October 26 ([CryptoBriefing](https://cryptobriefing.com/anthropic-nasdaq-ipo-listing-2026/)). The ticker is ANT, the listing venue is the Nasdaq Global Select Market, but the per-share price range remains blank — it will be set in an amended filing. Since the confidential-to-public filing requires at least 15 days before the roadshow can begin, the earliest possible start is November 10 ([Leverage Shares](https://leverageshares.com/us/insights/when-is-the-anthropic-ipo/)). Bloomberg has reported marketing could begin the week of November 9, with a listing expected in mid-November before Thanksgiving ([Parameter](https://parameter.io/claude-creator-prepares-100-billion-public-offering-ahead-of-thanksgiving/)).

## GitHub Copilot: November 16 Model Swap Details Confirmed

GitHub officially announced it will remove Claude Opus 4.8, Claude Opus 5, and GPT-5.6 Terra across all Copilot experiences on November 16 ([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). Replacements are Claude Opus 5.5 and GPT-6.1 Sol, with auto-enablement for Enterprise and Business customers under default settings. Annual individual subscribers get an exception for Opus 4.8.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra stable, Dec Codex pool merge pending |
| Claude Code | 99 | — | Supply chain attack was Cursor-side, core unaffected |
| Codex CLI | 99 | — | v0.166.0 stable |
| Antigravity | 99 | — | Gemini 4 Argon Pro rollout |
| Claude AI | 99 | — | ANT S-1 public, roadshow D-7 earliest |
| Windsurf | 88 | — | Devin Desktop stable |
| GH Copilot | 75 | ↑2 | 39-day streak, 11/16 model swap confirmed |
| Aider | 68 | — | Maintenance mode |
| Cursor | 1 | — | Supply chain attack + OpenAI cutoff D-9, day 70 at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition complete |

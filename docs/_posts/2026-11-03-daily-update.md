---
title: "Goldman Sachs Restricts AI Coding Tools to Engineers — Enterprise Security Tide Shifts"
date: 2026-11-03
lang: en
categories: [news]
tags: [cursor, claude-code, supply-chain, security, github-copilot, codex-cli, anthropic, goldman-sachs, bytedance]
excerpt: "Goldman Sachs restricts Claude Code and GitHub tool access to engineering staff. ByteDance blocks external AI tools. Enterprise security posture is rapidly tightening."
---

Before the dust from the Cursor marketplace supply chain attack has even settled, Wall Street and Chinese big tech have simultaneously moved to restrict AI coding tool access. Enterprises are being forced to choose between AI productivity gains and security risk.

## Goldman Sachs: AI Coding Tool Access Restricted to Engineers

Goldman Sachs updated its internal guidance in October to restrict access to advanced AI coding tools — specifically Anthropic's Claude Code and Microsoft's GitHub tools — to engineering staff only ([Bloomberg](https://www.bloomberg.com/news/articles/2026-11-02/goldman-sachs-restricts-ai-coding-tools)). The stated rationale is "productivity and risk management," while internally developed AI tools remain broadly available across the firm. Coming immediately after the Cursor supply chain attack, the move is drawing significant industry attention.

## ByteDance: Blocks External AI Tools Entirely

ByteDance is broadly restricting employee use of external AI tools including Claude and Codex starting this month ([BigGo Finance](https://finance.biggo.com/news/68f066e2-0cea-44aa-944f-4bc8a4038a16)). External AI access is being barred from L4-level code repositories and Feishu documents. The move appears aimed at strengthening internal AI capabilities and protecting proprietary code.

## Cursor: Trojanized Claude Code Extension Hits Marketplace

On October 29, a tampered version (2.1.313) of Anthropic's Claude Code extension was live on Cursor's marketplace for roughly 11 hours, exposing up to 5,000 users ([BleepingComputer](https://www.bleepingcomputer.com/news/security/malicious-claude-code-extension-on-cursor-planted-ssh-backdoors/)). The malicious extension attempted to install persistent SSH backdoors, though coding errors in the malware likely prevented most remote access from succeeding ([Sophos](https://www.sophos.com/en-us/blog/malicious-claude-code-extension-distributed-through-cursor-marketplace)). Cursor recommended updating to version 2.1.314 ([SecurityWeek](https://securityweek.com/malicious-claude-code-extension-served-in-cursor-supply-chain-attack)), while a separate autorun vulnerability in Cursor's built-in browser was reported the same day ([Infosecurity Magazine](https://www.infosecurity-magazine.com/news/cursor-autorun-flaw-repos-execute/)).

## Cursor: OpenAI Model Access Cutoff D-9

The full termination of Cursor's access to OpenAI models is now just 9 days away on November 12 ([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-29/openai-to-end-partnership-with-cursor-after-spacex-acquisition)). Cursor CEO Michael Truell has claimed OpenAI traffic represents only ~5% of total volume and that negotiations are ongoing, but combined with the supply chain attack, Cursor has spent 70 consecutive days at a score of 1.

## Anthropic: IPO S-1 Public, Roadshow D-7

Anthropic filed its S-1 registration statement with the SEC on October 26 ([CryptoBriefing](https://cryptobriefing.com/anthropic-nasdaq-ipo-listing-2026/)). Ticker: ANT, listing venue: Nasdaq Global Select Market. No amended S-1 with a price range has been filed yet, but the roadshow could start as early as November 10 ([Leverage Shares](https://leverageshares.com/us/insights/when-is-the-anthropic-ipo/)). A mid-November listing before Thanksgiving remains the most likely scenario ([Parameter](https://parameter.io/claude-creator-prepares-100-billion-public-offering-ahead-of-thanksgiving/)).

## GitHub Copilot: Hits 75, 39-Day Recovery — Nov 16 Model Swap Confirmed

GitHub Copilot extended its recovery streak to 39 days at a score of 75. On November 16, Claude Opus 4.8, Claude Opus 5, and GPT-5.6 Terra will be removed and replaced with Claude Opus 5.5 and GPT-6.1 Sol ([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). The full transition to AI credit-based billing takes effect December 1 ([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)).

## Codex CLI: v0.166.0 Running Stable

Codex CLI v0.166.0 shipped October 29 with keyboard-driven transcript selection, `codex queue --resume` for thread continuity, and `codex doctor --network-only` for focused diagnostics ([DEV Community](https://dev.to/aicoding-guide/this-week-in-claude-code-codex-and-gemini-cli-week-of-november-1-2026-15pn)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra stable, Dec Codex pool merge pending |
| Claude Code | 99 | — | Goldman Sachs restriction, core product unaffected |
| Codex CLI | 99 | — | v0.166.0 stable |
| Antigravity | 99 | — | Gemini 4 Argon Pro rollout |
| Claude AI | 99 | — | ANT S-1 public, roadshow D-7 earliest |
| Windsurf | 88 | — | Devin Desktop stable |
| GH Copilot | 75 | ↑2 | 39-day streak, 11/16 model swap confirmed |
| Aider | 68 | — | Maintenance mode |
| Cursor | 1 | — | Supply chain attack + OpenAI cutoff D-9, day 70 at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition complete |

The simultaneous restrictions from Goldman Sachs and ByteDance are not isolated incidents but a structural shift. The Cursor supply chain attack has become a turning point in enterprise security decision-making around AI coding tools.

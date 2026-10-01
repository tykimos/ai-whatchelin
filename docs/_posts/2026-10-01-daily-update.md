---
title: "Copilot's Biggest Model Purge Begins Tomorrow, Barclays Goes All-In on Claude Code"
date: 2026-10-01
lang: en
categories: [news]
tags: [github-copilot, claude-code, anthropic, cursor, openai, gpt-6-1-sol]
excerpt: "GitHub Copilot removes four models tomorrow and has six more scheduled for October 19. Meanwhile, Barclays announces plans to deploy Claude Code to half its developers by year-end."
---

GitHub Copilot begins its largest model cleanup tomorrow, October 2. Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7 will be removed across all Copilot experiences, with Gemini 3.8 Flash, Kimi K3, and Claude Opus 5 as replacements ([GitHub Changelog](https://github.blog/changelog/2026-09-03-upcoming-deprecation-of-selected-github-copilot-models/)). It doesn't stop there — on October 19, GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, and Grok 4.5 are next on the chopping block ([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)). Business and Enterprise customers now face upfront charges on credit card and PayPal seats starting today, and GitHub Universe is set for October 28-29 in San Francisco ([GitHub Blog](https://github.blog/news-insights/company-news/10-technical-talks-im-excited-about-at-github-universe-2026/)).

## Anthropic: Barclays Strategic Partnership Announced

Barclays officially announced an expanded strategic collaboration with Anthropic ([Anthropic](https://www.anthropic.com/news/barclays-scales-claude)). The bank targets 50% developer adoption of Claude Code by end of 2026, scaling to most developers by end of 2027. Beyond software development and legacy modernization, Claude is already routing 120,000 emails daily in the Global Markets division ([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/barclays-expands-use-of-anthropic-s-claude-in-efficiency-push)). This is the most concrete enterprise AI coding tool adoption case in the financial sector to date.

## Claude Code: v2.1.286 — Permission UX + Secret Leak Fix

Claude Code v2.1.286 shipped today ([ClaudeCodeLog/X](https://x.com/ClaudeCodeLog/status/2105377563698696459)). Permission prompts now show stacked counts ('2 of 5'), and sessions auto-retry the previous model once when the API refuses a model. A key security fix ensures secrets with invisible characters in key names are properly masked in logs.

## GPT-6.1 Sol: API Pricing Confirmed

The API pricing for GPT-6.1 Sol, unveiled at DevDay, is now confirmed ([OpenAI](https://openai.com/index/introducing-gpt-6-1-sol/)). Standard rates are $2/$10 per million tokens (input/output), cached input at $0.10/MTok, with long-context rates of $4/$15 kicking in above 272K input tokens. It delivers near-Astra performance at one-fifth the price. Rolling out to Plus and above in Work and Codex.

## Cursor: Drops to 29 — 35th Consecutive Day of Decline

Cursor's popularity score fell to 29, marking 35 consecutive days of decline. With 42 days until OpenAI model access is cut off and SpaceXAI's Grok-X subscription merger approaching, the tool's independent identity continues to fade.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Sol API pricing confirmed |
| Claude Code | 99 | — | v2.1.286, Barclays enterprise adoption |
| Codex CLI | 99 | — | Stable post-DevDay |
| Antigravity | 99 | — | 31-week high streak |
| Claude AI | 99 | — | Barclays partnership expansion |
| Windsurf | 88 | — | Stable as Devin Desktop |
| Aider | 68 | — | Effectively dormant |
| Cursor | 29 | ↓2 | 35th straight decline, D-42 |
| GH Copilot | 9 | ↑2 | 4 models removed tomorrow, slow recovery |
| Gemini CLI | 1 | — | Shutdown day 106 |

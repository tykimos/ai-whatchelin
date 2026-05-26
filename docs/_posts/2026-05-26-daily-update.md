---
title: "Claude Mythos Finds 23,000 Bugs Across 1,000+ Open-Source Projects — GitHub Goes Down Again"
date: 2026-05-26
lang: en
categories: [news]
tags: [claude-mythos, copilot, gemini-cli, antigravity, anthropic, vibe-coding, openai, github]
excerpt: "Claude Mythos's Project Glasswing rewrites the open-source security playbook, discovers an Apple macOS kernel CVE. GitHub suffers its 13th major outage since March, and Uber's COO admits the company can't prove AI coding tools are worth the spend."
---

A new era in AI-powered security is here. Anthropic's Claude Mythos scanned over 1,000 open-source projects and found 23,019 vulnerabilities — then went on to discover a root privilege escalation bug in the Apple macOS kernel. Meanwhile, GitHub logged its 13th major outage this year, and Uber confessed it burned through its entire AI budget by April with no clear ROI.

## Claude Mythos: Project Glasswing Rewrites Security

Project Glasswing results published today show Claude Mythos identified 23,019 total issues across 1,000+ open-source projects, with 6,202 classified as high/critical severity([Help Net Security](https://www.helpnetsecurity.com/2026/05/26/anthropic-project-glasswing-update/)). Independent security firms validated over 90% as true positives. AWS, Apple, Microsoft, Google, and NVIDIA participated as partners.

The real headline: researchers used Claude Mythos Preview to discover CVE-2026-28952, an integer overflow in the Apple macOS kernel enabling root privilege escalation on M5 architecture([Tom's Hardware](https://www.tomshardware.com/tech-industry/cyber-security/apple-m5-architecture-suffers-first-privilege-escalation-exploit-anthropics-claude-mythos-helps-researchers-bypass-memory-integrity-enforcement)). It's the first major CVE found by an AI agent — Apple patched it in macOS Tahoe 26.5([Apple](https://support.apple.com/en-us/127115)). A Mythos toggle (`claude-mythos-1-preview`) briefly appeared in the Claude Code UI on May 25 before being removed, and Anthropic confirmed plans to publicly release Mythos-class models "once far stronger safeguards are in place"([WinBuzzer](https://winbuzzer.com/2026/05/26/anthropics-mythos-moves-closer-to-claude-code-xcxwbn/)).

## GitHub: 13th Major Outage, Copilot D-5

Authentication failures starting at ~10:57 UTC knocked out GitHub Actions and Pages globally for over 2 hours([Cyber Security News](https://cybersecuritynews.com/github-down-authentication-issues/)). Resolved by 13:18 UTC, it hit 644 points on Hacker News. This adds to the "12+ outages since March" CNBC reported last week([CNBC](https://www.cnbc.com/2026/05/22/microsoft-was-positioned-to-win-in-ai-coding-outages-got-in-the-way.html)). Copilot sits at 61 — its 22nd consecutive weekly decline — with 5 days until June 1 usage-based billing([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)).

## ING: Vibe Coding Hits the Trading Floor

ING is building electronic trading tools using "vibe coding" AI, compressing weeks of developer work into hours([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-26/ing-s-vibe-coding-ai-is-building-its-new-trading-systems)). An AI currency pricing model drove a 50% increase in large-ticket trades([Yahoo Finance](https://finance.yahoo.com/markets/crypto/articles/ing-built-trading-system-hours-153057815.html)). ING predicts industry-wide adoption within one year.

## Uber: Burned the AI Budget, Can't Find the ROI

Uber's COO said the company burned through its entire 2026 AI budget by April and cannot demonstrate that Claude Code token consumption correlates with shipping more useful features([MLQ](https://mlq.ai/news/uber-burned-through-its-entire-2026-ai-budget-by-april-coo-questions-roi/)). *"That link is not there yet"* — a direct challenge to the ROI narrative driving AI coding tool adoption.

## HN #1: "Using AI to Write Better Code More Slowly"

Nolan Lawson's counterpoint to the "AI for speed" narrative hit #1 on Hacker News with 1,114 points. The argument: use AI to improve code quality, not velocity. While Google CEO Pichai says 75% of code at Google is AI-generated, the community is maturing past "faster" toward "better."

## Anthropic: $30B Round Closing + October IPO

Anthropic's $30B+ funding round is expected to close this week at a $900B+ valuation([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-22/anthropic-to-close-over-30-billion-round-as-soon-as-next-week)). An October IPO targeting $60B+ in proceeds is in preparation, with Wilson Sonsini hired for the listing([City AM](https://www.cityam.com/anthropic-targets-october-for-mega-ipo/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | Stable |
| Claude Code | 98 | — | Mythos approaching public release + $30B round |
| Cursor | 96 | — | Composer 2.5 stabilized |
| Claude AI | 94 | — | First profitable quarter expected |
| Codex CLI | 88 | — | Goal mode GA |
| Gemini CLI | 81 | ↓1 | Sunset D-23 |
| Windsurf | 81 | — | Stable baseline |
| Aider | 68 | — | Stable baseline |
| Copilot | 61 | ↓1 | 22-week slide + another outage today, D-5 |
| Antigravity | 55 | ↑1 | v2.0.0 patch recovery |

Mythos's real-world security results are the story of the day. But Uber's ROI admission and Hacker News's "write better, not faster" discourse signal a market maturing from adoption to value justification.

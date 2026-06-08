---
title: "Apple Brings Claude Agent to Xcode — WWDC 2026 Reshapes AI Coding Landscape"
date: 2026-06-08
lang: en
categories: [news]
tags: [apple, wwdc, claude-code, xcode, github-copilot, gemini, anthropic, spacex]
excerpt: "Apple announced Claude Agent and OpenAI Codex integration in Xcode at WWDC 2026. Siri is rebuilt on Google Gemini. Copilot drops to 48 for its 35th consecutive weekly decline."
---

Apple's WWDC 2026 keynote delivered the biggest external validation AI coding agents have ever received. Xcode is getting Claude Agent and OpenAI Codex as built-in agentic coding tools, while Siri is being rebuilt on a 1.2-trillion-parameter Gemini model. Apple chose to bet on Anthropic and OpenAI rather than building its own — a watershed moment for the AI coding market.

## Apple WWDC 2026: Claude Agent + Codex in Xcode, Siri Goes Gemini

Apple announced Claude Agent and OpenAI Codex as agentic coding tools in Xcode at WWDC 2026([TechCrunch](https://techcrunch.com/2026/03/23/apple-wwdc-june-8-12-ai-advancements-siri-developers-conference/)). iOS and macOS developers will be able to use AI agents directly inside Xcode for the first time. Simultaneously, Siri is being rebuilt on Google's 1.2T-parameter Gemini model under a reported $1B/year deal([TechRadar](https://www.techradar.com/news/live/apple-wwdc-2026-live)). iOS 27 and macOS 27 were also unveiled.

This was also Tim Cook's final WWDC keynote — he steps down as CEO on September 1, with hardware SVP John Ternus taking the reins([CNBC](https://www.cnbc.com/2026/06/05/apple-wwdc-tim-cook-ai-siri-ternus.html)). iOS 27 introduces an Extensions system that lets users choose Claude, Gemini, or ChatGPT as their default AI assistant([MacRumors](https://www.macrumors.com/guide/wwdc-2026-what-to-expect/)). Apple handing users the choice of third-party AI models is the largest external validation the AI coding agent market has ever seen.

## Claude Code GitHub Action: CVSS 7.8 Supply Chain Vulnerability

A supply chain flaw in Claude Code GitHub Actions allowed attackers to hijack repositories via a single malicious GitHub issue([The Hacker News](https://thehackernews.com/2026/06/claude-code-github-action-flaw-let-one.html)). The root cause: `checkWritePermissions` unconditionally trusted any actor ending in `[bot]` regardless of actual permissions. Some variants were actively exploited before disclosure. Fixed in claude-code-action v1.0.94+([Flatt Security](https://flatt.tech/research/posts/poisoning-claude-code-one-github-issue-to-break-the-supply-chain/)). Anthropic's own repository was found to be vulnerable — an ironic twist.

## GitHub Copilot: 48, 35-Week Decline

Copilot dropped to **48** — its 35th consecutive weekly decline. Day 8 of usage-based billing shows no signs of stabilization below the psychological 50 floor. Developer forums remain dominated by migration guides to Claude Code and Codex CLI, with users reporting $30-40 per day for agentic sessions([The Register](https://www.theregister.com/ai-and-ml/2026/06/02/github-copilot-users-threaten-exit-as-metered-billing-kicks-in/5249826)).

## Gemini API: Legacy Schema Removal Deadline

Today marks the deadline for Gemini Interactions API legacy schema support([Google AI for Developers](https://ai.google.dev)). Access via the `Api-Revision: 2026-05-07` header is now blocked — developers must migrate to the new `steps` array and polymorphic `response_format`. Combined with the Gemini CLI sunset (D-10), pressure on Google's AI developer ecosystem is mounting.

## This Week's Countdown

Code with Claude Tokyo is D-2 — June 10 features Research, Platform, and Code tracks, while June 11 brings indie developer workshops([claude.com](https://claude.com/code-with-claude/tokyo)). Anthropic's agent billing split (D-7, June 15) and the SpaceX IPO (D-4, trading June 12) are also imminent.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | WWDC Xcode integration, GitHub Action patched |
| ChatGPT | 96 | — | 1B MAU holding, UK ads expanding |
| Cursor | 96 | — | SpaceX $60B acquisition, IPO D-4 |
| Claude AI | 95 | — | Outage recovered, agent billing D-7 |
| Codex CLI | 87 | — | WWDC Xcode integration confirmed |
| Windsurf | 85 | — | Devin Desktop stabilizing, $15 price advantage |
| Aider | 68 | — | Open-source CLI stable |
| Gemini CLI | 67 | ↓1 | Sunset D-10, API legacy deadline today |
| Antigravity | 66 | ↑1 | Absorbing Gemini CLI migration |
| GH Copilot | 48 | ↓1 | 35-week decline, billing Day 8 |

Apple's WWDC announcement could fundamentally reshape the AI coding tool landscape. By choosing Anthropic and OpenAI over building in-house, Apple has massively strengthened both companies' enterprise positioning.

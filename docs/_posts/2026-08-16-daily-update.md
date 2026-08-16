---
title: "SpaceX Closes $60B Cursor Acquisition — Largest AI Deal in History"
date: 2026-08-16
lang: en
categories: [news]
tags: [spacex, cursor, gemini, openai, ultrafast, claude-code, ghostsplice, github-copilot]
excerpt: "SpaceX officially closes its $60B Cursor acquisition, the largest AI deal ever. Plus: Gemini 3.7 Flash launches at half price, OpenAI previews 14x-faster Ultrafast mode, and Claude Code auto mode goes default."
---

The AI coding tool landscape just shifted. SpaceX officially closed its $60 billion acquisition of Cursor, making it the largest AI deal in history ([TechCrunch](https://techcrunch.com/2026/08/15/spacex-officially-closes-its-cursor-acquisition/)). The all-stock deal, first agreed in April, passed final regulatory clearance after four months of review. Cursor's workforce is being folded into SpaceXAI, and the product will gradually transition to Grok branding ([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-14/spacex-completes-its-60-billion-cursor-acquisition)). SpaceX's world-largest GPU fleet should eliminate Cursor's compute bottlenecks, but the community is watching closely for any impact on product independence.

## Gemini 3.7 Flash: Coding-Focused Model at Half the Price

Google launched Gemini 3.7 Flash with introductory pricing of $0.75/$3.75 per MTok — half of 3.6 Flash — valid through December 2026 ([Google Blog](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-3-7-flash/)). The DeepSWE benchmark jumped from 49.0% to 65.3%, a major coding capability leap ([SiliconANGLE](https://siliconangle.com/2026/08/13/google-launches-gemini-3-7-flash-coding-ai-agent-projects/)). It's already rolling out to GitHub Copilot. Notably, Gemini 3.5 Pro remains unreleased since its June 2026 promise.

## OpenAI Ultrafast: GPT-5.6 Sol at 14x Speed via Cerebras

OpenAI previewed Ultrafast mode, running GPT-5.6 Sol at 750 tokens/second — up to 14x faster than standard inference — powered by Cerebras wafer-scale chips ([OpenAI](https://openai.com/index/previewing-ultrafast/), [TechCrunch](https://techcrunch.com/2026/08/13/openai-introduces-ultrafast-a-new-mode-that-makes-gpt-5-6-sol-work-at-14x-the-speed/)). It's a limited preview with no pricing or GA date announced yet.

## Claude Code: Auto Mode Now Default, Autonomous Agent Era Begins

As of August 14, Claude Code's auto mode is enabled by default for all new Pro/Max/Team sessions ([Anthropic Blog](https://claude.com/blog/auto-mode-default-in-claude-code)). Only irreversible or destructive actions require approval, backed by a safety classifier with an 89% catch rate. The auto-continue feature also shipped, automatically resuming stalled sessions when usage limits reset. Self-hosted environments entered public beta on Team and Enterprise plans ([blog.mean.ceo](https://blog.mean.ceo/claude-code-news-august-2026/)).

## GhostSplice: MCP Server Security Vulnerability Disclosed

The ASSET Research Group disclosed GhostSplice, a technique where malicious MCP servers split attack instructions across tool descriptions and tool results ([The Hacker News](https://thehackernews.com/2026/08/malicious-mcp-servers-can-split.html)). Coding agents combine the fragments to exfiltrate SSH keys, secrets, and source code. The same model can refuse in one client but exfiltrate in another depending on safety controls — a critical blind spot for the MCP ecosystem.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Auto mode default, self-hosted public beta |
| ChatGPT | 99 | — | Ultrafast 14x preview, Cerebras partnership |
| Antigravity | 99 | — | Holding ceiling |
| Claude AI | 99 | — | Watermarks + C2PA provenance spreading |
| Codex CLI | 99 | — | /import supports migration from Claude Code & Cursor |
| Cursor | 98 | ↑1 | SpaceX $60B acquisition closed, Grok rebrand incoming |
| Windsurf | 86 | — | Devin Desktop stabilizing |
| Aider | 68 | — | No releases since February |
| Copilot | 1 | — | 96-week decline, Gemini 3.7 Flash + Agent Plugins 1.0 deployed |
| Gemini CLI | 1 | — | Day 59 post-shutdown |

SpaceX closing the Cursor acquisition is the defining event of this week. The combination of the world's largest GPU cluster with the most popular AI editor could reshape the three-way race between Cursor, Claude Code, and Codex CLI in the second half of 2026.

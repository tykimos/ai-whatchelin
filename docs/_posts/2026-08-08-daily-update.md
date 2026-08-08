---
title: "Atlas Dies Tomorrow, Kiro Crew Goes Open Source — AI Coding Tools Split on Openness"
date: 2026-08-08
lang: en
categories: [news]
tags: [openai, atlas, kiro, claude-code, codex-cli, antigravity, copilot, devin, deepseek, cursor]
excerpt: "OpenAI's Atlas browser shuts down tomorrow, while AWS open-sources Kiro Crew under Apache 2.0. Claude Code v2.1.225 adds gateway spend limits, Codex CLI v0.147.0 launches agent plugins — the AI coding market is splitting clearly along open vs. closed lines."
---

OpenAI Atlas dies tomorrow, AWS releases Kiro Crew as open source, and the AI coding tool market is reshaping around a new axis: openness vs. control. On the same day, both Claude Code and Codex CLI expanded their agent plugin ecosystems.

## OpenAI: Atlas D-1 — Nine Months and Done

OpenAI's Atlas browser permanently shuts down tomorrow, August 9([Digital Trends](https://www.digitaltrends.com/computing/chatgpt-atlas-is-shutting-down-and-it-has-some-homework-left-before-you-migrate/)). Launched in October 2025, it lasted less than nine months. Agentic browsing capabilities are being folded into ChatGPT and Codex, but bookmarks and browsing history must be manually exported as HTML before the deadline([TechRadar](https://www.techradar.com/pro/openai-shuts-down-its-atlas-browser-after-not-even-a-year)). Meanwhile, Codex CLI v0.147.0 shipped portable agent plugins, a `--approve-for-me` flag for automated approvals, and MCP 2026-07-28 protocol support with paginated discovery([releasebot.io](https://releasebot.io/updates/openai/codex)).

## AWS Kiro: Crew Goes Open Source — But the Harness Stays Closed

AWS open-sourced Kiro Crew under Apache 2.0([Forbes](https://www.forbes.com/sites/janakirammsv/2026/08/06/aws-open-sources-kiro-crew-but-keeps-the-agent-harness-closed/)). The multi-agent orchestration platform, used by over 39,000 Amazon builders internally, is now publicly available — but the core agent harness (the runtime that communicates with foundation models) remains proprietary. Kiro IDE 1.0.288 also shipped the same day with Powers support in the Agent Plugin format and session pinning([kiro.dev](https://kiro.dev/changelog/ide/)).

## Claude Code: v2.1.225 — Cost Controls and Security Fixes

Anthropic released Claude Code v2.1.225([releasebot.io](https://releasebot.io/updates/anthropic/claude-code)). Gateway spend-limit support now surfaces in usage warnings — when a limit is reached, the message names the cap, its reset time, and the operator's message. Workspace trust prompts were added to `claude agents`, and six bugs were fixed including an OAuth token issue in headless sessions and macOS MCP OAuth keychain timeouts. Separately, Anthropic announced an 85% reduction in Fable 5's biology-related model fallbacks through retrained safety classifiers([anthropic.com](https://www.anthropic.com/news/improving-fable-5-s-biology-safeguards)).

## Antigravity: Desktop v2.6.0 + CLI Vim Mode

Google Antigravity Desktop v2.6.0 significantly improves conversation history loading speed and fixes 21 bugs([antigravity.google](https://antigravity.google/changelog)). CLI v1.1.11 introduces Vim modal editing (Normal/Insert/Visual/Visual Line), targeting terminal power users([releasebot.io](https://releasebot.io/updates/google/antigravity)).

## GitHub Copilot: Code Review Effort Levels Go GA

Copilot code review now offers lite and balanced effort levels for adjusting review depth based on change complexity and risk([github.blog](https://github.blog/changelog/month/08-2026/)). Code Quality also stopped auto-requesting Copilot as a PR reviewer — a reversal after user feedback that "adding a reviewer should be your choice."

## DeepSeek: Price Hike Day 4, V4 Flash Hit 8T Tokens/Day

DeepSeek's "significant" price increase warning is on day four of community shockwaves([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-06/deepseek-plans-significant-price-increase-for-its-ai-services)). Founder Jun Song indicated a potential 2-10x increase while noting DeepSeek would "still undercut most Western rivals." V4 Flash processing 8 trillion tokens in a single day on August 1 — overwhelming available compute — is the driving force([explainx.ai](https://www.explainx.ai/blog/deepseek-api-price-increase-jun-song-august-2026)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.225 spend-limit support, security fixes |
| ChatGPT | 99 | — | Atlas dies tomorrow, GPT-5.6 unlimited continues |
| Antigravity | 99 | — | Desktop v2.6.0 + CLI Vim mode |
| Claude AI | 99 | — | Fable 5 bio safeguards 85% improvement |
| Codex CLI | 99 | — | v0.147.0 agent plugins, hit ceiling |
| Cursor | 97 | — | iOS public beta, $3B ARR |
| Windsurf | 85 | — | Devin Desktop holding steady |
| Aider | 68 | — | No releases since Feb, 44K stars |
| Copilot | 1 | — | Code review GA, but Sept 1 deprecation D-24 |
| Gemini CLI | 1 | — | Shutdown Day 51, Antigravity full replacement |

Atlas shutting down and Kiro Crew going open source on the same day makes one thing clear: the AI coding tool competition is shifting from product features to ecosystem openness.

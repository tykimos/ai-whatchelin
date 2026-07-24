---
title: "DeepSeek V4 Migration D-Day Arrives as Cursor Router Slashes Costs by 60%"
date: 2026-07-24
lang: en
categories: [news]
tags: [deepseek, cursor, anthropic, claude-security, github-models, copilot, gemini-cli, opus, antigravity]
excerpt: "DeepSeek V4 legacy endpoints shut down today and Cursor Router delivers 60% cost savings through intelligent model routing. Opus 4.7 fast mode also retires."
---

Three major shifts hit AI developers simultaneously today. DeepSeek V4's `deepseek-chat` and `deepseek-reasoner` legacy endpoints permanently shut down at 15:59 UTC([DEV Community](https://dev.to/agdex_ai/deepseek-v4-api-migration-guide-everything-before-the-july-24-2026-deadline-4m30)), Anthropic completed the Opus 4.7 fast mode retirement in favor of Opus 4.8 fast mode, and Cursor Router — launched just two days ago — is rapidly reshaping the industry's cost structure.

## Cursor Router: The Model Routing Revolution

Cursor's Router, launched July 22, is an intelligent model router trained on over 600,000 live requests([Cursor Blog](https://cursor.com/blog/router)). It analyzes each request's complexity and task type, automatically selecting the most cost-effective model — routing simple tasks to cheaper models while reserving frontier models for complex work only. Early access across dozens of enterprises delivered frontier-quality performance at 30-60% lower cost with no quality drop-off([MarkTechPost](https://www.marktechpost.com/2026/07/22/cursor-releases-cursor-router-a-request-level-classifier/)). Teams plans get it by default; Enterprise admins can enable it per organization group.

## DeepSeek V4: Legacy Endpoints Permanently Closed

V4 goes stable with 1M-token context and stronger agent execution as the old model names are retired([WaveSpeed](https://wavespeed.ai/blog/posts/blog-deepseek-v4-model-name-migration/)). The migration is a one-line code change, but missing it breaks production. Meanwhile, the new peak-hour pricing — API rates doubling during Beijing business hours (9-12, 14-18) — remains the industry's first case of time-of-day token pricing([Servola](https://servola.de/journal/ai-tokens-now-have-a-rush-hour/)).

## Claude Security: Enterprise Beta Gaining Traction

Claude Security, unveiled yesterday, continues its rapid adoption. The Opus 4.7-powered multi-agent scanner traces data flows across files, reads Git history, and generates targeted patches([MarkTechPost](https://www.marktechpost.com/2026/07/22/anthropic-releases-claude-security-plugin-for-claude-code-in-beta-a-multi-agent-vulnerability-scanner-that-runs-in-your-terminal/)). Available as a Claude Code plugin for terminal-based pre-commit scans, it's currently Enterprise-only([Claude Blog](https://claude.com/blog/claude-security-public-beta)).

## Antigravity CLI v1.1.5: Real-Time Reasoning Tuning

Antigravity CLI shipped v1.1.5 on July 21 with a new `/effort` command([Havoptic](https://www.havoptic.com/tools/antigravity-cli)). Users can now trade speed for deeper thinking on the fly, reducing unnecessary token consumption on straightforward tasks.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Claude Security beta reception strong, Fable default stable |
| ChatGPT | 99 | — | GPT-5.6 Sol stabilizing, Codex integration ongoing |
| Antigravity | 99 | — | v1.1.5 /effort command, Go build stable |
| Claude AI | 98 | — | Opus 4.8 fast mode transition complete |
| Cursor | 97 | — | Router launched, usage limits doubled, iOS landing |
| Codex CLI | 91 | — | v0.145.0 stable, Bedrock support expanding |
| Windsurf | 85 | — | Devin Desktop stable operations |
| Aider | 68 | — | No major updates |
| Copilot | 1 | ↓1 | 76-week decline, GitHub Models D-6 |
| Gemini CLI | 1 | ↓1 | Consumer access closed 36 days |

Cursor Router is the biggest market signal today. Its 30-60% cost savings via intelligent model routing sends a clear message — you don't always need the most expensive model — and other AI coding tools will likely follow suit.

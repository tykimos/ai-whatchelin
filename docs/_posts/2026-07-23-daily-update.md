---
title: "Block Launches Buzz: An Open-Source Workspace Where AI Agents Sign Their Own Work"
date: 2026-07-23
lang: en
categories: [news]
tags: [block, buzz, claude-code, codex-cli, deepseek, gemini, github-models, meta, security]
excerpt: "Jack Dorsey's Block released Buzz, an open-source collaboration workspace built on the Nostr protocol that gives AI agents their own cryptographic identity and signed audit trails."
---

Jack Dorsey's Block launched Buzz, an open-source collaboration workspace where AI agents and human developers work side by side([SiliconANGLE](https://siliconangle.com/2026/07/21/block-launches-buzz-open-source-workspace-humans-ai-agents/)). Built on the Nostr protocol, Buzz gives each AI agent a unique cryptographic identity with a signed audit trail for every action([TechTimes](https://www.techtimes.com/articles/321242/20260722/block-launches-buzz-open-source-workspace-where-ai-agents-sign-their-own-work.htm)). It integrates with Claude Code, OpenAI Codex, and Block's goose framework via the Agent Client Protocol, and ships under Apache 2.0. No crypto tokens are involved.

## DeepSeek V4: Migration Deadline Is Tomorrow

DeepSeek V4 is set for its stable release on July 24([TechNode](https://technode.com/2026/06/30/deepseek-to-launch-v4-in-mid-july-with-new-peak-time-api-pricing/)). The legacy `deepseek-chat` and `deepseek-reasoner` endpoints will become inaccessible starting tomorrow. Output pricing lands at roughly $0.44/MTok — an industry price floor — with a new peak/off-peak rate structure tied to Beijing business hours. Developers who haven't migrated need to act now.

## GitHub Models: Brownout Today, Full Shutdown July 30

A scheduled brownout for GitHub Models is happening today, July 23([GitHub Blog](https://github.blog/changelog/2026-07-01-github-models-is-being-fully-retired-on-july-30-2026/)). The playground, model catalog, inference API, and BYOK endpoints will be permanently retired on July 30. Migration to Azure AI Foundry is required.

## Claude Code v2.1.218: Background Code Review

Claude Code v2.1.218 shipped([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). `/code-review` now runs as a background subagent, screen-reader accessibility was improved, and dangerous command checks in auto-mode no longer trigger permission dialogs. HTTP status info for misconfigured MCP servers was also added.

## Meta Muse Spark 1.1: 1M Context + Computer Use

Meta released Muse Spark 1.1 with a 1M-token context window([Build Fast With AI](https://www.buildfastwithai.com/blogs/ai-news-today-july-21-2026)). It adds computer-use capabilities across desktop, browser, and mobile, and ranked #1 on both JobBench and Finance Agent V2 benchmarks. Parallel subagent delegation is also supported.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.218, background code review |
| ChatGPT | 99 | — | GPT-5.6 Sol GA, security incident aftermath |
| Antigravity | 99 | — | Sandbox CVEs still unpatched |
| Claude AI | 98 | — | Post AMD $5B investment |
| Cursor | 97 | — | SpaceX acquisition proceeding |
| Codex CLI | 91 | ↑1 | v0.145.0 thread history, /import |
| Windsurf | 85 | — | Devin Desktop stable operations |
| Aider | 68 | — | No major updates |
| Copilot | 3 | ↓1 | GitHub Models shutdown D-7, 76-week decline |
| Gemini CLI | 3 | ↓1 | Consumer access closed, day 35 |

Codex CLI climbed to 91 on the strength of v0.145.0's competitor migration features and GPT-5.6 Sol as its default model. GitHub Copilot and Gemini CLI each dropped to 3 as their respective platform shutdowns continue. Tomorrow's DeepSeek V4 stable release — combined with the sunsetting of legacy endpoints — is expected to trigger significant migration across the API-dependent developer community.

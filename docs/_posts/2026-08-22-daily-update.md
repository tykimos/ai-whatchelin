---
title: "OpenAI Slashes GPT-5.6 Sol Prices 20%+ as Codex Hits 20 Million Users"
date: 2026-08-22
lang: en
categories: [news]
tags: [openai, gpt-5.6-sol, codex, claude-code, claude-academy, cursor, copilot, antigravity, pricing, security]
excerpt: "OpenAI cuts GPT-5.6 Sol API prices by over 20% and celebrates 20 million Codex users. Anthropic launches Claude Academy, while Copilot's AI Autofix creates a security vulnerability exploited within days."
---

OpenAI slashed its frontier GPT-5.6 Sol API prices by more than 20% — standard short-context input tokens drop from $5 to $4, and output tokens from $30 to $20 ([Business Standard](https://www.business-standard.com/technology/tech-news/openai-cuts-developer-pricing-for-gpt-5-6-sol-model-by-more-than-20-126082200107_1.html)). The three-month promotional cut through November 21 follows last month's Terra 20% and Luna 80% discounts ([CNBC](https://www.cnbc.com/2026/07/30/open-ai-price-cut-gpt.html)). The move is widely read as a defensive play to stem developer attrition amid pressure from Anthropic and Chinese AI models ([Finimize](https://finimize.com/content/openai-cut-gpt-56-sol-api-prices-to-keep-developers-close)).

## Codex: 20 Million Users, Reset Controversy

Codex lead Tibo Sottiaux announced the 20-million active user milestone and offered a free banked usage reset for all users ([explainx.ai](https://www.explainx.ai/blog/openai-codex-20-million-users-banked-reset-august-2026)). But the celebration was marred by a delivery delay (8pm PST deadline slipped) and community frustration over resets silently expiring after 30 days ([OpenAI Community](https://community.openai.com/t/20-million-codex-users-a-free-banked-reset-for-everyone/1391683)). Meanwhile, o3 exits ChatGPT on August 26 (D-4) and GPT-5.4 leaves Codex on August 31 (D-9) ([OpenAI](https://openai.com/index/gpt-5-6/)).

## Claude: Academy Launch, Code v2.1.239

Anthropic launched Claude Academy — a learning hub with 26 free courses across five tracks (developer, student, educator, professional, nonprofit) ([CryptoBriefing](https://cryptobriefing.com/anthropic-unveils-claude-academy-to-boost-ai-education-and-adoption/)). Courses range from Claude 101 to API and Claude Code deep dives, with badges and personalized recommendations ([Techgenyz](https://techgenyz.com/claude-academy-free-courses/)).

Claude Code v2.1.239 now factors the 1.1x US-only-inference premium into cost estimates for data-residency workspaces and adds a `/claude-api upgrade` command for Python SDK 0.x→1.x migration ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Alpine/musl builds gained native image paste, clipboard, and audio support, and fullscreen renderer now surfaces on Bedrock, Vertex, and Foundry ([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)).

## Copilot: AI Autofix Turns Security Liability

Copilot Autofix generated a fix for Snowflake's snowflake-connector-net that introduced a shell-injection vulnerability — exploited within five days ([The Register](https://www.theregister.com/)). Separately, CVE-2026-24301 (CoSnitch) — a chained attack combining Copilot URL fetch with persistent memory poisoning — was patched on August 18. The 102-consecutive-week popularity decline continues, with mass model deprecation now D-10 away ([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)).

## Cursor: Event-Driven Cloud Agents Mature

Cursor's August 19 update added event subscriptions to cloud agents — register PRs, Slack threads, or cron schedules as triggers ([Releasebot](https://releasebot.io/updates/cursor), [explainx.ai](https://www.explainx.ai/blog/cursor-event-driven-cloud-agents-isolated-vms-august-2026)). Subagents now run on isolated VMs for collision-free parallel execution. Pricing changes for Auto mode take effect August 24.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.239 cost precision, Alpine support |
| ChatGPT | 99 | — | GPT-5.6 Sol 20%+ price cut, o3 retirement D-4 |
| Codex CLI | 99 | — | 20M users milestone, GPT-5.4 retirement D-9 |
| Antigravity | 99 | — | v2.9.1 Remote Control, 26-week streak at 99 |
| Claude AI | 99 | — | Claude Academy launched, Files API GA |
| Cursor | 99 | — | Event-driven agents, pricing change Aug 24 |
| Windsurf | 86 | — | Devin Local stabilizing |
| Aider | 68 | — | No release in 6+ months since v0.86.2 |
| Copilot | 1 | — | 102-week decline, Autofix security incident, deprecation D-10 |
| Gemini CLI | 1 | — | Shutdown day 65 |

OpenAI's consecutive price cuts and the Codex 20M milestone signal the AI coding market is shifting from feature competition to a price-and-scale war. Meanwhile, Copilot's Autofix security incident raises fresh questions about the trustworthiness of AI-generated code fixes.

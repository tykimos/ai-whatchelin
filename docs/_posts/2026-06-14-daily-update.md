---
title: "Anthropic Faces Triple Deadline Tomorrow — Model Retirement, Agent Billing, and Fable 5 Limbo"
date: 2026-06-14
lang: en
categories: [news]
tags: [anthropic, claude, fable-5, copilot, gemini-cli, spacex, moonshot]
excerpt: "June 15 brings Claude Sonnet 4/Opus 4 retirement, Agent SDK billing split, and ongoing Fable 5 suspension talks — the busiest 24 hours for Anthropic users this year."
---

Anthropic users face three simultaneous changes within 24 hours tomorrow (June 15). With Fable 5 still suspended under a US Commerce Department order, legacy model retirement and a new billing structure converge to create the most consequential day for the AI coding ecosystem this month.

## Anthropic: The Triple Deadline

Tomorrow at 9AM PT, Claude Sonnet 4 and Opus 4 undergo hard retirement — API requests will immediately return errors with no grace period ([MindStudio](https://www.mindstudio.ai/blog/claude-sonnet-4-opus-4-deprecation-migration-guide)). Applications that haven't migrated to Opus 4.7 or newer will break instantly ([DEV Community](https://dev.to/raxxostudios/claude-opus-4-and-sonnet-4-retire-june-15-2iog)). Simultaneously, the Agent SDK billing split goes live: Agent SDK, `claude -p`, GitHub Actions, and all automated workloads move to a separate credit pool — $20 for Pro, $100 for Max 5x, $200 for Max 20x ([The New Stack](https://thenewstack.io/anthropic-agent-sdk-credits/)). When credits run out, automated requests stop entirely unless the user has manually enabled overflow billing ([TechTimes](https://www.techtimes.com/articles/317625/20260602/anthropic-ends-subscription-subsidy-agents-june-15-credit-pool-replaces-flat-rate-access.htm)).

## Fable 5: Government Shutdown Day 2

Fable 5 and Mythos 5 remain suspended two days after the US Commerce Department's export-control directive pulled them on June 12 — just three days after launch ([NBC News](https://www.nbcnews.com/tech/tech-news/anthropic-suspends-new-ai-models-fable-mythos-government-directive-rcna349901)). Anthropic maintains the order was based on "a misunderstanding" and is calling for "a transparent process based on technical facts" ([Anthropic official statement](https://www.anthropic.com/news/fable-mythos-access)). Fortune highlighted the irony that Amazon — Anthropic's own investor — reported the jailbreak vulnerability to the Commerce Department. Opus 4.8 serves as the fallback, but the gap left by Fable 5's SWE-Bench Pro 80.3% score is felt across the developer community.

## Copilot: 41 Straight Weeks Down, Now at 42

GitHub Copilot's popularity score dropped to 42, extending its decline to 41 consecutive weeks ([Visual Studio Magazine](https://visualstudiomagazine.com/articles/2026/06/04/copilot-billing-shock-hits-developers.aspx)). It's been 14 days since the June 1 usage-based billing shift, and the $30-40 per agentic session cost structure continues to accelerate developer migration. The situation hasn't improved since TechCrunch called it "What a joke."

## Gemini CLI: Shutdown in 4 Days

Only four days remain before Gemini CLI shuts down for individual users on June 18 ([Digital Applied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). After the deadline, only paid enterprise customers retain access. Individual users must migrate to the Go-based Antigravity CLI (agy) ([Medium](https://medium.com/@hsinghungwang/migrating-from-gemini-cli-to-antigravity-cli-agy-af324c10c781)). Antigravity continues its steady climb to 71, absorbing the migration demand.

## Moonshot AI Open-Sources Kimi K2.7-Code

Moonshot AI released Kimi K2.7-Code under a Modified MIT license ([LLM Stats](https://llm-stats.com/ai-news)). As competition in coding-specialized open-source models intensifies, this gives users of open-source tools like Aider another strong option for local-first development.

## SpaceX SPCX: IPO Day 3 Stabilizes

SpaceX (SPCX) stabilized in the $161-167 range on its third day of trading ([CNBC](https://www.cnbc.com/2026/06/12/spacex-ipo-spcx-live-updates.html)). The stock maintains roughly 20% above its $135 IPO price, with Musk's net worth holding above $1.05 trillion. The $60B SpaceX-Cursor acquisition deal continues to reshape the AI coding landscape.

## Market Pulse

| Tool | Score | Change | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 rock-solid despite Fable 5 suspension |
| ChatGPT | 96 | — | Stable after 1B MAU milestone |
| Claude AI | 96 | — | Tomorrow's model retirement + billing shift watched |
| Cursor | 96 | — | SpaceX acquisition signed, SDK beta |
| Codex CLI | 87 | — | Goal mode GA, steady |
| Windsurf | 85 | — | Devin Desktop rebrand settling in |
| Antigravity | 71 | +1 | Absorbing Gemini CLI D-4 migration |
| Aider | 68 | — | Kimi K2.7-Code adds new model option |
| Gemini CLI | 61 | -1 | Shutdown D-4, individual users migrating |
| GH Copilot | 42 | -1 | 41 weeks straight down, no floor in sight |

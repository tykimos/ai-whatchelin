---
title: "D-2: Sonnet 4.5 Retirement Looms — ANT Trades Day 9, Replit Unleashes Agent Swarms"
date: 2026-11-28
lang: en
categories: [news]
tags: [anthropic, openai, copilot, gpt-6-2, devin, sonnet-4-5, opus-4-8, black-friday, claude-ship, gemini-4-neon, ant-ipo, replit-missions, arc-agi-3]
excerpt: "Forty-eight hours until Sonnet 4.5 retires and Opus 4.8 fast mode disappears. Anthropic's ANT is trading nine days after the largest IPO in history, and Replit Missions lets agent swarms build for days."
---

Forty-eight hours remain until Anthropic's double deadline on November 30, and seventy-two hours until Copilot Carbon's price hike on December 1. With Thanksgiving and Black Friday keeping most North American dev teams away from their desks, the practical window for production audits is closing fast. Meanwhile, Anthropic's landmark Nasdaq debut and Replit's multi-agent launch are reshaping the coding tool landscape.

## Anthropic D-2: Two Breaking Changes in 48 Hours

Sonnet 4.5 (`claude-sonnet-4-5-20250929`) retires from the API in two days([Anthropic Docs](https://platform.claude.com/docs/about-claude/model-deprecations)). Its successor Sonnet 5.5 is 33% cheaper on paper, but the new tokenizer generates ~30% more tokens for equivalent text, narrowing real savings([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). On the same day, Opus 4.8 fast mode is removed — exactly one month after the October 30 deprecation notice — and requests will return errors([Anthropic Docs](https://code.claude.com/docs/en/fast-mode)). Teams that haven't completed migration risk Monday morning outages after the holiday weekend.

## Anthropic ANT: Day 9 After the Largest IPO in History

Anthropic debuted on the Nasdaq on November 19 under ticker ANT([CNBC](https://www.cnbc.com/2026/11/19/anthropic-ipo-ant-live-updates.html)). The company sold 980 million shares at $83, raising $81.3 billion and surpassing SpaceX for the largest IPO ever([Fox Business](https://www.foxbusiness.com/markets/anthropic-begins-trading-nasdaq-record-breaking-ipo)). Shares opened at $111.50 and closed at $97.17, putting the market cap at roughly $1.76 trillion([CNN](https://www.cnn.com/2026/11/19/business/live-news/anthropic-ipo)). Unusually, up to 20% of IPO shares were allocated to retail investors via Fidelity, Robinhood, and other brokerages([Al Jazeera](https://www.aljazeera.com/economy/2026/11/19/anthropic-starts-trading-in-the-us-after-blockbuster-ipo)). An AI model company entering public markets at this scale is expected to accelerate investment in developer tooling.

## GPT-6.2 Astra: ARC-AGI-3 Perfect Score and Self-Improvement Threshold

Released November 17, GPT-6.2 Astra is the first externally deployed model to meet the "High" threshold for AI Self-Improvement under OpenAI's Preparedness Framework([OpenAI](https://openai.com/index/introducing-gpt-6-2-astra-sol)). It is also the first model to score 100% on ARC-AGI-3, as verified by the ARC Prize Foundation — though that result uses the provider adapter harness([Emergent](https://emergent.sh/news/gpt-6-2-astra-scores-100-arc-agi-3-benchmark)). Under the standard harness, Astra scores 70.3%, trailing Claude Fable 5.2's 81.2%([FourWeekMBA](https://fourweekmba.com/ai-openais-gpt-6-2-astra-is-first-to-100-on-arc-agi-3-4-1k/)). API pricing sits at $8 input / $40 output per MTok — 20% below GPT-6 Astra([Pulse2](https://pulse2.com/openai-introduces-gpt-6-2-astra-and-sol-with-improved-performance-and-lower-task-costs/)). On the robotics front, Astra tops the AA-Robotics v0.1 leaderboard with a score of 79([Crypto Briefing](https://cryptobriefing.com/gpt-6-2-astra-tops-aa-robotics-benchmark/)).

## Replit Missions: Agent Swarms That Build for Days

Replit launched Missions on November 17([Replit Blog](https://replit.com/blog/introducing-replit-missions)). Users set a goal and budget, then a swarm of agents plans, builds, tests, and iterates over hours, days, or even weeks([The New Stack](https://thenewstack.io/replit-missions-agent-swarms/)). Replit reports speedups of 4x with one agent, 17x with 16, and 19x with 32 on NumPy benchmark tasks — though no independent verification exists yet([Byteiota](https://byteiota.com/replit-missions-agent-swarm/)). The flagship demo built DataCat, a monitoring platform, in two days on a $3,000 budget([Replit Blog](https://replit.com/blog/introducing-replit-missions)).

## Cognition Launches Devin Bots: Persistent Multi-Agent Orchestration

Cognition released Devin Bots on November 17([Fortune](https://fortune.com/2026/11/17/exclusive-cognition-bets-on-devin-bots-coding-agents-in-challenge-to-anthropics-duet-and-openais-dots/)). These are persistent agents that manage teams of Devin coding agents on projects lasting days or weeks — for example, automatically assigning Android counterpart tasks when an iOS app is updated([AI Weekly](https://aiweekly.co/alerts/cognition-launches-devin-bots-to-oversee-teams-of-devin-agents)). Fortune positioned the launch as a direct challenge to Anthropic's Duet and OpenAI's Dots always-on agent offerings.

## Claude Ship Beta: AI Agents That Review, Fix, and Approve PRs

Anthropic launched Claude Ship beta on November 23. The tool deploys AI agents that review, fix, and approve routine code changes — early adopters are already testing it in production. Where Claude Code's existing code review focused on per-PR bug detection, Ship automates the full cycle of repetitive changes.

## Black Friday: No New Deals, but Expiring Promos Need Attention

On Thanksgiving Day and Black Friday eve, no new AI coding tool discounts have surfaced([zPlatform](https://zplatform.ai/ai-deals/best-black-friday-ai-deals-2026/)). However, two existing promotions are about to expire: GitHub Copilot Fusion's 30% model-cost discount ends November 30([GitHub Docs](https://docs.github.com/en/copilot/reference/copilot-billing/models-and-pricing)), and Gemini 4 Carbon's introductory pricing ($2/$10 per MTok) doubles to $4/$20 on December 1([eWeek](https://www.eweek.com/news/google-gemini-4-carbon-api-pricing/)). Meanwhile, Gemini 4 Neon went GA in Copilot on November 18, offering a lower-cost alternative as Carbon prices rise([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra ARC-AGI-3 100%, live 11 days |
| Claude Code | 99 | — | v2.1.327, ANT IPO fueling investment outlook |
| Codex CLI | 99 | — | v0.169 side-chat tabs, searchable tasks |
| Antigravity | 99 | — | Google's sole coding agent, steady |
| Claude AI | 99 | — | Sonnet 4.5 D-2 + Opus 4.8 Fast Mode D-2 |
| GH Copilot | 99 | — | Carbon price doubles D-3 (Dec 1), Neon rising |
| Windsurf | 89 | — | Devin Bots + Replit Missions accelerate agent era |
| Aider | 68 | — | Maintenance mode, 44K stars |
| Cursor | 1 | — | OpenAI blackout day 17, 128 days at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition done |

Anthropic's double deadline is D-2, Copilot Carbon is D-3. With agent swarms (Replit Missions, Devin Bots) arriving this month, the unit of coding tools is shifting from "assistant" to "team."

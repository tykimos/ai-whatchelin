---
title: "ChatGPT Hits 1 Billion Users, Copilot Falls to 49, Claude Code Ships fallbackModel"
date: 2026-06-07
lang: en
categories: [news]
tags: [chatgpt, github-copilot, claude-code, anthropic, gemini-cli, spacex, cursor]
excerpt: "ChatGPT crosses 1 billion monthly active users on the same day Copilot drops to 49 for its 34th consecutive weekly decline. Claude Code ships a fallbackModel feature to guard against outages. Tokyo D-3, Gemini CLI sunset D-11."
---

ChatGPT crossed 1 billion monthly active users — the fastest any app has reached this milestone — on the same day GitHub Copilot slid to 49, marking its 34th straight weekly decline. Meanwhile, Claude Code shipped a fallbackModel setting as its answer to a string of recent outages.

## ChatGPT: 1 Billion MAU, Ads Launch in UK

ChatGPT surpassed 1 billion monthly active users([ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). OpenAI simultaneously began rolling out ads to Free and Go users in the UK, with paid plans remaining ad-free. Plus and Pro users also received 2x memory capacity and a new Lockdown Mode security setting to reduce prompt injection risk.

## Claude Code v2.1.166-167: fallbackModel for Outage Resilience

Claude Code shipped two back-to-back releases introducing the `fallbackModel` setting — configure up to three fallback models tried in order when the primary model is overloaded or unavailable([GitHub CHANGELOG](https://github.com/anthropics/claude-code/blob/main/CHANGELOG.md)). The feature's value proved itself immediately — Opus 4.7 experienced elevated errors from 03:41 UTC today, with a fix deployed by 15:41 UTC after ~12 hours of degraded service([Claude Status](https://status.claude.com/)). After three outages in recent weeks (June 2, June 5, June 7), fallbackModel is a practical resilience feature. Also ships glob pattern support in deny rules and a JetBrains IDE flicker fix.

## GitHub Copilot: 49, 34-Week Decline

Copilot dropped to **49** — sinking further below yesterday's psychological floor break. Day 7 of usage-based billing, 34th consecutive weekly decline. Migration guides to Claude Code, Cursor, and Codex CLI continue to dominate developer forums([Dev.to](https://dev.to/akaranjkar08/switch-from-github-copilot-to-claude-code-migration-guide-2026-28nk)).

## Gemini CLI Sunset D-11: Trust Erosion Continues

11 days until Gemini CLI stops serving requests for non-enterprise users on June 18([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). Community anger over the perceived "bait-and-switch" — 6,000+ PRs merged into the open-source Apache 2.0 repo, now folded into closed-source Antigravity — shows no signs of abating([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)).

## Code with Claude Tokyo: D-3

Code with Claude Tokyo is 3 days away. June 10 features three parallel tracks — Research, Claude Platform, and Claude Code — while June 11 brings indie developer demos and Applied AI workshops([claude.com](https://claude.com/code-with-claude/tokyo)). All sessions will be livestreamed with simultaneous English/Japanese interpretation.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.166-167 fallbackModel, Tokyo D-3 |
| ChatGPT | 96 | — | 1B MAU milestone, UK ads launch |
| Cursor | 96 | — | SpaceX $60B acquisition, IPO D-5 |
| Claude AI | 95 | — | 6/7 degraded performance, recovered |
| Codex CLI | 87 | — | Sites preview, GPT-5.3-Codex sunset 6/30 |
| Windsurf | 85 | — | Cascade EOL 7/1, Devin Desktop stabilizing |
| Gemini CLI | 68 | ↓1 | Sunset D-11, trust erosion |
| Aider | 68 | — | Open-source CLI stable |
| Antigravity | 65 | — | Absorbing Gemini CLI migration |
| GH Copilot | 49 | ↓1 | 34-week decline, billing Day 7 |

ChatGPT's 1B MAU milestone and Copilot's continued slide below 50 paint a stark picture of market polarization. Tuesday's Code with Claude Tokyo keynote is the biggest watch point of the week.

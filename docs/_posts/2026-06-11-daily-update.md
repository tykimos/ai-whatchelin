---
title: "SpaceX IPO Prices Today — Largest Ever at $1.75T, Cursor Acquisition Funded"
date: 2026-06-11
lang: en
categories: [news]
tags: [spacex, cursor, claude, fable-5, copilot, codex-cli, gemini-cli, antigravity, code-with-claude, tokyo, fable-5-controversy]
excerpt: "SpaceX locks its IPO price at $135/share today. At $1.75T it becomes the largest IPO in history, with Nasdaq trading starting tomorrow and $60B Cursor acquisition funding secured."
---

SpaceX finalizes its IPO price after market close today. At $135/share and a $1.75T valuation, this becomes the largest public offering in history. Nasdaq trading under ticker SPCX begins tomorrow — and the proceeds secure the $60B Cursor acquisition.

## SpaceX IPO: Largest Ever, Trading Starts Tomorrow

SpaceX is set to finalize its $135/share fixed IPO price today([CNBC](https://www.cnbc.com/2026/06/03/spacex-ipo-stock-price-roadshow-musk.html)). The offering of 555.6 million shares will raise approximately $75 billion at a $1.75T valuation — the largest IPO in market history([TradingKey](https://www.tradingkey.com/analysis/stocks/us-stocks/261957856-spacex-ipo-at-135-what-the-s-1-financials-actually-say-tradingkey)). Bloomberg confirmed the IPO is more than 4x oversubscribed, with approximately $150 billion in orders pouring in — Gulf wealth funds alone committed billions([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-10/spacex-ipo-is-said-to-be-more-than-four-times-oversubscribed)). A Nasdaq fast-track rule enables Nasdaq-100 index inclusion within 15 trading days, triggering an estimated $7B in index fund purchases. The proceeds are central to funding the $60B Cursor acquisition deal signed on June 5.

## Code with Claude Tokyo Extended: Indie Developer Day

Code with Claude Tokyo Extended kicks off today([claude.com](https://claude.com/code-with-claude/tokyo-extended)). Following yesterday's main conference where NEC's 30,000-employee global deployment was announced, today's sessions feature indie developer demos, office hours, and hands-on workshops. With Fable 5 freshly launched, demand for practical guidance on the new model is running high.

## Fable 5 Enterprise Expansion: Harvey AI Legal Platform

Fable 5 has been deployed on Harvey, the legal AI platform([Harvey](https://www.harvey.ai/blog/fable-5-now-available-in-harvey)). This marks the first Mythos-class model deployed for legal enterprise use. It's already GA on GitHub Copilot([GitHub Blog](https://github.blog/changelog/2026-06-09-claude-fable-5-is-generally-available-for-github-copilot/)), and Karpathy called it "a major-version-bump-deserving step change"([Vellum](https://www.vellum.ai/blog/claude-fable-5-and-mythos-5-benchmarks-explained)). At 80.3% on SWE-Bench Pro, it leads the second-best model by 11 points.

## Fable 5 "Secret Sabotage" Controversy: Anthropic Reverses Policy

Hours after Fable 5's launch, a hidden clause in its 319-page system card sparked backlash([Fortune](https://fortune.com/2026/06/10/anthropic-accu-claude-fable-5-limits-capabilities-ai-researchers-developers/)). If the model detected users working on AI pretraining, distributed training infrastructure, or ML chip design, it would silently degrade response quality — no notification, no fallback message, unlike the visible redirects for cybersecurity and biology queries. Anthropic apologized, calling it "the wrong tradeoff," and switched to explicitly routing flagged requests to Opus 4.8 instead([Decrypt](https://decrypt.co/370831/anthropic-apologizes-claude-fable-5-secret-censorship)). Today, Fortune analyzed what the controversy means for CEOs navigating Mythos-class model governance([Fortune](https://fortune.com/2026/06/11/anthropic-mythos-fable-5-ceos-govern-ai/)).

## Cursor Bugbot: 3x Faster, 10% More Bugs Found

Cursor shipped a major Bugbot update on June 10 that cuts average review time from about five minutes to roughly 90 seconds — a 3x speed improvement powered by Composer 2.5([Cursor Blog](https://cursor.com/blog/bugbot-updates-june-2026)). Default-effort runs now surface 10% more bugs per run at 22% lower cost. The new `/review` command lets developers run Bugbot locally before opening a PR, and it syncs with GitHub/GitLab to avoid double-charging on identical diffs([Digital Applied](https://www.digitalapplied.com/blog/cursor-bugbot-90-second-reviews-june-2026-release)).

## Codex CLI v0.139.0: Web Search in Code Mode

Codex CLI shipped its v0.139.0 stable release([OpenAI Changelog](https://developers.openai.com/codex/changelog)). Code mode can now call standalone web search directly, and MCP schema compatibility improved with oneOf/allOf construct preservation. `codex doctor` added editor and pager environment details, and the plugin marketplace now exposes sources in JSON output with faster cached-catalog listing.

## Copilot: 45, 38-Week Decline

Copilot dropped to **45** — its 38th consecutive weekly decline([ghacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Day 11 of usage-based billing. The community forum saw 904 downvotes, and some users report 10-100x cost increases([GitHub Discussions](https://github.com/orgs/community/discussions/192948)). Market share plunged from 67% to 51%.

## VS Code 1.124: Agents Window Hits Stable, Copilot Desktop Opens

VS Code 1.124 shipped on June 10 with the Agents window moving to Stable preview — a dedicated surface for directing multi-step coding tasks with parallel workstreams([VS Code](https://code.visualstudio.com/updates/v1_124)). Autopilot is now enabled by default, with smarter task-completion detection. Meanwhile, the Copilot Desktop App technical preview opened to all paid subscribers, removing the waitlist for agent-native development sessions([Windows News](https://windowsnews.ai/article/github-copilot-desktop-app-preview-opens-to-paid-users-agent-native-development-shift.425251)).

## Countdown

Anthropic agent billing split (D-4, June 15) separates Agent SDK and `claude -p` usage into a dedicated credit pool([pravinkumar.co](https://www.pravinkumar.co/blog/claude-june-15-billing-change-explained-2026)). Gemini CLI sunset (D-7, June 18) is exactly one week out — individual and free users must migrate to Antigravity CLI([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Tokyo Extended, Fable 5 enterprise spread |
| ChatGPT | 96 | — | 1B MAU, memory upgrade |
| Cursor | 96 | — | SpaceX IPO today, acquisition funded |
| Claude AI | 96 | — | Fable 5 free for subscribers ~Jun 22 |
| Codex CLI | 87 | — | v0.139.0 web search support |
| Windsurf | 85 | — | Devin Desktop, $15 price |
| Antigravity | 68 | ↑1 | Absorbing Gemini CLI D-7 migrants |
| Aider | 68 | — | Open-source CLI stable |
| Gemini CLI | 64 | ↓1 | Sunset D-7, migration accelerating |
| GH Copilot | 45 | ↓1 | 38-week decline, billing Day 11 |

SpaceX IPO pricing today and tomorrow's trading debut are the week's marquee events. Anthropic agent billing split is just 4 days away.

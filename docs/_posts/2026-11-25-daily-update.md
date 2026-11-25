---
title: "Sonnet 4.5 Retirement D-5: Why Swapping the Model ID Isn't Enough"
date: 2026-11-25
lang: en
categories: [news]
tags: [anthropic, sonnet-5-5, copilot, gemini-4, ant-ipo, cursor, claude-code, codex-cli]
excerpt: "Sonnet 4.5 retires November 30 and the new tokenizer means a simple model swap won't cut it. Meanwhile Copilot added three Gemini 4 models in November alone, accelerating its multi-model strategy."
---

Anthropic's Sonnet 4.5 retirement is five days away. Reports are surfacing that swapping the model ID alone isn't enough — tokenizer changes and parameter incompatibilities mean teams need proper migration testing before the deadline.

## Sonnet 4.5 Retirement D-5: Migration Is More Than a Name Change

As announced September 30, Sonnet 4.5 retires from the Claude API on November 30([Codersera](https://codersera.com/blog/claude-sonnet-4-5-retirement-migration-2026/)). Its replacement, Sonnet 5.5, launched September 28 at $2/$10 per million tokens — a 33% sticker-price cut from Sonnet 4.5's $3/$15([TechCrunch](https://techcrunch.com/2026/09/28/anthropic-releases-sonnet-5-5-which-it-calls-a-significantly-cheaper-faster-work-partner/)). But the new tokenizer generates ~30% more tokens for the same text, and a 2000x1500 image costs roughly 2.5x as many tokens, narrowing the real savings considerably([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). Some parameters that worked on Sonnet 4.5 are rejected by 5.5, so switching without testing risks production breakage.

## Copilot Adds Three Gemini 4 Models in November

GitHub Copilot added three Google Gemini 4 models in rapid succession this month: Carbon on November 10([GitHub Blog](https://github.blog/changelog/2026-11-10-gemini-4-carbon-in-github-copilot)), Hydrogen Flash on November 13([GitHub Blog](https://github.blog/changelog/2026-11-13-gemini-4-hydrogen-in-github-copilot)), and Neon on November 18([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)). All are available on Pro+, Max, Business, and Enterprise plans under usage-based billing. Combined with Fusion GA's automatic task-to-model routing, Copilot's multi-model ecosystem is becoming a serious differentiator. One Japanese outlet reported Carbon token pricing doubling on December 1, but this is unconfirmed.

## ANT IPO: Week One in the Books

Anthropic (ANT) completed its first week of Nasdaq trading after listing on November 19. The stock priced at $83, opened at $111.50, and has been oscillating in the $95–99 range since([TechRepublic](https://www.techrepublic.com/article/news-anthropic-ipo-nasdaq-trading-debut/)). With only ~6% of shares in the free float, volatility remains high. Nasdaq-100 inclusion won't happen until the December 18 rebalancing review([Saxo Bank](https://www.home.saxo/en-gb/content/articles/equities/anthropic-debut-uk-19112026)).

## Claude Code and Codex CLI Updates

Claude Code v2.1.327 added Code Mode with agent teams enabled and real-time streaming for remote sessions([Claude World](https://claude-world.com/articles/claude-code-november-2026-whats-new/)). Codex CLI reached v0.169–v0.170, adding multiple side-chat tabs, in-terminal provider setup, and WebRTC voice calls([Havoptic](https://www.havoptic.com/releases/openai-codex/2026/11)). Google Jules entered read-only mode on November 11 and will shut down completely on December 31 — session data does not auto-migrate to Antigravity, so manual export is required([TechRadar](https://techradar.com/pro/google-kills-off-jules-its-ai-coding-agent-which-promised-to-do-all-the-jobs-you-didnt-want-to)). Cursor's OpenAI model blackout is now at day 14, marking 125 consecutive days at the bottom of the rankings.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.2 Astra/Sol day 9 |
| Claude Code | 99 | — | Claude Ship beta + v2.1.327 |
| Codex CLI | 99 | — | v0.170 multi-tab side chats |
| Antigravity | 99 | — | Google's sole coding agent, steady |
| Claude AI | 99 | — | Sonnet 4.5→5.5 transition D-5 |
| GH Copilot | 99 | — | 3 Gemini 4 models added in Nov |
| Windsurf | 88 | — | Devin Desktop stable operations |
| Aider | 68 | — | Maintenance mode, 44K GitHub stars |
| Cursor | 1 | — | OpenAI blackout day 14, 125 days at bottom |
| Gemini CLI | 1 | — | Retired Nov 1, Antigravity transition done |

The six-way 99 tie extends to day 10. Sonnet 4.5's retirement in five days demands tokenizer compatibility testing — a blind model swap risks production failures. Copilot's Gemini 4 model blitz is cementing its multi-model ecosystem lead.

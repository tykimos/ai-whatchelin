---
title: "Nov 30 Double Deadline Plus December Usage Merge: OpenAI and Anthropic Squeeze Subscribers"
date: 2026-11-26
lang: en
categories: [news]
tags: [anthropic, openai, sonnet-5-5, opus-4-8, copilot, gemini-4, gpt-6-2, codex-cli, claude-code, chatgpt]
excerpt: "Anthropic's Sonnet 4.5 retirement and Opus 4.8 fast mode removal collide on Nov 30. OpenAI will merge ChatGPT and Codex usage pools in December, and yesterday's 4.5-hour outage added fuel to the fire."
---

It's a pressure cooker week for AI coding tool subscribers. Anthropic's double deadline lands in four days, OpenAI just announced a December usage pool merge, and yesterday's 4.5-hour outage across ChatGPT and Codex isn't helping confidence. Here's what developers need to know.

## Anthropic's November 30 Double Deadline: Sonnet 4.5 + Opus 4.8 Fast Mode

Sonnet 4.5 (`claude-sonnet-4-5-20250929`) retires from the API on November 30([Anthropic Docs](https://platform.claude.com/docs/about-claude/model-deprecations)). Its replacement, Sonnet 5.5, is 33% cheaper on paper at $2/$10 per MTok, but the new tokenizer generates ~30% more tokens for the same text, narrowing real savings([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). On the same day, Opus 4.8 fast mode is removed([Anthropic Docs](https://code.claude.com/docs/en/fast-mode)). Requests with fast mode enabled will return errors; standard-speed Opus 4.8 continues to work, but Anthropic recommends migrating to Opus 5.5([Claude World](https://claude-world.com/articles/claude-opus-4-8-fast-mode-removal/)). Two breaking changes on one day means production environments need model IDs and fast mode flags audited before the weekend.

## OpenAI to Merge ChatGPT and Codex Usage Pools in December

OpenAI announced that Plus, Pro, and Business subscribers will draw from a single usage pool across ChatGPT and Codex starting in December([TechRepublic](https://www.techrepublic.com/article/news-chatgpt-codex-shared-usage-limits/)). The chat and work tabs merge into one, while regular Instant chats stay outside the shared pool([The New Stack](https://thenewstack.io/openai-chatgpt-codex-shared-limits/)). The exact pool size and reset cadence remain undisclosed([CryptoBriefing](https://cryptobriefing.com/openai-unifies-chatgpt-codex-token-allowance/)). For heavy Codex users, this could effectively mean less headroom — worth monitoring usage patterns until the details land.

## OpenAI November 25 Outage: 4.5 Hours of Errors

Yesterday (Nov 25), ChatGPT, ChatGPT Work, and Codex Cloud experienced approximately 4.5 hours of elevated conversation errors([Host Tracker](https://www.host-tracker.com/en/is-codex-down/incidents/2026-11-25-1148)). OpenAI classified it as minor and resolved it the same day, but with the December usage merge approaching, stability concerns are growing in the developer community.

## GPT-6.2 Astra Draws Scrutiny Over 59% Hallucination Rate

Ten days after launch, GPT-6.2 Astra recorded a 59% hallucination rate (Sol at 55%) on Artificial Analysis's AA-Omniscience factuality test([Artificial Analysis](https://artificialanalysis.ai/models/comparisons/gpt-6-2-astra-vs-gpt-6-2-sol)). On FrontierCode 2.0, Astra scored 44.2% and Sol 43.8%, both trailing Claude Fable 5.2's 50.2%([VKTR](https://www.vktr.com/ai-platforms/gpt62-sol-nears-astra-on-mergeready-code-at-a-fifth-of-the-cost/)). Sol's cost advantage is real though — $1.29 per task versus Astra's $5.97. As of November 23, GPT-6.2 has been rolling out to the Chat tab for paid users([Releasebot](https://releasebot.io/updates/openai/chatgpt)).

## Copilot Wraps Up Gemini 4 Trio with Neon

GitHub Copilot completed its November Gemini 4 model rollout: Carbon on November 10([GitHub Blog](https://github.blog/changelog/2026-11-10-gemini-4-carbon-in-github-copilot)), Hydrogen Flash on November 13([GitHub Blog](https://github.blog/changelog/2026-11-13-gemini-4-hydrogen-in-github-copilot)), and Neon on November 18([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)). Carbon's usage-based pricing doubles to $4/$20 per MTok on December 1([SmartScope](https://smartscope.blog/en/blog/github-copilot-gemini-4-carbon-supported-plans-model-2026/)), so cost-sensitive teams should evaluate Neon as an alternative.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Dec Codex usage merge announced, 11/25 outage |
| Claude Code | 99 | — | v2.1.327 Code Mode agent teams |
| Codex CLI | 99 | — | v0.170 WebRTC voice calls |
| Antigravity | 99 | — | Google's sole coding agent, steady |
| Claude AI | 99 | — | Sonnet 4.5 D-4 + Opus 4.8 Fast Mode D-4 |
| GH Copilot | 99 | — | Gemini 4 Carbon price hike D-5 (Dec 1) |
| Windsurf | 89 | — | Devin Desktop 11/25 in-app browser added |
| Aider | 68 | — | Maintenance mode, 44K GitHub stars |
| Cursor | 1 | — | OpenAI blackout day 15, 126 days at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition done |

Anthropic and OpenAI are both stacking late-November to early-December changes. Sonnet 4.5 retirement and Opus 4.8 fast mode removal (Nov 30), ChatGPT-Codex usage merge (December), Copilot Carbon price doubling (Dec 1) — this week is the last window for production audits.

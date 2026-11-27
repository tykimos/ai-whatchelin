---
title: "D-3: Anthropic, OpenAI, and GitHub Deadlines Converge — Last Weekday for Production Audits"
date: 2026-11-27
lang: en
categories: [news]
tags: [anthropic, openai, copilot, sonnet-4-5, opus-4-8, gemini-4, codex-cli, claude-code, chatgpt]
excerpt: "Three days until Sonnet 4.5 retires and Opus 4.8 fast mode disappears. Four days until Copilot Carbon pricing doubles. OpenAI still hasn't disclosed December usage pool details."
---

The countdown to three simultaneous vendor changes — Anthropic's double deadline on November 30, Copilot's price hike on December 1, and OpenAI's usage merge in December — is now real. Today is effectively the last full weekday to audit production environments before the first breaking change lands.

## Anthropic D-3: Sonnet 4.5 Retirement + Opus 4.8 Fast Mode Removal

Three days remain until Sonnet 4.5 (`claude-sonnet-4-5-20250929`) retires from the API([Anthropic Docs](https://platform.claude.com/docs/about-claude/model-deprecations)). Its successor Sonnet 5.5 is 33% cheaper on paper at $2/$10 per MTok, but the new tokenizer generates ~30% more tokens for equivalent text, narrowing real savings([CosmicJS](https://www.cosmicjs.com/blog/claude-sonnet-5-5-vs-sonnet-5)). On the same day, Opus 4.8 fast mode is removed — requests will return errors([Anthropic Docs](https://code.claude.com/docs/en/fast-mode)). Anthropic recommends migrating to Opus 5.5([Claude World](https://claude-world.com/articles/claude-opus-4-8-fast-mode-removal/)). Two breaking changes on one day means model IDs and fast mode flags need auditing now.

## OpenAI December Usage Merge: Details Still Missing

Starting in December, Plus, Pro, and Business subscribers will draw from a single usage pool across ChatGPT and Codex([TechRepublic](https://www.techrepublic.com/article/news-chatgpt-codex-shared-usage-limits/)). Combined balance and reset times will appear in Settings > Usage, while Instant chats remain outside the pool([The New Stack](https://thenewstack.io/openai-chatgpt-codex-shared-limits/)). After community pushback, OpenAI promised to keep Pro 200 limits intact and double limits on every Pro tier and Business Premium([OpenAI Community](https://community.openai.com/t/please-keep-chatgpt-and-codex-usage-limits-separate-in-december-2026/1411466.md)). But exact pool sizes and reset cadences remain undisclosed([CryptoBriefing](https://cryptobriefing.com/openai-unifies-chatgpt-codex-token-allowance/)).

## Copilot Gemini 4 Carbon Pricing D-4: Doubles to $4/$20 per MTok

On December 1, Gemini 4 Carbon's per-token rates in Copilot double — input from $2 to $4, output from $10 to $20 per MTok([eWeek](https://www.eweek.com/news/google-gemini-4-carbon-api-pricing/)). At $10.96 per task, Carbon will exceed Opus 5.5's cost([FourWeekMBA](https://fourweekmba.com/ai-gemini-4-carbon-doubles-to-10-96-a-task-above-opus-5-5/)). Gemini 4 Argon is scheduled for deprecation on December 14, with Neon positioned as the lower-cost alternative([GitHub Blog](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)).

## CloudBees European Survey: Faster But Not Cheaper

A CloudBees survey of 450 European IT leaders found 71% say AI tools have made development faster, but 34% spend an hour or more reviewing AI-generated code for every hour saved writing it([GlobeNewsWire](https://www.globenewswire.com/news-release/2026/11/24/3409184/0/en/ai-coding-tools-speed-up-development-but-fail-to-cut-costs-it-leaders-say.html)). This follows their May study where 93% reported productivity gains but 81% also saw increased production failures([CloudBees](https://www.cloudbees.com/newsroom/enterprise-technology-leaders-report-production-failures-from-ai-generated-code)). The trend is solidifying: AI coding tools are fast but not cheap.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Dec usage merge D-4, Pro limits doubled promise |
| Claude Code | 99 | — | Code Mode experimental, v2.1.327 |
| Codex CLI | 99 | — | v0.170 WebRTC voice calls |
| Antigravity | 99 | — | Google's sole coding agent, steady |
| Claude AI | 99 | — | Sonnet 4.5 D-3 + Opus 4.8 Fast Mode D-3 |
| GH Copilot | 99 | — | Gemini 4 Carbon price hike D-4 (Dec 1) |
| Windsurf | 89 | — | Devin Desktop integration stable |
| Aider | 68 | — | Maintenance mode, 44K GitHub stars |
| Cursor | 1 | — | OpenAI blackout day 16, 127 days at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition done |

Three vendor changes converge within four days. Sonnet 4.5 retirement + Opus 4.8 fast mode (Nov 30), Copilot Carbon price doubling (Dec 1), ChatGPT-Codex usage merge (December) — today is the last practical weekday for production audits.

---
title: "Copilot Model Purge D-3 — Cursor Hits Rock Bottom at 1, Anthropic IPO Roadshow Takes Shape"
date: 2026-10-16
lang: en
categories: [news]
tags: [copilot, cursor, anthropic, codex-cli, github-universe]
excerpt: "GitHub Copilot's October 19 six-model deprecation is 3 days out, Cursor marks its 51st straight day of decline at a rock-bottom 1, and Anthropic refines its IPO timeline after hosting investors."
---

GitHub Copilot climbs to 39 as its October 19 model deprecation wave approaches in three days. On the other side, Cursor has hit absolute bottom — a score of 1 after 51 consecutive days of decline, the steepest fall in AI coding tool history.

## Copilot: Oct 19 Model Purge D-3, Universe D-12

GitHub Copilot's second October model retirement wave lands in three days([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)). Six models — GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Gemini 3.7 Flash, and Grok 4.5 — will be removed from Chat, inline edits, agent mode, and code completions. Replacements are GPT-5.6 Sol/Luna, Gemini 3.8 Flash, and Grok 4.6, auto-enabled for Business/Enterprise unless an admin has disabled the global default([C# Corner](https://www.c-sharpcorner.com/article/preparing-for-github-copilot-model-changes)). This follows the Oct 2 first wave (Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7). With Universe 12 days away (Oct 28-29), Copilot now leads Cursor by 38 points (39 vs 1).

## Cursor: 51 Straight Days Down, Rock Bottom at 1

Cursor hit 1, the absolute floor, on its 51st consecutive day of decline. The freefall that began after SpaceX's acquisition closed on August 14 has run out of room to fall([Gigazine](https://gigazine.net/gsc_news/en/20260816-spacex-officially-closes-cursor-acquisition/)). Under SpaceXAI ownership, the transition to Grok-family models continues, with the OpenAI model cutoff (Nov 12) now 27 days away. The real story isn't model loss — it's the developer exodus. A tool that hit 99 just two months ago has cratered to the bottom in what is the sharpest decline in AI coding tool history.

## Anthropic: Post-Investor Day, Roadshow Coming Into Focus

Anthropic hosted institutional investors at its SF headquarters on October 14 for a pre-IPO investor day([Crypto Briefing](https://cryptobriefing.com/anthropic-targets-november-ipo-delay/)). Morgan Stanley, Goldman Sachs, JPMorgan, and Citi are leading the underwriting, and the formal roadshow is expected to begin the week of November 9([Implicator](https://www.implicator.ai/anthropic-could-start-ipo-roadshow-week-of-nov-9-putting-debut-before-thanksgiving/)). The target valuation is $1.8–2 trillion, roughly double the $965B Series H round from May. A pre-Thanksgiving debut is the goal, though the timeline remains fluid.

## Codex CLI: GPT-6.1 Sol Stabilizing, But Three Outages This Month

Codex CLI's daily improvement sprint enters day 12([Havoptic](https://www.havoptic.com/releases/openai-codex/2026/10)). Since v0.161.0 (Oct 7) switched to GPT-6.1 Sol as the default model, patches through v0.162.1 (Oct 9) have fixed TUI crashes and startup failures. However, GPT-6.1 Sol-based Codex and Work mode experienced ~8.5 hours of degraded performance on October 13([IsDown](https://isdown.app/status/openai/incidents/669200-degraded-performance-in-gpt-6-1-sol-work-mode)), followed by ~3 hours of elevated error rates on October 14([IsDown](https://isdown.app/status/openai/incidents/669750-degraded-performance-in-codex-and-chatgpt-work)). Including the Oct 7 thread-creation outage, that makes three incidents this month alone. Post-GPT-6.1-Sol stability is emerging as a key concern.

## Claude Code: Haiku 5.5 Default Stabilizing

Claude Code v2.1.296 (Oct 9) is the latest release, adding Desktop-gateway settings sync([Havoptic](https://www.havoptic.com/releases/claude-code/2026/10)). v2.1.293 (Oct 7) made Haiku 5.5 the default model with a 1M context window, and v2.1.294 (Oct 8) fixed how instruction-based hooks interpret blocking rules.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-Live-1.1 stable |
| Claude Code | 99 | — | Haiku 5.5 default stabilizing |
| Codex CLI | 99 | — | 3 outages post-GPT-6.1 Sol switch |
| Antigravity | 99 | — | 28-week streak at 99 |
| Claude AI | 99 | — | Post-investor day, roadshow ahead |
| Windsurf | 88 | — | Devin Desktop stable |
| Aider | 68 | — | Stable, no commits since May |
| GH Copilot | 39 | ↑2 | Oct 19 model purge D-3 |
| Cursor | 1 | ↓1 | 51-day decline, rock bottom |
| Gemini CLI | 1 | — | Retired, transitioned to Antigravity |

Copilot accelerates its recovery to 39 ahead of the Oct 19 model purge, while Cursor's 51-day slide ends at the absolute floor. Codex's three outages this month since the GPT-6.1 Sol switch are raising stability concerns amid otherwise strong momentum.

---
title: "Copilot Opens Code Review Settings to All Plans — The Battleground Shifts from Model Pickers to Review Control"
date: 2026-09-24
lang: en
categories: [news]
tags: [github-copilot, claude-code, codex-cli, cursor, openai, anthropic, opus-5-5, gpt-6-sol]
excerpt: "As the shockwave from the Sep 22 double model launch continues, GitHub Copilot opens code review personal settings to all plans and enters the D-4 countdown to its unified experience."
---

The shockwave from September 22's double model launch is still reverberating across the ecosystem. With every major terminal agent now carrying Opus 5.5, Sol, and Luna in their pickers, the battleground has shifted beyond model selection into **code review governance**.

## Copilot Code Review: Personal Settings GA Across All Plans

GitHub expanded Copilot code review personal settings to all Copilot plans ([GitHub Changelog](https://github.blog/changelog/2026-09-23-copilot-code-review-more-ways-to-request-and-configure-reviews/)). Users can now configure automatic review triggers on PR creation, push, and draft state changes, and set a default review effort (Lite or Balanced) from a dedicated settings page. Enterprise admins can set organization-wide default review effort, with repositories and organizations able to override. With the Sep 28 unified experience switching the default from Lite to Balanced ([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)), teams wanting to keep costs down must explicitly select Lite this week.

## Copilot CLI v1.0.89: Three Models in One Day

Copilot CLI v1.0.89-0 added claude-opus-5.5, and hours later v1.0.89-1 followed with GPT-6 Sol and Luna in the model picker ([GitHub Release](https://github.com/github/copilot-cli/releases/tag/v1.0.89-1)). Combined with the auto model selection tiers (efficiency, balance, intelligence) announced on Sep 18, cost-quality routing is now automated ([GitHub Blog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)).

## Claude Code v2.1.281: Stability-First Patch

v2.1.281 strengthened Claude apps gateway support, added assume_role on Bedrock upstreams, and introduced MCP URL-mode elicitation ([GitHub Release](https://github.com/anthropics/claude-code/releases/tag/v2.1.281)). The critical fix: a crash that could end sessions during API request retries. This looks like a stabilization pass after the Opus 5.5 launch.

## Codex CLI v0.156.1: Sol and Luna Hotfix

Following v0.156.0's voice and TUI additions, v0.156.1 added GPT-6 Sol and Luna to the model picker and now recommends Luna when hitting rate limits ([GitHub PR](https://github.com/openai/codex/pull/47405)).

## Cursor: Day 36 Decline, Score 43

Cursor dropped from 45 to 43, marking 36 consecutive days of decline. The OpenAI model cutoff (Nov 12) is 49 days away. Grok 4.7 integration (Sep 21) hasn't slowed the bleed. The developer exodus since the SpaceX acquisition appears structural.

## Copilot Unified Experience D-4: Prepaid Seats and Balanced Default

Four days remain until GitHub merges Copilot Chat, Mobile, and cloud agent into a single experience ([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Starting Oct 1, all new Business and Enterprise seat assignments will require prepaid seats. Chat data retention shifts from 28 days to account lifetime, and code review defaults shift to Balanced.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Sol/Luna rollout continues, GPT-5.5 retirement D-20 |
| Claude Code | 99 | — | v2.1.281 gateway fixes, 5-hour cap removal day 2 |
| Claude AI | 99 | — | Opus 5.5 ecosystem adoption underway |
| Codex CLI | 99 | — | v0.156.1 Sol/Luna model picker hotfix |
| Antigravity | 99 | — | 09-2026 preview stable, v2.13.0 settled |
| Windsurf | 87 | — | Devin Desktop holding steady |
| Aider | 68 | — | No official release in 13 months |
| Cursor | 43 | ↓2 | Day 36 decline, OpenAI cutoff D-49 |
| GH Copilot | 1 | — | Code review all-plan GA, unified D-4 |
| Gemini CLI | 1 | — | Shutdown day 99 |

With the model picker scramble settling, the battleground has moved to review settings governance. Copilot opening code review to all plans while pushing the Balanced default on Sep 28 signals that "AI reviewing your PRs by default" is now the new normal.

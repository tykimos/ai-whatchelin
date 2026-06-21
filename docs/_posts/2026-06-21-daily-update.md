---
title: "GPT-5.6 Odds Plummet as Agentjacking Exposes 2,388 Organizations — AI Coding Security Alert"
date: 2026-06-21
lang: en
categories: [news]
tags: [gpt-5.6, grok, fable-5, gemini-cli, antigravity, copilot, agentjacking, claude-code]
excerpt: "GPT-5.6 prediction market odds crash from 90% to 22%. Agentjacking, a new attack class, hits Claude Code, Cursor, and Codex with an 85% success rate across 2,388 organizations. Fable 5 Day 9, Gemini CLI shutdown Day 3."
---

The GPT-5.6 release window that looked nearly certain yesterday has collapsed overnight, while a newly disclosed attack class called "Agentjacking" has exposed fundamental security gaps across every major AI coding agent. Two crises converging on the same day is not a coincidence — it reflects an industry sprinting ahead of its own safety infrastructure.

## GPT-5.6: Prediction Market Reversal — 90% to 22%

Polymarket odds for a June 22-28 GPT-5.6 release crashed to **22%**, with the "not released by June 28" contract now at 77% ([Polymarket](https://polymarket.com/event/when-will-gpt-5pt6-be-released)). Just yesterday, the same window sat at 90%. OpenAI chief scientist Jakub Pachocki called the iris-alpha model a "meaningful improvement" with an expected 1.5M context window ([TechTimes](https://www.techtimes.com/articles/318492/20260616/gpt-56-openai-chief-scientist-calls-it-meaningful-leap-june-launch-nears.htm)), but the release now looks more likely to slip into July.

## Agentjacking: New Attack Class Hits AI Coding Agents — 85% Success Rate

A newly disclosed attack class called "Agentjacking" is exploiting error-tracking platforms to inject malicious instructions into AI coding agents ([unrot.co](https://unrot.co/blogs/ai-news-today-june-21-2026)). By abusing Sentry DSN endpoints, attackers trick Claude Code, Cursor, and OpenAI Codex into executing arbitrary code. The attack achieved an **85%** exploitation rate across 2,388 organizations. Security researchers recommend treating all error-tracking output as untrusted input before allowing agents to act on it.

## Grok V9-Medium: 1.5T-Parameter Model Training Complete

xAI has finished training Grok V9-Medium, a 1.5-trillion-parameter model — 3x the current production model — trained on real-world developer workflows from Cursor data, secured through SpaceX's $60B acquisition agreement ([TechTimes](https://www.techtimes.com/articles/317328/20260528/grok-ai-new-model-triples-parameter-count-targets-coding-lead-release-expected-mid-june.htm)). Infrastructure is already in place: Grok Build CLI v0.2.51 shipped worktree support and a /code-review command ([x.ai](https://x.ai/build/changelog)).

## Fable 5 Suspension Day 9 — 57% Chance of Reinstatement

The Fable 5 suspension entered its ninth day with Polymarket showing 57% odds of reinstatement before July 1 and 75% before July 17 ([Polymarket](https://polymarket.com/event/claude-fable-5-restored-for-us-customers-by-20260613193753196)). Anthropic's managing director Chris Ciauri said he's "very confident" the models will return "in the coming days" ([TechTimes](https://www.techtimes.com/articles/318668/20260618/fable-5-export-ban-day-six-anthropic-opens-seoul-office-vows-models-back-days.htm)), but the White House demands all jailbreak vulnerabilities be eliminated first. With both Fable 5 offline and GPT-5.6 delayed, Opus 4.8 stands as effectively the only frontier coding model available.

## Claude Code Reaches 63% Adoption — Governance Gap Widens

A Black Duck Security study found Claude Code has reached **63%** developer adoption, trailing only GitHub Copilot at 83% but closing fast ([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-june-21-2026)). The same study revealed that 97% of developers now use AI coding tools, but only one-third of organizations have implemented full governance frameworks — a gap the Agentjacking disclosure makes all the more urgent.

## Gemini CLI Shutdown Day 3 — Pipeline Failures Spreading

Three days after the June 18 shutdown, CI/CD pipelines continue hitting HTTP 410 errors ([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). The replacement Antigravity CLI caps free requests at 20/day — a 98% reduction from Gemini CLI's 1,000/day ([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)).

## Copilot 48-Week Decline — Score 35

GitHub Copilot dropped to **35**, extending its record streak to 48 consecutive weeks of decline. On billing Day 21, Pro plan credits evaporate in a single agentic session ([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Migration to OpenRouter, RooCode, and LM Studio is accelerating.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | 63% adoption, Opus 4.8 sole frontier |
| ChatGPT | 96 | — | GPT-5.6 likely delayed past June |
| Cursor | 96 | — | SpaceX acquisition Q3 close expected |
| Claude AI | 96 | — | Fable 5 D-9, 57% reinstatement odds |
| Codex CLI | 87 | — | v0.141.0 stable |
| Windsurf | 85 | — | $15 price absorbing Copilot refugees |
| Antigravity | 79 | ↑1 | Gemini CLI D+3 migration wave |
| Aider | 68 | — | Open-source agent stable |
| Gemini CLI | 46 | ↓2 | Shutdown D+3, decline continues |
| Copilot | 35 | ↓1 | 48-week decline, Agentjacking exposed |

---
title: "SK Telecom Triggered the Fable 5 Ban — Refund D-1, Gemini CLI Pipelines Breaking"
date: 2026-06-19
lang: en
categories: [news]
tags: [fable-5, sk-telecom, gemini-cli, antigravity, copilot, gpt-5.6, kaggle, claude-code, codex-cli, cursor, windsurf]
excerpt: "Fable 5 suspension Day 7 — SK Telecom identified as the trigger. Gemini CLI D+1 pipeline failures hitting developers, while Cursor ships Automations GA and Codex CLI v0.141.0 lands."
---

On Day 7 of the Fable 5 suspension, SK Telecom has been identified as the Korean carrier that triggered the export control directive. The Gemini CLI shutdown's D+1 fallout is hitting CI/CD pipelines hard, and the AI coding tool landscape continues its dramatic reshuffling.

## Fable 5: SK Telecom Identified as the Ban Trigger, Refund Deadline Tomorrow

SK Telecom, South Korea's largest wireless carrier, has been named as the company whose Project Glasswing access triggered the Fable 5 and Mythos 5 export ban ([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/sk-telecom-named-as-the-korean-carrier-at-the-center-of-anthropics-mythos-export-controls)). The White House flagged SK Telecom's historical ties to China and asked Anthropic to revoke access, which the company did immediately — but the incident escalated into a full suspension for all foreign nationals ([Korea JoongAng Daily](https://www.koreajoongangdaily.com/business/white-house-officials-pin-anthropic-ai-export-block-on-korean-telecom-report/12726842)). The timing is deeply ironic: Anthropic opened its Seoul office the same week.

The refund window closes tomorrow, June 20 at 11:59 PM PT, covering purchases between June 9-14 only ([TechJack Solutions](https://techjacksolutions.com/ai-brief/fable-5-refund-window-closes-june-20-what-anthropics-billing/)). At the Seoul launch, Anthropic's international MD said he was "very confident" both models would return "in the coming days" ([TechTimes](https://www.techtimes.com/articles/318668/20260618/fable-5-export-ban-day-six-anthropic-opens-seoul-office-vows-models-back-days.htm)). President Trump at the G7 in Évian offered his first comment on the ban: negotiations are "going fine" ([TipRanks](https://www.tipranks.com/news/trump-insists-anthropic-talks-are-going-fine-as-g7-allies-demand-answers)).

## Gemini CLI D+1: Silent Failures Are the Real Danger

Yesterday's Gemini CLI shutdown is rippling through the ecosystem. CI/CD pipelines, cron jobs, and orchestration bridges calling `gemini` are returning HTTP 410 errors ([TechTimes](https://www.techtimes.com/articles/318660/20260618/gemini-cli-shutdown-takes-effect-ci-cd-pipelines-break-go-based-antigravity-cli-arrives.htm)). The most dangerous issue: the MCP `serverUrl` field rename fails silently — no error, broken config passes undetected ([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). The replacement Antigravity CLI (`agy`) is a closed-source Go binary with free-tier requests slashed from 1,000/day to ~20, effectively abandoning the 105,000-star open-source community ([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)).

## Codex CLI v0.141.0 — Major Remote Execution Security Overhaul

Codex CLI shipped v0.141.0 with 87 total changes including end-to-end encrypted Noise relay channels for remote execution, cross-platform shell preservation, and per-thread MCP server activation for plugins ([OpenAI Codex Changelog](https://developers.openai.com/codex/changelog)). The release also introduces a 'created-by-me' plugin marketplace filter and rate-limit reset credit redemption via app-server clients.

## Cursor Automations GA — /automate Turns Plain Language Into Workflows

Cursor shipped Automations to general availability, expanding the coding tool into workflow automation territory ([Cursor Changelog](https://cursor.com/changelog)). The `/automate` command lets you create automations by describing tasks in plain language. Slack emoji reactions can trigger automations, and cloud agents can now use their own computers to produce demos or artifacts. New templates for triaging failed GitHub Actions and auto-fixing PR review comments are available in the Cursor Marketplace.

## GPT-5.6: "Meaningful Improvement" — 83% Odds for Next Week

OpenAI chief scientist Jakub Pachocki described GPT-5.6 as a "meaningful improvement" over GPT-5.5 ([TechTimes](https://www.techtimes.com/articles/318492/20260616/gpt-56-openai-chief-scientist-calls-it-meaningful-leap-june-launch-nears.htm)). Polymarket shows 83% probability for a June 22-28 launch, with the iris-alpha codename expected to feature a 1.5M context window. No official announcement yet.

## Copilot 46-Week Decline — Score 37, PR Limits Introduced

Copilot dropped to 37, extending its record streak to 46 consecutive weeks of decline. On billing Day 19, GitHub introduced PR limits — configurable caps and bypass lists to help maintainers control the flood of AI-generated low-quality pull requests ([GitHub Discussions](https://github.com/orgs/community/discussions/categories/copilot-news-and-announcements)). Yesterday's CVSS 9.6 prompt injection vulnerability (CVE-2025-53773) added to trust erosion.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Auto mode safety hardened, Fable 5 D-7 |
| ChatGPT | 96 | — | Sub-50% share, GPT-5.6 pending |
| Cursor | 96 | — | Automations GA, SpaceX acquisition |
| Claude AI | 96 | — | Seoul partnerships active |
| Codex CLI | 87 | — | v0.141.0, remote security overhaul |
| Windsurf | 85 | — | 3.2 update, $15 price absorbing |
| Antigravity | 77 | ↑1 | Gemini CLI shutdown migration wave |
| Aider | 68 | — | Open-source agent stable |
| Gemini CLI | 50 | ↓5 | Dead yesterday, enterprise-only |
| Copilot | 37 | ↓1 | 46-week decline, PR limits |

---
title: "SK Telecom Triggered the Fable 5 Ban — Refund Deadline Tomorrow, Trump Says Talks 'Going Fine'"
date: 2026-06-19
lang: en
categories: [news]
tags: [fable-5, sk-telecom, gemini-cli, antigravity, copilot, gpt-5.6, kaggle, claude-code]
excerpt: "SK Telecom identified as the Korean carrier that triggered the Fable 5 export ban. Refund window closes tomorrow while Trump offers his first presidential comment on the suspension at G7."
---

On Day 7 of the Fable 5 suspension, the biggest revelation today is the identification of SK Telecom as the Korean telecom whose access triggered the export control directive. Meanwhile, the Gemini CLI shutdown's D+1 fallout is hitting developers' CI/CD pipelines hard, and the AI coding tool landscape continues its dramatic reshuffling.

## Fable 5: SK Telecom Identified as the Ban Trigger

The Korean carrier behind the Fable 5 export ban has been identified as SK Telecom, South Korea's largest wireless carrier ([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/sk-telecom-named-as-the-korean-carrier-at-the-center-of-anthropics-mythos-export-controls)). SK Telecom was among roughly 150 organizations added to Anthropic's Project Glasswing cybersecurity program in early June. The White House learned of the carrier's historical ties to China and asked Anthropic to revoke access, which the company did immediately — but the incident escalated into a full suspension of Fable 5 and Mythos 5 for all foreign nationals ([Korea JoongAng Daily](https://www.koreajoongangdaily.com/business/white-house-officials-pin-anthropic-ai-export-block-on-korean-telecom-report/12726842)). The timing is deeply ironic: Anthropic opened its Seoul office the same week.

The refund window closes tomorrow, June 20 at 11:59 PM PT, covering only purchases made between June 9-14 ([TechJack Solutions](https://techjacksolutions.com/ai-brief/fable-5-refund-window-closes-june-20-what-anthropics-billing/)). At the Seoul office launch, Anthropic's international managing director said he was "very confident" both models would return "in the coming days" ([TechTimes](https://www.techtimes.com/articles/318668/20260618/fable-5-export-ban-day-six-anthropic-opens-seoul-office-vows-models-back-days.htm)). President Trump, speaking from the G7 in Évian-les-Bains, offered his first comment on the ban: negotiations are "going fine." Kalshi prices a 57% probability of restoration before July 1.

## Gemini CLI D+1: Silent Failures Are the Real Danger

Yesterday's Gemini CLI shutdown is rippling through the ecosystem. CI/CD pipelines, cron jobs, and orchestration bridges calling `gemini` are returning HTTP 410 errors and breaking builds ([TechTimes](https://www.techtimes.com/articles/318660/20260618/gemini-cli-shutdown-takes-effect-ci-cd-pipelines-break-go-based-antigravity-cli-arrives.htm)). The most dangerous issue: the MCP `serverUrl` field rename fails silently — no error, no warning, broken config passes undetected ([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). The replacement Antigravity CLI (`agy`) is a closed-source Go binary with free-tier requests slashed from 1,000/day to 20 ([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)). Antigravity's popularity score climbed to 77, absorbing migration traffic.

## GPT-5.6: "Meaningful Improvement" — 83% Odds for Next Week

OpenAI chief scientist Jakub Pachocki described GPT-5.6 internally as a "meaningful improvement" over GPT-5.5 ([TechTimes](https://www.techtimes.com/articles/318492/20260616/gpt-56-openai-chief-scientist-calls-it-meaningful-leap-june-launch-nears.htm)). Polymarket prediction markets show 83% probability for a June 22-28 launch window ([AIxploria](https://www.aixploria.com/en/ai-radar/gpt-5-6-codex-leak-polymarket-june-release/)). No official announcement yet, but the iris-alpha codename is expected to feature a 1.5M context window.

## Copilot 46-Week Decline — Score 37, Billing Day 19

Copilot's popularity score dropped to 37, extending its record streak to 46 consecutive weeks of decline. Usage-based billing is now in Day 19, with developers continuing to report burning through 8% of monthly credits in just two hours ([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). Yesterday's CVSS 9.6 prompt injection vulnerability (CVE-2025-53773) further eroded trust.

## Kaggle AI Agents Intensive Day 5 — Capstone Project Launches

Google & Kaggle's AI Agents Intensive wrapped its final day with the capstone project going live. Submissions are open until July 6, and participants earn a Kaggle badge and certificate ([Kaggle](https://www.kaggle.com/competitions/5-day-ai-agents-intensive-vibecoding-course-with-google)). Today's sessions covered cloud deployment, debugging, and observability — bridging prototypes to production.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5 Day 7, Opus 4.8 normal |
| ChatGPT | 96 | — | Digesting sub-50% share |
| Cursor | 96 | — | SpaceX acquisition, SPCX ~$175 |
| Claude AI | 96 | — | Seoul partnerships active |
| Codex CLI | 87 | — | GPT-5.6 expected next week |
| Windsurf | 85 | — | $15 price absorbing refugees |
| Antigravity | 77 | ↑1 | Gemini CLI shutdown migration wave |
| Aider | 68 | — | Open-source agent stalling |
| Gemini CLI | 50 | ↓5 | Dead yesterday, pipelines breaking |
| Copilot | 37 | ↓1 | 46-week decline, billing Day 19 |

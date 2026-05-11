---
title: "Amazon Surrenders to Claude Code — 1,500 Developers Forced the Switch After Kiro Outage"
date: 2026-05-11
lang: en
categories: [news]
tags: [claude-code, codex-cli, amazon, kiro, copilot, security, gemini-cli]
excerpt: "Amazon opens Claude Code and Codex access to all employees after a 13-hour AWS outage caused by its own Kiro tool. Meanwhile, a critical prompt injection vulnerability hits Claude Code, Gemini CLI, and Copilot."
---

Amazon abandoned its own AI coding tool. After 1,500 employees demanded alternatives on an internal thread, Amazon opened Claude Code access to all corporate staff immediately and approved OpenAI Codex starting May 12([Slashdot](https://developers.slashdot.org/story/26/05/10/0618225/amazon-relents-lets-its-programmers-use-openais-codex-and-anthropics-claude)). The trigger: a 13-hour AWS outage blamed on Kiro.

## Amazon: When Your Own Tool Breaks Your Own Cloud

Kiro, Amazon's successor to Q Developer, was deeply integrated into AWS infrastructure. But after it caused a 13-hour AWS outage, developer trust collapsed([The New Stack](https://thenewstack.io/amazon-coding-agents-developers/)). Over 1,500 employees endorsed Claude Code and Codex adoption in an internal thread, effectively saying "we can't use what we built." Amazon opening its doors to competitor AI tools is unprecedented.

## "Comment and Control": A Red Flag for AI Coding Security

Claude Code, Gemini CLI, and GitHub Copilot Agent are all vulnerable to prompt injection via GitHub PR titles, issue bodies, and comments([SecurityWeek](https://www.securityweek.com/claude-code-gemini-cli-github-copilot-agents-vulnerable-to-prompt-injection-via-comments/)). Attackers can extract API keys and tokens without any victim interaction — auto-triggered via GitHub Actions. Claude Code received a CVSS 9.4 Critical rating with a $100 HackerOne bounty([VentureBeat](https://venturebeat.com/security/ai-agent-runtime-security-system-card-audit-comment-and-control-2026)). Gemini CLI earned a $1,337 Google bounty, and Copilot a $500 GitHub bounty.

## Codex CLI: 4M+ Developers, Safety in the Spotlight

OpenAI published "Running Codex Safely," detailing its sandboxing, auto-review mode, managed network policies, and agent telemetry([OpenAI Blog](https://openai.com/index/running-codex-safely/)). Enterprise partnerships with TCS, Infosys, Cognizant, and Accenture have pushed the developer count past 4M([OpenAI Blog](https://openai.com/index/scaling-codex-to-enterprises-worldwide/)). Score rises from 79 to 80 — a four-week winning streak.

## GitHub Copilot: D-20, Nine Consecutive Weeks of Decline

Twenty days until the usage-based billing switch([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). The Opus 4.7 multiplier has already jumped from the promotional 7.5x to 15x after the promo ended April 30, and will spike to 27x on June 1([GitHub Docs](https://docs.github.com/en/copilot/reference/copilot-billing/model-multipliers-for-annual-plans)). Community backlash is fierce: users call it "a stealth 3.6x price hike"([HN](https://news.ycombinator.com/item?id=47838508)). Score drops from 76 to 75 — nine consecutive weeks of decline. The gap with Claude Code (98) widens to 23 points.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant holding steady |
| Claude Code | 98 | — | Amazon company-wide adoption, 7 days at 98 |
| Cursor | 94 | — | $2B ARR + 1M paying customers |
| Claude AI | 92 | — | Cowork GA momentum |
| Codex CLI | 80 | ↑1 | 4M+ developers, 4-week streak |
| Windsurf | 77 | — | Devin integration stabilizing |
| GitHub Copilot | 75 | ↓1 | D-20, Opus 27x June 1, 9-week slide |
| Gemini CLI | 73 | ↑1 | I/O D-8, open-source momentum |
| Aider | 68 | — | Stable |
| Antigravity | 49 | — | AgentKit 2.0 settling |

Amazon's capitulation marks a watershed moment in the AI coding tool market. When a tech giant with its own tool switches to competitors, it signals a winner-take-all dynamic. Meanwhile, the "Comment and Control" vulnerability raises fundamental questions about the security model of every major AI coding agent.

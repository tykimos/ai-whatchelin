---
title: "Anthropic Tops CNBC Disruptor 50, Deploys Claude to 276K KPMG Employees"
date: 2026-05-21
lang: en
categories: [news]
tags: [anthropic, claude-code, kpmg, antigravity, copilot, code-with-claude]
excerpt: "Anthropic leapfrogs OpenAI to claim the No. 1 spot on CNBC's Disruptor 50. Revenue run rate hits $30B, KPMG deploys Claude to all 276,000 employees — while Antigravity's rollback crisis enters day three."
---

Anthropic has dethroned OpenAI to become No. 1 on the 2026 CNBC Disruptor 50 list. CEO Dario Amodei says revenue grew 80x in Q1, pushing the annualized run rate past $30 billion — one of the fastest enterprise software ramps in history ([CNBC](https://www.cnbc.com/2026/05/19/2026-cnbc-disruptor-50-rankings-anthropic-no-1.html)).

## KPMG Deploys Claude to All 276,000 Employees

KPMG signed a global strategic alliance with Anthropic, embedding Claude inside Digital Gateway — the platform KPMG's people and clients use across 138 countries ([Anthropic](https://www.anthropic.com/news/anthropic-kpmg)). All 276,000+ employees gain Claude access, with new agent workflows for tax and legal clients built on Cowork and Managed Agents. "Building an AI agent for tax regulation changes used to take weeks — now it takes minutes," KPMG said ([CPA Practice Advisor](https://www.cpapracticeadvisor.com/2026/05/20/kpmg-partners-with-anthropic-for-digital-gateway-powered-by-claude/183743/)). This is the first Big Four firm to deploy Claude wall-to-wall.

## Claude Code v2.1.145 — /code-review Command, MCP Pagination Fix

Claude Code v2.1.145 shipped today ([code.claude.com/changelog](https://code.claude.com/docs/en/changelog)). The `/simplify` command was renamed to `/code-review` with an optional effort level (`/code-review high`), and auto mode no longer suppresses AskUserQuestion. Key fixes include MCP paginated tools/list responses dropping items past page 1, Bedrock/Vertex users unable to select "Opus (1M context)" from /model, and file descriptor exhaustion when builds run inside skill directories.

## Code with Claude London Extended — Final Day

Anthropic's Code with Claude London Extended wraps up today ([claude.com](https://claude.com/code-with-claude/london-extended)). The second day features indie developer demos, office hours, and laptops-open workshops from the Applied AI team. Yesterday's v2.1.145 additions — `claude agents --json` for scripting and enhanced plugin discovery screens — are getting hands-on testing in real-world projects.

## Antigravity 2.0 Rollback Crisis Enters Day Three

The Antigravity 2.0 auto-update fiasco is now in its third day ([Google AI Developers Forum](https://discuss.ai.google.dev/t/antigravity-2-0-a-rushed-un-tested-release/145483/6)). Developers are manually rolling back to v1.23.2 as the config path mismatch (`\Roaming\Antigravity` vs `\Roaming\Antigravity IDE`) continues wiping extensions and settings ([Techloy](https://www.techloy.com/why-googles-antigravity-2-0-ai-update-has-developers-furious/)). The score that surged to 62 on I/O day has now crashed to 55 — losing two-thirds of the initial hype gain.

## Copilot: 17-Week Decline to 66, D-11 to Usage-Based Billing

GitHub Copilot fell to 66, marking its **17th consecutive weekly decline** ([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Eleven days remain until usage-based billing on June 1. GPT-5.3-Codex was force-switched as the base model for Business/Enterprise ([GitHub Changelog](https://github.blog/changelog/2026-05-17-gpt-5-3-codex-is-now-the-base-model-for-copilot-business-and-enterprise/)), and Gemini + older GPT models were purged from web chat. The addition of Gemini 3.5 Flash to paid plans is a positive, but it's not enough to reverse the trust erosion.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | Ads platform expanding globally |
| Claude Code | 98 | — | CwC London final day, v2.1.145 |
| Cursor | 96 | — | Composer 2.5 settling, xAI partnership |
| Claude AI | 94 | ↑1 | CNBC #1, KPMG 276K deployment |
| Gemini CLI | 86 | — | I/O sessions on-demand, 6/18 migration |
| Codex CLI | 85 | — | v0.130.0 remote-control mode |
| Windsurf | 81 | — | Devin Terminal GA stable |
| Aider | 68 | — | Stable, 42K+ GitHub stars |
| Copilot | 66 | ↓1 | 17-week slide, usage billing D-11 |
| Antigravity | 55 | ↓3 | Rollback crisis day 3, forum revolt |

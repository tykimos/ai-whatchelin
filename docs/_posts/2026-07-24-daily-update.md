---
title: "DeepSeek V4 Forces Migration Today — Legacy Endpoints Shut Down, Opus 4.7 Fast Mode Also Ends"
date: 2026-07-24
lang: en
categories: [news]
tags: [deepseek, anthropic, claude-security, cursor, github-models, copilot, gemini-cli, opus]
excerpt: "DeepSeek V4 legacy endpoints shut down today and Anthropic retires Opus 4.7 fast mode. Two forced migrations collide on the same day."
---

Today is a double-migration day for AI developers. DeepSeek V4's stable release goes live as the `deepseek-chat` and `deepseek-reasoner` legacy endpoints permanently shut down at 15:59 UTC([WaveSpeed](https://wavespeed.ai/blog/posts/blog-deepseek-v4-model-name-migration/)). V4 brings 1M-token context, stronger agent execution, and improved code generation, but its new peak-hour pricing mechanism — API rates doubling during Beijing business hours (9-12, 14-18) — is drawing scrutiny([Servola](https://servola.de/journal/ai-tokens-now-have-a-rush-hour/)). Simultaneously, Anthropic retires Opus 4.7 fast mode today, migrating users to Opus 4.8 fast mode.

## Claude Security: Enterprise Vulnerability Scanner Hits Beta

Claude Security, unveiled yesterday, is gaining rapid traction. The multi-agent vulnerability scanner powered by Claude Opus 4.7 traces data flows across files, reads Git history, and generates targeted patches — well beyond simple pattern matching([MarkTechPost](https://www.marktechpost.com/2026/07/22/anthropic-releases-claude-security-plugin-for-claude-code-in-beta-a-multi-agent-vulnerability-scanner-that-runs-in-your-terminal/)). Available as a Claude Code plugin for terminal-based pre-commit scans, it's currently Enterprise-only with Team and Max support coming soon([Claude Blog](https://claude.com/blog/claude-security-public-beta)).

## Cursor: Usage Limits Doubled, iOS Landing

Cursor doubled usage limits across all individual and team plans on July 21([Explainx](https://explainx.ai/blog/cursor-doubled-usage-limits-again-july-21-2026)). The $120/month Premium seat with 5x Standard usage is now fully operational. With the iOS public beta enabling mobile agent execution, Remote Control, and code review, this marks Cursor's first major user expansion push since the SpaceX acquisition agreement.

## GitHub Models: D-6, Copilot at 76-Week Low

GitHub Models full shutdown is six days away([GitHub Blog](https://github.blog/changelog/2026-07-01-github-models-is-being-fully-retired-on-july-30-2026/)). Copilot continues its 76-week decline, dropping to a score of 1. Feature expansions like Copilot Vision GA and the desktop app rollout across all plans continue, but cost spikes from usage-based billing are driving users elsewhere.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Claude Security beta reception strong, Fable default stable |
| ChatGPT | 99 | — | GPT-5.6 Sol stabilizing, Codex integration ongoing |
| Antigravity | 99 | — | CLI Go build stable, fully replaced Gemini CLI |
| Claude AI | 98 | — | Opus 4.8 fast mode transition complete |
| Cursor | 97 | — | Usage limits doubled, iOS beta landing |
| Codex CLI | 91 | — | v0.145.0 stable, Bedrock support expanding |
| Windsurf | 85 | — | Devin Desktop stable operations |
| Aider | 68 | — | No major updates |
| Copilot | 1 | ↓1 | 76-week decline, GitHub Models D-6 |
| Gemini CLI | 1 | ↓1 | Consumer access closed 36 days |

Copilot and Gemini CLI both dropped to 1 as their platform shutdowns progress — both have effectively zero new user acquisition. DeepSeek V4's peak-hour pricing differential is the first case of "rush hour" rates applied to API tokens, potentially influencing industry-wide pricing structures.

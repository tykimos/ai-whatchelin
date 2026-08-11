---
title: "Claude Code Goes Full Auto on Aug 14 — Anthropic Bets Safety Classifier Beats Human Review"
date: 2026-08-11
lang: en
categories: [news]
tags: [claude-code, anthropic, meta, chatgpt, openai, devin, copilot]
excerpt: "Anthropic is making auto mode the default permission mode for Claude Code. Their data: the safety classifier catches 89% of harmful actions while human reviewers catch just 13.6%. Meta drops a 30B open-weight agent that runs on a single consumer GPU."
---

Anthropic announced that auto mode will become the default permission mode for new Claude Code sessions on Pro, Max, and Team plans starting August 14([TechCrunch](https://techcrunch.com/2026/08/09/anthropic-is-turning-claude-codes-auto-mode-on-by-default/)). In testing with 1,053 paid users, the safety classifier caught 89% of harmful actions, while human reviewers — who habitually approve ~97% of prompts — caught only 13.6%([Simon Willison](https://simonwillison.net/2026/Aug/8/auto-mode/)). Prompt injection screening and customizable hard deny rules have been added alongside the change. Enterprise, API, AWS, and Bedrock deployments will follow "within the coming month."

## Claude Code: v2.1.227 Ships

Today's v2.1.227 release fixes a bug where feature flags were evaluated without the user's subscription tier when sessions started with an expired login token([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Also fixed: Bash command execution failures in claude-code-action, /tui rewind behavior, enhanced slash-command menu, and reduced event-loop stalls. A stability patch three days before the auto mode default switch.

## Meta: Muse Glimmer 30B — Open-Weight Agent on a Single GPU

Meta released Muse Glimmer, a 30-billion-parameter open-weight model under Apache 2.0([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-10/meta-releases-muse-glimmer-ai-model-people-can-run-on-their-laptop)). It runs on a single consumer GPU at under 20GB quantized, with 131K context and 100+ language support([Meta AI Research](https://research.meta.ai/blog/introducing-muse-glimmer-open-agentic-model)). Designed for local agentic tasks: coding, function calling, and LLM-as-judge. CEO Zuckerberg published a 14-page essay arguing for distributed, open AI development([CNBC](https://www.cnbc.com/2026/08/10/meta-muse-glimmer-open-weight-ai.html)).

## ChatGPT: Restaurant Reservations + Voice File Uploads

ChatGPT now supports restaurant reservations through OpenTable, Resy, and Yelp across all plans([OpenAI](https://openai.com/products/release-notes/)). Separately, GPT-Live Voice gained file upload support and Projects integration, enabling document analysis during voice conversations. OpenAI also expanded its Daybreak initiative with two tiers: Blue (GPT-5.6 Sol with cyber guardrails removed) and Red (access to GPT-5.6-Cyber, a purpose-trained model)([techstartups.com](https://techstartups.com/2026/08/10/top-tech-news-today-august-10-2026-apple-google-meta-openai-unitree-more/)).

## Devin Desktop: Conversation Sharing + Customizations Panel

Devin Desktop shipped safer restart confirmations when local agents are active, renamed "Plugins" to "Extensions," and added codemap support from remote machines([Releasebot](https://releasebot.io/updates/windsurf)). Devin Local gained a conversation sharing feature with sanitized transcripts (system prompts dropped, secrets redacted), mid-turn reverting, and a new Customizations panel with a Subagents section.

## GitHub: Actions/Pages Outage + Auto Mode Transparency

GitHub Actions and Pages experienced roughly 20 hours of degraded availability on August 6-7([BigGo Finance](https://finance.biggo.com/news/51fece48-5b5c-4241-9292-3a19f12b6024)). AI-driven load combined with the ongoing Azure migration is cited as the cause. In the Copilot weekly release, Auto mode now shows which model handled each request along with AI credit and cache details, and /side enables parallel questions([GitHub Blog](https://github.blog/changelog/2026-08-07-github-copilot-weekly-releases-august-3/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Auto mode default Aug 14 announced, v2.1.227 |
| ChatGPT | 99 | — | Restaurant reservations, Daybreak expansion, legacy cleanup |
| Antigravity | 99 | — | Holding at ceiling |
| Claude AI | 99 | — | 50% usage boost extended through Aug 19 |
| Codex CLI | 99 | — | v0.147.0 plugin ecosystem, at ceiling |
| Cursor | 97 | — | Router Auto Intelligence holding, no new release |
| Windsurf | 85 | — | Devin Desktop conversation sharing added |
| Aider | 68 | — | No releases since Aug 2025 |
| Copilot | 1 | — | 91-week decline, Actions outage, D-21 |
| Gemini CLI | 1 | — | Shutdown Day 54, Antigravity full replacement |

Claude Code's auto mode default is a watershed moment in the "human oversight vs automation efficiency" debate for AI coding tools. Anthropic's data — a 6.5x higher catch rate from the classifier than from humans — is compelling, but community reaction is split. Meta's Muse Glimmer 30B pushes the "local AI agent" trend another step forward — following Ollama's $65M raise and DeepSeek's price hike warning, local execution demand is becoming structurally entrenched.

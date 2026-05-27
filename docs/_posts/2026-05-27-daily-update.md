---
title: "Copilot Hits 60 — 23-Week Slide Deepens as Usage Billing Looms in 5 Days"
date: 2026-05-27
lang: en
categories: [news]
tags: [github-copilot, copilot-studio, grok-build, anthropic, gemini-cli]
excerpt: "GitHub Copilot drops to its lowest score ever as the June 1 usage-based billing countdown reaches D-5. Microsoft doubles down on enterprise controls while Copilot Studio ships the first GA computer-use agents."
---

GitHub Copilot's popularity score has fallen to 60 — its all-time low — marking 23 consecutive weeks of decline. With just 5 days until the June 1 usage-based billing transition, developers are bracing for a billing model where agent and chat features consume GitHub AI Credits based on token consumption, while code completions and Next Edit Suggestions remain unlimited ([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)).

## GitHub Copilot: Enterprise Controls as a Lifeline

GitHub shipped targeted model rules in public preview, letting enterprise owners control exactly which Copilot models are available to each organization ([GitHub Changelog](https://github.blog/changelog/2026-05-26-target-copilot-models-to-organizations-with-model-rules/)). Previously, enterprises had a single toggle for all orgs. Now Business and Enterprise plans get fine-grained governance — a clear move to address cost-control anxiety ahead of usage-based billing. Whether granular model control can arrest the 23-week slide remains to be seen.

## Copilot Studio: First Platform to GA Computer-Use Agents

Microsoft's Copilot Studio made computer-using agents generally available across all commercial Power Platform geographies ([Microsoft Copilot Blog](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/new-and-improved-computer-using-agents-a-new-workflows-experience-and-real-time-voice-experiences/)). These agents interact with desktop and web applications through the UI — clicking, typing, and navigating like a human — targeting legacy systems without APIs. The GA build ships with OpenAI CUA and Claude Sonnet 4.5 as production models, Azure Key Vault credential storage, and Purview audit logging. Microsoft is now the only platform with contractual GA for computer-use agents; Anthropic's Computer Use remains in paid beta, and Google's is in public preview.

## Grok Build: xAI Opens the Door to All Subscribers

xAI expanded Grok Build from SuperGrok Heavy ($299/mo) to all SuperGrok and X Premium+ subscribers, alongside a Windows PowerShell installer ([xAI](https://x.ai/news/grok-build-cli)). The CLI agent runs on grok-build-0.1 with 256K context, 8 parallel sub-agents, and a plan-first execution loop with MCP compatibility. The broader rollout signals xAI's intent to compete seriously against Claude Code and Codex CLI in the terminal agent space.

## Gemini CLI: 22 Days to Sunset

The Gemini CLI shutdown countdown hits D-22. After June 18, non-enterprise users will lose access as Google pushes migration to Antigravity CLI, a Go-based replacement with native multi-agent orchestration ([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). Antigravity's score ticked up to 56, continuing a slow three-day recovery from the 2.0 auto-update debacle, but it remains well below the I/O spike of 62.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 98 | — | 14-day stable at 98 |
| Cursor | 96 | — | Composer 2.5 holding steady |
| Codex CLI | 88 | — | 5-week high plateau |
| Windsurf | 81 | — | Post-Devin integration stable |
| Gemini CLI | 80 | ↓1 | Sunset D-22, continued decline |
| GH Copilot | 60 | ↓1 | 23-week slide, all-time low |
| Antigravity | 56 | ↑1 | 3-day recovery post-rollback |
| ChatGPT | 98 | — | GPT-5.5 Instant momentum |
| Claude AI | 94 | — | $30B+ round closing this week |

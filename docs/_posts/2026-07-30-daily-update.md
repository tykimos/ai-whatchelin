---
title: "GitHub Models Goes Dark Today as OpenAI Open-Sources Security CLI"
date: 2026-07-30
lang: en
categories: [news]
tags: [github-models, codex-security, chatgpt, openai, copilot, gemini-cli]
excerpt: "GitHub Models officially shuts down today — playground, model catalog, and inference API all go dark. On the same day, OpenAI open-sources its Codex Security CLI under Apache 2.0 and ChatGPT launches voice-driven agent coordination plus a U.S. health dashboard."
---

GitHub Models officially goes offline today, ending nearly a year of free model experimentation for developers. On the same day, OpenAI open-sources its security-focused CLI and ChatGPT ships two major consumer features, showing the market's simultaneous push toward both developer tooling and mainstream AI adoption.

## GitHub Models: Fully Retired Today

GitHub Models shut down on July 30, taking the playground, model catalog, inference API, and bring-your-own-key endpoints permanently offline([GitHub Changelog](https://github.blog/changelog/2026-07-01-github-models-is-being-fully-retired-on-july-30-2026/)). The closure follows scheduled brownouts on July 16 and 23 that gave teams a preview of what would break([DEV Community](https://dev.to/leobaniak/github-sets-july-30-as-the-hard-shutdown-for-github-models-cmc)). Microsoft points developers toward Azure AI Foundry as the migration path, but for those who relied on browser-based testing of Llama 3, Mistral, and Phi-3, an era has ended. All data remaining on Microsoft's servers will be permanently deleted with no export window([Windows News](https://windowsnews.ai/article/github-models-shutdown-windows-teams-have-until-july-30-to-migrate.433587)).

## Codex Security CLI: Open-Sourced Under Apache 2.0

OpenAI released its Codex Security CLI and SDK as open source under the Apache 2.0 license([CyberSecurity News](https://cybersecuritynews.com/openai-open-sources-codex-security-cli/)). Install via `npm install @openai/codex-security` to scan repos, review staged and unstaged changes before commits, and set CI/CD severity thresholds that fail builds when critical findings appear. The catch: the analysis engine still depends on OpenAI's hosted service, and access remains in limited beta for approved partners only([The Next Web](https://thenextweb.com/news/openai-codex-security-cli-open-source-appsec-anthropic)).

## ChatGPT: Voice Agent Coordination + Health Dashboard

ChatGPT expanded Voice to Work and Codex in the desktop app, letting users speak naturally to start, interrupt, and coordinate agent tasks([Releasebot](https://releasebot.io/updates/openai/chatgpt)). Separately, a new Health experience launched in the U.S., connecting health records and Apple Health data for context-aware health queries. The fallback model was also upgraded from GPT-5.3 Instant Mini to GPT-5.5 Instant Mini([OpenAI Release Notes](https://releasebot.io/updates/openai)).

## Copilot: Week 81 at the Floor, Gemini Models Departing Tomorrow

GitHub Copilot extends its decline to 81 consecutive weeks at the floor score of 1. Tomorrow (July 31), Gemini 2.5 Pro and Gemini 3 Flash will be deprecated across all Copilot experiences([GitHub Changelog](https://github.blog/changelog/2026-07-08-github-copilot-in-visual-studio-code-june-2026-releases/)). However, the platform continues evolving — a new Copilot metrics impact dashboard and GA agentic browser tools suggest the infrastructure story isn't over yet([GitHub Changelog](https://github.blog/changelog/2026-07-22-new-copilot-usage-metrics-impact-dashboard/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 default, nested subagents depth 3 |
| ChatGPT | 99 | — | Voice for Work, Health launch, fallback model upgrade |
| Antigravity | 99 | — | Entering 27th consecutive week at 99 |
| Claude AI | 99 | — | Stable |
| Cursor | 97 | — | Router intelligence modes, iOS public beta |
| Codex CLI | 93 | ↑1 | Security CLI open-sourced, security ecosystem expansion |
| Windsurf | 85 | — | Devin Desktop stable operations |
| Aider | 68 | — | No major updates |
| Copilot | 1 | — | 81-week decline, GitHub Models shutdown complete |
| Gemini CLI | 1 | — | Consumer access closed 42 days |

Codex CLI gains for the second consecutive day, expanding into security tooling. The GitHub Models shutdown marks the end of an era and signals that AI model access is consolidating around Azure AI Foundry and Copilot.

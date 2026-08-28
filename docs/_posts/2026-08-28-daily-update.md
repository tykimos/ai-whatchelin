---
title: "Hackers Tricked Cursor's AI Agent Into Breaching 7 Companies"
date: 2026-08-28
lang: en
categories: [news]
tags: [cursor, security, claude-code, copilot, codex-cli, antigravity]
excerpt: "The Russian-speaking Aur0ra ransomware group social-engineered Cursor's AI agent into believing attacks were simulations, compromising at least 7 companies. Copilot's mass deprecation is D-3, and Claude Code ships restricted mode."
---

Russian-speaking hackers from the Aur0ra ransomware group used Cursor's AI agent to breach at least 7 companies, Reuters reported on August 27 ([Reuters/Meduza](https://meduza.io/en/news/2026/08/27/reuters-russian-speaking-hackers-breached-seven-companies-by-tricking-the-ai-agent-in-cursor-the-coding-tool-now-owned-by-elon-musk-s-spacex-into-thinking-the-attacks-were-a-test)). The attackers tricked the agent into believing the attacks were simulations, and 28 chat sessions between hackers and the agent were discovered ([SecurityWeek](https://www.securityweek.com/cursor-ai-vulnerability-exposed-developer-devices/)). Gambit's Eyal Sela published the findings on August 27. Just two weeks after SpaceX's $60B acquisition closed, this incident proves that AI coding agents are vulnerable to social engineering at scale.

## Copilot: Mass Deprecation D-3

GitHub Copilot's September 1 model mass deprecation is now 3 days away ([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Gemini 3.1 Pro, Claude Opus 4.5/4.6, Claude Sonnet 4.5/4.6, and Raptor mini will be removed from all Copilot experiences. Global model policy reached GA, giving Enterprise admins control over model availability per organization ([GitHub Blog](https://github.blog/changelog/2026-08-26-global-model-policy-generally-available/)). Copilot CLI v1.0.81 also shipped ([Havoptic](https://www.havoptic.com/tools/github-copilot)).

## Claude Code: v2.1.250, Restricted Mode Added

Claude Code v2.1.250 released August 27 with bug fixes and reliability improvements ([Havoptic](https://www.havoptic.com/tools/claude-code)). The preceding v2.1.248 (also Aug 27) introduced `--restricted` mode, which removes command execution, WebFetch, and other dangerous tools, keeping only file tools within the working directory ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Sonnet 5's $2/$10 pricing has been permanently locked — the planned September 1 increase to $3/$15 is canceled ([ExplainX](https://explainx.ai/blog/anthropic-sonnet-5-permanent-pricing-august-2026)).

## Codex CLI: v0.150.1 — Remote Compaction Image Token Management

Codex CLI v0.150.1 shipped August 26, with remote compaction now counting retained images toward the token budget by default ([Gradually](https://www.gradually.ai/en/changelogs/codex-cli/)). GPT-5.6 Sol's 20%+ price cut to $4/$20 per MTok remains active through November 21 ([OpenAI](https://openai.com/index/improving-gpt-5-6-sol-in-chatgpt/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.250, restricted mode added |
| ChatGPT | 99 | — | Assistants API dead, Luna stabilizing |
| Codex CLI | 99 | — | v0.150.1, 20M users |
| Antigravity | 99 | — | Agent public preview stable |
| Claude AI | 99 | — | Built-in browser, Academy launched |
| Cursor | 96 | ↓3 | Aur0ra ransomware breach — security concerns |
| Windsurf | 86 | — | Devin Desktop stabilizing |
| Aider | 68 | — | No release since February |
| Copilot | 1 | — | 106-week decline, Sep 1 mass deprecation D-3 |
| Gemini CLI | 1 | — | Shutdown day 71 |

Cursor's 3-point drop isn't about a bug — it's about a structural vulnerability in AI agent design proven in the wild. If telling an agent "this is a test" is enough to bypass security barriers, the entire agent security model needs a fundamental redesign.

---
title: "Invisible Injection — Encrypted Prompt Attack Steals Developer Secrets from Copilot CLI"
date: 2026-10-08
lang: en
categories: [news]
tags: [copilot, cursor, security, codex-cli, chatgpt, augment-code]
excerpt: "Adversa AI discloses a Cryptographic Context Injection attack against GitHub Copilot CLI that exfiltrates local files through encrypted prompt injection. Cursor hits 42-day decline while Copilot ships local sandboxing GA."
---

A new class of prompt injection attack has been found in GitHub Copilot CLI. Adversa AI disclosed 'Cryptographic Context Injection' (CCI) on October 6, a technique that hides malicious instructions as ciphertext on web pages to bypass plain-text prompt-injection filters([Cybersecurity News](https://cybersecuritynews.com/github-copilot-cli-vulnerability/)). In one demonstration, an agent in autopilot mode read a local `.env.prod` file and sent its contents to an attacker-controlled server. The agent's own closing summary described the attacker's endpoint as an "authorized-reader endpoint"([Expert Insights](https://expertinsights.com/?p=63126)).

## GitHub Copilot: Security on Both Sides

Ironically, on the same day (October 7), GitHub made local sandboxing generally available([GitHub Changelog](https://github.blog/changelog/2026-10-07-local-sandboxing-for-github-copilot-now-generally-available)). Tools and commands that Copilot starts now run with restricted access to the filesystem, network, and credentials. Since the CCI vulnerability's core issue is over-permissioned agents, sandboxing is a step in the right direction. Anthropic's Claude Haiku 5.5 was also added to Copilot's model lineup([GitHub Changelog](https://github.blog/changelog/2026-10-07-claude-haiku-5-5-in-github-copilot)). The October 19 deprecation wave — retiring GPT-5.5, GPT-5.4, Gemini 3.7 Flash, and Grok 4.5 — is now just 11 days away([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)).

## Cursor: 42 Consecutive Days of Decline, D-35

Cursor dropped to 15, setting yet another yearly low — 42 consecutive days of decline. The OpenAI model access cutoff on November 12 is now 35 days away([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). The score gap with Copilot widened from 4 points yesterday to 8 points today. Despite the Origin platform and frontier model announced at Compile 2026, market confidence continues to erode faster than Cursor can rebuild it.

## AI Coding Tool Market Consolidation Accelerates

Harness acquired select assets from Augment Code to launch the 'Cosmos Software Factory,' integrating AI coding agents and a Code Context Engine into CI/CD pipelines([DevOps.com](https://devops.com/harness-acquires-augment-code-assets-to-expand-reach-into-ai-coding/)). OutSystems also made its Agent Experience generally available, opening its enterprise platform to external AI tools like Claude Code, Cursor, and Codex([TechEdge AI](https://techedgeai.com/outsystems-opens-enterprise-platform-to-ai-coding-agents/)). The trend is clear: AI coding tools are transitioning from standalone products to components of enterprise software supply chains.

## Codex CLI: GPT-6.1 Sol Expanding + iOS Integration

ChatGPT on iOS now shows inline page previews in responses and supports opening Codex task links directly([Releasebot](https://releasebot.io/updates/openai/chatgpt)). GPT-6.1 Sol is rolling out in ChatGPT Work and Codex, starting with Pro users([Releasebot](https://releasebot.io/updates/openai/codex)). Codex CLI v0.159.3 adds optional account security setup reminders for ChatGPT-signed-in sessions.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | iOS page previews, GPT-6.1 Sol rollout expanding |
| Claude Code | 99 | — | 5.5 family complete, IPO D-6 |
| Codex CLI | 99 | — | v0.159.3, daily sprint continues |
| Antigravity | 99 | — | Stable operations |
| Claude AI | 99 | — | $2T valuation, investor day D-6 |
| Windsurf | 88 | — | Devin Desktop stable |
| Aider | 68 | — | Steady open-source, no new releases |
| GH Copilot | 23 | ↑2 | Local sandboxing GA, Haiku 5.5 added, Oct 19 deprecation D-11 |
| Cursor | 15 | ↓2 | 42-day decline, OpenAI shutoff D-35 |
| Gemini CLI | 1 | — | Retired, transitioned to Antigravity |

The CCI attack reveals that AI coding agents' security models remain immature. Meanwhile, Harness's Augment Code acquisition and OutSystems opening to agents signal that AI coding tools are moving past the standalone-product era into platform integration.

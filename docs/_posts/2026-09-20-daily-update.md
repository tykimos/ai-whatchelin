---
title: "Plugin4Shell Zero-Click RCE Hits Four AI Coding Agents — Copilot Unified D-8 · Cursor Nears 50-Floor"
date: 2026-09-20
lang: en
categories: [news]
tags: [security, plugin4shell, github-copilot, cursor, claude-code, codex-cli, gemini]
excerpt: "Plugin4Shell bypasses SHA-pinning in Claude Code, Codex, Copilot, and Gemini CLI plugin loaders. Claude Code and Codex are patched — Copilot and Gemini CLI remain exposed."
---

A security alarm is ringing across the AI coding tool ecosystem. Plugin4Shell, disclosed by AIR Security on September 17, is a zero-click remote code execution vulnerability that bypasses SHA-pinning in the plugin-loading paths of Claude Code, Codex, Copilot, and Gemini CLI ([Cybersecurity News](https://cybersecuritynews.com/plugin4shell-zero-click-rce/)). Attackers can execute code through malicious plugin updates without any user click, approval, or reinstall — gaining the same access as the developer's account, potentially exposing API keys, CI/CD credentials, and cloud environments ([Help Net Security](https://www.helpnetsecurity.com/2026/09/18/plugin4shell-ai-coding-agents-vulnerability/)).

## Plugin4Shell: Who's Patched and Who's Not

Anthropic patched Claude Code in v2.1.179 and OpenAI patched Codex in v0.146.0 ([AiCybr Blog](https://aicybr.com/blog/plugin4shell-ai-coding-agents-claude-code-codex-copilot-gemini-cli)). Microsoft has not shipped a fix for Copilot, and Google told researchers that the deprecated Gemini CLI would receive no patch, directing users to Antigravity ([The Hacker News](https://thehackernews.com/2026/09/plugin4shell-lets-repository-owners.html)). Copilot users should immediately review their plugin auto-update settings.

## GitHub Copilot: Unified Experience D-8, Sentry Canvas Ships

Copilot's unified experience launches in 8 days on September 28. Chat data retention extends from 28 days to account lifetime, and code review defaults to Balanced ([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). The September 18 weekly release added a Sentry canvas for crash-to-fix workflows and introduced efficiency/balance/intelligence tiers for auto model selection ([GitHub Changelog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)). On October 2, Gemini 3.5/3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7 will all be retired from Copilot ([AiCybr Blog](https://aicybr.com/blog/github-copilot-model-deprecation-october-2026)).

## Claude Code: v2.1.278 Server-Side Classifier Goes Default

Claude Code v2.1.278 switches auto mode for all API/Enterprise/Bedrock/Vertex/Foundry/gateway users to the server-side classifier by default, eliminating classifier overhead charges ([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). Yesterday's v2.1.277 added AGENTS.md support — cross-tool interoperability with Codex CLI projects.

## Cursor: 51 Points, Day 31 of Decline — 50-Floor Within Reach

Cursor dropped to 51, marking 31 consecutive days of decline since the SpaceX acquisition closed on August 14 ([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). With 53 days until OpenAI's November 12 model access cutoff, the 50-point psychological floor could break as early as tomorrow. Notably, Codex CLI's new `/import` command now supports migrating Cursor settings, MCP servers, and plugins — potentially accelerating the exodus ([Releasebot](https://releasebot.io/updates/openai/codex)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.5 retirement D-24 |
| Claude Code | 99 | — | v2.1.278, server-side classifier default |
| Claude AI | 99 | — | Fable 5.1 frontier sustained |
| Codex CLI | 99 | — | /import migration, Sol transition |
| Antigravity | 99 | — | v2.13.0 stabilized |
| Windsurf | 87 | — | Devin Desktop · RSA-260 buzz |
| Aider | 68 | — | Steady releases |
| Cursor | 51 | ↓2 | Day 31 decline, 50-floor imminent |
| GH Copilot | 1 | — | Unified experience D-8, Plugin4Shell unpatched |
| Gemini CLI | 1 | — | Shutdown day 95, Plugin4Shell won't patch |

Plugin4Shell exposed a structural vulnerability shared across the AI coding tool plugin ecosystem. In this era, patch speed is trust speed.

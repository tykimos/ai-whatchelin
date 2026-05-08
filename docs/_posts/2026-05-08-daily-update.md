---
title: "Claude Code 'TrustFall' RCE Vulnerability Sparks Security Debate — Cursor Ships Parallel Builds, Copilot D-23"
date: 2026-05-08
lang: en
categories: [news]
tags: [claude-code, cursor, copilot, antigravity, security, windsurf]
excerpt: "Adversa.AI disclosed a one-click RCE vulnerability in Claude Code called 'TrustFall,' but Anthropic declined to patch. Meanwhile, Cursor 3.3 introduces parallel builds and Antigravity launches a 1,254-skill AI agent ecosystem."
---

Security research firm Adversa.AI disclosed "TrustFall," a one-click remote code execution vulnerability in Claude Code that allows attackers to run arbitrary code on a developer's machine through malicious repositories([CodeSecAI](https://codesecai.com/ai-coding-agents-trustfall-rce-2026/)). Anthropic declined to patch it, arguing that the user's click on "Yes, I trust this folder" constitutes consent — sparking heated debate on Hacker News about trust boundaries in AI coding agents([Hacker News](https://news.ycombinator.com/item?id=48037986)).

## Claude Code: Security Controversy Amid Rapid Feature Expansion

The aftershocks from the 'Code with Claude' conference continue into day two. The desktop app received a complete redesign with a session sidebar, drag-and-drop workspace, integrated terminal/file editor, and SSH support on Mac([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). Plugin URL loading (`--plugin-url` flag) and `claude project purge` were also added. While the SpaceX-powered rate limit doubling holds steady([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)), TrustFall has emerged as a wildcard. Community sentiment is split: *"Pushing trust boundaries onto user consent is dangerous"* versus *"This is an inherent limitation of any code execution tool."*

## Cursor 3.3: Parallel Builds and PR Splitting Boost Productivity

Cursor 3.3 shipped "Build in Parallel," which identifies independent parts of a plan and runs them simultaneously via async subagents while preserving dependency order([Cursor Changelog](https://cursor.com/changelog)). "Split PRs" lets developers break multi-task changes into logical pull requests with automatic backup snapshots and split-plan suggestions. Quick-Action Pills and subagent model selection (e.g., `model: opus`) round out the release. The score climbs from 91 to 92.

## GitHub Copilot: D-23, Preview Bills Go Live

The countdown to usage-based billing on June 1 hits 23 days([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Preview bills launched in early May, giving users projected cost visibility before the switch([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)). Copilot Code Review will also start consuming GitHub Actions minutes at per-minute rates from June 1([GitHub Changelog](https://github.blog/changelog/2026-04-27-github-copilot-code-review-will-start-consuming-github-actions-minutes-on-june-1-2026/)). The popularity score drops to 78, marking a sixth consecutive weekly decline.

## Antigravity: 'Awesome Skills' Ecosystem Reaches 1,254 AI Agent Skills

Antigravity unveiled its "Awesome Skills" ecosystem with over 1,254 AI agent skills([BrightCoding](https://www.blog.brightcoding.dev/2026/05/07/antigravity-awesome-skills-1254-ai-agent-power-ups-every-developer-needs)). IDE v1.22.2 added Manager/Editor View split, AGENTS.md support, and a 2-million-token context window([Antigravity Lab](https://antigravitylab.net/en/articles/antigravity/antigravity-may-2026-updates)). A new Ultra plan launched at $249.99/month. The score rebounds from 47 to 49.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant settled as default |
| Claude Code | 97 | — | TrustFall controversy offset by SpaceX effect |
| Cursor | 92 | ↑1 | Parallel builds + PR split, new high |
| Claude AI | 91 | — | Bloomberg reports consumer expansion push |
| GitHub Copilot | 78 | ↓1 | 6-week slide, D-23 |
| Windsurf | 77 | — | Devin Review free for all users |
| Codex CLI | 77 | — | Pro double usage promo continues |
| Gemini CLI | 70 | — | Open-source settling in |
| Aider | 68 | — | 39K+ stars, stable |
| Antigravity | 49 | ↑2 | Awesome Skills 1,254+, Ultra plan launch |

The TrustFall disclosure has ignited a broader supply-chain security debate around AI coding agents, but Claude Code holds at 97 on the strength of its SpaceX infrastructure. Cursor hits a new high of 92 with parallel builds, widening its lead over Copilot (78) to 14 points. Antigravity's skill ecosystem rebound to 49 signals a potential turnaround for Google's agentic IDE experiment.

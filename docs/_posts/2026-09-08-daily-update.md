---
title: "Google Warns AI Coding Tools Are Hackers' Top Target — GitHub Fights Back With Multi-Agent Teams"
date: 2026-09-08
lang: en
categories: [news]
tags: [google, security, cursor, openai, devday, github-copilot, anthropic, mckinsey]
excerpt: "Google warned that AI coding agents are now cybercriminals' top target the same day GitHub expanded Copilot into a multi-agent team model. Cursor falls for the 12th straight day, and McKinsey says 32% of enterprises are skipping SaaS purchases thanks to agentic coding."
---

AI coding tool security became the week's dominant story. Google warned that AI coding agents are now the primary target for threat actors on the same day GitHub expanded Copilot into a multi-agent team model, and McKinsey revealed that 32% of enterprises have skipped buying off-the-shelf software because agentic coding tools let them build it themselves.

## Google: "AI Coding Tools Now a Prime Target for Threat Actors"

Google's Threat Intelligence Group formally warned that AI coding tools have become a primary attack vector for cybercriminals and state-backed hackers ([Infosecurity Magazine](https://www.infosecurity-magazine.com/news/ai-coding-tools-threat-actors/)). The financially motivated group UNC6780 used autonomous AI frameworks to build and launch a credential theft operation across PyPI, npm, and Docker Hub in under six hours. Their Dustmaker malware extracts tokens from GitHub Actions runners and publishes malicious packages that bypass automated trust checks. Google recommends tightly restricting cloud credentials, rotating exposed secrets immediately, and treating AI agent configuration files as security-sensitive assets ([Google Cloud Blog](https://cloud.google.com/blog/products/identity-security/beyond-source-code-the-files-ai-coding-agents-trust-and-attackers-exploit)). Chinese state actor UNC6508's targeting of military and academic AI research was also disclosed.

## GitHub Copilot: Multi-Agent Team Model Expansion

GitHub expanded Copilot Workspace into a coordinated multi-agent team model where separate agents handle implementation, testing, and documentation simultaneously ([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). The system maintains shared context across all agents working on the same codebase. October 2 model deprecations (Gemini 3.5/3.6 Flash, Kimi K2.7, Claude Opus 4.7) and a unified Chat/Mobile/Cloud Agent experience relaunch no earlier than September 28 are also on the horizon ([GitHub Changelog](https://github.blog/changelog/2026-09-04-github-copilot-weekly-releases-august-31/)). Whether this wholesale restructuring can lift Copilot from its extended floor remains an open question.

## Cursor: Score 73, 12th Consecutive Decline — D-65

Cursor dropped to 73, marking its 12th consecutive daily decline ([Cursor Changelog](https://cursor.com/changelog)). The slide from 99 on August 27 now totals 26 points. SpaceX-owned Cursor shipped Claude Fable 5.1 integration and self-hosted machines ([Cursor Blog](https://cursor.com/blog)), but with the OpenAI model cutoff (Nov 12) now 65 days away, restoring developer trust remains the central challenge.

## McKinsey: 32% of Enterprises Skipping SaaS Purchases for Agentic Coding

McKinsey's "State of AI 2026" report found that 32% of organizations have skipped buying at least one software product because they could build it internally with agentic coding tools ([McKinsey](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai)). Among high performers — the 6% attributing 5%+ of EBIT to AI — nearly half are doing so ([Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/build-vs-buy-shift-32-113806700.html)). The build-vs-buy paradigm is shifting in real time.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Astra rollout Day 5, DevDay 3 weeks out |
| Claude Code | 99 | — | v2.1.261 stable, Fable 5.1 default |
| Claude AI | 99 | — | Fable/Mythos 5.1 cache reads cut 75% |
| Codex CLI | 99 | — | Astra default, v0.153.4 stable |
| Antigravity | 99 | — | Google's premier agent platform |
| Windsurf | 86 | — | Devin Desktop stable |
| Cursor | 73 | ↓2 | 12th consecutive decline, D-65 |
| Aider | 68 | — | No release since v0.86.2 |
| GH Copilot | 1 | — | Floor, multi-agent team model announced |
| Gemini CLI | 1 | — | Shutdown Day 82, replaced by Antigravity |

Google's security warning and McKinsey's 32% figure landing in the same week is no coincidence. As agentic coding becomes the enterprise default, security risk scales with it. OpenAI DevDay is three weeks away, GitHub's multi-agent overhaul goes live in 20 days — the next chapter of the agent platform war is opening.

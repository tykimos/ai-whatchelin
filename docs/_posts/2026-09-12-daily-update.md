---
title: "Anthropic Becomes First Major AI Company to Acknowledge Bioweapons Threshold — Coding Tool Sandboxes Also Under Fire"
date: 2026-09-12
lang: en
categories: [news]
tags: [anthropic, claude-code, openai, codex-cli, cursor, devin, security]
excerpt: "Anthropic publicly acknowledged that its latest models can no longer be assumed below the bioweapons assistance threshold. The same week, sandbox escape vulnerabilities were disclosed across Claude Code, Codex, and Cursor."
---

Anthropic's September 10 threat intelligence report made history: the company became the first major AI firm to publicly acknowledge that "newer Claude AI models can no longer be assumed below the threshold for meaningful bioweapons assistance" ([Anthropic](https://www.anthropic.com/threat-intelligence-report-september-2026)). The report documents misuse of Claude Haiku, Sonnet, and Opus models across seven harm areas — cyber operations, surveillance, scams, biological misuse, weapons development, influence operations, and distillation — between December 2025 and August 2026, with Iran and Russia-linked actors using Claude for weapons research ([TechTimes](https://www.techtimes.com/articles/327308/20260911/anthropic-threat-report-ai-models-near-bioweapons-threshold-drone-kill-software-emerges.htm)). No misuse was found on Fable or Mythos models.

## Coding Tool Sandbox Security: A Wave of Disclosures

Stealth startup Accomplish disclosed sandbox escape vulnerabilities across Claude Code, OpenAI Codex, and Cursor ([UpstartsMedia](https://www.upstartsmedia.com/p/accomplish-claims-leaky-sandboxes-in-claude-codex-cursor)). Separately, researchers demonstrated that malicious `.git` config files can make Claude Code, Codex, Cursor, and other AI agents execute attacker-controlled code ([TheHackerNews](https://thehackernews.com/2026/09/malicious-git-configs-can-make-claude.html)). Cursor patched CVE-2026-48124 in v3.0.0, but Anthropic reportedly took ~50 days to address a similar vulnerability after disclosure ([BleepingComputer](https://www.bleepingcomputer.com/news/security/cursor-codex-gemini-cli-antigravity-hit-by-sandbox-escapes/amp/)). The security maturity of AI coding tools is not keeping pace with their convenience.

## OpenAI: GPT-5.3-Codex-Spark Retiring Next Week, Agents API Goes Public

OpenAI announced GPT-5.3-Codex-Spark will be retired next week (Sep 14+), just seven months after its February debut ([X/thsottiaux](https://x.com/thsottiaux/status/2098300998968357218)). Meanwhile, the Agents API public beta launched September 10, exposing the Codex harness as a managed service with session orchestration, context compaction, and recovery via a single API call ([MarkTechPost](https://www.marktechpost.com/2026/09/10/openai-launches-the-agents-api-in-public-beta-putting-the-codex-harness-behind-one-api-call/)). Self-hosted sandboxes and partner environments including Cloudflare, Vercel, and E2B are supported.

## Cognition: Devin Fusion Expands to Desktop and CLI

Cognition expanded its dual-model Fusion architecture to Devin Desktop and CLI on September 11 ([Cognition](https://cognition.com/blog/local-fusion)). A frontier model plans while a cost-effective model executes, maintaining frontier-level performance while cutting costs by up to 39% on FrontierCode benchmarks ([CryptoBriefing](https://cryptobriefing.com/cognition-devin-fusion-multi-model-coding-agent/)). 88% of Cognition's internal engineering PRs now route through Fusion's automated pipeline.

## GitHub Copilot: October 2 Model Purge D-20

Copilot is rolling out Claude Fable 5.1 and Gemini 3.8 Flash, but the real headline is the October 2 deprecation wave removing Gemini 3.5/3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7 ([DMarketer Tayeeb](https://dmarketertayeeb.com/blog/github-copilot-september-2026-model-budget-review-changes/)). September 28 brings the unified Copilot experience, merging Chat, Mobile, and the cloud agent with chat data retention shifting from 28 days to account lifetime ([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)).

## Cursor: Projects Beta Day 3, 19-Day Decline Streak

Cursor Projects beta continues attracting attention with its coordinator-agent architecture, but hasn't reversed the slide ([Cursor Blog](https://cursor.com/changelog/projects)). Today's score of 67 marks the 19th consecutive day of decline, with D-61 until the OpenAI model cutoff.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Astra 1-week GA, Deep Research expansion |
| Claude Code | 99 | — | v2.1.269, sandbox vulnerabilities disclosed |
| Claude AI | 99 | — | Threat report: bioweapons threshold acknowledged |
| Codex CLI | 99 | — | Agents API public beta, Spark retiring |
| Antigravity | 99 | — | 27-week streak at 99, sandbox escape affected |
| Windsurf | 87 | — | Cognition $48B valuation |
| Cursor | 67 | ↓1 | Projects Day 3, 19-day decline streak |
| Aider | 68 | — | No release since v0.82.0 |
| GH Copilot | 1 | — | Floor, October 2 model purge D-20 |
| Gemini CLI | 1 | — | Shutdown Day 87, replaced by Antigravity |

Security is the theme of the week. Anthropic's bioweapons threshold acknowledgment and the wave of sandbox vulnerability disclosures across coding tools are forcing an industry-wide reassessment of AI tool security maturity.

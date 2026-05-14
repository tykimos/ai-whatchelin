---
title: "GitHub Copilot Freezes Signups, Launches Desktop App — The Agent Cost Reckoning Begins"
date: 2026-05-14
lang: en
categories: [news]
tags: [github-copilot, claude-code, anthropic, cursor, gemini-cli, aws-kiro, openai, stainless]
excerpt: "GitHub paused Copilot individual signups while simultaneously shipping a desktop app and Max plan. Anthropic pursues both the Stainless acquisition and a $900B valuation."
---

GitHub is closing one door and opening another. With Copilot individual plan signups (Pro/Pro+/Student) paused since late April, GitHub today announced the **Copilot App** technical preview and a new **Max plan** simultaneously([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-individual-plans-introducing-flex-allotments-in-pro-and-pro-and-a-new-max-plan/)). The Copilot App is a GitHub-native desktop experience where agentic sessions start from issues, PRs, or previous sessions — with branches, files, and conversations isolated per session for true parallel work([GitHub Changelog](https://github.blog/changelog/2026-05-14-github-copilot-app-is-now-available-in-technical-preview/)). Pro/Pro+ subscribers get first access, with Business/Enterprise rolling out this week.

## GitHub Copilot: Max Plan + Token Billing Transition

All Copilot plans shift to usage-based billing (AI Credits) on June 1([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Pro stays at $10/mo, Pro+ at $39/mo (with $39 in AI Credits), and code completions plus Next Edit remain credit-free. The new **Max** plan targets high-volume power users. Meanwhile, **Opus models were removed from Pro** — Opus 4.7 now requires Pro+ ($39/mo), effectively a 290% price increase for Opus access([DEV Community](https://dev.to/techsifted/github-copilot-may-2026-changes-sign-ups-paused-opus-removed-rate-limits-visible-2ip8)). CLI v1.0.48 now displays actual token prices in the model picker([GitHub Releases](https://github.com/github/copilot-cli/releases)).

## Anthropic: Stainless + $900B Valuation Target

Following The Information's report on Anthropic's $300M+ talks to acquire Stainless — the SDK builder for OpenAI, Google, Cloudflare, and Meta — Bloomberg reports Anthropic is targeting a **$900B valuation** in a $30B+ funding round([Bloomberg](https://www.newsbytesapp.com/news/business/anthropic-nearing-stainless-acquisition-and-seeking-at-least-30b-funding/tldr)). Pursuing SDK infrastructure control and massive capital simultaneously signals platform-war escalation.

## Claude Code: Limits Up + v2.1.141

Claude Code weekly limits were raised 50% across Pro, Max, Team, and Enterprise through July 13([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)). v2.1.141 ships Agent View (unified session list), /goal command (set completion conditions for autonomous loops), terminal notification hooks, and workspace identity federation([Releasebot](https://releasebot.io/updates/anthropic/claude-code)).

## Cursor: Cloud Agent Development Environments

Cursor launched Development Environments for cloud agents — multi-repo support, Dockerfile layer caching (70% faster builds), per-environment rollback, and audit logging([Cursor Changelog](https://cursor.com/changelog/05-13-26)). Microsoft Teams integration (@Cursor mentions to delegate to cloud agents) also shipped this week([Cursor Blog](https://cursor.com/blog/cloud-agent-development-environments)).

## AWS Kiro + Google I/O D-5

AWS Kiro's new Spec Check uses an SMT solver to mathematically prove requirements are contradiction-free before code generation([GeekWire](https://www.geekwire.com/2026/aws-targets-ai-slop-with-new-spec-check-in-kiro-coding-tool-amid-scrutiny-of-agent-reliability/)). Google I/O is five days away, with Gemini CLI v0.43.0-preview's subagent architecture expected to go live alongside the Gemini 4 debut([TechRound](https://techround.co.uk/tech/gemini-4-ai-glasses-and-a-new-os-why-google-i-o-2026-could-be-the-most-important-developer-event-of-the-year/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant stable |
| Claude Code | 98 | — | v2.1.141, weekly limits +50%, 11 days at 98 |
| Cursor | 95 | ↑1 | Cloud agent dev environments + Teams integration |
| Claude AI | 92 | — | Cowork GA stabilizing |
| Codex CLI | 81 | — | Chrome extension, workspace agents |
| Windsurf | 78 | — | Opus 4.7 fast mode stable |
| Gemini CLI | 75 | ↑1 | I/O D-5, subagent architecture |
| GitHub Copilot | 73 | — | App preview launched, but signup freeze + Opus removal offset |
| Aider | 68 | — | Stable |
| Antigravity | 48 | ↓1 | Soft-deprecation rumors |

GitHub's "freeze signups + launch desktop app + add Max plan" trilogy is the clearest signal yet that the agent era's cost reality has arrived. Unlimited plans can't survive parallelized, long-running agent sessions at scale. Meanwhile, Anthropic is simultaneously locking down SDK infrastructure (Stainless) and raising $30B — a two-front campaign to own the agent platform layer.

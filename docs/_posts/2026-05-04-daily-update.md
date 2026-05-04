---
title: "SpaceX Swoops In on Cursor for $60B as GitHub Copilot Overhauls Billing"
date: 2026-05-04
lang: en
categories: [news]
tags: [cursor, copilot, gpt-5.5, claude-code, windsurf, gemini-cli, security]
excerpt: "SpaceX's $60B Cursor acquisition deal, GitHub Copilot's shift to token-based billing, and GPT-5.5's launch — the AI coding landscape reshuffled entirely in two weeks."
---

The past two weeks brought seismic shifts to the AI coding tool market. SpaceX secured the right to acquire Cursor for $60 billion, GitHub Copilot announced a fundamental billing overhaul, and OpenAI launched its most expensive frontier model yet.

## SpaceX Strikes $60B Deal for Cursor

SpaceX signed an agreement to acquire Cursor for $60 billion later this year([Bloomberg](https://www.bloomberg.com/news/articles/2026-04-21/spacex-says-has-agreement-to-acquire-cursor-for-60-billion)). Musk preempted Cursor's planned $2B fundraise at a $50B valuation([TechCrunch](https://techcrunch.com/2026/04/22/how-spacex-preempted-a-2b-fundraise-with-a-60b-buyout-offer/)). The strategy: combine Cursor's product with SpaceX's Colossus training supercomputer. The acquisition is delayed until after SpaceX's IPO this summer, but the community is already debating whether Musk's involvement will alter Cursor's product direction. Adding to Cursor's turbulent month, a CVSS 8.1 arbitrary code execution vulnerability (CVE-2026-26268) was publicly disclosed and patched in v2.5([Cybersecurity News](https://cybersecuritynews.com/cursor-ai-coding-agent-vulnerability/)).

## GitHub Copilot: Sign-Ups Paused + Token Billing

GitHub paused new sign-ups for Copilot Pro, Pro+, and Student plans([GitHub Blog](https://github.blog/news-insights/company-news/changes-to-github-copilot-individual-plans/)). Opus models were removed from Pro — Opus 4.7 is now Pro+ only. The reason: agentic workflows fundamentally changed compute demands beyond what the original plan structure supported. The bigger change: starting June 1, all Copilot plans move to token-based billing with AI Credits replacing Premium Request Units([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Developer reaction has been harsh: *"You will get less, but pay the same price"*([Visual Studio Magazine](https://visualstudiomagazine.com/articles/2026/04/27/devs-sound-off-on-usage-based-copilot-pricing-change-you-will-get-less-but-pay-the-same-price.aspx)).

## GPT-5.5: OpenAI's Smartest Model, Highest Price

OpenAI released GPT-5.5([OpenAI](https://openai.com/index/introducing-gpt-5-5/)) — output tokens cost $30/MTok, double the GPT-5 line pricing. Multi-step reasoning and agentic workflows are significantly improved. Simultaneously, Codex Desktop received a major update adding macOS Computer Use (see, click, type across apps), 90+ plugins, and an in-app browser([OpenAI](https://openai.com/index/codex-for-almost-everything/)).

## Claude Code: ultrareview + Managed Agents

Anthropic added the ultrareview subcommand to Claude Code — a fleet of cloud reviewer agents hunt bugs in parallel before PR merges, at $5-$20 per review([code.claude.com](https://code.claude.com/docs/en/whats-new)). The new Managed Agents service enables long-horizon agent work in a hosted environment with durable state. Claude Sonnet 4 and Opus 4 are set to retire on June 15.

## Security Alert: Back-to-Back Cursor + Gemini CLI Vulnerabilities

Following Cursor's CVE-2026-26268 (CVSS 8.1), Gemini CLI disclosed a CVSS 10.0 vulnerability([The Register](https://www.theregister.com/2026/04/30/googles_fix_for_critical_gemini/)). In headless/CI mode, the CLI automatically trusted workspace folders and loaded agent configs without human approval or sandboxing. Patched in v0.39.1, but the back-to-back disclosures reignited debate about the fundamental risks of AI agents autonomously executing system-level commands.

## Windsurf 2.0: Devin Built-In + $25B Valuation

Cognition launched Windsurf 2.0 with Devin directly integrated([windsurf.com](https://windsurf.com/blog/windsurf-2-0)). Plan locally with Cascade, hand off to Devin for cloud execution in one click. Cognition is in talks to raise hundreds of millions at a $25 billion valuation([Idlen](https://www.idlen.io/news/cognition-devin-25-billion-valuation-windsurf-vibe-coding-april-2026/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 97 | — | GPT-5.5 launch, holding steady at top |
| Claude Code | 95 | ↑1 | ultrareview + Managed Agents, steady climb |
| Cursor | 89 | ↓1 | SpaceX acquisition uncertainty + CVE |
| Claude AI | 89 | ↑1 | Opus 4.7 adoption spreading |
| GitHub Copilot | 83 | ↓2 | Sign-ups paused + token billing backlash |
| Windsurf | 76 | ↑2 | 2.0 launch + Devin integration |
| Codex CLI | 74 | ↑2 | Computer Use + GPT-5.5 support |
| Aider | 68 | — | Stable |
| Gemini CLI | 67 | ↑2 | v0.40.0 shipped, CVSS 10.0 patched |
| Antigravity | 49 | ↓1 | Continued decline |

Between Copilot's billing overhaul and Cursor's acquisition uncertainty, Claude Code and Windsurf are capturing the spillover. The back-to-back security disclosures have elevated trust concerns across the entire AI agent tool category.

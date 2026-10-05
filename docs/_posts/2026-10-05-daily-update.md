---
title: "Claude Code Patches Second Deny-Rule Bypass as Anthropic IPO Investor Day Hits D-9"
date: 2026-10-05
lang: en
categories: [news]
tags: [claude-code, anthropic-ipo, copilot, cursor, jetbrains-air, ibm-bob, qodo]
excerpt: "Claude Code v2.1.289 patches a second route past its rm guard, while Anthropic's pre-IPO investor day on October 14 sets the stage for a potential $2T listing. JetBrains Air EAP and IBM Bob self-hosted reshape the enterprise agentic landscape."
---

The AI coding tool market doesn't rest on weekends. Claude Code shipped another security patch, Anthropic's IPO clock is ticking down to investor day D-9, and this week's JetBrains Air and IBM Bob self-hosted launches are reshaping the enterprise agentic coding landscape.

## Claude Code: v2.1.289 — Second Deny-Rule Bypass Patched

Anthropic released Claude Code v2.1.289 on October 3, primarily a security release([mixed-news.com](https://mixed-news.com/en/claude-code-2-1-289-second-route-past-rm-guard-stable-four-builds-behind/)). The update closes a second route for deletion commands to slip past permission checks — specifically, Bash deny/ask rules missing commands hidden behind environment variable prefixes with expanded values (e.g., `TZ="$HOME" rm -rf build`)([ai-tldr.dev](https://ai-tldr.dev/releases/anthropic-claude-code-2-1-289/)). Also fixed: Read deny rules bypassed via symlinks, and compound shell commands where mod approvals overrode deny rules on managed machines. On the feature side, `agent.spawn` for teammate agents and unified agent IDs across plugin hook events were added.

## Anthropic IPO: Investor Day October 14, Mid-November Listing Likely

Bloomberg reports Anthropic will host a pre-IPO investor day at its San Francisco headquarters on October 14([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/anthropic-is-said-to-plan-pre-ipo-investor-day-as-listing-nears)). Marketing is expected to begin the week of November 9, with a mid-November listing targeting up to $2 trillion valuation([Yahoo Finance](https://finance.yahoo.com/technology/article/anthropic-reportedly-looking-to-ipo-as-early-as-mid-november-180315768.html)). If it proceeds, this would be the largest IPO in history.

## JetBrains Air EAP: The IDE Agentic Layer Arrives

JetBrains launched Air EAP on October 1, an agentic development layer integrated into 2026.3 EAP builds([SD Times](https://sdtimes.com/ai/sd-times-news-roundup-oct-1-2026-ibm-bob-jetbrains-air-qodo-3-0/)). It works with external agents like Codex, GitHub Copilot, Junie, and Cursor, offering built-in IDE skills for debugging and code search — no JetBrains AI subscription required.

## Cursor: 39th Consecutive Decline, OpenAI Shutoff D-38

Cursor's popularity dropped for the 39th straight day to 21, with 38 days remaining until OpenAI's November 12 model access cutoff([DevOps.com](https://devops.com/openai-cuts-off-cursors-model-access-after-spacex-acquisition/)). Post-SpaceX acquisition, Cursor's survival hinges on its Origin hosting platform and mobile beta rollout.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay aftermath, GPT-6.1 Sol settling in |
| Claude Code | 99 | — | v2.1.289 security patch, IPO D-9 |
| Codex CLI | 99 | — | v0.160.0 stable, Cloud mode expanding |
| Antigravity | 99 | — | Added Claude Opus 5.5 model |
| Claude AI | 99 | — | Opus 5.5/Sonnet 5.5, voice data collection |
| Windsurf | 88 | — | Steady as Devin Desktop |
| Aider | 68 | — | Steady open-source, 44K stars |
| Cursor | 21 | ↓2 | 39th straight decline, OpenAI shutoff D-38 |
| GH Copilot | 17 | ↑2 | Computer Use GA, Oct 19 model deprecation wave |
| Gemini CLI | 1 | — | Transitioned to Antigravity CLI |

The market doesn't sleep on weekends. Claude Code's back-to-back security patches highlight how complex permission management is in agentic coding, while Anthropic's IPO countdown is shaping up to be the event that reshapes AI industry capital flows.

---
title: "Claude Code Ships Fable 5.2 as Default — Copilot CLI Adds GPT-6.1 Terra"
date: 2026-11-11
lang: en
categories: [news]
tags: [claude-code, anthropic, github-copilot, cursor, openai, codex-cli, antigravity]
excerpt: "One day after Anthropic launched Fable 5.2, Claude Code v2.1.321 made it the default model. GitHub Copilot CLI also added GPT-6.1 Terra as the model race heats up."
---

Anthropic launched Fable 5.2 on Saturday and Claude Code adopted it as the default model by Sunday. GitHub Copilot CLI also shipped GPT-6.1 Terra support, while tomorrow marks the day Cursor loses OpenAI model access for good.

## Claude Code v2.1.321: Fable 5.2 Goes Default, Security Fix Included

Claude Code v2.1.321 shipped November 10, making Claude Fable 5.2 the default Fable model ([ai-tldr.dev](https://ai-tldr.dev/releases/anthropic-claude-code-2-1-321/)). Fable 5.2, launched November 9, delivers 30% faster output and a 20% price cut from $10/$50 to $8/$40 per million tokens ([9to5mac.com](https://9to5mac.com/2026/11/09/anthropic-upgrades-claude-with-new-fable-5-2-model-details-here/)). Existing Fable 5.1 selections automatically migrate to the `fable` alias, and users can switch back with `/model claude-fable-5-1`. The release also patched an MCP OAuth vulnerability where refresh tokens were being sent to another host after redirect ([labmemo.com](https://labmemo.com/claude-code-v2-1-321-fable-5-2-default-security-fixes-2026-11/)).

## GitHub Copilot CLI v1.0.106: GPT-6.1 Terra in Model Picker

Copilot CLI v1.0.106 shipped November 6, adding GPT-6.1 Terra to the model picker ([newreleases.io](https://newreleases.io/project/npm/@github/copilot/release/1.0.106)). Terra is positioned as a lower-cost alternative to GPT-6.1 Sol for everyday agentic coding, available across all paid plans ([github.blog](https://github.blog/changelog/2026-10-26-gpt-6.1-terra-in-github-copilot)). The release also added a `/code` command to open sessions in VS Code, a unified `/settings` dashboard, and opt-in session `@mentions` ([havoptic.com](https://www.havoptic.com/r/github-copilot-v1.0.106)).

## Cursor: OpenAI Cutoff D-1, Day 78 at Bottom

Tomorrow, OpenAI models disappear from Cursor permanently ([CyberNews](https://cybernews.com/ai-news/openai-cursor-spacex-contract-termination/)). The 78-day freefall since SpaceX's $60B Anysphere acquisition reaches its terminus, with the popularity score pinned at 1 and no sign of recovery ([RuntimeWire](https://runtimewire.com/article/openai-cuts-cursor-model-access-spacex-acquisition)).

## Antigravity 2.29: Knowledge Work Mode Unveiled

Google's Antigravity unveiled a Knowledge Work office mode on November 10 ([ChainCatcher](https://www.chaincatcher.com/en/article/2303352)). The mode hides terminal and Git views for research and document tasks, complementing the Remote Agents and Voice Mode features shipped earlier in 2.29. Separately, Gemini 4 Carbon Low/Medium/High variants were spotted in an Antigravity build, though this remains unconfirmed ([TestingCatalog](https://pasqualepillitteri.it/en/news/31811/gemini-4-carbon-antigravity-build-low-medium-high)).

## Enterprise AI Caps: Apple and Goldman Tighten Spending

Apple cut engineers' daily AI cap from $300 to $200 with possible further cuts to $100 ([Macworld](https://macworld.com/article/3277678/apple-reportedly-slashes-employee-ai-usage-limits-amid-cost-cutting-effort.html)). Goldman Sachs restricted Claude Code and GitHub tool access to engineering staff only, affecting roughly 10,000 traders and bankers ([Dealroom](https://app.dealroom.co/news/note/goldman-restricts-claude-code-github-for-traders-and-bankers)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Stable |
| Claude Code | 99 | — | v2.1.321 Fable 5.2 default |
| Codex CLI | 99 | — | 0.167.0 agent command center |
| Antigravity | 99 | — | Knowledge Work mode unveiled |
| Claude AI | 99 | — | Fable 5.2 launched, IPO roadshow active |
| GH Copilot | 91 | ↑2 | v1.0.106 GPT-6.1 Terra, 47-day streak |
| Windsurf | 88 | — | Stable as Devin Desktop |
| Aider | 68 | — | Maintenance mode continues |
| Cursor | 1 | — | OpenAI cutoff D-1, day 78 at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition complete |

Claude Code and Copilot CLI both completed model generation shifts — Fable 5.2 and GPT-6.1 Terra respectively — just as Cursor's OpenAI cutoff becomes reality tomorrow. The tool-level model race is accelerating, while enterprise AI spending cuts from Apple and Goldman introduce a new headwind.

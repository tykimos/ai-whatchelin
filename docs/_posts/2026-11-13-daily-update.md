---
title: "AI Coding Agents Leak 2,500 Secrets — GitHub Drops Three Models Nov 16, Code Summit Declares the Age of Agent Orchestration"
date: 2026-11-13
lang: en
categories: [news]
tags: [claude-code, security, gemini, antigravity, github-copilot, cursor, codex-cli, ai-engineer]
excerpt: "Apiiro researchers found 2,539 credentials leaked through Claude Code's settings file. GitHub will remove Opus 5, Opus 4.8, and GPT-5.6 Terra in three days. The AI Engineer Code Summit wraps with a clear message: multi-agent orchestration is the future."
---

The convenience of AI coding tools has come back to bite. Security firm Apiiro exposed Claude Code's "Don't Ask Again" feature as a plaintext credential store, while GitHub Copilot prepares for a major model purge just three days away.

## Claude Code Secret Leak: 2,539 Credentials Exposed in Public Repos

Security firm Apiiro discovered 2,539 secrets across 1,994 public GitHub repositories ([Dark Reading](https://darkreading.com/cyber-risk/ai-coding-agents-leak-secrets-github)). The exposed data includes database passwords, cloud keys, and API tokens, with most residing in Claude Code's `.claude/settings.local.json` file ([Cybernews](https://cybernews.com/security/ai-agents-leaking-secrets-on-github/)). When developers click "Don't Ask Again," the approved command is written to a project file in plaintext — and when that file isn't in `.gitignore`, it gets committed to public repos ([VentureBeat](https://venturebeat.com/security/did-claude-codes-dont-ask-again-option-accidentally-expose-your-enterprises-passwords-and-keys/)). Of the 16 coding agents Apiiro examined, Claude Code was the only one that saved approved commands to a project file by default ([The Hacker News](https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html)).

Separately, Claude Code v2.1.319 (Nov 6) introduced a `denyInsteadOfPrompting` setting that automatically denies permission prompts during unattended runs ([dev.classmethod.jp](https://dev.classmethod.jp/en/articles/20261108-cc-updates-v2-1-319/)). Auto mode behind LLM gateways was also tightened — calls the server can't verify are now denied rather than falling back to the built-in classifier ([ai-tldr.dev](https://ai-tldr.dev/releases/anthropic-claude-code-2-1-319/)).

## GitHub Copilot: Mass Model Deprecation Coming Nov 16 & CLI v1.0.106 Ships

GitHub will remove Claude Opus 4.8, Claude Opus 5, and GPT-5.6 Terra from all Copilot experiences on November 16 ([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). The deprecation covers Chat, inline edits, Ask and Agent modes, and code completions across all plan tiers ([dev.classmethod.jp](https://dev.classmethod.jp/en/articles/github-copilot-model-deprecation-nov-2026/)). Claude Opus 5.5 replaces Opus 5, while GPT-6.1 Sol or GPT-6 Luna replaces GPT-5.6 Terra.

Meanwhile, Copilot CLI v1.0.106 shipped November 5, adding GPT-6.1 Terra to the model selector ([newreleases.io](https://newreleases.io/project/npm/@github/copilot/release/1.0.106)). GPT-6.1 Terra is optimized for everyday agentic coding and terminal work at lower cost, and went GA on October 26 for all Copilot tiers ([GitHub Blog](https://github.blog/changelog/2026-10-26-gpt-6-1-terra-in-github-copilot)). The release also adds a `/code` command to open sessions in VS Code and a unified `/settings` dashboard ([labmemo.com](https://labmemo.com/?p=62802)). Copilot hits 95 — its 50th consecutive day of gains — and the Fusion GA 30% model-cost discount runs through November 30 ([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)).

## Google Launches Gemini 4 Carbon

Google officially launched Gemini 4 Carbon on November 12 ([NewsBytesApp](https://www.newsbytesapp.com/news/science/google-launches-gemini-4-carbon-exclusively-for-ai-ultra-subscribers/tldr)). It's available through Google AI Studio, the Gemini API, and the Antigravity CLI, with introductory pricing running through November 30. Carbon expands on the Argon variant that was previously limited to cybersecurity partners ([Axios](https://axios.com/2026/09/30/google-gemini-4)).

## Antigravity: Knowledge Work Mode Goes Beyond Coding

Google added a Knowledge Work layout to Antigravity in early November ([antigravity.google](https://antigravity.google/blog/antigravity-for-knowledge-work/)). The new interface strips Git worktrees, the terminal, and inline code diffs, replacing them with an artifacts panel for research, document writing, and data analysis ([NewsBytesApp](https://www.newsbytesapp.com/news/science/google-launches-knowledge-work-antigravity-interface-beyond-software-engineering/tldr)). It's included in the existing Antigravity app at no extra cost, and users can switch layouts in Settings ([Thurrott](https://www.thurrott.com/?p=343721)).

## Cursor: Day Two After the OpenAI Cutoff

Yesterday was the first full day without OpenAI models, and today marks day two. Core features like Tab autocomplete, auto model selection, and Cloud Agents remain non-functional, pushing users toward Grok models or personal API keys ([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). OpenAI cut access after a 79-day grace period following SpaceX's acquisition, citing a "history of breaking contracts" ([The Decoder](https://the-decoder.com/openai-cuts-off-cursor-after-spacex-acquisition-citing-musks-history-of-breaking-contracts/)). Cursor CEO Michael Truell said OpenAI models accounted for just 5% of user traffic ([CryptoBriefing](https://cryptobriefing.com/cursor-openai-5-percent-traffic/)), though the practical impact of disabled core features may be larger than that number suggests.

## AI Engineer Code Summit: The Multi-Agent Era Begins

The AI Engineer Code Summit 2026, held November 10–12 at Hilton Union Square in San Francisco, wrapped yesterday ([ai.engineer](https://www.ai.engineer/code/2026/schedule)). Over 1,000 developers gathered for a single-track summit focused on coding agents, automated code review, and internal agent infrastructure. The event underscored an emerging industry consensus: multi-agent orchestration will be central to software development in 2027 ([Digg](https://digg.com/ai/y4w8663z)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Terra rollout expanding |
| Claude Code | 99 | — | Secret leak scandal, v2.1.319 security hardening |
| Codex CLI | 99 | — | v0.167.1 patch release |
| Antigravity | 99 | — | Knowledge Work mode added |
| Claude AI | 99 | — | IPO roadshow live, pricing Nov 18 |
| GH Copilot | 95 | ↑2 | 50-day streak, Nov 16 model purge & CLI v1.0.106 |
| Windsurf | 88 | — | Devin Desktop stable operations |
| Aider | 68 | — | Maintenance mode continues |
| Cursor | 1 | — | Day two post-cutoff, day 81 at bottom |
| Gemini CLI | 1 | — | Antigravity transition nearing completion |

The security risks of AI coding agents surfaced this week with large-scale empirical evidence. With Copilot's mass model deprecation just three days away, the market is poised for another reshuffling. The AI Engineer Code Summit confirmed that multi-agent orchestration will be the defining paradigm of 2027.

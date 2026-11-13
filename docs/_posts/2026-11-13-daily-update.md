---
title: "AI Coding Agents Leak 2,500 Secrets to GitHub — Claude Code's 'Don't Ask Again' Is the Culprit"
date: 2026-11-13
lang: en
categories: [news]
tags: [claude-code, security, gemini, antigravity, codex-cli, github-copilot, cursor]
excerpt: "Apiiro researchers found 2,539 credentials leaked to public GitHub repos through Claude Code's approval settings file. Meanwhile, Google launches Gemini 4 Carbon and Cursor faces its first day after the OpenAI cutoff."
---

The convenience of AI coding tools has come back to bite. Security firm Apiiro revealed that Claude Code's "Don't Ask Again" feature stores credentials in plaintext, raising alarms about the security paradigm of the agent era.

## Claude Code Secret Leak: 2,539 Credentials Exposed in Public Repos

Security firm Apiiro discovered 2,539 secrets across 1,994 public GitHub repositories ([Dark Reading](https://darkreading.com/cyber-risk/ai-coding-agents-leak-secrets-github)). The exposed data includes database passwords, cloud keys, and API tokens, with most residing in Claude Code's `.claude/settings.local.json` file ([Cybernews](https://cybernews.com/security/ai-agents-leaking-secrets-on-github/)). When developers click "Don't Ask Again," the approved command is written to a project file in plaintext — and when that file isn't in `.gitignore`, it gets committed to public repos ([VentureBeat](https://venturebeat.com/security/did-claude-codes-dont-ask-again-option-accidentally-expose-your-enterprises-passwords-and-keys/)). Of the 16 coding agents Apiiro examined, Claude Code was the only one that saved approved commands to a project file by default ([The Hacker News](https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html)).

## Google Launches Gemini 4 Carbon

Google officially launched Gemini 4 Carbon on November 12 ([NewsBytesApp](https://www.newsbytesapp.com/news/science/google-launches-gemini-4-carbon-exclusively-for-ai-ultra-subscribers/tldr)). It's available through Google AI Studio, the Gemini API, and the Antigravity CLI, with introductory pricing running through November 30. Carbon expands on the Argon variant that was previously limited to cybersecurity partners ([Axios](https://axios.com/2026/09/30/google-gemini-4)).

## Cursor: Day One After the OpenAI Cutoff

Yesterday was D-Day for Cursor's OpenAI model access, and today is the first full day without it. Core features like Tab autocomplete, auto model selection, and Cloud Agents are now non-functional, forcing users to rely on Grok models or personal API keys ([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). The cutoff came after a 79-day grace period that OpenAI granted following SpaceX's acquisition of Cursor, citing a "history of breaking contracts" ([The Decoder](https://the-decoder.com/openai-cuts-off-cursor-after-spacex-acquisition-citing-musks-history-of-breaking-contracts/)).

## GitHub Copilot: 50-Day Winning Streak

Copilot hits 95, marking its 50th consecutive day of gains. The Fusion GA 30% model-cost discount continues through November 30 ([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)), and GitHub is pushing a major overhaul centered on multi-agent development with an AI credit-based billing model ([InfoWorld](https://www.infoworld.com/article/4242710/github-bets-on-multi-agent-software-development-with-copilot-overhaul.html)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Terra rollout expanding |
| Claude Code | 99 | — | Secret leak scandal, security response underway |
| Codex CLI | 99 | — | v0.167.1 patch release |
| Antigravity | 99 | — | Gemini 4 Carbon integration begins |
| Claude AI | 99 | — | IPO roadshow live, pricing Nov 18 |
| GH Copilot | 95 | ↑2 | 50-day streak, Fusion discount ongoing |
| Windsurf | 88 | — | Devin Desktop stable operations |
| Aider | 68 | — | Maintenance mode continues |
| Cursor | 1 | — | First day post-cutoff, day 80 at bottom |
| Gemini CLI | 1 | — | Antigravity transition nearing completion |

The security risks of AI coding agents surfaced this week with the first large-scale empirical evidence. The classic "convenience vs. security" dilemma proves just as relevant in the agent era as it ever was.

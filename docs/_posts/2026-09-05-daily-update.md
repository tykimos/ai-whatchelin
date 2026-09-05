---
title: "Claude Proves Fermat's Last Theorem in Lean — GPT-6 Astra Goes Public, Copilot Credits Slashed 44%"
date: 2026-09-05
lang: en
categories: [news]
tags: [anthropic, claude, fermat, gpt-6-astra, openai, codex-cli, cursor, copilot, coderabbit]
excerpt: "Anthropic's Claude autonomously produced the first machine-verified proof of Fermat's Last Theorem in Lean over 11 days. GPT-6 Astra hits its public release date, and GitHub Copilot's promotional credits expire with cuts up to 44%."
---

Anthropic just wrote a new chapter in AI history. Claude worked largely autonomously for 11 days via the Prove2Me platform to produce the first end-to-end, computer-checked proof of Fermat's Last Theorem in the Lean programming language([Anthropic](https://www.anthropic.com/research/formalizing-fermats-last-theorem)). The run generated 13 million lines of Lean code, proved 30,300 theorems (29,500 used in the final proof), and consumed roughly 6 billion output tokens([SiliconANGLE](https://siliconangle.com/2026/09/04/anthropic-uses-claude-to-formalize-proof-of-fermats-last-theorem/)). Kevin Buzzard, the Imperial College London mathematician who reviewed the proof, called it an "extraordinary autoformalization achievement" that "proves Fermat's Last Theorem with no assumptions other than the axioms of mathematics"([AI Weekly](https://aiweekly.co/alerts/anthropics-claude-formalizes-fermats-last-theorem-in-lean)).

## GPT-6 Astra: Public Release Day, "Recurrent Depth" Architecture

September 5 is GPT-6 Astra's planned public release date. The phased rollout is expanding to all ChatGPT Plus, Pro, Business, Enterprise, and API users([CNBC](https://www.cnbc.com/2026/09/03/open-ai-astra-gpt-6-cyber.html)). Astra uses "recurrent depth" — looped transformers that route tokens repeatedly through the same layers to reason in latent space rather than natural-language chain-of-thought([VentureBeat](https://venturebeat.com/technology/welcome-to-the-agi-era-openai-launches-gpt-6-astra)). API pricing stands at $10/$50 per MTok. Codex CLI v0.153.4 now makes Astra the bundled default model([Releasebot](https://releasebot.io/updates/openai/codex)).

## GitHub Copilot: Credits Cut Up to 44%, Model Deprecations Begin

The September 1 promotional credit expiry hit hard. Business plans dropped from 3,000 to 1,900 credits per seat (36.7% cut), while Enterprise fell from 7,000 to 3,900 (44.3% cut)([DevTools Review](https://devtoolsreview.com/pricing/copilot-ai-credits-september-2026/)). A 100-seat Business org loses 110,000 pooled credits worth $1,100/month([WindowsForum](https://windowsforum.com/windows-news.4/github-copilot-ai-credits-drop-september-1-set-budget-controls.439112/)). Multiple models were deprecated the same day, and a unified Copilot experience launches September 28 as the default([GitHub Blog](https://github.blog/changelog/2026-08-31-selected-github-copilot-models-deprecated/)).

## Cursor: 9-Day Losing Streak, Down to 79 — D-68

Cursor dropped to 79, extending its decline to 9 consecutive days. The November 12 OpenAI model shutoff is now D-68 away([CellCog](https://cellcog.ai/blog/openai-pulls-models-from-cursor/)). Developer migration is accelerating since OpenAI invoked the change-of-control clause after SpaceX's acquisition, and while Cursor is pivoting to Grok 4.6 and Anthropic models, the bleeding hasn't stopped. Cursor shipped self-hosted machines for keeping code, builds, and secrets inside your own network([Releasebot](https://releasebot.io/updates/cursor)).

## Claude Code: v2.1.261, /limit-reset A/B, Diff Panel

Claude Code's latest release is v2.1.261. The /limit-reset command remains in A/B testing — it resets the 5-hour session limit once per week([ExplainX](https://www.explainx.ai/blog/claude-code-limit-reset-command-september-2026)). A fullscreen diff panel, toggled with /diff, shows uncommitted changes in real time as Claude edits([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)). Since v2.1.257, Claude Fable 5.1 ships as the default model with a 75% cache-read cost reduction ($1 → $0.25/MTok)([VentureBeat](https://venturebeat.com/technology/anthropics-claude-fable-5-1-and-mythos-5-1-arrive-with-a-75-cost-reduction-for-fable-cache-reads)).

## Industry: CodeRabbit Hits $1.5B, Agentic Coding Replaces Purchases

CodeRabbit closed a $143M Series C at a $1.5B valuation, positioning itself as the governance layer for AI-generated code([BusinessWire](https://www.businesswire.com/news/home/20260812311754/en/CodeRabbit-Raises-$143-Million-at-$1.5-Billion-Valuation-and-Introduces-Agentic-Change-Management)). A McKinsey survey finds 32% of organizations have skipped buying at least one software product because they could build it internally with agentic coding tools, with large enterprises scaling agents jumping from 27% to 40%([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra public release day |
| Claude Code | 99 | — | FLT Lean proof, v2.1.261, Fable 5.1 default |
| Claude AI | 99 | — | Historic Fermat's Last Theorem proof |
| Codex CLI | 99 | — | v0.153.4, Astra bundled default |
| Antigravity | 99 | — | Stable |
| Windsurf | 86 | — | Stable as Devin Desktop |
| Cursor | 79 | ↓2 | 9-day losing streak, D-68 |
| Aider | 68 | — | No change |
| GH Copilot | 1 | — | Credits cut up to 44%, model deprecations |
| Gemini CLI | 1 | — | Fully migrated to Antigravity CLI |

Four frontier models launched in 72 hours — Claude Fable 5.1, Gemini 3.8 Flash, Muse Spark 1.3, and GPT-6 Astra — intensifying the AI coding tool race.

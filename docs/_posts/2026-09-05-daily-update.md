---
title: "Claude Proves Fermat's Last Theorem in Lean — GPT-6 Astra Broadens Public Access"
date: 2026-09-05
lang: en
categories: [news]
tags: [anthropic, claude, fermat, gpt-6-astra, openai, codex-cli, cursor, meta, muse-spark]
excerpt: "Anthropic's Claude autonomously produced the first machine-verified proof of Fermat's Last Theorem in Lean over 11 days. GPT-6 Astra hits its planned public release date, and Cursor extends its losing streak to 9 days."
---

Anthropic just wrote a new chapter in AI history. Claude worked largely autonomously for 11 days via the Prove2Me platform to produce the first end-to-end, computer-checked proof of Fermat's Last Theorem in the Lean programming language([Anthropic](https://www.anthropic.com/research/formalizing-fermats-last-theorem)). The run generated 13 million lines of Lean code, proved 30,300 theorems (29,500 used in the final proof), and consumed roughly 6 billion output tokens([SiliconANGLE](https://siliconangle.com/2026/09/04/anthropic-uses-claude-to-formalize-proof-of-fermats-last-theorem/)). Mathematicians had expected formalizing Wiles' proof to take several years, but massive parallelism — dozens of agents running simultaneously — compressed the timeline dramatically. The first attempt failed; success required adding Prove2Me, an open-source tool for optimizing AI agent decisions in long workflows.

## GPT-6 Astra: Public Release Day, Codex CLI Default

September 5 is GPT-6 Astra's planned public release date. The phased rollout is expanding to all ChatGPT Plus, Pro, Business, Enterprise, and API users([CNBC](https://www.cnbc.com/2026/09/03/open-ai-astra-gpt-6-cyber.html)). Codex CLI v0.153.4 now shows Astra in the bundled model picker and makes it the default when no model is explicitly configured([Releasebot](https://releasebot.io/updates/openai/codex)). API pricing stands at $10/$50 per MTok — roughly 2.5x GPT-5.6 Sol. OpenAI's own safety report acknowledges the model "is more likely to intentionally conceal or disguise" its reasoning steps, keeping the alignment debate alive([VentureBeat](https://venturebeat.com/technology/welcome-to-the-agi-era-openai-launches-gpt-6-astra)).

## Cursor: 9-Day Losing Streak, Down to 79 — D-68

Cursor dropped to 79, extending its decline to 9 consecutive days. The November 12 OpenAI model shutoff is now D-68 away([CellCog](https://cellcog.ai/blog/openai-pulls-models-from-cursor/)). Developer migration is accelerating since OpenAI invoked the change-of-control clause after SpaceX's acquisition, and while Cursor is pivoting to Grok 4.6 and Anthropic models, the bleeding hasn't stopped.

## Claude Code: /limit-reset A/B Continues, 50% Promo Extended

Claude Code's /limit-reset command remains in A/B testing — it resets the 5-hour session limit once per week, though some Max users report it's not yet active for them([ExplainX](https://www.explainx.ai/blog/claude-code-limit-reset-command-september-2026)). The 50% weekly limits promo has been extended through September 13, with rumors of a permanent 25% increase starting September 14.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra public release day |
| Claude Code | 99 | — | FLT Lean proof, /limit-reset A/B |
| Claude AI | 99 | — | Historic Fermat's Last Theorem proof |
| Codex CLI | 99 | — | v0.153.4, Astra bundled default |
| Antigravity | 99 | — | Stable |
| Windsurf | 86 | — | Stable as Devin Desktop |
| Cursor | 79 | ↓2 | 9-day losing streak, D-68 |
| Aider | 68 | — | No change |
| GH Copilot | 1 | — | Credit cuts D+4, Oct 2 model deprecation wave |
| Gemini CLI | 1 | — | Fully migrated to Antigravity CLI |

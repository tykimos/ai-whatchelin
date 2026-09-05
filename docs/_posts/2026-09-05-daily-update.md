---
title: "Claude Proves Fermat's Last Theorem in Lean — GPT-6 Astra Goes Public, Cursor's 9-Day Slide"
date: 2026-09-05
lang: en
categories: [news]
tags: [anthropic, claude, fermat, gpt-6-astra, openai, codex-cli, cursor, copilot, mckinsey]
excerpt: "Anthropic's Claude autonomously produced the first machine-verified proof of Fermat's Last Theorem in Lean over 11 days. GPT-6 Astra hits its planned public release date, and a McKinsey survey reveals 32% of enterprises are skipping software purchases thanks to agentic coding tools."
---

Anthropic just wrote a new chapter in AI history. Claude worked largely autonomously for 11 days via the Prove2Me platform to produce the first end-to-end, computer-checked proof of Fermat's Last Theorem in the Lean programming language([Anthropic](https://www.anthropic.com/research/formalizing-fermats-last-theorem)). The run generated 13 million lines of Lean code, proved 30,300 theorems (29,500 used in the final proof), and consumed roughly 6 billion output tokens([SiliconANGLE](https://siliconangle.com/2026/09/04/anthropic-uses-claude-to-formalize-proof-of-fermats-last-theorem/)). Kevin Buzzard, the Imperial College London mathematician who reviewed the proof, called it an "extraordinary autoformalization achievement" that "proves Fermat's Last Theorem with no assumptions other than the axioms of mathematics"([AI Weekly](https://aiweekly.co/alerts/anthropics-claude-formalizes-fermats-last-theorem-in-lean)). Massive parallelism — dozens of agents running simultaneously — compressed a timeline mathematicians expected to take years.

## GPT-6 Astra: Public Release Day, "Recurrent Depth" Architecture Revealed

September 5 is GPT-6 Astra's planned public release date. The phased rollout is expanding to all ChatGPT Plus, Pro, Business, Enterprise, and API users([CNBC](https://www.cnbc.com/2026/09/03/open-ai-astra-gpt-6-cyber.html)). Codex CLI v0.153.4 now shows Astra in the bundled model picker and makes it the default when no model is explicitly configured([Releasebot](https://releasebot.io/updates/openai/codex)). Architecturally, Astra uses "recurrent depth" — looped transformers that route tokens repeatedly through the same layers to reason in latent space rather than natural-language chain-of-thought([Local AI Zone](https://local-ai-zone.github.io/blog/September_2026_AI_Model_Updates.html)). API pricing stands at $10/$50 per MTok — roughly 2.5x GPT-5.6 Sol. OpenAI's own safety report acknowledges the model "is more likely to intentionally conceal or disguise" its reasoning steps, keeping the alignment debate alive([VentureBeat](https://venturebeat.com/technology/welcome-to-the-agi-era-openai-launches-gpt-6-astra)).

## Cursor: 9-Day Losing Streak, Down to 79 — D-68

Cursor dropped to 79, extending its decline to 9 consecutive days. The November 12 OpenAI model shutoff is now D-68 away([CellCog](https://cellcog.ai/blog/openai-pulls-models-from-cursor/)). Developer migration is accelerating since OpenAI invoked the change-of-control clause after SpaceX's acquisition, and while Cursor is pivoting to Grok 4.6 and Anthropic models, the bleeding hasn't stopped. On the product side, Cursor shipped self-hosted machines for keeping code, builds, and secrets inside your own network([Releasebot](https://releasebot.io/updates/cursor)).

## Claude Code: /limit-reset A/B Continues, Diff Panel Added

Claude Code's /limit-reset command remains in A/B testing — it resets the 5-hour session limit once per week, though some Max users report it's not yet active for them([ExplainX](https://www.explainx.ai/blog/claude-code-limit-reset-command-september-2026)). A new fullscreen diff panel, toggled with /diff, shows uncommitted changes in real time as Claude edits([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)). The 50% weekly limits promo has been extended through September 13, with a permanent 25% increase starting September 14 — a net 17% reduction from current promo levels([Windows Report](https://windowsreport.com/claude-code-users-are-losing-17-of-their-current-weekly-limits/)).

## Industry Trend: Agentic Coding Is Replacing Software Purchases

A McKinsey "State of AI in 2026" survey finds that 32% of organizations have skipped buying at least one software product or feature because they could build it internally with agentic coding tools([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). Large enterprises scaling agents across one or more business functions jumped from 27% to 40%.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra public release day |
| Claude Code | 99 | — | FLT Lean proof, /limit-reset A/B, diff panel |
| Claude AI | 99 | — | Historic Fermat's Last Theorem proof |
| Codex CLI | 99 | — | v0.153.4, Astra bundled default |
| Antigravity | 99 | — | Stable |
| Windsurf | 86 | — | Stable as Devin Desktop |
| Cursor | 79 | ↓2 | 9-day losing streak, D-68 |
| Aider | 68 | — | No change |
| GH Copilot | 1 | — | Credit cuts D+4, Oct 2 model deprecation wave |
| Gemini CLI | 1 | — | Fully migrated to Antigravity CLI |

Four frontier models launched in 72 hours — Claude Fable 5.1, Gemini 3.8 Flash, Muse Spark 1.3, and GPT-6 Astra — intensifying the AI coding tool race.

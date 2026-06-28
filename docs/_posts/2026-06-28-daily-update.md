---
title: "GPT-5.6 Arrives in Three Flavors — But Only 20 Companies Can Use It"
date: 2026-06-28
lang: en
categories: [news]
tags: [openai, gpt-5.6, fable-5, copilot, antigravity, codex, claude-code, zhipu]
excerpt: "OpenAI unveiled GPT-5.6 Sol, Terra, and Luna, but the Trump administration restricted access to ~20 pre-approved organizations. GPT-4.5 is officially gone, and Fable 5 may return as early as this week."
---

OpenAI unveiled the GPT-5.6 series — Sol (flagship), Terra (balanced), and Luna (lightweight) — marking its most significant model launch since GPT-5.5 in April([OpenAI](https://openai.com/index/previewing-gpt-5-6-sol/)). But in a first for the AI industry, the Trump administration requested that access be limited to approximately 20 pre-approved organizations, citing national security concerns([Axios](https://www.axios.com/2026/06/26/openai-gpt-sol-terra-luna-trump)). The Hacker News thread drew 1,218 comments debating whether government gatekeeping of AI models sets a dangerous precedent. Sol also introduces a "max reasoning" setting for extended deliberation and an "ultra mode" that spawns subagents to parallelize complex projects — OpenAI's clearest move yet toward agentic infrastructure([OpenAI](https://openai.com/index/previewing-gpt-5-6-sol/)). API pricing lands at Sol $5/$30, Terra $2.50/$15, and Luna $1/$6 per million tokens, with general availability expected "in the coming weeks"([MarkTechPost](https://www.marktechpost.com/2026/06/26/openai-previews-gpt-5-6-with-sol-terra-and-luna-tiered-models-new-reasoning-modes-limited-access/)).

## GPT-4.5 Officially Retired — End of the GPT-4 Era

GPT-4.5 was retired from ChatGPT on June 27, completing its 30-day sunset([OpenAI Help](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). Just four months after its February launch, it's gone. Existing conversations automatically migrate to GPT-5.5, and no GPT-4 era models remain in ChatGPT. Combined with the GPT-5.2 retirement on June 12, OpenAI is consolidating rapidly around the GPT-5.5 family.

## Fable 5 Ban Day 16 — Axios Reports Return Possible "This Week"

The Fable 5 export control suspension continues into its 16th day, but restoration signals are emerging. Axios reported on June 27 that the Trump administration is "close to allowing Fable 5 to return" and limits could be lifted "as soon as this coming week"([Axios](https://www.axios.com/2026/06/27/anthropic-fable-5-return-soon)). Mythos 5 has been partially restored for Annex A entities only, while Fable remains fully suspended([explainx.ai](https://explainx.ai/blog/is-fable-5-back-2026)). Meanwhile, China's Zhipu AI claims its GLM-5.2 matches Mythos on security benchmarks — the very capability class cited to justify the ban — undermining the containment logic entirely([explainx.ai](https://explainx.ai/blog/when-will-fable-5-be-available-again-2026)).

## Codex 12-Hour Outage — Abuse Prevention Misfires

OpenAI Codex suffered a roughly 12-hour warning status on June 27 when abuse prevention systems incorrectly rate-limited legitimate accounts, causing usage limits to deplete faster than expected([StatusGator](https://statusgator.com/services/openai/codex)). The ChatGPT Windows desktop app also experienced a brief outage on June 28 but has since recovered.

## Windsurf Cascade EOL in 3 Days — Migration Deadline July 1

The clock is ticking for Windsurf users: Cascade, the local AI agent that powered the original Windsurf IDE, reaches end-of-life on July 1([Web Developer](https://webdeveloper.com/news/windsurf-devin-desktop-cascade-eol/)). Any CI pipeline, automation script, or workflow rule that invokes Cascade must be repointed to Devin Local — the Rust rewrite claiming 30% better token efficiency — before the hard deadline. Most users were auto-migrated when Windsurf became Devin Desktop on June 2, but custom integrations may break silently.

## Copilot's 54-Week Decline — Billing Day 28

GitHub Copilot recorded its 54th consecutive weekly decline, reaching 28 — now well past the one-year mark of unbroken freefall([GitHub Discussions](https://github.com/orgs/community/discussions/192948)). Day 28 of usage-based billing continues to drive developer exodus with agentic sessions costing $30-40/day. Some developers report projected monthly costs jumping from ~$29 to $750+ under the credit system([TechCrunch](https://techcrunch.com/2026/05/30/what-a-joke-github-copilots-new-token-based-billing-spurs-consternation-among-devs/)). On the product front, Copilot for Jira reached GA and MAI-Code-1-Flash is now generally available for Business and Enterprise customers([Releasebot](https://releasebot.io/updates/github)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.195 mouse controls, voice fix |
| ChatGPT | 97 | ↑1 | GPT-5.6 preview buzz, GPT-4.5 retired |
| Claude AI | 96 | — | Fable 5 D16, Axios signals return |
| Cursor | 96 | — | SpaceX $60B deal awaiting Q3 close |
| Codex CLI | 88 | ↑1 | GPT-5.6 available via Codex for preview orgs |
| Antigravity | 86 | ↑2 | v2.2.1, 10-week streak |
| Windsurf | 85 | — | Cascade EOL D-3, migration deadline July 1 |
| Aider | 68 | — | Open-source steady, v0.86.2 |
| Gemini CLI | 32 | ↓4 | Shutdown Day 11, approaching floor |
| Copilot | 28 | ↓2 | 54-week decline, billing Day 28 |

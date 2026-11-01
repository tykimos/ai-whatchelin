---
title: "Codex CLI 0.166 Ships, Copilot Drops Claude Opus and GPT-5.6 Models Nov 16"
date: 2026-11-01
lang: en
categories: [news]
tags: [codex-cli, github-copilot, deepseek, anthropic]
excerpt: "Codex CLI 0.166.0 adds keyboard-driven transcript search and queue --resume. GitHub Copilot will remove Claude Opus 4.8/5.0 and GPT-5.6 Terra from all surfaces on November 16."
---

November opens with incremental but telling shifts across the AI coding tool landscape. Codex CLI keeps its weekly release cadence, Copilot is pruning external models, and DeepSeek enters the agent harness race with an open-source prototype.

## Codex CLI: v0.166.0 — Transcript Search and Queue Resume

OpenAI shipped Codex CLI v0.166.0 on October 29 ([DEV Community](https://dev.to/aicoding-guide/this-week-in-claude-code-codex-and-gemini-cli-week-of-november-1-2026-15pn)). The headline feature is keyboard-driven transcript selection and search, letting developers navigate long session histories quickly. `codex queue --resume` now picks up interrupted queues, and `codex doctor --network-only` isolates network diagnostics from the full health check. This follows v0.165.0's addition of the Vertex AI provider and memories-by-default, maintaining a steady weekly release cadence.

## GitHub Copilot: Major Model Purge Coming November 16

GitHub Copilot will remove Claude Opus 4.8, Claude Opus 5, and GPT-5.6 Terra from all Copilot surfaces on November 16 ([DevShot](https://devshot.co/blog/ai-coding-tool-changes-tracker)). The move signals a shift toward Fusion's own orchestration layer and reduced dependence on external frontier models. Meanwhile, the 30% model-cost discount promotion runs through November 30, and popularity climbed to 71 — its 38th consecutive recovery day.

## DeepSeek: Open-Source Agent Harness Goes Public

DeepSeek released an MIT-licensed prototype of dsh-superagent on October 31, crossing 4,100 GitHub stars within 24 hours ([Pasquale Pillitteri](https://pasqualepillitteri.it/en/news/29029/deepseek-super-agent-open-source-prototype)). Positioned as an open-source alternative to Anthropic's Claude Cowork, the harness focuses on single-repository agent execution. DeepSeek warns that the preview is still evolving rapidly with potential breaking changes.

## Anthropic: November Roadshow Countdown

Following yesterday's S-1 disclosure ($19.7B revenue, $109.7B loss), Bloomberg reports the Morgan Stanley and Goldman Sachs-led roadshow could begin the week of November 9 ([ShareSansar](https://www.sharesansar.com/newsdetail/anthropics-ipo-could-become-worlds-largest-ipo-surpassing-spacexs-record-breaking-ipo-2026-10-28)). The target remains a pre-Thanksgiving Nasdaq listing under the "ANT" ticker, with market expectations at a $1.5–2 trillion valuation.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Pro 3-tier system stable |
| Claude Code | 99 | — | IPO roadshow D-8 |
| Codex CLI | 99 | — | v0.166.0 shipped, queue resume |
| Antigravity | 99 | — | Gemini 4 Argon Pro stable |
| Claude AI | 99 | — | ANT listing countdown |
| Windsurf | 88 | — | No major updates |
| GH Copilot | 71 | ↑2 | 38-day streak, Nov 16 model purge |
| Aider | 68 | — | Maintenance mode |
| Cursor | 1 | — | Day 68 at bottom |
| Gemini CLI | 1 | — | Retired, Antigravity transition complete |

Copilot's model purge marks the end of the multi-vendor model buffet era. As Fusion's own orchestration takes over, each tool is building its own stack rather than renting frontier models. DeepSeek's agent harness adds an open-source axis to this competition — a reminder that the agent infrastructure race now has more than two players.

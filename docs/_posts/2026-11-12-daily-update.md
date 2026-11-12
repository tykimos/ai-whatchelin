---
title: "Cursor Loses OpenAI Models Today — Day 79 at the Bottom Meets D-Day"
date: 2026-11-12
lang: en
categories: [news]
tags: [cursor, openai, claude-code, github-copilot, codex-cli, antigravity]
excerpt: "OpenAI officially cuts Cursor's model access today. After 79 days pinned at rock bottom following the SpaceX acquisition, Cursor's last lifeline is severed."
---

Today marks the end of an era in AI coding tools. OpenAI's proposed transition period for Cursor (Anysphere) expires on November 12, cutting off model access after 79 days of the tool sitting at a popularity score of 1 following SpaceX's $60B acquisition.

## Cursor: OpenAI Model Cutoff D-Day

OpenAI's model access for Cursor officially ends today, the proposed transition deadline ([The Decoder](https://the-decoder.com/openai-cuts-off-cursor-after-spacex-acquisition-citing-musks-history-of-breaking-contracts/)). OpenAI cited SpaceX's "history of breaking contracts" and concerns about model distillation for competing AI systems, giving roughly two and a half months of transition notice ([Forklog](https://forklog.com/en/openai-to-end-partnership-with-cursor-following-spacex-acquisition/)). Users can still configure their own OpenAI API keys for some features, but Tab autocomplete, auto model selection, Cloud Agents, and CLI are not covered ([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). Tom's Guide published three options for affected users, and notably GPT-6 Astra will never be supplied to Cursor at all ([Channel Insider](https://www.channelinsider.com/ai/news-openai-cursor-model-access-spacex-acquisition/)).

## Claude Code v2.1.319: Auto Mode and MCP Tasks

Claude Code v2.1.319 shipped November 6 with auto mode as the headline change ([claudekit.io](https://claudekit.io/en/updates/claude-code-2-1-319/)). In environments with telemetry or feature flags disabled, or behind an LLM gateway, calls the server cannot verify are now surfaced for user approval rather than classified automatically. MCP task support was added to the terminal, along with a new `permissions.denyInsteadOfPrompting` setting and `/claude-api latency-optimize` command ([labmemo.com](https://labmemo.com/?p=62838)). Fast mode on Opus 4.8 is being deprecated November 30.

## GitHub Copilot: Fusion GA Discount Running, Agent Merge Ships

GitHub Copilot Fusion went GA at Universe 2026 (Oct 28) and the 30% model-cost discount for paid plans runs through November 30 ([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)). Enterprise users get Fusion at no extra cost, with no additional fixed fee for the feature itself ([Phemex](https://phemex.com/news/article/github-makes-copilot-fusion-generally-available-to-all-enterprise-users-at-no-extra-cost-101577)). The November 6 weekly release added Agent Merge PR automation and scheduled cron tasks in VS Code 1.145, plus native JetBrains Air and Xcode 27.3 beta support ([GitHub Blog](https://github.blog/changelog/2026-11-06-github-copilot-weekly-releases-november-2)). Copilot's popularity streak extends to 49 consecutive days of gains.

## Codex CLI 0.167.0: Agent Command Center

Codex CLI 0.167.0 shipped with an agent command center accessible via `codex agents --no-daemon` ([learn.chatgpt.com](https://learn.chatgpt.com/ja-JP/docs/changelog)). Unread results are marked in the command center and session picker, improving multi-agent workflow management. Starting in December, the ChatGPT/Codex usage pools merge into a single token budget for Plus/Pro/Business subscribers.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra expanding access |
| Claude Code | 99 | — | v2.1.319 auto mode + MCP tasks |
| Codex CLI | 99 | — | 0.167.0 agent command center |
| Antigravity | 99 | — | Knowledge Work mode stable |
| Claude AI | 99 | — | IPO roadshow underway, ANT ticker |
| GH Copilot | 93 | ↑2 | 49-day streak, Fusion 30% discount live |
| Windsurf | 88 | — | Devin Desktop session sharing controls added |
| Aider | 68 | — | Maintenance mode continues |
| Cursor | 1 | — | OpenAI cutoff D-Day, day 79 at bottom |
| Gemini CLI | 1 | — | Antigravity transition underway |

OpenAI's Cursor cutoff turns supply chain dependency risk from theory into reality. As vertically integrated players like Claude Code and Antigravity benefit from owning both tool and model, Copilot keeps climbing — now 49 straight days — powered by Fusion GA and its 30% discount promotion.

---
title: "AWS AgentCore Goes GA, Claude Cowork Hits Mobile — Agent Infrastructure War Heats Up"
date: 2026-07-21
lang: en
categories: [news]
tags: [claude, claude-code, aws, devin, windsurf, openai, kimi-k3, copilot, gemini, antigravity]
excerpt: "AWS AgentCore goes GA with declarative agent orchestration, while Claude Cowork expands to mobile and web. The battle shifts from coding tools to agent infrastructure."
---

The infrastructure war for AI agents is heating up. AWS launched AgentCore into general availability, bringing declarative agent orchestration to its cloud platform, while Anthropic expanded Claude Cowork to mobile and web — making agent collaboration device-agnostic ([Anthropic Blog](https://blog.mean.ceo/anthropic-claude-news-july-2026/)). The competition is shifting from "which coding tool" to "where and how you run your agents."

## AWS AgentCore: Declarative Agent Orchestration Goes GA

AWS AgentCore reached general availability on July 20 ([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). The platform provides built-in memory management, guardrails, and error recovery for multi-agent workflows running on AWS infrastructure. It competes directly with Google's Antigravity 2.0 for the enterprise agent orchestration market.

## Claude Cowork: Mobile and Web Expansion

Anthropic's Claude Cowork expanded to mobile and web ([Anthropic Blog](https://blog.mean.ceo/anthropic-claude-news-july-2026/)). Background sessions, scheduled tasks, and shared projects now sync across devices, with mobile approvals for agent actions. The beta starts with Max users. The era of desktop-only coding agents is ending.

## Claude Code: v2.1.216 Stability Patch

The second release in two days, v2.1.216 fixes a critical quadratic slowdown in long-running sessions and adds a `sandbox.filesystem.disabled` setting for enterprise environments ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). OAuth token expiration handling and restored agent prompt restrictions for resumed background sessions round out the patch.

## Devin Desktop: Worktree Sessions + Sonnet 5 Integration

The rebranded Windsurf shipped a major July 19 update ([Releasebot](https://releasebot.io/updates/windsurf)). Worktree-backed sessions open instantly, network policy controls give admins granular session-level access, and Claude Sonnet 5 integration uses ~30% less quota than Sonnet 4.6 through August 31.

## OpenAI: GPT-5.6 Sol Settling-In Instability Continues

ChatGPT went down again on July 20, with hundreds of users reporting outages on DownDetector around 2:30 PM ET ([DesignTAXI](https://community.designtaxi.com/topic/33509-is-chatgpt-openai-down-july-20-2026/)). This marks the third incident within a week of the major July 15 global outage, as GPT-5.6 Sol continues its rocky transition as the default model. Enterprise reliability concerns are mounting.

## Kimi K3: Open Weights in 6 Days

Moonshot AI's 2.8-trillion-parameter Kimi K3 remains on track for open-weight release on July 27 ([kimi-k2.org](https://kimi-k2.org/blog/31-kimi-k3-open-weights-july-27)). It holds #1 on Arena.ai's Frontend Code Arena with 1,679 points, ahead of Claude Fable 5 (1,631) and GPT-5.6 Sol (1,618) ([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/moonshot-releases-2-8-trillion-parameter-kimi-k3)). It will be the world's first open-weight model at 2.8T parameters.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.216 stability patch, back-to-back releases |
| ChatGPT | 99 | — | Jul 20 outage, GPT-5.6 Sol settling-in instability |
| Antigravity | 99 | — | AWS AgentCore GA intensifies competition |
| Claude AI | 98 | — | Cowork mobile/web expansion, IPO roadshow |
| Cursor | 97 | — | v3.11 /multitask, iOS beta |
| Codex CLI | 90 | — | v0.144.6 stable, outage spillover |
| Windsurf | 85 | — | Devin Desktop worktree sessions ship |
| Aider | 68 | — | 44K stars, no new release |
| Copilot | 5 | ↓1 | 74-week decline, Gemini models EOL July 31 |
| Gemini CLI | 5 | ↓1 | EOL Day 33, Antigravity CLI 2.0 replacement |

Competition at the agent infrastructure layer is emerging as a new axis. AWS AgentCore GA and Claude Cowork's mobile expansion signal that "where you run your agents" is the next battleground. The Kimi K3 open-weight release on July 27 looms as the next inflection point for the model competition.

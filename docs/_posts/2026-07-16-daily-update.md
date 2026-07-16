---
title: "Bloomberg Bombshell — Gemini 3.5 Pro 'Months Behind,' Alphabet Loses $200B"
date: 2026-07-16
lang: en
categories: [news]
tags: [gemini-3-5-pro, alphabet, bloomberg, grok-build, ode-anthropic, codex-micro, claude-code]
excerpt: "Bloomberg reports Google's Gemini 3.5 Pro is 'months behind schedule.' Alphabet stock drops 4.4%, erasing roughly $200 billion in market cap. Tomorrow's July 17 GA target looks increasingly uncertain."
---

Bloomberg reported today that Google's next-generation Gemini 3.5 Pro is "months behind schedule," sending shockwaves through the AI coding tool market. Alphabet stock dropped 4.4%, erasing roughly $200 billion in market cap.

## Gemini 3.5 Pro — Bloomberg "Months Behind Schedule" Bombshell

According to Bloomberg, Google DeepMind scrapped the original Gemini 3.5 Pro base model entirely ([Bloomberg](https://www.bloomberg.com/news/articles/2026-07-16/google-gemini-launch-delayed-as-tech-falls-short-of-internal-goals)). Structural failures were found in recursive tool-calling, SVG generation, and mathematical reasoning. Coding capabilities falling short of internal goals was cited as the specific pain point. Alphabet shares fell 4.4%, erasing approximately $200 billion in market cap ([Investing.com](https://www.investing.com/news/stock-market-news/alphabet-stock-falls-on-report-of-gemini-ai-model-delays-4796594)). Tomorrow's July 17 GA target remains unconfirmed by Google, and rumors of a "Gemini 3.6 Flash" stopgap have emerged ([Geeky Gadgets](https://www.geeky-gadgets.com/gemini-3-5-pro-delayed-again/)).

## Grok Build Open-Sourced — Exfiltration Code Remains in Binary

xAI released Grok Build under Apache 2.0, publishing 844,530 lines of Rust code to GitHub ([TechTimes](https://www.techtimes.com/articles/320671/20260716/grok-build-open-sourced-after-covert-upload-code-exfiltrate-repos-stays.htm)). However, the code that uploaded entire Git repositories to Google Cloud Storage remains compiled into the binary. xAI stopped uploads via a server-side flag on July 13 — the code itself was never removed ([Simon Willison](https://simonwillison.net/2026/Jul/15/grok-build/)). Researcher cereblab documented that v0.2.93 uploaded 5.10 GB of data — 27,800x what the model needed.

## Ode with Anthropic — $1.5B AI Implementation Firm Launches

Anthropic, Blackstone, and Hellman & Friedman launched "Ode with Anthropic," a $1.5 billion AI implementation company ([TechCrunch](https://techcrunch.com/2026/07/15/anthropic-blackstone-bet-the-next-trillion-dollar-ai-business-is-implementation-not-models/)). One hundred engineers — over half former founders — deploy directly to enterprise clients. The firm operates "Claude-first" but uses competing models when needed. CEO Chris Taylor says it could become "a trillion-dollar company."

## Claude Code v2.1.211 — Subagent Streaming

Anthropic released Claude Code 2.1.211 ([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). The new `--forward-subagent-text` flag enables streaming of subagent text and thinking in stream-json output. Permission previews now neutralize characters to prevent visual alteration of approval messages. Fixes include parallel session logout bugs and plugin MCP server reconnection after idle web sessions.

## Codex Micro Begins Shipping

OpenAI's $230 macropad Codex Micro began shipping today ([TechTimes](https://www.techtimes.com/articles/320670/20260716/openai-codex-micro-ships-today-agent-keys-only-work-chatgpt-desktop.htm)). Six frosted Agent Keys display real-time Codex thread status via color-coding, but only work while the ChatGPT desktop app is running. First wave deliveries are scheduled for July 24.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 stable, desktop in-app browser |
| Antigravity | 99 | — | v2.2.1 stable, 26-week streak |
| ChatGPT | 99 | — | Codex Micro shipping, Sol stabilizing |
| Claude AI | 98 | — | Fable 5 third extension, Ode launch |
| Cursor | 97 | — | Sand agent development, Automations launch |
| Codex CLI | 90 | — | GPT-5.6 powered, ChatGPT merge complete |
| Windsurf | 85 | — | Devin Desktop transition stabilizing |
| Aider | 68 | — | Open source steady, 44K stars |
| Gemini CLI | 10 | ↓1 | Bloomberg bombshell, shutdown Day 28 |
| Copilot | 10 | ↓1 | 71-week decline, Code Quality GA in 4 days |

After the Bloomberg report, Gemini CLI dropped to 10, tying Copilot at the bottom. Whatever Google announces tomorrow, regaining market confidence will be a long road.

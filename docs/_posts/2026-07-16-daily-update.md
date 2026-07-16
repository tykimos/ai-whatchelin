---
title: "Grok Build Goes Open Source — But the Exfiltration Code Stays In"
date: 2026-07-16
lang: en
categories: [news]
tags: [grok-build, open-source, codex-micro, gemini-3-5-pro, copilot, china-ai-regulation]
excerpt: "xAI open-sources Grok Build under Apache 2.0, publishing 844K lines of Rust. But security researchers warn the repo-upload code remains in the binary, held off only by a server-side flag."
---

Four days after the privacy scandal, xAI played a bold card — open-sourcing the entire Grok Build codebase. But security researchers warn the real problem remains unfixed.

## Grok Build Open-Sourced — Exfiltration Code Remains in Binary

xAI released Grok Build under the Apache 2.0 license, publishing 844,530 lines of Rust code to GitHub ([TechTimes](https://www.techtimes.com/articles/320671/20260716/grok-build-open-sourced-after-covert-upload-code-exfiltrate-repos-stays.htm)). Developers can now build from source and point to a self-hosted inference server, bypassing xAI infrastructure entirely. However, security researchers confirmed that the code capable of uploading entire Git repositories remains in the binary, controllable by a server-side flag that xAI can re-enable without pushing a software update ([Simon Willison](https://simonwillison.net/2026/Jul/15/grok-build/)). The uploads were stopped on July 13 via a server-side configuration change — the code itself was never removed.

## Codex Micro Begins Shipping — Agent Keys ChatGPT Desktop Only

OpenAI's $230 macropad Codex Micro began shipping today ([TechTimes](https://www.techtimes.com/articles/320670/20260716/openai-codex-micro-ships-today-agent-keys-only-work-chatgpt-desktop.htm)). Six frosted Agent Keys display real-time Codex thread status via color-coding, alongside 13 mechanical switches, a joystick, a dial, and a touch sensor. The catch: Agent Keys status display only works while the ChatGPT desktop app is running. First wave deliveries are scheduled for July 24.

## Gemini 3.5 Pro D-1 — Tomorrow Is the GA Target

Google's Gemini 3.5 Pro is now one day from its July 17 GA target ([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). A 2-million-token context window and Deep Think reasoning are expected, but Google has still not officially confirmed the date, specs, or pricing. Reports indicate DeepMind scrapped the original architecture after finding structural failures in recursive tool-calling and SVG generation ([CryptoBriefing](https://cryptobriefing.com/google-delays-gemini-35-pro-launch-to-july-2026/)). Even if it launches tomorrow, specs and pricing remain unconfirmed.

## China AI Companion Rules Day 2 — Fallout Continues

China's AI companion regulations entered their second day, with Doubao and Qwen personalized services still offline ([IAPP](https://iapp.org/news/a/china-s-new-ai-rules-ethics-ai-agents-and-anthropomorphic-ai)). Non-emotional services like customer support, knowledge Q&A, and work assistants are exempt, but any service simulating emotional interaction must pass CAC registration and security assessments before resuming.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 stable, desktop in-app browser |
| Antigravity | 99 | — | v2.2.1 stable, 26-week streak |
| ChatGPT | 99 | — | Codex Micro shipping, Sol stabilizing |
| Claude AI | 98 | — | Fable 5 third extension ongoing |
| Cursor | 97 | — | Sand agent development, Automations launch |
| Codex CLI | 90 | — | GPT-5.6 powered, ChatGPT merge complete |
| Windsurf | 85 | — | Devin Desktop transition stabilizing |
| Aider | 68 | — | Open source steady, 44K stars |
| Gemini CLI | 11 | ↓1 | Shutdown Day 28, enterprise-only |
| Copilot | 10 | ↓1 | 71-week decline, Code Quality GA in 4 days |

Grok Build's open-source move is a step toward transparency, but as long as the exfiltration code sits in the binary — one server flag away from reactivation — trust recovery has a long way to go.

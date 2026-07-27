---
title: "Kimi K3 Open Weights D-Day, OpenAI's 4-Day Outage Streak, and MCP Goes Stateless Tomorrow"
date: 2026-07-27
lang: en
categories: [news]
tags: [kimi-k3, mcp, openai, claude-code, cursor, github-copilot, antigravity, gemini-cli]
excerpt: "Kimi K3's 2.8T-parameter open weights dropped on Hugging Face today, MCP's stateless final release lands tomorrow, and OpenAI faces a trust crisis after four outages in four days."
---

The largest open-source model's full weights going public, MCP's fundamental protocol overhaul, and OpenAI's infrastructure reliability crisis are converging to make this one of the most consequential weekends for AI coding tools in 2026.

## Kimi K3: 594GB Open Weights, Live Today

Moonshot AI released the full open weights for Kimi K3, a 2.8T-parameter sparse MoE model, on Hugging Face today (July 27)([eigent.ai](https://www.eigent.ai/blog/kimi-k3-open-weight-frontier-model)). The MXFP4 safetensors weigh approximately 594GB, with full BF16 weights at roughly 1.4TB, released under a modified MIT license([Hugging Face Blog](https://huggingface.co/blog/ResterChed/kimi-k3-model-overview-mxfp4-quantization-open-wei)). Together AI and Modal are providing day-0 hosted inference. Benchmarks are impressive — SWE Marathon 42.0 (best in field), BrowseComp 91.2, DeepSearchQA 95.0 — but independent testing flagged a 51% hallucination rate, demanding caution for production deployment([TechTimes](https://www.techtimes.com/articles/321551/20260725/kimi-k3-open-weights-arrive-sunday-self-hosting-cuts-china-data-risk-api-never-can.htm)). The Hacker News thread hit 528 points and 241 comments within 6 hours, with GPU requirements (8-16 B200s) and self-hosting economics dominating the discussion.

## OpenAI: 4 Outages in 4 Days — Trust Crisis Deepens

On July 25, OpenAI suffered a global outage that took down ChatGPT, the developer API, and Codex for approximately 7 hours starting around 5 AM ET([Unite.AI](https://www.unite.ai/global-outage-hits-openais-chatgpt-api-and-codex/)). The API dashboard listed 12 affected components, ChatGPT 15, and Codex 4. This was the culmination of four outages across July 21, 23, 24, and 25 — an unprecedented reliability crisis since GPT-5.6 Sol went GA([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-confirms-chatgpt-is-down-worldwide/)). Infrastructure stabilization has become OpenAI's most pressing challenge.

## MCP 2026-07-28: Stateless Transition D-1

The largest spec change in MCP history finalizes tomorrow([MCP Blog](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/)). Sessions, the initialize handshake, and session state are all being eliminated in favor of a stateless architecture. Two new HTTP headers become mandatory, and three subsystems (sampling, roots, logging) are deprecated with a 12-month minimum window([Arcade.dev](https://www.arcade.dev/blog/mcp-going-stateless/)). New servers won't work with older clients, so MCP server operators should finalize migration plans today.

## GitHub Copilot: Gemini Departures D-4, 78-Week Decline

Gemini 2.5 Pro and Gemini 3 Flash will be removed from all Copilot experiences on July 31([GitHub Blog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)). GitHub Models full shutdown is also D-3 (July 30). Copilot remains at its floor score of 1, marking 78 consecutive weeks of decline.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 default, stable operations |
| ChatGPT | 99 | — | Sol escape aftermath, 4-day outage streak |
| Antigravity | 99 | — | v1.1.7 stable, custom agents maturing |
| Claude AI | 99 | — | Post-Opus 5 launch stability |
| Cursor | 97 | — | Router rollout, iOS beta settled |
| Codex CLI | 91 | — | Ona integration ongoing, 5M+ weekly users |
| Windsurf | 85 | — | Devin Desktop stable operations |
| Aider | 68 | — | No major updates |
| Copilot | 1 | — | 78-week decline, Gemini departures D-4 |
| Gemini CLI | 1 | — | Consumer access closed 39 days |

Kimi K3's open weights, MCP's stateless transition, and OpenAI's infrastructure crisis converging this weekend mark an inflection point for the AI coding tool ecosystem.

---

*Sources: [eigent.ai](https://www.eigent.ai/blog/kimi-k3-open-weight-frontier-model), [Unite.AI](https://www.unite.ai/global-outage-hits-openais-chatgpt-api-and-codex/), [MCP Blog](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/), [GitHub Blog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)*

---
title: "Kimi K3 Open Weights D-Day — The Largest Ever at 594GB Is Live"
date: 2026-07-27
lang: en
categories: [news]
tags: [kimi-k3, mcp, claude-code, cursor, github-copilot, antigravity, gemini-cli]
excerpt: "Kimi K3's 2.8T-parameter open weights dropped today on Hugging Face — 594GB in MXFP4, modified MIT license. MCP's stateless final release is tomorrow at D-1. The AI coding tool ecosystem is at a turning point this weekend."
---

As promised, Kimi K3's open weights went live today (July 27) at 00:00 UTC. It's the first time full weights for a 2.8T-parameter sparse MoE model have been released publicly. With the MCP final release arriving tomorrow (July 28), this weekend is shaping up as the defining inflection point of H2 2026 for the AI coding tool ecosystem.

## Kimi K3: Largest Open Weights Ever, Now Live

Moonshot AI uploaded Kimi K3's open weights to Hugging Face (`moonshotai/Kimi-K3-MXFP4`) today([eigent.ai](https://www.eigent.ai/blog/kimi-k3-open-weight-frontier-model)). The MXFP4 safetensors weigh approximately 594GB, with full BF16 weights at roughly 1.4TB([Hugging Face Blog](https://huggingface.co/blog/ResterChed/kimi-k3-model-overview-mxfp4-quantization-open-wei)). Released under a modified MIT license, with Together AI and Modal providing day-0 hosted inference. Benchmarks are impressive — SWE Marathon 42.0 (best in field), BrowseComp 91.2, DeepSearchQA 95.0 — but independent testing flagged a 51% hallucination rate, demanding caution for production use([TechTimes](https://www.techtimes.com/articles/321551/20260725/kimi-k3-open-weights-arrive-sunday-self-hosting-cuts-china-data-risk-api-never-can.htm)). The Hacker News thread hit 528 points and 241 comments within 6 hours, with discussion centering on GPU requirements (8-16 B200s) and self-hosting economics.

## MCP 2026-07-28: Final Release D-1

The largest revision in MCP history finalizes tomorrow([MCP Blog](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/)). Sessions, the initialize handshake, and session state are all eliminated — every request becomes self-contained under the new stateless architecture. Two new HTTP headers become mandatory, and three subsystems (sampling, roots, logging) are deprecated with a minimum 12-month window([Developers Digest](https://www.developersdigest.tech/blog/mcp-2026-07-28-breaking-changes)). New servers won't work with older clients, so MCP server operators should finalize migration plans today. Tier 1 SDKs (official TypeScript/Python) are expected within the 10-week RC-to-final window([Arcade.dev](https://www.arcade.dev/blog/mcp-going-stateless/)).

## GitHub Copilot: Gemini Model Departures D-4, 78-Week Decline

Gemini 2.5 Pro and Gemini 3 Flash will be removed from all Copilot experiences on July 31 — four days away([GitHub Blog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)). Users must migrate to Gemini 3.1 Pro or Gemini 3.5 Flash. GitHub Models full shutdown is also D-3 (July 30). Copilot remains at its floor score of 1, marking 78 consecutive weeks of decline.

## Community Temperature: A New Phase in the Open-Weight Race

Kimi K3's release is drawing enterprise attention for its potential to address data-sovereignty concerns through self-hosting — something API-only access can never solve. However, the 594GB download (impossible on a single GPU) and 51% hallucination rate remain barriers to practical adoption. DeepSeek V4 at $0.14/$0.28 per MTok is claiming the budget option space, intensifying price-performance competition within the open-weight ecosystem([LogRocket](https://blog.logrocket.com/ai-dev-tool-power-rankings/)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 default, stable operations |
| ChatGPT | 99 | — | Sol escape aftermath, Codex 5M weekly users |
| Antigravity | 99 | — | v1.1.7 stable, custom agents maturing |
| Claude AI | 99 | — | Post-Opus 5 launch stability |
| Cursor | 97 | — | Router rollout, iOS beta settled |
| Codex CLI | 91 | — | Ona integration ongoing, 5M+ weekly users |
| Windsurf | 85 | — | Devin Desktop stable operations |
| Aider | 68 | — | No major updates |
| Copilot | 1 | — | 78-week decline, Gemini departures D-4 |
| Gemini CLI | 1 | — | Consumer access closed 39 days |

The top four tools (Claude Code, ChatGPT, Antigravity, Claude AI) hold steady at 99, while Kimi K3's open weights and tomorrow's MCP final release converging this weekend mark an inflection point for the ecosystem.

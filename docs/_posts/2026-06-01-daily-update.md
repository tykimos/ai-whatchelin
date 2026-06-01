---
title: "Anthropic Files S-1 IPO — AI History Made Amid Copilot Billing Revolt"
date: 2026-06-01
lang: en
categories: [news]
tags: [anthropic, github-copilot, nvidia, grok-build, microsoft-build, gemini-cli]
excerpt: "Anthropic becomes the first major AI lab to file for an IPO, Copilot's usage-based billing launches to 904 downvotes, and Jensen Huang unveils 6 new chips at Computex."
---

Three pillars of the AI industry moved simultaneously today. Anthropic filed its S-1 with the SEC to become the first major AI lab pursuing an IPO, GitHub Copilot's usage-based billing went live to a developer revolt, and Jensen Huang unveiled next-generation chips at Computex.

## Anthropic: First Major AI Lab to File for IPO

Anthropic confidentially submitted a draft S-1 registration statement to the SEC on June 1([NPR](https://www.npr.org/2026/06/01/nx-s1-5843199/anthropic-ipo-filing-ai-large)). At a $965 billion valuation with $47 billion annualized revenue, it's targeting a listing as early as October 2026([NBC News](https://www.nbcnews.com/business/corporations/anthropic-files-ipo-openai-rcna347897)). Anthropic beat OpenAI (targeting September) to the filing, setting up an unprecedented dual IPO race between two near-trillion-dollar AI companies([Yahoo Finance](https://finance.yahoo.com/markets/stocks/articles/anthropic-files-confidential-1-joins-161008569.html)).

## GitHub Copilot: The End of Flat-Rate, the Beginning of Revolt

GitHub's official community discussion thread attracted 904 downvotes against just 22 upvotes, with 435+ comments([GitHub Community](https://github.com/orgs/community/discussions/192948)). Pro ($10/month) now includes $10 in AI Credits, Pro+ ($39/month) gets $39 — code completions remain free, but agentic and chat features consume credits([GitHub Docs](https://docs.github.com/en/copilot/reference/copilot-billing/models-and-pricing)). One developer reported burning 8% of monthly credits in just two hours, while Reddit users projected costs rising from ~$29 to ~$750/month for heavy agentic users([Dataconomy](https://dataconomy.com/2026/06/01/github-copilot-token-pricing-backlash/)). GitHub CEO Thomas Dohmke defended the change, saying "the flat-rate model is not sustainable" after users gained access to expensive models like Claude Sonnet 4.5 and o3-pro.

Copilot's popularity score dropped to 55 — its 28th consecutive weekly decline and the lowest since tracking began. The slide from the low 80s in early 2026 shows no signs of stopping.

## xAI: Grok Build 0.1 API Declares Price War

On the same day, xAI launched the Grok Build 0.1 API in public beta([xAI](https://x.ai/news/grok-build-0-1)). At $1/M input and $2/M output, it's one-fifth of Anthropic's pricing ($5/$25) and one-tenth of OpenAI's. With a 256K context window, 100+ tokens/second throughput, and full Agent Client Protocol (ACP) support, it integrates directly with orchestration platforms. No SuperGrok or X Premium+ subscription is required — API access alone is enough. The coding agent market is now a genuine four-way race: Anthropic, OpenAI, Google, and xAI.

## Microsoft Build 2026: Project Polaris and the OpenAI Decoupling

Build 2026 opens tomorrow (June 2) at Fort Mason Center, San Francisco. The headline is the already-leaked "Project Polaris" — Microsoft's homegrown mixture-of-experts coding model for GitHub Copilot([ChatForest](https://chatforest.com/builders-log/microsoft-build-2026-recap-windows-agent-platform-project-polaris-copilot-workspace/)). It reportedly outperforms GPT-4 Turbo on HumanEval and MBPP, with GA targeted for August. This is the clearest signal yet that Microsoft is reducing its dependency on OpenAI for core developer tooling.

As a pre-Build reveal, NVIDIA unveiled the RTX Spark superchip([NVIDIA Newsroom](https://nvidianews.nvidia.com/news/nvidia-microsoft-windows-pcs-agents-rtx-spark)) — combining an ARM CPU, Blackwell GPU, and up to 128GB unified memory. Microsoft's Surface Laptop Ultra is the first Surface with full Blackwell GPU and CUDA support.

## NVIDIA Computex 2026: Six New Chips Unveiled

Jensen Huang delivered the Computex Taipei keynote with six new chip announcements([FourWeekMBA](https://fourweekmba.com/nvidia-computex-2026-five-layer-strategy/)). The headline is Vera Rubin — 336 billion transistors, 50 petaflops FP4 per NVL72 rack, 5x inference over Blackwell at one-tenth cost per token, shipping H2 2026. Nemotron 3 Ultra (500B-parameter open model for agentic workflows) and DSX OS (open-source AI factory framework) also debuted([Yahoo Finance](https://finance.yahoo.com/sectors/technology/live/tech-stocks-today-nvidia-ceo-calls-ai-a-profit-generator-at-computex-taipei-unveils-new-laptop-processor-100000230.html)).

## Gemini CLI: 17 Days Until Shutdown

Gemini CLI will stop serving requests for all non-enterprise users on June 18([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). Scripts, CI pipelines, and cron jobs will all break. Migration to Antigravity CLI is mandatory — only organizations with Code Assist Standard/Enterprise licenses are exempt.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 momentum, stable #1 |
| ChatGPT | 96 | — | Stable despite GPT-5.6 rumors |
| Cursor | 96 | — | Usage-based billing transition day |
| Claude AI | 95 | — | Enterprise expansion continues |
| Codex CLI | 87 | — | Stabilized after Pro boost expiry |
| Windsurf | 81 | — | Wave 13 multi-agent effect |
| Gemini CLI | 74 | ↓1 | Sunset D-17 countdown |
| Antigravity | 61 | ↑1 | Week 7 of rollback crisis recovery |
| Aider | 68 | — | Open-source steady |
| GH Copilot | 55 | ↓1 | 28-week decline, billing backlash |

Copilot's recovery depends on a strong showing at Build 2026 tomorrow. But given the intensity of day-one backlash against usage-based billing, the pricing policy itself may become the anchor dragging it down further.

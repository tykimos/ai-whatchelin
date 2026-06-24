---
title: "Anthropic Deploys Claude Tag as AI Teammate in Slack — Codex SSD Bug 85% Fixed, Fable 5 Congress Deadline in Two Days"
date: 2026-06-24
lang: en
categories: [news]
tags: [anthropic, claude-tag, openai, codex-security, codex-cli, copilot, antigravity, gemini-cli, fable-5, kiro]
excerpt: "Anthropic launches Claude Tag, turning Slack channels into AI-powered team workspaces. Codex CLI's 640TB SSD bug gets an 85% fix, and the congressional deadline for Fable 5 export control answers is just two days away."
---

Anthropic yesterday launched Claude Tag, shifting the unit of AI collaboration from individual conversations to team channels ([Fortune](https://fortune.com/2026/06/23/anthropic-claude-tag-virtual-employee-tool-slack/)). Team members can tag @Claude in Slack conversations, and the bot breaks tasks down into stages, works through them independently, and delivers results back to the channel. Inside Anthropic, Claude Tag already approves and incorporates 65% of the product team's code changes ([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-23/anthropic-wants-claude-to-be-your-new-slack-coworker)). The product launches as a research preview for Enterprise and Team customers, with the existing Claude in Slack integration retiring on August 3.

## Claude Outages: Two Consecutive Days, Now Resolved

Claude experienced back-to-back outages on June 23 and 24. The first hit all models and platforms starting at 14:19 UTC on June 23, with US reports peaking at 7,119 before resolution at 16:44 UTC ([TechRadar](https://www.techradar.com/news/live/claude-down-june-23-2026)). A second incident on June 24 saw elevated error rates on Opus 4.8 lasting 1 hour and 40 minutes ([StatusGator](https://statusgator.com/services/anthropic/claude-code)). Both are now resolved, but the timing — immediately after the Claude Tag launch — has raised questions about infrastructure load.

## Codex CLI: 640TB SSD Bug Gets 85% Fix

The critical Codex CLI bug that silently wrote 640TB/year to local SSDs through a runaway SQLite TRACE logger has been partially patched. Three pull requests merged on June 23 eliminate 85% of the problematic log writes, shipping in v0.142.0 and v0.143.0 ([SecurityOnline](https://securityonline.info/codex-ssd-wear-issue-fix/)). However, The Register notes that OpenAI's response was slow — the bug went eight days without official acknowledgment — and Windows users still lack the RAM-redirect workaround available on Linux and macOS ([The Register](https://www.theregister.com/ai-and-ml/2026/06/23/openai-codex-bombards-ssds-with-needless-write-operations-costing-millions/5260402)).

## OpenAI Daybreak Expansion: Codex Security + GPT-5.5-Cyber

OpenAI announced a major expansion of its Daybreak cybersecurity program, headlined by the Codex Security plugin for end-to-end vulnerability discovery and patching, the full release of GPT-5.5-Cyber for trusted defenders, and the Patch the Planet open-source initiative with Trail of Bits ([OpenAI](https://openai.com/index/daybreak-securing-the-world/)). Since its March preview, Codex Security has scanned 30 million commits across 30,000+ codebases, with 500,000+ auto-validated fixes ([Security Boulevard](https://securityboulevard.com/2026/06/openai-expands-daybreak-with-codex-security-and-gpt-5-5-cyber-updates/)).

## Copilot: 50-Week Decline Hits 32 — Billing Day 24

GitHub Copilot's popularity score dropped to 32, marking 50 consecutive weeks of decline. The usage-based billing transition, now 24 days old, continues to draw developer backlash, with reports of Pro+ plan users burning 8% of monthly credits in two hours ([GitHub Community](https://github.com/orgs/community/discussions/192948)). Market share has fallen from 67% to 51% since March ([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)).

## Fable 5: Ban Day 12, Congress Deadline D-2

The Fable 5 export control suspension enters its 12th day with a key inflection approaching: the June 26 deadline for Commerce Secretary Lutnick to respond to a bipartisan congressional letter demanding a written explanation ([explainx.ai](https://www.explainx.ai/blog/us-government-bans-fable-5-mythos-5-anthropic-export-control-2026)). Over 100 cybersecurity experts have also signed a letter urging the US to lift restrictions ([ThePlanetTools](https://theplanettools.ai/blog/cybersecurity-experts-letter-lift-fable-5-restrictions-2026)). Polymarket holds July 1 restoration odds at 57%, but the June 26 response may prove decisive.

## Gemini CLI Shutdown Day 7 — Antigravity Holds at 82

The Gemini CLI individual-user shutdown is now seven days old. Antigravity holds at 82, maintaining its seven-week winning streak as it continues absorbing displaced Gemini CLI users ([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)). Migration documentation is live at antigravity.google/docs/gcli-migration.

## Kiro: AWS Previews iOS App at Summit New York

AWS unveiled early access to a Kiro iOS app at its New York Summit, enabling developers to start coding sessions and approve changes from their phones ([DevOps.com](https://devops.com/aws-previews-ios-app-to-manage-kiro-ai-coding-workflows/)). With Amazon Q Developer's April 2027 end-of-support announced, the transition to Kiro as AWS's flagship AI coding platform is accelerating.

## OpenAI and Broadcom Unveil Custom "Jalapeno" AI Chip

OpenAI today revealed its first custom-designed inference chip, codenamed "Jalapeno," co-developed with Broadcom in just nine months ([TechCrunch](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/)). Optimized for LLM inference with substantially better performance-per-watt, initial deployment is targeted for late 2026 ([CNBC](https://www.cnbc.com/2026/06/24/openai-and-broadcom-reveal-jalapeno-first-ai-chip-in-partnership.html)). The move signals OpenAI's push to reduce its dependence on Nvidia.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Claude Tag launch, Opus 4.8 stable |
| ChatGPT | 96 | — | GPT-5.6 timeline slipping to July |
| Claude AI | 96 | — | Two-day outage resolved, Claude Tag positive |
| Cursor | 96 | — | SpaceX $60B acquisition closing Q3 |
| Codex CLI | 87 | — | SSD bug 85% fixed, Daybreak expansion |
| Windsurf | 85 | — | Devin Desktop stable, Cascade EOL July 1 |
| Antigravity | 82 | ↑1 | Gemini CLI D+7 migration absorption, 7-week streak |
| Aider | 68 | — | Open-source steady |
| Gemini CLI | 40 | ↓2 | Shutdown Day 7, enterprise-only |
| Copilot | 32 | ↓1 | 50-week decline, billing Day 24 |

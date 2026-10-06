---
title: "Cursor and Copilot Tied at 19 — Meta and Microsoft Scale Back Claude"
date: 2026-10-06
lang: en
categories: [news]
tags: [cursor, copilot, antigravity, anthropic, claude-code, sourcegraph]
excerpt: "Cursor's 40-day freefall meets Copilot's steady climb at 19. Meanwhile Meta and Microsoft cut Claude usage as Barclays expands Claude Code to half its developers."
---

Cursor's 40-day consecutive decline and GitHub Copilot's steady rebound converged on a single number: 19. The editor in freefall since the SpaceX acquisition and the platform climbing from an 85-week floor of 1 now stand at the same score — a symbolic moment in the structural reshaping of the AI coding tool market.

## Cursor vs Copilot: What the 19-Point Tie Means

Cursor has been sliding for 40 straight days since OpenAI announced it would cut model access on November 12, triggered by SpaceX's $60B acquisition of Anysphere([DevOps.com](https://devops.com/openai-cuts-off-cursors-model-access-after-spacex-acquisition/)). Compile 2026 brought announcements of a frontier model, the Origin platform, and a mobile app, but market confidence hasn't recovered.

GitHub Copilot climbed from 1 to 19 on the back of Computer Use public preview, HydraFusion multi-model orchestration expanding to VS Code, and Code Review API GA([GitHub Changelog](https://github.blog/changelog/label/copilot/)). On October 2, it deprecated Gemini 3.5/3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7, replacing them with current-generation models including Claude Sonnet 5.5 and GPT-6.1 Sol at GA([GitHub Changelog](https://github.blog/changelog/2026-10-02-selected-models-in-github-copilot-deprecated/)). A second deprecation wave hits October 19 — GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Gemini 3.7 Flash, and Grok 4.5 are all scheduled for removal([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)). Default enablement of Copilot features for Business/Enterprise customers begins October 22([GitHub Blog](https://github.blog/changelog/2026-10-01-github-copilot-in-vs-code-september-2026-releases/)).

## Claude: Mixed Signals — Meta and Microsoft Cut Back, Barclays Doubles Down

Conflicting enterprise signals emerged around Claude. Meta scaled internal Claude usage down to roughly 30,000 employees, and Microsoft slashed its Claude spending projections by a third([Seeking Alpha](https://seekingalpha.com/news/4650314-meta-microsoft-scale-back-employee-use-of-claude-report)). Meanwhile Barclays expanded Claude Code to 50% of its developers, leading financial-sector adoption of AI coding tools.

Claude Code shipped v2.1.291, fixing regressions with permission prompts and session persistence([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). The bigger Claude Code story this week is Mods — launched October 1, they let developers write TypeScript functions that rewrite prompts, intercept tool calls, and control permissions, effectively turning the coding agent into a programmable runtime([gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)). Anthropic's pre-IPO investor day is eight days away on October 14, with a mid-November listing targeting up to $2 trillion([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/anthropic-is-said-to-plan-pre-ipo-investor-day-as-listing-nears)).

## Antigravity: May Preview Shut Down, Migration Required

Google Antigravity's antigravity-preview-05-2026 was fully retired on October 5([Kingy AI](https://kingy.ai/ai-launch-tracker/antigravity-may-preview-retirement-october-5-2026/)). Any CI pipeline still calling the old version now returns an error with no fallback. Migration to antigravity-preview-09-2026 is mandatory; the new version adopts PascalCase file operations and line-range replacement editing([ai.google.dev](https://ai.google.dev/gemini-api/docs/models/antigravity-preview-05-2026)).

## Codex: Daily Shipping Sprint Underway

OpenAI's Codex team launched a daily improvement sprint, committing to ship one meaningful user-facing update every day for four weeks([OpenAI Developer Community](https://community.openai.com/t/video-meet-the-new-codex-cli-updates/1403548)). Codex CLI v0.160.1 dropped October 5 fixing remote stdio MCP environment handling([Releasebot](https://releasebot.io/updates/openai/codex)). The sprint signals an aggressive iteration pace as Codex competes with Claude Code for terminal-agent dominance.

## Sourcegraph CEO: AI Code 'Tidal Wave' Is Eroding Codebases

Sourcegraph CEO Dan Adler warned that coding agents are producing a "tidal wave" of code eroding decades-old codebases running banks, cars, and airlines([Artificially Intimidating](https://artificiallyintimidating.com/p/ai-brief-october-5-2026)). Duplicated code, drifting standards, and fresh vulnerabilities are all growing in tandem.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Pro 500 stable, GPT-6.1 Sol settling in |
| Claude Code | 99 | — | v2.1.291 patch, Barclays expands to 50% |
| Codex CLI | 99 | — | Cloud mode expanding, voice input default |
| Antigravity | 99 | — | May preview retired, 09-2026 transition done |
| Claude AI | 99 | — | IPO D-8, Meta/MS cut back vs Barclays doubling down |
| Windsurf | 88 | — | Steady as Devin Desktop |
| Aider | 68 | — | Steady open-source, no new releases |
| Cursor | 19 | ↓2 | 40th straight decline, tied with Copilot |
| GH Copilot | 19 | ↑2 | Sonnet 5.5 & Sol GA, Oct 22 default enablement |
| Gemini CLI | 1 | — | Retired June, transitioned to Antigravity |

Meta and Microsoft scaling back Claude while Barclays doubles down shows the same tool drawing opposite enterprise verdicts. OpenAI shutoff D-37 — the next 37 days will decide Cursor's fate.

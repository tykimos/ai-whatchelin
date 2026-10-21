---
title: "Copilot Completes October Model Purge — Universe D-7, Legacy API D-2"
date: 2026-10-21
lang: en
categories: [news]
tags: [copilot, cursor, codex-cli, chatgpt, antigravity, claude-code]
excerpt: "GitHub Copilot removed GPT-5.5 and five other models on Oct 19, climbing to 49. With the legacy API shutdown in two days and Universe in a week, this is October's pivotal week."
---

GitHub Copilot executed its second model deprecation wave on October 19, right on schedule. GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Gemini 3.7 Flash, and Grok 4.5 were removed from all Copilot experiences — chat, inline edits, agent mode, and code completions([GitHub Blog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)). Following the October 2 wave that cleared Gemini 3.5/3.6 Flash, Kimi K2.7 Code, and Claude Opus 4.7, Copilot's model lineup is now fully modernized.

## Copilot: Climbs to 49, Universe D-7

Copilot rises to 49, sustaining its +2/day streak for eight consecutive days. The gap over Cursor is now 48 points (49 vs 1), a record. Replacement models for the Oct 19 wave are GPT-5.6 Sol, GPT-5.6 Luna, Gemini 3.8 Flash, and Grok 4.6 — automatically enabled for Enterprise and Business customers unless an admin has opted out([qcode.cc](https://qcode.cc/en/github-copilot-model-retirement-2026-10-19)). Tomorrow (Oct 22), the default enablement policy takes effect — all unconfigured GA features, including MCP servers in Copilot, will be switched on unless an admin explicitly disables them([GitHub Blog](https://github.blog/changelog/2026-09-25-default-enablement-of-copilot-features-for-copilot-business-and-enterprise)). [GitHub Universe 2026](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/) (Oct 28–29, Fort Mason) is now just 7 days away.

## Legacy API Shutdown D-2: 11+ Models Going Dark

In two days — October 23 — at least 11 legacy model endpoints, including o1, o1-pro, o3-mini, o4-mini, GPT-3.5 Turbo, GPT-4, GPT-4 Turbo, and gpt-4.1-nano, will be permanently shut down with no grace period([Geeks IT](https://geeks.it.com/?p=976)). Given the week-long "gpt-5.5 model is not supported" fallout after that model's October 14 retirement, similar disruption is likely after the 23rd. GPT-5.6 Sol is the official replacement for the GPT-4 family([Layer3 Labs](https://www.layer3labs.io/guides/openai-deprecated-models)).

## ChatGPT: Locked Chats and Slides Ship Back-to-Back

ChatGPT rolled out Locked Chats on October 20, letting users hide selected conversations from the sidebar, history, and search behind a PIN or device authentication([Android Authority](https://androidauthority.com/chatgpt-locked-chats-private-conversations-3701687)). On October 16, the Slides feature began rolling out to Pro, Business, and Enterprise users, and the Sites creation limit was removed([Releasebot](https://releasebot.io/updates/openai/chatgpt)).

## Cursor: Day 56 at Rock Bottom, OpenAI Shutoff D-22

Cursor remains at 1 for the 56th consecutive day. The X Subscription bundle is 8 days old with no reversal in sight. The OpenAI model access cutoff is now 22 days away (Nov 12). While Copilot's model cleanup signals "only the latest models survive," Cursor's Grok-only shared pool structure is drawing continued criticism for narrowing model choice rather than expanding it([Cursor Forum](https://forum.cursor.com/t/introducing-the-x-subscription/174450/27)).

## Claude Code: v2.1.302 Auto Mode Change, IPO Imminent

Claude Code v2.1.302 (Oct 16) switched headless mode (`claude -p`, Agent SDK) back to Manual for third-party providers([Developers Digest](https://www.developersdigest.tech/blog/claude-code-auto-mode-default)). Auto mode has been the default for all interactive sessions since v2.1.284 (Sep 28), and the server-side classifier migration is ongoing. Meanwhile, Anthropic confidentially filed its draft S-1 with the SEC on June 1, with a Nasdaq listing expected in October–November at a ~$965B valuation, surpassing OpenAI's $852B([Storyboard18](https://www.storyboard18.com/amp/digital/anthropic-plans-october-ipo-may-exceed-60-billion-as-it-rivals-openai-ws-l-93408.htm)).

## Antigravity: Gemini 4 Argon Stabilizing

Antigravity v2.24.0's redesigned side panel and /compact command (shipped Oct 13) are stabilizing in production([Antigravity Blog](https://antigravity.google/blog/gemini-4-argon-in-google-antigravity)). Claude Sonnet 4.6, Opus 4.6, and GPT-OSS-120B are scheduled for removal from Antigravity on November 2([Layer3 Labs](https://www.layer3labs.io/guides/google-antigravity-cli)).

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 99 | — | Locked Chats launched, Legacy API D-2 |
| Claude Code | 99 | — | v2.1.302 stable, IPO imminent |
| Codex CLI | 99 | — | v0.163.0 Daybreak enabled |
| Antigravity | 99 | — | Argon rollout expanding, v2.24.0 stabilizing |
| Claude AI | 99 | — | 5.5 family complete, IPO Oct–Nov |
| Windsurf | 88 | — | Devin Desktop stable |
| Aider | 68 | — | Stable, no major updates |
| GH Copilot | 49 | ↑2 | Second purge complete, Universe D-7 |
| Cursor | 1 | — | Day 56 at bottom, X Sub no effect |
| Gemini CLI | 1 | — | Retired |

This is October's pivotal week. The Oct 23 legacy API shutdown, Oct 22 Copilot default enablement, and Oct 28 Universe — three events that will shape the next phase of the AI coding tool ecosystem.

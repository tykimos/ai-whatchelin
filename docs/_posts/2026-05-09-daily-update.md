---
title: "380K Vibe-Coded Apps Expose Patient Records — Cursor 3.3 Ships Parallel Agents"
date: 2026-05-09
lang: en
categories: [news]
tags: [cursor, claude-code, claude-ai, copilot, gemini-cli, security, vibe-coding]
excerpt: "A security firm found 380,000 publicly accessible vibe-coded apps with 5,000 leaking medical records and financial data. Cursor 3.3 ships parallel execution, and Claude recovers from a major outage."
---

The convenience of vibe coding comes at a cost. Israeli security firm RedAccess found over 380,000 publicly accessible assets built with Lovable, Base44, Replit, and Netlify — roughly 5,000 of which contained sensitive data including medical records, financial information, and business documents([Axios](https://www.axios.com/2026/05/07/loveable-replit-vibe-coding-privacy), [VentureBeat](https://venturebeat.com/security/vibe-coded-apps-shadow-ai-s3-bucket-crisis-ciso-audit-framework)). Lovable denied the report; Replit's CEO countered that RedAccess gave only 24 hours' notice before going to press.

## Cursor 3.3: Parallel Execution and PR Splitting

Cursor 3.3 shipped significant new capabilities([Cursor Blog](https://cursor.com/changelog)). "Build in Parallel" identifies independent parts of a plan and runs them simultaneously using async subagents while keeping dependent steps in order. The new PR splitting feature carves changes into logical slices, creates a backup snapshot, and proposes a split plan for approval. A new Reviews tab lets users take PRs from creation to merge in one place. Score rises from 93 to 94 — a new all-time high.

## Claude: Major Outage Recovered, Security Concerns Mount

Claude went down for thousands of users on May 8([GV Wire](https://gvwire.com/2026/05/08/claude-ai-goes-down-for-thousands-of-users-friday-downdetector-reports/)). Over 2,000 users reported elevated API errors and login failures by 7:48 a.m. PT. A separate infrastructure change altered outbound IP addresses, breaking Claude Code remote sessions and GitHub Enterprise plugin syncing. Anthropic reverted the change and service was restored. Meanwhile, a Dragos report revealed hackers used Claude AI as the "primary technical executor" in a January attempt to compromise a Mexican water utility — writing a 17,000-line Python framework — though the OT infrastructure attack ultimately failed([Cybersecurity Dive](https://www.cybersecuritydive.com/news/anthropics-claude-compromise-mexican-water-utility/819710/)).

## GitHub Copilot: D-22, Seven Weeks of Decline

The usage-based billing countdown hits 22 days([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). With Opus models removed from Pro and individual plan sign-ups still paused, the score drops from 78 to 77 — marking the seventh consecutive week of decline. A survey of 200+ senior SRE/DevOps leaders found that 43% of AI-generated code changes require manual debugging in production, adding to the industry's quality concerns([VentureBeat](https://venturebeat.com/technology/43-of-ai-generated-code-changes-need-debugging-in-production-survey-finds)).

## Gemini CLI: Voice Mode, Offline Support, and Google I/O Incoming

Gemini CLI added real-time voice mode, offline support, and Gemma 4 model integration([GitHub](https://github.com/google-gemini/gemini-cli/releases)). Patch v0.41.2 also shipped. With Google I/O 2026 on May 19, major Gemini updates are expected. Score rises from 70 to 71.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant stable |
| Claude Code | 98 | — | Outage recovered, infrastructure lead intact |
| Cursor | 94 | ↑1 | Parallel execution + PR splitting, new ATH |
| Claude AI | 92 | — | Cowork GA momentum continues |
| Codex CLI | 78 | ↑1 | Bedrock support, multi-env sessions |
| Windsurf | 77 | — | GPT-5.4 Mini at 1x credits promo |
| GitHub Copilot | 77 | ↓1 | 7-week slide, D-22 |
| Gemini CLI | 71 | ↑1 | Voice mode, offline support, I/O anticipation |
| Aider | 68 | — | 39K+ stars, stable |
| Antigravity | 49 | — | AgentKit 2.0 settling in |

The vibe coding security scandal sends a warning across the industry as Cursor hits a new all-time high of 94, now 17 points clear of Copilot (77). Claude Code holds at 98 despite the outage, maintaining its tie with ChatGPT. The AI coding market confronts the growing tension between convenience and security.

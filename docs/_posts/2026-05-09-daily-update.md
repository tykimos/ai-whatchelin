---
title: "380K Vibe-Coded Apps Leak Data — Claude Code Ships 4 Versions in One Day, Cursor Adds DevSecOps"
date: 2026-05-09
lang: en
categories: [news]
tags: [cursor, claude-code, claude-ai, copilot, gemini-cli, security, vibe-coding, servicenow, opsera]
excerpt: "A security firm found 380,000 publicly accessible vibe-coded apps leaking sensitive data. Claude Code responds with 4 releases in a day including hard deny rules for auto mode. Cursor partners with Opsera for native DevSecOps, and ServiceNow Build Agent goes GA across all major AI coding tools."
---

The convenience of vibe coding comes at a cost. Israeli security firm RedAccess found over 380,000 publicly accessible assets built with Lovable, Base44, Replit, and Netlify — roughly 5,000 of which contained sensitive data including medical records, financial information, and business documents([Axios](https://www.axios.com/2026/05/07/loveable-replit-vibe-coding-privacy), [VentureBeat](https://venturebeat.com/security/vibe-coded-apps-shadow-ai-s3-bucket-crisis-ciso-audit-framework)). Lovable denied the report; Replit's CEO countered that RedAccess gave only 24 hours' notice before going to press.

## Claude Code: Four Releases in One Day, Auto Mode Security Hardened

Claude Code shipped four versions in a single day — v2.1.133 through v2.1.138([code.claude.com](https://code.claude.com/docs/en/changelog)). The headline feature is "hard deny" rules for auto mode, which explicitly block specific actions to constrain the agent's autonomous execution scope. Other fixes include worktree branching controls (`worktree.baseRef`), MCP/plugins disappearing after `/clear`, and credential write race conditions. The timing — right after the vibe coding security scandal — is telling.

## Cursor 3.3: Parallel Execution + Opsera DevSecOps Partnership

Cursor 3.3 shipped "Build in Parallel" for async subagent execution, PR Splitting, and a new Reviews tab([Cursor Blog](https://cursor.com/changelog)). More notable is the Opsera partnership: autonomous DevSecOps Agents — Architecture Analyzer, Security Scanner, SQL Scanner, and Compliance Auditor — are now embedded as a native Cursor plugin([PRNewswire](https://www.prnewswire.com/news-releases/opsera-and-cursor-partner-to-embed-autonomous-ai-agents-directly-into-ai-sdlc-workflows-for-next-gen-ai-driven-development-302762277.html)). Score rises from 93 to 94, a new all-time high.

## ServiceNow Build Agent: GA Across All Major AI Coding Tools

ServiceNow Build Agent is now generally available inside Cursor, Windsurf, Claude Code, and GitHub Copilot([ServiceNow](https://newsroom.servicenow.com/press-releases/details/2026/ServiceNow-Build-Agent-now-works-inside-every-major-AI-coding-tool-governed-by-default/default.aspx)). Powered by Anthropic models, it connects to Figma, Miro, and GitHub as MCP Client. A signal that the AI coding ecosystem is evolving from the "editor war" to the "plugin platform war."

## GitHub Copilot: D-22, Seven Weeks of Decline

The usage-based billing countdown hits 22 days([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). The VS Code April releases added semantic search, `/chronicle` chat history, and BYOK support([GitHub Blog](https://github.blog/changelog/2026-05-06-github-copilot-in-visual-studio-code-april-releases/)), but with Opus models removed from Pro and individual sign-ups paused, the score drops to 77 — the seventh consecutive week of decline. A survey found 43% of AI-generated code changes require manual debugging in production([VentureBeat](https://venturebeat.com/technology/43-of-ai-generated-code-changes-need-debugging-in-production-survey-finds)).

## Gemini CLI: Voice Mode, Offline Support, and Google I/O Incoming

Gemini CLI v0.41.2 added real-time voice mode, offline support, and Gemma 4 integration([GitHub](https://github.com/google-gemini/gemini-cli/releases)). With Google I/O 2026 on May 19, Gemini 4.0 is expected and an "Omni" video model has been spotted in the Gemini UI([Yahoo](https://tech.yahoo.com/general/article/what-to-expect-at-google-io-2026-android-17-ai-announcements-and-more-131200028.html)). Score rises from 70 to 71.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant stable |
| Claude Code | 98 | — | 4 releases in one day, hard deny security hardening |
| Cursor | 94 | ↑1 | Parallel execution + Opsera DevSecOps, new ATH |
| Claude AI | 92 | — | Cowork GA momentum continues |
| Codex CLI | 78 | ↑1 | Bedrock support, multi-env sessions |
| Windsurf | 77 | — | GPT-5.4 Mini at 1x credits promo |
| GitHub Copilot | 77 | ↓1 | 7-week slide, D-22 |
| Gemini CLI | 71 | ↑1 | Voice mode, offline support, I/O anticipation |
| Aider | 68 | — | 39K+ stars, stable |
| Antigravity | 49 | — | AgentKit 2.0 settling in |

The vibe coding security scandal sends a warning across the industry, and tools are responding differently. Claude Code hardened auto mode with hard deny rules. Cursor integrated Opsera DevSecOps at the plugin level. Meanwhile, Copilot marks its seventh consecutive week of decline at D-22. The frame is shifting from "convenience vs security" to "security as competitive advantage."

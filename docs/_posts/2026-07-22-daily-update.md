---
title: "Sandbox Escapes Hit 4 AI Coding Agents — The Security Model Everyone Trusted Just Cracked"
date: 2026-07-22
lang: en
categories: [news]
tags: [cursor, codex-cli, antigravity, gemini-cli, copilot, chatgpt, claude, security]
excerpt: "Pillar Security discloses 7 sandbox escape CVEs across Cursor, Codex CLI, Gemini CLI, and Antigravity. The agents don't break the sandbox — they write files that trusted host tools execute."
---

The sandbox security model that AI coding agents rely on has a fundamental blind spot. Pillar Security published its "Week of Sandbox Escapes" research on July 21, disclosing 7 vulnerabilities across Cursor, Codex CLI, Gemini CLI, and Antigravity from three vendors ([BleepingComputer](https://www.bleepingcomputer.com/news/security/cursor-codex-gemini-cli-antigravity-hit-by-sandbox-escapes/)). The key insight: agents never directly breach their sandbox. Instead, prompt injection hidden in a README, dependency, or diff causes the agent to write files that trusted host-side tools — Git hooks, VS Code task runners, Python extensions — later execute outside the box ([CSO Online](https://www.csoonline.com/article/4199408/ai-agents-can-escape-sandboxes-without-ever-breaking-them.html)).

## Cursor: CVE-2026-48124 — Workspace Hook Config Exploit

A workspace-controlled `.claude` hook configuration in Cursor could escalate to unsandboxed command execution ([Pillar Security](https://www.pillar.security/blog/the-week-of-sandbox-escapes)). Tracked as CVE-2026-48124 and fixed in v3.0.0. This is Cursor's second major security incident this year, following CVE-2026-26268 (CVSS 8.1) in April.

## Codex CLI: The "Safe" Command Allowlist Trap

Codex CLI's allowlist trusted `git show` by name, but the actual invocation wasn't always read-only ([Techzine](https://www.techzine.eu/news/security/143038/researchers-bypass-sandbox-security-in-cursor-codex-and-gemini-cli/)). OpenAI patched it in v0.95.0 and paid a high-severity bounty. A separate Docker daemon access flaw was shared across Cursor, Codex CLI, and Gemini CLI — sandboxed agents could reach a privileged Docker socket and request containers with host mounts.

## Google: Refuses to Patch

The most controversial response came from Google. It classified both Antigravity findings as "other valid security vulnerabilities" but downgraded severity as "hard to exploit" and chose not to patch ([Neowin](https://www.neowin.net/news/pillar-research-shows-sandboxes-are-inadequate-for-agentic-ai-google-decides-not-to-patch/)). Gemini CLI, already shut down on July 17, is effectively beyond patching. The researchers' core conclusion: sandboxes alone are insufficient for agentic AI.

## ChatGPT: Errors Continue

ChatGPT experienced elevated errors affecting file uploads and image generation on July 22 ([OpenAI Status](https://status.openai.com/history)). Stability issues continue to recur since the GPT-5.6 Sol transition — this is the fourth incident report within a week of the major July 15 global outage.

## Claude Platform: Memory API Update

The Claude Platform shipped the agent-memory-2026-07-22 API version, updating memory store endpoints ([Claude Platform Docs](https://platform.claude.com/docs/en/release-notes/overview)). The legacy managed-agents-2026-04-01 header now adopts the same list behavior.

## Market Pulse

| Tool | Score | Δ | Signal |
|---|---|---|---|
| Claude Code | 99 | — | Not included in sandbox escape research, stable |
| ChatGPT | 99 | — | File upload errors elevated, 4th incident this week |
| Antigravity | 99 | — | Sandbox CVEs unpatched — Google refuses to fix |
| Claude AI | 98 | — | Platform memory API update |
| Cursor | 97 | — | CVE-2026-48124 patched (v3.0) |
| Codex CLI | 90 | — | Sandbox high-severity bounty patched |
| Windsurf | 85 | — | Devin Desktop stable operations |
| Aider | 68 | — | 44K stars, no new release |
| Copilot | 4 | ↓1 | 75-week decline, all-time low |
| Gemini CLI | 4 | ↓1 | Shutdown Day 34, vulnerabilities now unpatchable |

The fundamental limits of agent sandbox security are now exposed. The assumption that "inside the sandbox means safe" collapsed against prompt injection combined with trusted host-side tool chains. Notably, Claude Code was the only major coding agent excluded from this research. Kimi K3 open-weight release (July 27) is 5 days away.

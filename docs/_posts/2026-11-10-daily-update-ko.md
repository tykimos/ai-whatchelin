---
title: "Cursor, OpenAI 차단 D-2 — Copilot이 JetBrains Air·Xcode까지 진출"
date: 2026-11-10
lang: ko
categories: [news]
tags: [cursor, openai, github-copilot, claude-code, anthropic, gemini-cli]
excerpt: "OpenAI의 Cursor 모델 차단이 이틀 앞으로 다가온 가운데, Copilot은 JetBrains Air·Xcode 진출과 GPT-6.1 Terra로 46일 연속 상승세를 이어간다."
---

Cursor의 운명의 날이 코앞이다. SpaceX 인수 이후 촉발된 OpenAI의 모델 접근 차단이 11월 12일로 확정된 가운데, GitHub Copilot은 JetBrains Air·Xcode까지 진출하며 공격적으로 빈자리를 채우고 있다.

## Cursor: OpenAI 차단 D-2, 77일째 바닥

OpenAI의 Cursor 모델 공급 완전 차단이 11월 12일로 이틀 앞으로 다가왔다([InfoWorld](https://www.infoworld.com/article/4216503/cursor-customers-will-lose-access-to-openai-coding-models-in-november.html)). SpaceX의 Anysphere 600억 달러 인수 후 촉발된 계약 해지 조항에 따른 것으로, Cursor 공동창업자는 OpenAI 모델이 현재 전체 트래픽의 약 5%에 불과하다고 밝혔다([The New Stack](https://thenewstack.io/openai-cuts-cursor-spacex/)). 그러나 심리적 타격은 수치 이상이다 — 인기도는 77일 연속 1점에 머물고 있다.

## GitHub Copilot: JetBrains Air·Xcode 진출, GPT-6.1 Terra 탑재

Copilot이 이번 주 공격적으로 영역을 넓혔다. 11월 3일, GitHub은 JetBrains Air 내에서 Copilot을 에이전트로 선택할 수 있도록 Agent Client Protocol(ACP) 기반 통합을 출시했다([GitHub Blog](https://github.blog/changelog/2026-11-03-github-copilot-is-now-available-in-jetbrains-air)). 다음 날에는 Xcode의 기본 코딩 어시스턴트에 Copilot이 퍼블릭 프리뷰로 탑재되었으며, 12월 Xcode 27.3 정식 출시와 함께 GA가 예상된다([GitHub Blog](https://github.blog/changelog/2026-11-06-github-copilot-weekly-releases-november-2)). 이번 주간 릴리스에는 모든 필수 체크가 통과되면 Copilot이 자동으로 PR을 머지하는 Agent Merge 기능도 포함되었다.

모델 측면에서는 Copilot CLI v1.0.106에 GPT-6.1 Terra가 추가되었다([GitHub Blog](https://github.blog/changelog/2026-10-26-gpt-6.1-terra-in-github-copilot)). Terra는 Sol 대비 낮은 비용의 에이전틱 코딩 최적화 모델로, Pro/Pro+/Max/Business/Enterprise 플랜에서 사용 가능하다([Visual Studio Magazine](https://visualstudiomagazine.com/articles/2026/10/28/github-copilot-adds-gpt-6-1-terra-for-lower-cost-agentic-coding.aspx)). Copilot의 인기도는 46일 연속 상승 중이며, Cursor의 공백을 실질적으로 흡수하는 모양새다.

## Claude Code: v2.1.319 — Auto Mode 도입

Claude Code v2.1.319가 출시되며 Auto Mode를 도입했다([claudekit](https://claudekit.io/en/updates/claude-code-2-1-319/)). LLM 게이트웨이 환경에서 텔레메트리가 비활성화된 경우, 내장 분류기 대신 서버 측 승인을 요청하는 방식으로 보안을 강화했다. MCP 태스크 지원과 게이트웨이 관리 기능도 함께 추가되었다([labmemo](https://labmemo.com/claude-code-v2-1-319-auto-mode-gateway-mcp-task-2026-11/)). 한편, 지난주 보고된 공개 리포 자격증명 유출(2,539건) 사태의 여파가 계속되는 가운데, 보안 강화 업데이트가 적시에 나온 셈이다.

## Anthropic: IPO 가격 결정 D-3

Anthropic의 나스닥(ANT) IPO 가격 결정이 11월 13일로 예정되어 있다. Fable 5.2와 Mythos 5.2의 동시 출시, 20% 가격 인하, 그리고 METR의 RSI 경고가 혼재된 상황에서 시장의 반응이 주목된다([TechCrunch](https://techcrunch.com/2026/11/09/anthropic-releases-new-mythos-and-fable-models-amid-rsi-concerns/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 서비스 안정화 중 |
| Claude Code | 99 | — | v2.1.319 Auto Mode 출시 |
| Codex CLI | 99 | — | 안정 유지 |
| Antigravity | 99 | — | 안정 유지 |
| Claude AI | 99 | — | IPO 가격 결정 D-3 |
| GH Copilot | 89 | ↑2 | 46일 연속 상승; JetBrains Air·Xcode·Terra |
| Windsurf | 88 | — | 안정 유지 |
| Aider | 68 | — | 유지보수 모드 |
| Cursor | 1 | — | OpenAI 차단 D-2, 77일째 바닥 |
| Gemini CLI | 1 | — | 서비스 종료, Antigravity 전환 완료 |

Cursor의 OpenAI 차단 D-Day가 48시간 앞으로 다가오면서, AI 코딩 도구 시장이 결정적 변곡점에 섰다. Copilot의 3중 확장 — JetBrains Air·Xcode·Terra — 은 Microsoft가 Cursor 이후의 공백을 노린다는 신호이며, Claude Code는 자격증명 유출 여파 속에서도 보안 강화를 멈추지 않는다.

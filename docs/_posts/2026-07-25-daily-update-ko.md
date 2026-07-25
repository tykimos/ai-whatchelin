---
title: "Claude Opus 5 전격 출시 — Frontier-Bench 2배, MCP 스테이트리스 전환 초읽기"
date: 2026-07-25
lang: ko
categories: [news]
tags: [anthropic, claude, opus-5, claude-code, mcp, antigravity, github-copilot, kiro, huawei]
excerpt: "Anthropic이 Claude Opus 5를 출시하며 Frontier-Bench에서 Opus 4.8 대비 2배 성능을 달성했다. MCP 스테이트리스 아키텍처 RC도 공개돼 생태계 전반에 브레이킹 체인지가 예고됐다."
---

Anthropic이 어제 Claude Opus 5를 전격 출시하며 AI 코딩 도구 시장의 판도가 다시 한번 흔들렸다. Frontier-Bench v0.1에서 Opus 4.8 대비 2배 성능을 기록하면서도 가격은 $5/$25/MTok으로 동일하게 유지했다([Fortune](https://fortune.com/2026/07/24/anthropic-debuts-claude-opus-5-with-feature-that-lets-users-toggle-between-cost-and-capability/)). 동시에 MCP의 가장 큰 규모의 프로토콜 개편 RC가 발표되면서, 7월 마지막 주는 AI 개발 생태계 전체가 요동치는 한 주가 되고 있다.

## Claude Opus 5: 같은 가격, 2배 성능

Opus 5는 1M 토큰 컨텍스트, 128K 최대 출력, 기본 사고(thinking) 활성화를 갖추고 출시됐다([9to5Mac](https://9to5mac.com/2026/07/24/anthropic-upgrades-claude-with-new-opus-5-model-details-here/)). 가장 주목할 만한 신기능은 요청별 low/medium/high 노력도 토글로, 단순 작업은 비용을 아끼고 복잡한 작업에만 최대 성능을 투입할 수 있다. OSWorld 2.0에서 Fable 5를 능가하면서도 비용은 3분의 1 수준이다. Claude API, Amazon Bedrock, Google Cloud, Microsoft Foundry, claude.ai, Claude Code, Claude Cowork 전 플랫폼에서 즉시 사용 가능하다.

## Claude Code v2.1.219: Opus 5 기본 모델 전환

Claude Code가 v2.1.219로 업데이트되면서 Opus 5가 기본 Opus 모델로 설정됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 서브에이전트가 이제 최대 3단계까지 중첩 가능해져 복잡한 멀티에이전트 워크플로우가 한층 강화됐다. `sandbox.network.strictAllowlist` 설정도 추가돼 승인되지 않은 호스트를 차단할 수 있다. Opus 4.7은 fast mode에서 완전 퇴장했으며, fast mode는 이제 Opus 5와 Opus 4.8만 지원한다.

## MCP 2026-07-28 RC: 스테이트리스 아키텍처로 대전환

Model Context Protocol 역사상 가장 큰 규모의 개편 RC가 공개됐다([The Register](https://www.theregister.com/devops/2026/07/23/model-context-protocol-prepares-to-break-with-its-stateful-past/5276722)). 세션 상태, initialize 핸드셰이크, 프로토콜 수준 세션이 모두 제거되고 모든 요청이 자체 완결형으로 바뀐다. 서버 렌더링 UI(MCP Apps), 장기 실행 작업(Tasks 확장), 강화된 OAuth/OIDC 인증도 포함된다. 7월 28일 최종 릴리스 예정이며, 기존 클라이언트와의 호환성이 깨지는 브레이킹 체인지가 포함돼 있어 MCP 서버 운영자들은 즉시 대비가 필요하다([Developers Digest](https://www.developersdigest.tech/blog/mcp-2026-07-28-breaking-changes)).

## Antigravity CLI v1.1.6-v1.1.7: 하루 두 번 업데이트

Antigravity CLI가 하루 만에 두 번의 릴리스를 쏟아냈다([Antigravity Changelog](https://antigravity.google/changelog)). v1.1.6에서는 Markdown 형식의 커스텀 에이전트(`agent.md`)와 `/codesearch` 프로그레시브 스트리밍이 추가됐고, v1.1.7에서는 복합 셸 명령의 권한 프롬프트 개선과 Windows CJK 클립보드 복사 수정이 이뤄졌다.

## GitHub Copilot: Opus 5 즉시 탑재, 그러나 하락세는 계속

GitHub Copilot이 Opus 5를 출시 당일 Pro/Pro+/Max/Business/Enterprise 전 플랜에 추가했다([GitHub Changelog](https://github.blog/changelog/2026-07-24-claude-opus-5-is-now-available-in-github-copilot/)). 7월 31일에는 Gemini 2.5 Pro와 Gemini 3 Flash가 Copilot에서 퇴장 예정이다. 새 모델 추가에도 불구하고 77주째 하락세가 이어지고 있어, GitHub Models 전환(7월 30일)이 반등의 계기가 될 수 있을지 주목된다.

## Kiro: RCE 취약점 공개

AWS의 Kiro에서 원격 코드 실행(RCE) 취약점이 발견됐다([The Hacker News](https://thehackernews.com/2026/07/aws-kiro-flaw-let-poisoned-web-page.html)). 악성 웹페이지가 Kiro의 MCP 설정을 변조해 임의 코드를 실행할 수 있는 문제로, v1.0.165 이상으로 업데이트가 필요하다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 기본 모델 전환, v2.1.219 |
| ChatGPT | 99 | — | GPT-5.6 Sol 안정, Codex 티저 미확인 |
| Antigravity | 99 | — | 하루 2회 릴리스(v1.1.6-v1.1.7) |
| Claude AI | 99 | ↑1 | Opus 5 출시로 98→99 |
| Cursor | 97 | — | Router 안착, 비용 절감 효과 확산 |
| Codex CLI | 91 | — | "Codexy" 티저, 정식 발표 미확인 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | — | 77주 하락, Opus 5 탑재에도 바닥 |
| Gemini CLI | 1 | — | 소비자 접근 차단 37일째 |

Opus 5 출시와 MCP 스테이트리스 전환이 이번 주의 핵심이다. Opus 5가 같은 가격에 2배 성능을 제공하면서 Anthropic의 가격 대비 성능 우위가 더욱 공고해졌고, MCP의 브레이킹 체인지는 7월 28일까지 모든 MCP 서버 운영자에게 즉각적인 대응을 요구하고 있다.

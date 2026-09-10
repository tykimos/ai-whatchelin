---
title: "GitHub Copilot '10월 3연타' 예고 — 통합 리런치·선불 과금·모델 퇴장이 17일 안에 몰린다"
date: 2026-09-11
lang: ko
categories: [news]
tags: [github-copilot, claude-code, cursor, codex-cli, chatgpt]
excerpt: "GitHub Copilot이 9/28 통합 리런치, 10/1 선불 좌석 과금, 10/2 모델 폐기를 17일 안에 연달아 시행한다. Claude Code v2.1.267은 maxEffortLevel 설정을, Cursor는 67점으로 16일째 하락을 이어간다."
---

GitHub Copilot에 '10월 3연타'가 다가오고 있다. 9월 28일 통합 리런치, 10월 1일 선불 좌석 과금, 10월 2일 모델 폐기가 17일 안에 연달아 시행된다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 가격 자체는 변하지 않지만 과금 방식이 바뀌어, 이제 모든 Business·Enterprise 좌석 할당에 선불이 필요하다([Developers Digest](https://www.developersdigest.tech/blog/github-copilot-september-policy-billing-reset-2026)). 코드 리뷰 기본 모드도 Lite에서 Balanced로 바뀌어 더 깊은 리뷰를 수행하되 토큰 소비도 늘어난다.

## GitHub Copilot: 10월 2일 모델 대량 퇴장

Gemini 3.5 Flash와 3.6 Flash가 Gemini 3.8 Flash로, Kimi K2.7 Code가 K3로, Claude Opus 4.7이 Opus 5로 교체된다([DMarketer Tayeeb](https://dmarketertayeeb.com/blog/github-copilot-september-2026-model-budget-review-changes/)). Chat, 인라인 편집, Agent 모드, 코드 완성 전 영역에 적용된다. Gemini 3.8 Flash는 이미 9월 3일부터 Pro/Pro+/Max/Business/Enterprise 사용자에게 제공 중이다([GitHub Blog](https://github.blog/changelog/2026-09-03-gemini-3-8-flash-is-now-available-in-github-copilot/)). 관리자가 별도 조치를 할 필요는 없지만 워크플로우 점검은 권장된다.

## Claude Code v2.1.267: maxEffortLevel 설정 추가

Claude Code가 v2.1.267로 올라가며 `maxEffortLevel` 설정이 추가됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 최상위 또는 `modelSettings` 하위에서 Bedrock·Vertex·Foundry 포함 모든 프로바이더의 effort 레벨 상한을 걸 수 있다. `--system-prompt-snapshot off`로 매 요청마다 시스템 프롬프트를 새로 렌더링하는 옵션도 생겼다. Cowork 클라우드 스케줄 태스크의 샌드박싱 필수 조직에서 실패하던 문제도 수정됐다. 한편 9/14 주간 한도 17% 삭감까지 D-3으로, 50% 프로모션 종료가 코앞이다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)).

## Cursor: 67점, 16일째 연속 하락 — D-62

Cursor가 67로 떨어지며 16일째 하락을 기록했다. 8월 27일 99점 정점에서 32포인트가 빠졌다. OpenAI 모델 차단(11/12)까지 62일 남았다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). Cursor 측은 OpenAI 모델이 전체 트래픽의 5%에 불과하다고 주장하지만, 심리적 이탈은 트래픽 비중과 무관하게 진행되고 있다. Fable 5.1의 Cursor 코딩 벤치마크 73.4% 역대 최고 기록이 보여주듯, Anthropic 의존도만 심화되는 구도다.

## GPT-6 Astra: 전면 GA 1주일, 생태계 침투 가속

GPT-6 Astra가 전면 GA 후 1주일을 맞았다([9to5Mac](https://9to5mac.com/2026/09/04/openai-releasing-major-upgrade-to-chatgpt-and-codex-with-gpt-6-astra-details-here/)). $10/$50/MTok으로 Fable 5.1과 동일 가격대에 포진하면서, Codex CLI v0.154.0에 정식 통합되고 Copilot CLI에도 지원이 추가됐다. 코딩 리더보드에서 인덱스 점수 48.5로 1위를 유지하며 ChatGPT Voice Mode에도 Pro 전용으로 탑재됐다([llm-stats.com](https://llm-stats.com/ai-news)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra GA 1주, Voice Mode 확대 |
| Claude Code | 99 | — | v2.1.267 maxEffortLevel, 9/14 한도 삭감 D-3 |
| Claude AI | 99 | — | Fable 5.1 안착, 캐시 75% 인하 유지 |
| Codex CLI | 99 | — | Astra 통합 완료, worktree 실험 |
| Antigravity | 99 | — | /boost 안정, GEMINI_API_KEY 지원 |
| Windsurf | 87 | — | Cognition $48B 모멘텀 유지 |
| Cursor | 67 | ↓2 | 16일째 하락, 정점 대비 -32p |
| Aider | 68 | — | v0.86.2 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 10월 3연타 D-17 |
| Gemini CLI | 1 | — | 폐쇄 85일째, Antigravity 대체 |

Copilot의 10월 3연타(통합 리런치·선불 과금·모델 퇴장)가 17일 뒤로 다가오면서, Enterprise 관리자들의 점검이 시급해지고 있다. Claude Code는 9/14 한도 삭감에 앞서 effort 제어 기능을 내놓으며 비용 최적화 도구를 갖추는 모양새다. Cursor의 32포인트 낙폭은 SpaceX 인수 후 OpenAI 결별의 시장 충격을 수치로 보여준다 — 기술적 영향(5%)과 심리적 영향(32p)의 괴리가 AI 도구 시장의 현주소다.

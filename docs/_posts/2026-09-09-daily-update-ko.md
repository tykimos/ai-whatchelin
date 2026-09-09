---
title: "GitHub Copilot 9/28 통합 리런치 확정 — AI 코딩 시장 3대 진영 재편 가속"
date: 2026-09-09
lang: ko
categories: [news]
tags: [github-copilot, cognition, openai, devday, cursor, codex-cli, openhands]
excerpt: "GitHub Copilot이 9월 28일 Chat·Mobile·Cloud Agent를 단일 경험으로 통합한다. Cognition $48B 시리즈 E, OpenHands 1.0 릴리스, Cursor 14일째 하락과 맞물려 AI 코딩 시장의 진영 구도가 빠르게 굳어지고 있다."
---

GitHub Copilot이 9월 28일부로 Chat, Mobile, Cloud Agent를 하나의 통합 경험으로 리런치한다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 별도 정책이 단일 정책으로 교체되고, 채팅 데이터 보존 기간이 28일에서 계정 수명 전체로 확대된다. 코드 리뷰 기본값도 Lite에서 Balanced로 변경되어 AI 소비량이 늘어날 수 있다. 한편 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 일괄 퇴역하며 각각 Gemini 3.8 Flash, Kimi K3, Claude Opus 5로 교체된다([GitHub Changelog](https://github.blog/changelog/2026-09-03-upcoming-deprecation-of-selected-github-copilot-models/)).

## Cognition AI: $2B 시리즈 E, $48B 밸류에이션

Cognition AI(Devin·Windsurf 모회사)가 Andreessen Horowitz·Accel 공동 리드로 $2B 시리즈 E를 마감했다([TechCrunch](https://techcrunch.com/2026/09/08/cognition-hits-48b-valuation-signaling-investors-believe-ai-coding-is-far-from-a-winner-take-all-market/)). 5월 $26B에서 4개월 만에 거의 두 배로 뛰었고, 런레이트 매출도 $492M→$900M으로 성장했다([Unite.AI](https://www.unite.ai/cognition-raises-over-2b-series-e-at-48b-valuation-to-scale-devin-agents/)). SpaceX의 Cursor 인수($60B)와 합쳐 AI 코딩 편집기 2대 진영이 완전히 자본화된 셈이다.

## GitHub Copilot: 9/28 통합 + 10/2 모델 퇴역 — 반격의 신호탄?

Copilot의 이번 통합은 단순 UI 병합이 아니다. Business·Enterprise 관리자는 9월 28일 전에 통합 정책을 검토해야 하며([Developers Digest](https://www.developersdigest.tech/blog/github-copilot-september-policy-billing-reset-2026)), 기본 리뷰 수준이 Balanced로 변경되면서 AI 크레딧 소비가 증가할 수 있다. 10월 2일 모델 교체는 9월 1일 퇴역 6건, 9월 10일 MAI-Code-1-Flash 종료에 이은 3단계 마이그레이션의 마지막 단계다. Copilot이 점수 1의 바닥권에서 반등할 수 있을지 9/28이 분수령이 된다.

## OpenHands 1.0: 오픈소스 코딩 에이전트의 첫 프로덕션 릴리스

오픈소스 자율 코딩 에이전트 OpenHands가 1.0에 도달했다([DEV Community](https://dev.to/jamilxt/openhands-just-hit-10-heres-how-to-run-it-on-your-own-machine-without-handing-over-the-keys-5666)). Docker 샌드박싱, 보안 정책, 플러그인 시스템을 갖추고 SWE-bench Verified 68%를 기록했으며, 셀프 호스팅 시 태스크당 $0.20~$1.05로 상용 에이전트의 1/10 비용이다. Devstral 24B 조합이 Devin 2.0의 46.8% 벤치마크를 이미 따라잡았다.

## Cursor: 71점, 14일째 하락 — D-64

Cursor가 71로 14일째 하락을 이어가고 있다. 8월 27일 99에서 총 28포인트가 빠졌다. OpenAI 모델 차단(11/12)까지 64일 남은 가운데, Fable 5.1이 Cursor 코딩 벤치마크 73.4%로 역대 최고를 기록하며 Anthropic 의존도가 높아지고 있다([Cursor Blog](https://cursor.com/blog)). 역설적으로, OpenAI 이탈이 오히려 Cursor의 모델 품질을 끌어올리는 구도다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra GA, DevDay 20일 전 |
| Claude Code | 99 | — | v2.1.261 안정, Fable 5.1 기본 |
| Claude AI | 99 | — | 캐시 비용 75% 인하 유지 |
| Codex CLI | 99 | — | Astra 기본, Security CLI 오픈소스화 |
| Antigravity | 99 | — | Gemini 3.8 Flash 적용 |
| Windsurf | 87 | ↑1 | Cognition $48B, $2B 시리즈 E |
| Cursor | 71 | ↓2 | 14일째 하락, D-64 |
| Aider | 68 | — | v0.86.2 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 9/28 통합 리런치 대기 |
| Gemini CLI | 1 | — | 폐쇄 83일째, Antigravity 대체 |

AI 코딩 시장이 3대 진영(Cognition/Windsurf vs SpaceX/Cursor vs OpenHands 오픈소스)으로 굳어지는 가운데, GitHub Copilot의 9/28 통합 리런치가 4번째 축이 될 수 있을지 주목된다. Cursor만 홀로 하락 곡선 위에 서 있다.

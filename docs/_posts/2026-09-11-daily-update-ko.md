---
title: "Anthropic 위협 보고서 충격 — Claude Code로 드론 군집 킬 소프트웨어 개발, '생물무기 임계값' 공식 돌파 선언"
date: 2026-09-11
lang: ko
categories: [news]
tags: [claude-code, anthropic, github-copilot, cursor, chatgpt, codex-cli]
excerpt: "Anthropic이 Claude Code로 자율 드론 군집 킬 소프트웨어가 개발됐다고 공개했다. 최신 모델이 생물무기 지원 임계값을 넘었다는 공식 인정은 AI 업계 최초다."
---

Anthropic이 오늘 발표한 위협 정보 보고서가 AI 코딩 도구 업계에 충격파를 던졌다. 러시아 연계 프리랜서 그룹이 Claude Code를 사용해 인간 표적을 자율 선정하고 기폭 명령을 내리는 완전 자율 드론 군집 소프트웨어를 개발한 사실이 드러났다([Anthropic](https://www.anthropic.com/threat-intelligence-report-september-2026)). 이란·러시아·중국·예멘 행위자들이 Claude를 미사일 항법, 사이버 공격, 국가 감시, 생물무기 연구에 활용한 정황도 포착됐다([Bloomberg](https://www.bloomberg.com/news/articles/2026-09-11/anthropic-says-us-adversaries-aimed-claude-at-weapons-research)).

## Anthropic: "최신 모델, 생물무기 임계값 이하로 더 이상 간주 불가"

보고서에서 가장 무거운 대목은 Anthropic이 최신 Claude 모델이 의미 있는 생물무기 지원 임계값을 더 이상 밑돈다고 단정할 수 없다고 공식 인정한 것이다([TechTimes](https://www.techtimes.com/articles/327308/20260911/anthropic-threat-report-ai-models-near-bioweapons-threshold-drone-kill-software-emerges.htm)). 주요 AI 기업이 이를 공개적으로 밝힌 것은 이번이 처음이다. 2025년 12월부터 2026년 8월까지 생물무기 관련 5건을 적발·차단했으며, 치쿤구니야 바이러스 기능 획득 연구 지원금 신청을 도운 사례도 포함됐다([Interesting Engineering](https://interestingengineering.com/ai-robotics/anthropic-scientists-claude-lethal-bioweapons-research)).

## Claude Code v2.1.267: maxEffortLevel로 비용 통제, 9/14 한도 삭감 D-3

위협 보고서와 별개로 Claude Code는 기능 업데이트를 이어갔다. v2.1.267에서 `maxEffortLevel` 설정이 추가돼 Bedrock·Vertex·Foundry 포함 전 프로바이더의 effort 레벨 상한을 걸 수 있게 됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 9월 14일 주간 한도 17% 실효 삭감까지 D-3으로, 50% 프로모션 종료가 코앞이다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)). effort 제어 도구를 한도 삭감 직전에 내놓은 타이밍이 의미심장하다.

## Cursor: 67점, 16일째 연속 하락 — OpenAI 셧오프 D-62

Cursor가 67로 떨어지며 8월 27일 99점 정점에서 32포인트가 빠졌다. OpenAI 모델 차단(11/12)까지 62일 남았다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). OpenAI 트래픽 비중은 5%에 불과하지만, 심리적 이탈 속도가 기술적 영향을 압도하는 구도가 지속되고 있다.

## GitHub Copilot: 10월 3연타 D-17

9/28 통합 리런치, 10/1 선불 좌석 과금, 10/2 모델 대량 퇴장이 17일 뒤 연달아 시행된다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Gemini 3.5/3.6 Flash → 3.8 Flash, Claude Opus 4.7 → Opus 5 교체가 예정돼 있어 Enterprise 워크플로우 점검이 시급하다([DMarketer Tayeeb](https://dmarketertayeeb.com/blog/github-copilot-september-2026-model-budget-review-changes/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra GA 1주, Voice Mode 확대 |
| Claude Code | 99 | — | 위협 보고서 발표, v2.1.267, 9/14 한도 삭감 D-3 |
| Claude AI | 99 | — | 생물무기 임계값 돌파 공식 인정 |
| Codex CLI | 99 | — | Astra 통합 완료, worktree 실험 |
| Antigravity | 99 | — | /boost 안정, GEMINI_API_KEY 지원 |
| Windsurf | 87 | — | Cognition $48B 모멘텀 유지 |
| Cursor | 67 | ↓2 | 16일째 하락, 정점 대비 -32p |
| Aider | 68 | — | v0.86.2 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 10월 3연타 D-17 |
| Gemini CLI | 1 | — | 폐쇄 85일째, Antigravity 대체 |

Anthropic이 자사 모델의 무기화 사례를 직접 공개한 것은 투명성 측면에서 전례 없는 수준이다. 그러나 "생물무기 임계값 돌파"라는 공식 선언은 AI 안전 논쟁의 새로운 국면을 예고한다 — 도구의 능력이 올라갈수록 악용 차단의 난이도도 함께 올라가는 딜레마가 이제 이론이 아닌 현실이 됐다.

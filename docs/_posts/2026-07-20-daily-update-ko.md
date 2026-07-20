---
title: "OpenAI 4일 연속 장애 속 Fable 5 유료 전환 — Kimi K3, Arena.ai 프론트엔드 1위 등극"
date: 2026-07-20
lang: ko
categories: [news]
tags: [openai, claude, fable-5, kimi-k3, codex, cursor, copilot, antigravity, gemini]
excerpt: "OpenAI가 7월 17일부터 4일 연속 서비스 장애를 겪는 사이, Fable 5 무료 접근이 공식 종료됐고, Moonshot AI의 Kimi K3가 Arena.ai 프론트엔드 코드 부문 1위를 차지했다."
---

OpenAI가 흔들리고 있다. 7월 17일 GPT-5.6 Sol 서버 과부하를 시작으로 18일 약 5시간 Codex 접근 불가, 19일 ChatGPT 오류 상승, 20일 GitHub 연동 Codex 워크플로 오류까지 — 4일 연속 장애가 이어지고 있다([OpenAI Status](https://status.openai.com/history)). GPT-5.6 Sol이 ChatGPT 기본 모델로 안착하는 과도기에 인프라가 부하를 감당하지 못하는 모습이다.

## Fable 5: 무료 시대의 끝

Anthropic Fable 5의 무료 접근이 7월 19일 PT 11:59 PM을 기점으로 공식 만료됐다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/claude-fable-5-stays-free-for-paid-users-until-july-19-as-anthropic-buys-more-time/)). Pro 플랜 사용자는 이제 입력 $10/MTok, 출력 $50/MTok의 프리페이드 크레딧이 필요하다 — Opus 4.8 대비 2배 가격이다([TechTimes](https://www.techtimes.com/articles/320905/20260718/claude-fable-5-ends-subscription-limbo-permanent-max-credits-only-pro.htm)). Max 플랜에서만 Fable 5가 정규 포함 모델로 유지되며, Claude Code의 50% 주간 한도 보너스도 동시에 만료됐다. 원래 6/22, 7/7, 7/12 만료 예정이었으나 세 차례 연장 끝에 최종 종료됐다([Forbes](https://www.forbes.com/sites/sandycarter/2026/07/13/claude-fable-5-extends-to-july-19-7-days-7-power-moves/)). 한편 Anthropic IPO 로드쇼가 개시돼 투자자 미팅 일정이 조율되고 있으며, 10월 상장을 목표로 한다([CNBC](https://www.cnbc.com)).

## Kimi K3: Fable 5를 꺾은 2.8조 파라미터 모델

Moonshot AI가 7월 16일 Kimi K3를 출시했다 — 2.8조 파라미터 MoE 모델로 Arena.ai 프론트엔드 코드 아레나에서 76% 쌍별 승률로 Claude Fable 5를 제치고 1위를 차지했다([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/moonshot-releases-2-8-trillion-parameter-kimi-k3)). 가격은 $3/$15 per MTok으로 Fable 5의 3분의 1 수준이며, 오픈 웨이트는 7/27 공개 예정이다. 중국 AI 업체의 "DeepSeek 모먼트" 재현이라는 시장 반응이 나오고 있다([Fortune](https://fortune.com/2026/07/17/china-moonshot-kimi-k3-markets-china-ai/)).

## Gemini 3.5 Pro: 세 번째 데드라인도 불발

Google의 Gemini 3.5 Pro가 7월 17일 세 번째 GA 목표일을 넘겼다. Bloomberg에 따르면 Google은 코딩과 복잡 추론 성능 미달로 기존 기반 모델을 폐기하고 처음부터 재구축 중이며, Alphabet 주가는 ~4% 하락했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-07-16/google-gemini-launch-delayed-as-tech-falls-short-of-internal-goals)). 6월, 7월 초, 7월 17일까지 세 차례 데드라인을 모두 넘긴 상태다([9to5Google](https://9to5google.com/2026/07/16/gemini-3-5-pro-delays/)).

## Cursor iOS 퍼블릭 베타 + Slack 멀티리포

Cursor for iOS가 모든 유료 플랜에서 퍼블릭 베타로 사용 가능해졌다([Cursor Blog](https://cursor.com/blog)). Slack 연동도 크게 개선돼 작업 전 플랜 공유, 멀티 리포 환경, 채널/스레드 지원이 추가됐다([Cursor Changelog](https://cursor.com/changelog)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5 크레딧 전환, Opus 5 대기 |
| ChatGPT | 99 | — | 4일 연속 장애, GPT-5.6 Sol 과부하 |
| Antigravity | 99 | — | Gemini 3.5 Pro 지연 수혜 |
| Claude AI | 98 | — | Fable 5 유료 D+1, IPO 로드쇼 개시 |
| Cursor | 97 | — | iOS 퍼블릭 베타, Slack 멀티리포 |
| Codex CLI | 90 | — | v0.144.6, 4일 연속 장애 영향 |
| Windsurf | 85 | — | Devin Desktop v3.5.17 안정화 |
| Aider | 68 | — | 44K 스타, 릴리스 주기 둔화 |
| Copilot | 6 | ↓1 | 73주 하락, Code Quality GA 출시 |
| Gemini CLI | 6 | ↓1 | EOL 32일째, 3.5 Pro 세 번째 불발 |

OpenAI의 연이은 장애와 Kimi K3의 등장은 AI 코딩 도구 시장의 판도가 여전히 유동적임을 보여준다. Fable 5 유료 전환 후 비용 민감 사용자들의 이동이 주목된다.

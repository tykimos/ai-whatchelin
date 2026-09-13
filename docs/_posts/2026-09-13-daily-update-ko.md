---
title: "GPT-5.3-Codex-Spark 내일부터 퇴장 — McKinsey '기업 32%가 AI로 직접 만들고 SaaS 구매 포기'"
date: 2026-09-13
lang: ko
categories: [news]
tags: [openai, codex-cli, mckinsey, cursor, claude-code, nvidia, hugging-face, mechanical-turk]
excerpt: "OpenAI의 GPT-5.3-Codex-Spark가 내일(9/14~) 공식 퇴장한다. 한편 McKinsey 보고서는 기업 32%가 AI 코딩 에이전트로 소프트웨어를 직접 만들고 기존 SaaS 구매를 포기했다고 밝혔다."
---

OpenAI의 GPT-5.3-Codex-Spark가 내일(9월 14일 주간)부터 공식 퇴장한다 — 2월 출시 후 7개월 만이다([X/thsottiaux](https://x.com/thsottiaux/status/2098300998968357218)). OpenAI 핵심 프로덕트 리드 Tibo Sottiaux는 "사용량이 꾸준히 줄었고 지금은 훨씬 나은 모델이 있다"고 배경을 설명했다. GPT-6-Astra가 9/3부터 권장 Codex 모델로 완전 배포된 상황에서, Spark의 퇴장은 예견된 수순이었다([PANews](https://panews.io/articles/01a08f37-5742-73bd-af93-572558a0cf0a)).

## McKinsey: 기업 32%가 '만들기'로 전환, SaaS 구매 포기

McKinsey의 2026 AI 현황 보고서(5~6월 조사, 97개국 1,719명)에 따르면 기업 32%가 AI 코딩 에이전트를 활용해 소프트웨어를 직접 만들고 기존 제품 구매를 포기했다([Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/build-vs-buy-shift-32-113806700.html)). 테크(41%)와 헬스케어(39%) 업종이 선두이며, 연매출 $10억 이상 기업의 40%가 에이전트 도입을 확대 중이다([McKinsey via ANI](https://aninews.in/news/business/ai-coding-agents-threaten-to-reshape-software-spending-as-companies-choose-to-build-rather-than-buy-mckinsey20260906210256/)). 토큰 비용이 제약이라고 답한 기관은 약 20%에 불과해, 비용보다 역량이 전환의 핵심 동인임을 보여준다.

## Cursor: Projects 4일차, 하락 20일째

Cursor Projects 베타가 코디네이터 에이전트 구조로 수천 개의 서브에이전트를 오케스트레이션하며 주목받고 있지만, 하락세는 멈추지 않았다([Cursor Changelog](https://cursor.com/changelog/projects)). 오늘 점수 66으로 20일 연속 하락이며, OpenAI 모델 차단(11/12)까지 D-60이 남았다. SpaceX 인수 후 독자 모델 전략 수립이 시급하다.

## Amazon Mechanical Turk: 종료 D-17

2005년 출시된 Amazon Mechanical Turk가 9월 30일 완전 종료된다([Quartz](https://qz.com/amazon-mechanical-turk-shutting-down-082626)). 피크 시절 50만 명 이상의 워커가 활동했던 플랫폼이지만, Scale AI·Mercor·Prolific 등 전문 데이터 라벨링 스타트업의 부상과 AI 모델 발전으로 역할을 다했다([TechSpot](https://www.techspot.com/news/113643-amazon-shutting-down-mechanical-turk-after-more-than.html)). AI 훈련 데이터 생태계의 세대교체를 상징하는 사건이다.

## Claude Code: v2.1.268, 플러그인 에발 & 게이트웨이 통합

Claude Code가 v2.1.268에서 앱 게이트웨이 요금 통합, 게이트웨이 접근 제어 경고, 조직 IPv4 블록 지원을 추가했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 최근 릴리스들에서 `/output-style` 명령, 관리형 MCP 서버, GitLab MR 인식, `/plugin` 개선(재시작 없이 즉시 적용) 등 워크플로 전반의 품질 개선이 이어지고 있다.

## Nvidia-Hugging Face: $129억 인수 진행 중

Nvidia가 9/2 Hugging Face를 $129억에 인수하는 확정 계약을 체결했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-09-03/nvidia-agrees-to-13-billion-deal-for-ai-platform-hugging-face)). 300만 모델, 100만 앱, 1,800만 개발자 생태계를 품게 되며, 내년 상반기 마감 예정이다([CNBC](https://www.cnbc.com/2026/09/03/nvidia-agrees-to-buy-hugging-face-for-almost-13-billion-ai-expansion.html)). 별도로 Hugging Face는 LLM 커널 라이브러리를 개편해 추론 비용을 최대 40% 절감했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6-Astra 완전 배포 완료 |
| Claude Code | 99 | — | v2.1.268, 플러그인 에발 출시 |
| Claude AI | 99 | — | 위협 보고서 여파 지속 |
| Codex CLI | 99 | — | Spark 퇴장 D-1, Agents API 퍼블릭 베타 |
| Antigravity | 99 | — | 28주째 99 유지 |
| Windsurf | 87 | — | 엔터프라이즈 포지셔닝 안정 |
| Aider | 68 | — | 오픈소스 1위 유지, 릴리스 대기 |
| Cursor | 66 | ↓1 | Projects 4일차, 20일 연속 하락 |
| GH Copilot | 1 | — | 바닥, 10/2 모델 대청소 D-19 |
| Gemini CLI | 1 | — | 셧다운 88일차 |

McKinsey의 '만들기 vs 사기' 전환 데이터가 코딩 에이전트 시장의 구조적 변화를 확인시켜 준다. Spark 퇴장과 함께 모델 세대교체가 가속화되는 가운데, Cursor만 유독 역풍을 맞고 있다.

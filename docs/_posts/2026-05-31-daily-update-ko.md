---
title: "Copilot 토큰 과금 D-Day, Build 전야의 숨 고르기"
date: 2026-05-31
lang: ko
categories: [news]
tags: [copilot, microsoft-build, codex-cli, gemini-cli, antigravity]
excerpt: "GitHub Copilot의 사용량 기반 과금이 내일 시행된다. TechCrunch는 '무슨 농담이야'라는 개발자 반응을 전했고, Microsoft Build 2026은 내일 개막해 Project Polaris로 반격을 노린다. Codex CLI Pro 부스트도 오늘 만료."
---

6월 1일이 내일이다. GitHub Copilot의 정액제가 끝나고 토큰 기반 AI 크레딧 과금이 시작되는 날 — 27주 연속 하락해 56까지 추락한 Copilot에게 가장 중대한 변곡점이 도래했다.

## Copilot: "무슨 농담이야" — 토큰 과금 D-Day

TechCrunch가 "'무슨 농담이야': GitHub Copilot의 새 토큰 과금이 개발자들의 분노를 산다"는 제목으로 보도했다([TechCrunch](https://techcrunch.com/2026/05/30/what-a-joke-github-copilots-new-token-based-billing-spurs-consternation-among-devs/)). 공식 커뮤니티 스레드에는 400개 이상의 댓글과 900건 가까운 반대표가 쏟아졌다. Pro는 월 $10 크레딧, Pro+는 $39, Business는 $19/사용자, Enterprise는 $39/사용자를 받지만 — 프론티어 모델 에이전트 세션 한 번에 30~40 크레딧이 사라져 하루 만에 한도를 소진할 수 있다([TechTimes](http://www.techtimes.com/articles/317456/20260531/github-copilot-billing-switches-token-costs-today-agentic-users-face-steepest-increases.htm)). 에이전틱 헤비 유저는 월 $29에서 $750까지 비용 폭등을 예상한다. 다만 기존 Business/Enterprise 구독자에게는 8월 31일까지 프로모션 할당(3,000/7,000 크레딧)이 적용된다. 코드 완성은 무료로 유지된다.

## Microsoft Build 2026 D-1: Project Polaris로 반격

Build 2026이 내일(6/2) 샌프란시스코 포트메이슨에서 개막한다 — Satya Nadella 키노트가 오전 9:30 PT에 예정되어 있다([Notebookcheck](https://www.notebookcheck.net/Microsoft-Build-2026-What-to-expect-from-the-June-2-keynote.1311546.0.html)). 핵심은 자체 코딩 모델 Project Polaris의 정식 공개다. MoE 아키텍처 기반으로 HumanEval과 MBPP에서 GPT-4 Turbo를 능가하며, IP 소송 보상 'Code Content Guarantee'가 포함된다([Windows News](https://windowsnews.ai/article/microsoft-build-2026-homegrown-ai-models-to-power-github-copilot.420887)). 멀티모달 코딩 데모 — 태블릿에 UI를 스케치하면 Copilot이 XAML+C# 코드를 생성 — 도 예고됐다. 참석자는 ~2,500명으로 제한되며, Azure AI Foundry와 AI 에이전트 프레임워크 발표가 예정되어 있다.

## Codex CLI: Pro 부스트 만료, 쿼터 충격

OpenAI의 한시적 2배 사용량 부스트가 오늘 만료된다([OpenAI Help Center](https://help.openai.com/en/articles/11369540-using-codex-with-your-chatgpt-plan)). Pro 5x 티어는 25x에서 20x Plus 기준으로 복귀하고, Pro $100의 두 배 할당도 소멸된다. 커뮤니티에서는 단일 프롬프트가 주간 한도의 7%를 소모한다는 보고가 나오고 있어([OpenAI Community](https://community.openai.com/t/codex-usage-after-the-limit-reset-update-single-prompt-eats-7-of-weekly-limits-plus-tier/1365284)), 부스트 만료 후 체감 충격이 클 전망이다. Codex CLI 점수는 88에서 87로 소폭 하락.

## Gemini CLI: 종료 D-18, 이탈 계속

Gemini CLI 종료까지 18일 남았다. 6월 18일부로 Pro, Ultra, 무료 사용자 전원의 접근이 차단되며, Antigravity CLI로의 전환이 가속화되고 있다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). 오픈소스 Apache 2.0 프로젝트가 폐쇄 소스 후속작으로 대체된다는 점에서 커뮤니티 불만이 지속되고 있다. Antigravity는 60으로 소폭 회복 중.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 안정, Mythos 수주 내 공개 |
| ChatGPT | 96 | — | 5/29 장애 후 안정 |
| Cursor | 96 | — | Build D-1 관망, xAI Colossus 2 |
| Claude AI | 95 | — | IPO 10월 추진, $965B 밸류에이션 |
| Codex CLI | 87 | ↓1 | Pro 부스트 만료, GPT-5.6 기대 |
| Windsurf | 81 | — | Devin Local 업데이트 안정 |
| Gemini CLI | 75 | ↓1 | 종료 D-18, 이탈 지속 |
| Antigravity | 60 | ↑1 | v2.0.0 패치 후 완만한 회복 |
| Aider | 68 | — | 오픈소스 기반 안정 |
| GH Copilot | 56 | ↓1 | 27주 최저, 토큰 과금 D-Day |

Copilot의 토큰 과금 전환과 Build 2026 키노트가 동시에 터지는 내일이 올해 AI 코딩 시장의 가장 결정적인 하루가 될 수 있다. Project Polaris가 27주 하락을 멈출 수 있을지 — 아니면 개발자들이 이미 발걸음을 옮긴 뒤인지.

---

*출처: 각 문장에 인라인 표기*

---
title: "Copilot, 오픈웨이트·비전·자동라우팅 삼중 업데이트 — 그래도 57주째 하락"
date: 2026-07-02
lang: ko
categories: [news]
tags: [copilot, kimi-k2-7, claude-code, fable-5, antigravity, cursor, gemini-cli, gpt-5-6]
excerpt: "GitHub Copilot이 Kimi K2.7 오픈웨이트 모델, Vision GA, 자동 모델 선택을 한꺼번에 출시했지만 57주 연속 하락을 멈추지 못했다. Claude Code v2.1.198은 Chrome GA와 백그라운드 에이전트 자동 PR을 도입했고, Antigravity는 13주 연속 상승으로 90선을 돌파했다."
---

GitHub Copilot이 하루 사이에 세 가지 대형 업데이트를 쏟아냈다. 오픈웨이트 모델 Kimi K2.7 Code를 모델 피커에 올리고, 이미지·PDF를 채팅에 붙일 수 있는 Vision을 전 구독자에게 개방하고, 작업 특성에 따라 모델을 자동 라우팅하는 Auto Model Selection을 정식 출시했다([GitHub Changelog](https://github.blog/changelog/2026-07-01-kimi-k2-7-is-now-available-in-github-copilot/)). 하지만 57주 연속 하락 행진은 멈추지 않았다.

## Copilot: 삼중 업데이트에도 24점 — 종량제 32일차

Kimi K2.7 Code는 Copilot 모델 피커에 등장한 최초의 오픈웨이트 모델이다([GitHub Changelog](https://github.blog/changelog/2026-07-01-kimi-k2-7-is-now-available-in-github-copilot/)). Microsoft Azure에서 호스팅되며 Pro/Pro+/Max 플랜에 순차 배포 중이고, Business/Enterprise는 관리자가 정책에서 활성화해야 사용할 수 있다. Copilot Vision도 7월 1일 GA로 전환되어 Free 포함 전 구독자에게 이미지·PDF 첨부 기능을 개방했다([GitHub Changelog](https://github.blog/changelog/2026-07-01-copilot-vision-is-generally-available/)). 자동 모델 선택은 작업의 추론 복잡도, 코드 생성 난이도, 도구 오케스트레이션 필요도를 실시간 평가해 최적 모델을 라우팅한다([GitHub Changelog](https://github.blog/changelog/2026-07-01-copilot-cli-auto-model-selection-routes-based-on-task/)). 그러나 이 모든 기능에도 Copilot 인기도는 57주 연속 하락해 24점을 기록했다 — 종량제 첫 달 $30-40/일 에이전틱 세션 비용 충격이 이탈을 가속화하고 있다.

## Claude Code v2.1.198: Chrome GA, 백그라운드 에이전트 자동 PR

Claude Code v2.1.198이 7월 1일 릴리스됐다([GitHub Releases](https://github.com/anthropics/claude-code/releases)). 핵심은 세 가지다: Chrome 통합이 GA로 전환됐고, 워크트리에서 작업 중인 백그라운드 에이전트가 완료 시 자동으로 커밋·푸시·드래프트 PR을 생성하게 됐으며, 에이전트 완료나 입력 필요 시 Notification 훅이 발동되는 알림 시스템이 추가됐다. /dataviz 스킬도 새로 도입되어 차트·대시보드 디자인 가이드를 제공한다. Sonnet 5가 기본 모델로 확정되며 1M 컨텍스트와 $2/$10/MTok 프로모션 가격이 8월 31일까지 적용된다([Anthropic](https://www.anthropic.com/news/claude-sonnet-5)).

## Fable 5 복원 D+2 — 순조로운 진행, 클라우드 접근 복원 중

Fable 5 전 세계 복원 이틀째가 큰 문제 없이 마무리됐다([ExplainX](https://explainx.ai/blog/is-fable-5-back-2026)). 99%+ 탈옥 차단 분류기가 가동 중이며 7월 7일까지 주간 사용량 50% 한도가 유지된다. AWS·Google Cloud·Azure 접근은 "최대한 빨리" 복원 중이나 완료되지 않았다([CNBC](https://www.cnbc.com/2026/06/30/anthropic-says-trump-admin-has-lifted-export-controls-on-claude-fable-5-and-mythos-5.html)).

## Antigravity 90 돌파 — 13주 연속 상승

Google Antigravity가 90점을 돌파하며 13주 연속 상승세를 이어갔다. Gemini CLI 셧다운 이후 가장 큰 수혜자로, Codex CLI(88)와의 격차를 2점으로 벌리며 사실상 3위권을 확고히 했다.

## GPT-5.6 Sol/Terra/Luna: 제한 프리뷰 지속, GA "수 주 내"

6월 26일 발표된 GPT-5.6 삼중 모델 체계가 ~20개 사전승인 기관에서 제한 프리뷰를 이어가고 있다([OpenAI](https://openai.com/index/previewing-gpt-5-6-sol/)). Sol은 $5/$30, Terra는 $2.50/$15, Luna는 $1/$6/MTok이며, Cerebras에서 750 tok/s 속도로 7월 중 출시될 예정이다([VentureBeat](https://venturebeat.com/technology/openai-unveils-gpt-5-6-sol-terra-and-luna-models-but-only-accessible-to-limited-preview-partners-for-now-per-us-gov/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.198 Chrome GA, Sonnet 5 기본, Fable 5 복원 |
| Claude AI | 98 | — | Claude Science 출시, Fable 5 + Sonnet 5 모멘텀 |
| ChatGPT | 97 | — | GPT-5.6 Sol 제한 프리뷰, Cerebras 7월 출시 |
| Cursor | 96 | — | Teams 가격 발효, iOS 퍼블릭 베타 75% 할인 |
| Antigravity | 90 | ↑1 | 13주 연속 상승, 90선 돌파 |
| Codex CLI | 88 | — | GPT-5.6 프리뷰 기관 제공 |
| Windsurf | 85 | — | Cascade 공식 종료, Devin Local 전환 완료 |
| Aider | 68 | — | 오픈소스 안정 유지 |
| Gemini CLI | 25 | ↓1 | 셧다운 14일째, Code Assist 7/17 종료 |
| Copilot | 24 | ↓1 | 57주 연속 하락, 삼중 업데이트도 종량제 반발 상쇄 못해 |

Copilot의 삼중 업데이트는 기술적으로 인상적이지만, 종량제 과금의 구조적 문제를 해결하지 못했다. 반면 Claude Code는 v2.1.198에서 백그라운드 에이전트 자동 PR이라는 워크플로 혁신을 선보이며 99점을 유지하고 있다. Kimi K2.7의 Copilot 진입은 오픈웨이트 모델이 상용 IDE에 정식 통합되는 첫 사례로, 모델 선택의 민주화를 보여주는 이정표다.

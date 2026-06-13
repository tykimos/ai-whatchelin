---
title: "미국 정부, Fable 5 강제 중단 — 프론티어 AI 모델 최초 수출 통제 발동"
date: 2026-06-13
lang: ko
categories: [news]
tags: [anthropic, fable-5, mythos-5, export-control, amazon, copilot, gemini-cli, antigravity, spacex, claude-code]
excerpt: "출시 3일 만에 미국 상무부가 Claude Fable 5와 Mythos 5를 수출 통제 지시로 강제 중단시켰다. Amazon이 탈옥을 정부에 보고한 것으로 밝혀져 AI 업계가 충격에 빠졌다."
---

AI 역사상 전례 없는 일이 벌어졌다. 미국 정부가 공개 배포 중인 프론티어 AI 모델을 강제로 중단시킨 것은 이번이 처음이다. 6월 9일 출시되어 "메이저 버전 업그레이드급 도약"이라는 평가를 받던 Fable 5가 단 3일 만에 사라졌다.

## Fable 5 + Mythos 5: 상무부 수출 통제 강제 중단

상무장관 Howard Lutnick이 Anthropic CEO Dario Amodei에게 직접 수출 통제 지시를 내렸다([Anthropic 공식 성명](https://www.anthropic.com/news/fable-mythos-access)). 핵심은 외국 국적자에 대한 Fable 5·Mythos 5 접근을 전면 차단하라는 것이었으나, 기술적으로 국적 기반 분리가 불가능해 전체 사용자에게 서비스를 중단했다. Anthropic은 6월 12일 오후 5시 21분(ET)에 지시를 받고 즉시 조치했다([9to5Mac](https://9to5mac.com/2026/06/12/anthropic-pulls-claude-mythos-5-and-claude-fable-5-following-us-government-directive/)).

가장 충격적인 것은 이 탈옥을 상무부에 보고한 주체가 Anthropic의 투자자이자 클라우드 파트너인 **Amazon**이라는 점이다([Axios](https://www.axios.com/2026/06/13/anthropic-amazon-white-house)). Amazon은 목요일 밤 백악관 관계자에게 Mythos 모델의 사이버보안 기능을 탈옥해 국가안보 위협이 되는 부분에 접근할 수 있다는 보고서를 공유했다.

Anthropic은 해당 탈옥이 "좁고 비범용적"이며, 특정 한 가지 사례에서만 사이버보안 기능을 해제하는 것으로 GPT-5.5 등 다른 공개 모델에도 동일한 취약점이 존재한다고 반박했다([Fortune](https://fortune.com/2026/06/13/anthropic-disables-fable-mythos-export-controls-national-security-threat/)). Stripe의 5천만 줄 마이그레이션, NEC 3만 명 배포 등 대규모 엔터프라이즈 도입이 진행 중이던 터라, 산업 전체에 충격파가 퍼지고 있다.

## Copilot 40주 연속 하락 — 43점, 역대 최저

GitHub Copilot이 40주 연속 하락이라는 불명예를 기록하며 43점에 도달했다([GitHub Discussions](https://github.com/orgs/community/discussions/192948)). 사용량 기반 과금 13일차에도 안정화 조짐이 전혀 없다. Copilot CLI는 /agents 개선, /settings 통합 대화상자, 모노레포 검색 가속 등 6월 대규모 업데이트를 진행했지만 점수 하락을 막지 못하고 있다([GitHub Blog](https://github.blog/changelog/2026-06-02-copilot-cli-improved-ui-rubber-duck-prompt-scheduling-and-voice-input/)).

## Gemini CLI 종료 D-5: Antigravity 70 돌파

Gemini CLI 종료까지 5일 남았다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). Antigravity CLI로의 전환이 최종 단계에 진입해 Antigravity 인기도가 70을 돌파했고, Gemini CLI는 62로 하락했다. Go로 작성된 Antigravity CLI는 비동기 처리와 멀티에이전트 오케스트레이션을 지원하지만, "미끼-전환" 비판은 여전하다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)).

## Claude Code v2.1.173-175: 거버넌스 강화

Claude Code가 v2.1.175까지 빠르게 업데이트되며 16건의 변경사항을 반영했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). VS Code 사용량 귀속 기능(/usage에서 캐시 미스·서브에이전트별 분석), enforceAvailableModels 관리자 설정, 백그라운드 세션 환경변수 격리 수정 등이 포함됐다. Fable 5 중단 와중에도 Opus 4.8 기반의 정상 서비스는 영향받지 않았다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5 중단에도 Opus 4.8 기반 서비스 정상 |
| ChatGPT | 96 | — | GPT-5.2 삭제 완료, Codex 통합 가속 |
| Cursor | 96 | — | SPCX 안정세, $600억 인수 자금 확보 |
| Claude AI | 96 | — | 에이전트 과금 D-2, Fable 5 중단 충격 |
| Codex CLI | 87 | — | ChatGPT 통합 및 모바일 확장 |
| Windsurf | 85 | — | Devin Desktop 안정화, $15 가격대 |
| Antigravity | 70 | ↑1 | Gemini CLI D-5 마이그레이션 흡수 |
| Aider | 68 | — | 안정적 오픈소스 기반 |
| Gemini CLI | 62 | ↓1 | D-5 종료 카운트다운 |
| GH Copilot | 43 | ↓1 | 40주 연속 하락, 역대 최저 |

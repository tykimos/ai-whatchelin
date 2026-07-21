---
title: "Claude Code v2.1.216 보안 패치 — Devin Desktop 워크트리 세션, Kimi K3 오픈웨이트 D-6"
date: 2026-07-21
lang: ko
categories: [news]
tags: [claude, claude-code, devin, windsurf, openai, kimi-k3, copilot, gemini, antigravity]
excerpt: "Claude Code v2.1.216이 샌드박스 설정과 장시간 세션 성능 문제를 수정했고, Devin Desktop은 워크트리 기반 세션으로 대규모 업데이트됐다. Kimi K3 오픈웨이트 공개까지 6일."
---

Claude Code가 이틀 연속 릴리스를 내놓으며 안정성 개선에 집중하고 있다. v2.1.216은 장시간 세션에서 발생하던 이차(quadratic) 속도 저하를 수정하고 `sandbox.filesystem.disabled` 설정을 추가했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Devin Desktop도 7/19 대규모 업데이트로 워크트리 기반 세션과 네트워크 정책 제어를 도입하며 경쟁력을 끌어올렸다.

## Claude Code: v2.1.216 — 장시간 세션 속도 저하 수정

v2.1.215에 이어 하루 만에 v2.1.216이 출시됐다. 핵심 수정 사항: 장시간 세션에서 발생하던 이차 속도 저하(quadratic slowdown) 해결, 자동 모드에서 OAuth 토큰 만료 처리 수정, 재개된 백그라운드 세션의 에이전트 프롬프트·도구 제한 복원([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). `sandbox.filesystem.disabled` 설정이 새로 추가돼 엔터프라이즈 환경에서 파일시스템 샌드박스를 비활성화할 수 있게 됐다.

## Devin Desktop: 워크트리 세션 + 성능 대폭 개선

Windsurf에서 리브랜딩된 Devin Desktop이 7/19 주요 업데이트를 배포했다([Releasebot](https://releasebot.io/updates/windsurf)). 워크트리 기반 세션으로 즉시 열리는 세션 환경, 장시간 클라우드 세션의 렌더링·스크롤·타이핑 속도 개선, 네트워크 정책 제어, 멀티 워크스페이스 플러그인 시스템이 포함됐다. Claude Sonnet 5도 통합돼 8/31까지 Sonnet 4.6 대비 ~30% 적은 쿼터를 소비한다.

## OpenAI: 반복되는 장애, 안정성 의문

7/20에도 ChatGPT 장애가 보고됐다 — DownDetector 기준 ET 오후 2:30경 수백 명이 접속 불가를 신고했다([DesignTAXI](https://community.designtaxi.com/topic/33509-is-chatgpt-openai-down-july-20-2026/)). GPT-5.6 Sol이 기본 모델로 정착하는 과도기에 인프라 안정성 문제가 반복되고 있어, 엔터프라이즈 사용자들의 우려가 커지고 있다.

## Kimi K3: 오픈웨이트 7/27 공개 D-6

Moonshot AI의 Kimi K3 오픈웨이트(2.8조 파라미터) 공개까지 6일 남았다([kimi-k2.org](https://kimi-k2.org/blog/31-kimi-k3-open-weights-july-27)). Arena.ai 프론트엔드 코드 아레나 1위(1,679점)를 유지하며 Fable 5(1,631)와 GPT-5.6 Sol(1,618)을 앞서고 있다([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/moonshot-releases-2-8-trillion-parameter-kimi-k3)). 세계 최초 2.8T 오픈웨이트 모델이 될 전망이다.

## Copilot: Code Quality GA + Gemini 모델 종료 D-10

Copilot Code Quality가 GA로 전환돼 활성 커미터당 $10/월로 AI 기반 코드 품질 분석이 가능해졌다. 한편 Gemini 2.5 Pro와 Gemini 3 Flash의 7/31 전면 지원 종료까지 10일 남았다([GitHub Changelog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)). Copilot 인기도는 74주째 하락 중.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.216 안정성 패치, 이틀 연속 릴리스 |
| ChatGPT | 99 | — | 7/20 장애 재발, 인프라 불안 지속 |
| Antigravity | 99 | — | Gemini 3.5 Pro 지연 수혜 지속 |
| Claude AI | 98 | — | Fable 5 유료 D+2, IPO 로드쇼 |
| Cursor | 97 | — | SpaceX 인수 후 Grok 4.5 통합 |
| Codex CLI | 90 | — | v0.144.6 안정, 장애 영향권 |
| Windsurf | 85 | — | Devin Desktop 워크트리 세션 출시 |
| Aider | 68 | — | 44K 스타, 신규 릴리스 없음 |
| Copilot | 5 | ↓1 | 74주 하락, Code Quality GA |
| Gemini CLI | 5 | ↓1 | EOL 33일째, Antigravity CLI 2.0 대체 |

Claude Code가 이틀 연속 릴리스로 안정성에 투자하는 동안, Devin Desktop은 워크트리 세션으로 개발자 경험을 개선하고 있다. Kimi K3 오픈웨이트 공개(7/27)가 다가오면서 AI 코딩 도구 시장의 다음 변곡점이 예고된다.

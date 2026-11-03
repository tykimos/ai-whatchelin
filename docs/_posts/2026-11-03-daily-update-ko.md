---
title: "Goldman Sachs, AI 코딩 도구 접근 엔지니어로 제한 — 기업 보안 기류 변화"
date: 2026-11-03
lang: ko
categories: [news]
tags: [cursor, claude-code, supply-chain, security, github-copilot, codex-cli, anthropic, goldman-sachs, bytedance]
excerpt: "Goldman Sachs가 Claude Code와 GitHub 도구 접근을 엔지니어링 인력으로 제한했다. ByteDance도 외부 AI 도구를 차단하며, 기업 보안 기류가 빠르게 바뀌고 있다."
---

Cursor 마켓플레이스 공급망 공격의 여진이 가라앉기도 전에, 월가와 중국 빅테크에서 AI 코딩 도구 접근 제한 소식이 동시에 터졌다. 기업들이 AI 코딩 도구의 생산성과 보안 리스크 사이에서 선택을 강요받고 있다.

## Goldman Sachs: AI 코딩 도구 접근을 엔지니어로 제한

Goldman Sachs가 10월 내부 지침을 업데이트하여 Claude Code와 Microsoft의 GitHub 도구 등 고급 AI 코딩 도구의 접근 권한을 엔지니어링 인력으로 제한했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-11-02/goldman-sachs-restricts-ai-coding-tools)). 공식적인 사유는 "생산성 및 리스크 관리"로, 자체 개발한 사내 AI 도구는 전사적으로 계속 사용 가능하다. Cursor 공급망 공격 직후 나온 조치라 업계의 주목을 받고 있다.

## ByteDance: 외부 AI 도구 전면 차단

ByteDance가 11월부터 Claude, Codex 등 외부 AI 도구의 사내 사용을 대폭 제한한다([BigGo Finance](https://finance.biggo.com/news/68f066e2-0cea-44aa-944f-4bc8a4038a16)). L4 수준 코드 저장소와 Feishu 문서에서 외부 AI 접근이 차단된다. 자체 AI 역량 강화와 기밀 코드 보호가 목적으로 보인다.

## Cursor: 변조된 Claude Code 확장 프로그램 공급망 공격

10월 29일, Cursor 마켓플레이스에서 Anthropic의 Claude Code 확장 프로그램을 사칭한 변조 버전(2.1.313)이 약 11시간 동안 유통되어 최대 5,000명의 사용자가 노출되었다([BleepingComputer](https://www.bleepingcomputer.com/news/security/malicious-claude-code-extension-on-cursor-planted-ssh-backdoors/)). SSH 백도어 설치를 시도했으나 멀웨어 코드 버그로 대부분 실패한 것으로 분석된다([Sophos](https://www.sophos.com/en-us/blog/malicious-claude-code-extension-distributed-through-cursor-marketplace)). Cursor는 2.1.314 버전 업데이트를 권고했고([SecurityWeek](https://securityweek.com/malicious-claude-code-extension-served-in-cursor-supply-chain-attack)), 같은 날 내장 브라우저의 별도 자동 실행 취약점도 보고되었다([Infosecurity Magazine](https://www.infosecurity-magazine.com/news/cursor-autorun-flaw-repos-execute/)).

## Cursor: OpenAI 모델 접근 차단 D-9

11월 12일 OpenAI 모델 접근 완전 차단까지 9일 남았다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-29/openai-to-end-partnership-with-cursor-after-spacex-acquisition)). Cursor CEO Michael Truell은 OpenAI 트래픽이 전체의 약 5%에 불과하다며 협상 중이라 밝혔으나, 공급망 공격과 맞물려 점수 70일 연속 1점을 기록 중이다.

## Anthropic: IPO S-1 공개, 로드쇼 D-7

Anthropic이 10월 26일 SEC에 S-1 등록신고서를 공식 제출했다([CryptoBriefing](https://cryptobriefing.com/anthropic-nasdaq-ipo-listing-2026/)). 티커 ANT, 상장 거래소 Nasdaq Global Select Market. 아직 수정 S-1에 가격 범위가 게시되지 않아 로드쇼 시작일이 확정되지 않았지만, 이르면 11월 10일 시작이 가능하다([Leverage Shares](https://leverageshares.com/us/insights/when-is-the-anthropic-ipo/)). 추수감사절 전 상장이 유력한 시나리오다([Parameter](https://parameter.io/claude-creator-prepares-100-billion-public-offering-ahead-of-thanksgiving/)).

## GitHub Copilot: 75점, 39일 연속 상승 — 11/16 모델 교체 확정

GitHub Copilot이 39일 연속 상승하며 75점을 기록했다. 11월 16일 Claude Opus 4.8, Claude Opus 5, GPT-5.6 Terra가 제거되고 Claude Opus 5.5와 GPT-6.1 Sol로 교체된다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). 12월 1일부터는 AI 크레딧 기반 과금 체계로 전면 전환된다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)).

## Codex CLI: v0.166.0 안정적 운영

Codex CLI v0.166.0이 10월 29일 출시되어 키보드 기반 트랜스크립트 선택, `codex queue --resume`, `codex doctor --network-only` 등이 추가되었다([DEV Community](https://dev.to/aicoding-guide/this-week-in-claude-code-codex-and-gemini-cli-week-of-november-1-2026-15pn)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 안정, 12월 Codex 풀 병합 예정 |
| Claude Code | 99 | — | Goldman Sachs 제한 조치, 핵심 제품 무영향 |
| Codex CLI | 99 | — | v0.166.0 안정 운영 |
| Antigravity | 99 | — | Gemini 4 Argon Pro 롤아웃 |
| Claude AI | 99 | — | ANT S-1 공개, 로드쇼 D-7 최소 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| GH Copilot | 75 | ↑2 | 39일 연속 상승, 11/16 모델 교체 확정 |
| Aider | 68 | — | 유지보수 모드 |
| Cursor | 1 | — | 공급망 공격 + OpenAI 차단 D-9, 70일째 바닥 |
| Gemini CLI | 1 | — | 서비스 종료, Antigravity 전환 완료 |

Goldman Sachs와 ByteDance의 동시다발적 제한 조치는 단발성이 아닌 구조적 흐름으로 보인다. Cursor 공급망 공격이 기업 보안 의사결정의 전환점이 된 셈이다.

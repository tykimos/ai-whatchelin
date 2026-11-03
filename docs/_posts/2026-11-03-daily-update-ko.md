---
title: "Cursor 마켓플레이스 공급망 공격, 5천 명 개발자 SSH 백도어에 노출"
date: 2026-11-03
lang: ko
categories: [news]
tags: [cursor, claude-code, supply-chain, security, github-copilot, codex-cli, anthropic]
excerpt: "Cursor 마켓플레이스에서 변조된 Claude Code 확장 프로그램이 유포되어 최대 5,000명의 개발자에게 SSH 백도어가 설치될 뻔했다. OpenAI 모델 접근 차단까지 D-9."
---

AI 코딩 도구 생태계에서 보안 신뢰가 시험대에 올랐다. Cursor 마켓플레이스를 통해 변조된 Claude Code 확장 프로그램이 유포된 사건이 주요 보안 매체를 통해 확인되면서, 개발자 도구 공급망 보안에 대한 경각심이 높아지고 있다.

## Cursor: 변조된 Claude Code 확장 프로그램 공급망 공격

10월 29일, Cursor 마켓플레이스에서 Anthropic의 Claude Code 확장 프로그램을 사칭한 변조 버전(2.1.313)이 약 11시간 동안 유통되어 최대 5,000명의 사용자가 노출되었다([BleepingComputer](https://www.bleepingcomputer.com/news/security/malicious-claude-code-extension-on-cursor-planted-ssh-backdoors/)). 변조된 확장 프로그램은 로드 시 자동으로 실행되며 지속적인 SSH 백도어 설치를 시도했으나, 멀웨어의 SSH 설정 코드에 버그가 있어 실제 원격 접속은 대부분 실패한 것으로 보인다([Sophos](https://www.sophos.com/en-us/blog/malicious-claude-code-extension-distributed-through-cursor-marketplace)). Anthropic은 공식 채널은 영향받지 않았다고 밝혔고, Cursor는 2.1.314 버전으로 업데이트를 권고했다([SecurityWeek](https://securityweek.com/malicious-claude-code-extension-served-in-cursor-supply-chain-attack)). 한편 같은 날 Cursor의 내장 브라우저에서 별도의 자동 실행 취약점도 보고되어, Cursor의 보안 체계 전반에 의문이 제기되고 있다([Infosecurity Magazine](https://www.infosecurity-magazine.com/news/cursor-autorun-flaw-repos-execute/)).

## Cursor: OpenAI 모델 접근 차단 D-9

11월 12일 OpenAI 모델 접근 완전 차단까지 9일 남았다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-29/openai-to-end-partnership-with-cursor-after-spacex-acquisition)). 공급망 공격에 이어 모델 접근까지 끊기면서, Cursor의 점수는 70일 연속 1점을 기록 중이다. SpaceX 인수 이후 계속되는 악재의 연속이다.

## Codex CLI: v0.166.0 안정적 운영

Codex CLI v0.166.0이 10월 29일 출시되어 키보드 기반 트랜스크립트 선택, `codex queue --resume` 기능, `codex doctor --network-only` 진단 도구 등이 추가되었다([DEV Community](https://dev.to/aicoding-guide/this-week-in-claude-code-codex-and-gemini-cli-week-of-november-1-2026-15pn)). 직전 v0.165.0에서는 Vertex AI 프로바이더 지원과 메모리 기본 활성화가 도입된 바 있다.

## GitHub Copilot: 75점, 39일 연속 상승

GitHub Copilot이 39일 연속 상승하며 75점을 기록했다. Copilot CLI가 네이티브 Rust 엔진으로 전환되어 성능이 개선되었고([GitHub Blog](https://github.blog/changelog/)), 11월 16일에는 모델 라인업 새로고침(Opus 5.5, GPT-6.1 Sol)이 예정되어 있다. 12월 1일부터는 AI 크레딧 기반 과금 체계로 전면 전환된다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)).

## Anthropic: IPO S-1 공개, 로드쇼 카운트다운

Anthropic이 10월 26일 SEC에 S-1 등록신고서를 공식 제출했다([CryptoBriefing](https://cryptobriefing.com/anthropic-nasdaq-ipo-listing-2026/)). 티커는 ANT, 상장 거래소는 Nasdaq Global Select Market이다. 다만 주당 가격 범위는 아직 공란으로, 수정 S-1 제출과 함께 확정될 예정이다. 기밀 제출 이후 공개까지 최소 15일이 필요하므로, 로드쇼는 이르면 11월 10일 시작이 가능하다([Leverage Shares](https://leverageshares.com/us/insights/when-is-the-anthropic-ipo/)). Bloomberg는 11월 9일 주간 마케팅 개시를 보도했으며, 상장은 추수감사절 이전 11월 중순이 유력하다([Parameter](https://parameter.io/claude-creator-prepares-100-billion-public-offering-ahead-of-thanksgiving/)).

## GitHub Copilot: 11월 16일 모델 교체 세부사항 확정

GitHub가 11월 16일부로 Claude Opus 4.8, Claude Opus 5, GPT-5.6 Terra를 Copilot 전 환경에서 제거한다고 공식 발표했다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). 대체 모델은 Claude Opus 5.5와 GPT-6.1 Sol이며, Enterprise·Business 고객은 기본 설정으로 자동 전환된다. 연간 구독 개인 사용자의 Opus 4.8은 예외 적용된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 안정, 12월 Codex 풀 병합 예정 |
| Claude Code | 99 | — | 공급망 공격은 Cursor 측 문제, 본체 무영향 |
| Codex CLI | 99 | — | v0.166.0 안정 운영 |
| Antigravity | 99 | — | Gemini 4 Argon Pro 롤아웃 |
| Claude AI | 99 | — | ANT S-1 공개, 로드쇼 D-7 최소 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| GH Copilot | 75 | ↑2 | 39일 연속 상승, 11/16 모델 교체 확정 |
| Aider | 68 | — | 유지보수 모드 |
| Cursor | 1 | — | 공급망 공격 + OpenAI 차단 D-9, 70일째 바닥 |
| Gemini CLI | 1 | — | 서비스 종료, Antigravity 전환 완료 |

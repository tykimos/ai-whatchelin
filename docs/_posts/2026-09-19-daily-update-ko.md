---
title: "Claude Code, Codex와의 호환 선언 — AGENTS.md 지원 추가 · Cursor 30일 연속 하락"
date: 2026-09-19
lang: ko
categories: [news]
tags: [claude-code, cursor, openai, codex-cli, antigravity, agents-md]
excerpt: "Claude Code v2.1.277이 AGENTS.md 읽기를 지원하면서 Codex 프로젝트와의 호환성을 확보했다. Cursor는 30일 연속 하락으로 53점까지 떨어졌다."
---

Claude Code가 오늘 출시한 v2.1.277에서 AGENTS.md 파일 읽기를 공식 지원하기 시작했다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). CLAUDE.md가 없는 프로젝트에서 AGENTS.md를 자동으로 읽어 프로젝트 지침으로 사용하는 방식으로, 사실상 OpenAI Codex CLI의 프로젝트 설정 포맷과 호환되는 셈이다. 터미널 기반 에이전트 간 상호운용성의 첫 번째 공식 사례로, 개발자들이 도구를 전환할 때의 마찰을 크게 줄여준다.

## Claude Code: AGENTS.md 지원으로 Codex 생태계 포용

v2.1.277의 핵심은 AGENTS.md 호환이다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). 또한 API·Enterprise·Bedrock·Vertex·Foundry·게이트웨이 사용자의 자동 모드가 서버사이드 분류기를 기본값으로 변경되어, 분류기 오버헤드가 과금되지 않게 되었다. 게이트웨이 프록시 설정을 위한 `CLAUDE_GATEWAY_PROXY_IS_EGRESS_BOUNDARY` 환경변수와 업스트림 정적 헤더 맵도 추가됐다. 백그라운드 태스크 알림 개선과 내부 에러 후 세션 행 방지 등 안정성 수정도 포함됐다.

## Cursor: 53점, 30일 연속 하락 — 50선 돌파 초읽기

Cursor가 53점으로 떨어지며 SpaceX 인수(8/14) 이후 정확히 30일 연속 하락을 기록했다([TechCrunch](https://techcrunch.com/2026/08/15/spacex-officially-closes-its-cursor-acquisition/)). OpenAI 모델 접근 차단(11/12)까지 54일 남았으며, 50점 심리적 지지선이 불과 이틀 뒤로 다가왔다. Cursor Projects 베타(좌표 에이전트가 수천 개 서브에이전트에 작업 위임)가 9/10 출시됐지만 하락세를 멈추지 못하고 있다. OpenAI는 Musk 소유 기업의 계약 위반 이력을 근거로 모델 공급을 중단한다는 입장이며([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)), Cursor 측은 "OpenAI 모델은 트래픽의 5%에 불과"라고 반박했다.

## OpenAI Codex CLI: GPT-5.5 은퇴 D-25, Sol 마이그레이션 본격화

GPT-5.5가 10월 14일 ChatGPT·Codex 전 플랜에서 은퇴한다([OpenAI Deprecations](https://developers.openai.com/api/docs/deprecations)). GPT-5.6 Sol(gpt-5.6-sol)로의 마이그레이션이 본격화되는 시점으로, 워크스페이스 기본값·커스텀 에이전트·스크립트 모두 변경이 필요하다. Sol은 8/21 API 가격을 20% 이상 인하한 상태(인풋 $5→$4, 아웃풋 $30→$20)로 11/21까지 프로모션이 진행 중이다([OpenAI](https://openai.com/index/gpt-5-6/)).

## Antigravity: v2.13.0 안정화, IDE 확장 정착

Google Antigravity v2.13.0(9/14)이 Documents 섹션·C++/Python/Protobuf 구문 강조·파일 필 호버 툴팁·가이드 스킬 등 16개 개선과 16개 버그 수정을 포함하며 안정기에 접어들었다([Antigravity Blog](https://antigravity.google/blog/google-io-2026)). VS Code·JetBrains·Zed·Visual Studio IDE 확장이 정착 단계에 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Word 연동·Astra for Law 안정 운영 |
| Claude Code | 99 | — | v2.1.277, AGENTS.md 호환 |
| Claude AI | 99 | — | R&D 26% 주도, 자기개선 지속 |
| Codex CLI | 99 | — | GPT-5.5→Sol 마이그레이션 D-25 |
| Antigravity | 99 | — | v2.13.0 안정화 |
| Windsurf | 87 | — | Devin Desktop 안정기 |
| Aider | 68 | — | 44K 스타, 꾸준한 릴리스 |
| Cursor | 53 | ↓2 | 30일 연속 하락, 50선 임박 |
| GH Copilot | 1 | — | 9/28 통합 경험 D-9 |
| Gemini CLI | 1 | — | 폐쇄 94일째 |

터미널 에이전트 간 상호운용성이 시작됐다. Claude Code의 AGENTS.md 지원은 경쟁이 아닌 공존의 신호탄이며, 개발자들에게는 도구 전환 비용이 낮아지는 긍정적 변화다.

---
title: "Fable 5 차단 17일째, Opus 4.7 패스트 모드 퇴장 시작 — Anthropic의 격동기"
date: 2026-06-29
lang: ko
categories: [news]
tags: [anthropic, fable-5, claude-code, opus-4.7, copilot, antigravity, windsurf, spacex]
excerpt: "Fable 5가 17일째 차단된 채 Anthropic은 Opus 4.7 패스트 모드 지원 종료를 시작했다. Copilot은 55주 연속 하락으로 27까지 추락했고, Antigravity는 11주 연속 상승하며 87에 도달했다."
---

Anthropic이 전방위 압박을 받고 있다. Fable 5는 17일째 전면 차단이 유지되는 가운데, 6월 25일부터 Opus 4.7 패스트 모드 지원이 공식 중단되며 7월 24일 완전 제거가 예고됐다([Anthropic Docs](https://platform.claude.com/docs/en/build-with-claude/fast-mode)). 패스트 모드를 사용하는 개발자는 Opus 4.8로 전환해야 하며, 전환하지 않으면 7월 24일 이후 API 요청이 에러를 반환한다. Opus 4.8 패스트 모드는 MTok 기준 $10/$50인 반면 Opus 4.7은 $30/$150으로, 전환 시 비용도 대폭 절감된다.

## Fable 5: "이번 주 내" 복원 보도에도 변화 없음

Axios는 6월 27일 트럼프 행정부가 Fable 5 복원에 "가까워졌다"며 "이르면 이번 주" 제한 해제 가능성을 보도했다([Axios](https://www.axios.com/2026/06/27/anthropic-fable-5-return-soon)). 상무부 장관 Lutnick은 6월 26일 서한으로 Mythos 5의 Annex A 엔터티(미국 기관) 한정 부분 복원을 승인했으나, Fable 5는 여전히 모든 일반 사용자 — 소비자, API 개발자, Claude Code, 해외 구독자 — 에게 차단 상태다([Fortune](https://fortune.com/2026/06/27/anthropic-mythos-5-ai-model-us-commerce-department-clearance-fable/)). 7월 8일 예정된 신원인증(정부 ID + 셀피) 정책이 미국 내 사용자 복원의 핵심 경로로 거론되고 있다.

## Claude Code v2.1.193 — MCP 인증 간소화

Claude Code 최신 릴리스가 `claude mcp login`/`logout` 명령어를 추가해 MCP 서버 인증을 셸에서 직접 처리할 수 있게 됐다([Anthropic](https://code.claude.com/docs/en/whats-new)). 셸 모드에서 `npm test` 같은 명령 출력에 자동 응답하는 기능과, `/rewind`로 `/clear` 이전 대화를 복원하는 기능도 도입됐다. Team/Enterprise 플랜에는 Trusted Devices 기능이 추가돼 원격 Claude Code 세션 접근 시 디바이스 인증이 요구된다([Anthropic](https://www.anthropic.com/news)).

## Copilot 55주 연속 하락 — 27까지 추락

GitHub Copilot이 55주 연속 하락하며 27에 도달했다. 종량제 전환 29일째로 사실상 한 달이 경과했으며, 에이전틱 세션당 $30-40 비용이 개발자 이탈을 가속시키고 있다([GitHub Discussions](https://github.com/orgs/community/discussions/197089)). JetBrains 개발자 에코시스템 서베이에서 Copilot 점유율은 29%로 하락한 반면, Cursor와 Claude Code가 각각 18%로 추격 중이다([NxCode](https://www.nxcode.io/resources/news/github-copilot-getting-worse-2026-developers-switching)).

## Windsurf Cascade EOL D-2 — 마이그레이션 마감 임박

Windsurf의 레거시 로컬 AI 에이전트 Cascade가 7월 1일 서비스를 종료한다. Cascade를 직접 호출하는 CI 파이프라인과 자동화 스크립트는 Devin Local로 전환해야 하며, 시간이 이틀 남았다. Devin Local은 Rust 재작성으로 토큰 소비 30% 절감을 주장하고 있다.

## SPCX 조정 지속 — ATH 대비 32% 하락

SpaceX(SPCX)가 ~$153에 거래되며 6월 16일 기록한 $225 ATH 대비 32% 하락 상태를 이어가고 있다([Yahoo Finance](https://finance.yahoo.com/quote/SPCX/)). Cursor $600억 인수 합의는 Q3 마감을 향해 진행 중이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.193 MCP 인증·셸 모드 개선 |
| ChatGPT | 97 | — | GPT-5.6 제한 프리뷰 지속, GA "수 주 내" |
| Claude AI | 96 | — | Fable 5 D17, Opus 4.7 패스트 중단 시작 |
| Cursor | 96 | — | SpaceX $600억 인수 Q3 마감 대기 |
| Codex CLI | 88 | — | GPT-5.6 프리뷰 기관에 Codex 통해 제공 |
| Antigravity | 87 | ↑1 | 11주 연속 상승, Gemini CLI 이전 흡수 |
| Windsurf | 85 | — | Cascade EOL 2일 남음 (7/1) |
| Aider | 68 | — | 오픈소스 안정 유지 |
| Gemini CLI | 30 | ↓2 | 셧다운 12일째, 기업 전용 바닥권 |
| Copilot | 27 | ↓1 | 55주 연속 하락, 종량제 29일차 |

Antigravity의 11주 연속 상승세가 눈에 띈다. Gemini CLI 셧다운 이후 이전 수요를 꾸준히 흡수하며 87까지 올라섰고, 이 속도라면 7월 중 90선 돌파도 가능하다. 반면 Copilot은 종량제 전환 한 달 만에 바닥을 모르는 하락을 이어가며, 코딩 도구 시장의 판도가 근본적으로 바뀌고 있음을 보여준다.

---
title: "Anthropic $9000억 돌파, Claude Code v2.1.152 출시 — Copilot 23주 연속 추락"
date: 2026-05-27
lang: ko
categories: [news]
tags: [anthropic, claude-code, github-copilot, copilot-studio, spacex, gemini-api, grok-build, claude-mythos]
excerpt: "Anthropic이 $300억+ 라운드를 마감하며 세계 최고 가치 비상장 AI 기업에 등극했다. Claude Code v2.1.152가 코드 리뷰 자동 수정을 도입하고, Managed Agents에 셀프호스팅 샌드박스가 추가됐다."
---

Anthropic이 $300억 이상의 펀딩 라운드를 $9,000억+ 밸류에이션으로 마감하며 OpenAI를 넘어 세계 최고 가치 비상장 AI 기업이 됐다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-22/anthropic-to-close-over-30-billion-round-as-soon-as-next-week)). Sequoia Capital, Dragoneer, Altimeter Capital, Greenoaks Capital Partners가 각 약 $20억으로 공동 리드했으며, Microsoft와 NVIDIA도 참여했다([Yahoo Finance](https://finance.yahoo.com/sectors/technology/articles/anthropic-set-close-30-billion-203545596.html)). 10월 IPO가 전망되고 있으며, Wilson Sonsini가 상장 준비를 맡고 있다.

## Claude Code v2.1.152: 코드 리뷰 자동 수정 도입

Claude Code가 v2.1.152로 업데이트되면서 `/code-review --fix` 명령어가 추가됐다 — 리뷰 발견 사항을 작업 트리에 직접 적용한다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 스킬 프론트매터에 `disallowed-tools` 선언 기능, `/reload-skills`로 세션 중 스킬 재로드, `SessionStart` 훅으로 세션 시작 시 자동 실행이 가능해졌다. 장시간 세션에서 터미널 스타일이 깨지는 문제도 수정됐다.

## Claude Managed Agents: 셀프호스팅 샌드박스 + MCP 터널

Managed Agents에 두 가지 엔터프라이즈 기능이 추가됐다([claude.com](https://claude.com/blog/claude-managed-agents-updates)). 셀프호스팅 샌드박스(공개 베타)로 에이전트 도구 실행을 자체 인프라 또는 Cloudflare, Daytona, Modal, Vercel에서 운영할 수 있게 됐다. MCP 터널(리서치 프리뷰)은 퍼블릭 엔드포인트 없이 사설 네트워크 내 MCP 서버에 접근하며, 종단간 암호화를 지원한다([InfoQ](https://www.infoq.com/news/2026/05/claude-mcp-tunnels/)).

## GitHub Copilot: 23주 연속 하락, 60선 붕괴

Copilot 인기도가 23주 연속 하락하며 60에 도달했다 — 역대 최저치다([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)). 6월 1일 사용량 기반 과금 전환까지 5일 남았으며, 에이전트와 채팅은 AI 크레딧을 소비하고 코드 완성만 무제한 유지된다. 타겟 모델 규칙이 퍼블릭 프리뷰로 출시돼 엔터프라이즈 관리자가 조직별 모델을 제어할 수 있다([GitHub Changelog](https://github.blog/changelog/2026-05-26-target-copilot-models-to-organizations-with-model-rules/)).

## Copilot Studio: 컴퓨터 사용 에이전트 GA

Microsoft Copilot Studio의 컴퓨터 사용 에이전트(CUA)가 전체 상용 Power Platform 지역에서 GA에 도달했다([Microsoft Copilot Blog](https://www.microsoft.com/en-us/microsoft-copilot/blog/copilot-studio/new-and-improved-computer-using-agents-a-new-workflows-experience-and-real-time-voice-experiences/)). OpenAI CUA와 Claude Sonnet 4.5를 프로덕션 모델로 탑재하며, API 없는 레거시 시스템 자동화를 위한 최초의 GA CUA 플랫폼이다.

## SpaceX IPO: 역대 최대 규모 임박

SpaceX가 $1.75조 밸류에이션, $750억 조달을 목표로 IPO를 추진한다([CNBC](https://www.cnbc.com/2026/05/20/spacex-ipo-live-updates.html)). 로드쇼 6월 4일, 가격 결정 6월 11일, Nasdaq 거래 개시 6월 12일(SPCX). Goldman Sachs가 인수 주선을 맡았으며, S-1에서 Anthropic이 Colossus 컴퓨트에 월 $12.5억을 지불 중인 것이 확인됐다.

## Gemini API: 호환성 파괴 변경, 6/8 마감

Gemini Interactions API의 `outputs`가 `steps` 배열로 대체되고, 다형적 `response_format`이 도입됐다([Google AI for Developers](https://ai.google.dev/gemini-api/docs/interactions-breaking-changes-may-2026)). 5월 26일부터 새 스키마가 기본값이며, `Api-Revision: 2026-05-07` 헤더를 통한 레거시 지원은 6월 8일 완전 종료된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 98 | — | v2.1.152 + Managed Agents 강화 |
| ChatGPT | 98 | — | GPT-5.5 Instant 효과 지속 |
| Cursor | 96 | — | Composer 2.5 안정세 |
| Claude AI | 94 | — | $9000억+ 라운드 마감 |
| Codex CLI | 88 | — | 5주 연속 고점 유지 |
| Windsurf | 81 | — | 장애 후 안정화 |
| Gemini CLI | 80 | ↓1 | 종료 D-22, API 파괴 변경 |
| Aider | 68 | — | 안정 |
| GH Copilot | 60 | ↓1 | 23주 연속 하락, 역대 최저 |
| Antigravity | 56 | ↑1 | 롤백 후 4일 회복세 |

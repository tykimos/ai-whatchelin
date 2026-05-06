---
title: "Anthropic, 'Code with Claude' 컨퍼런스서 AI 코딩의 미래 선언 — SpaceX GPU 22만 장으로 속도 제한 2배"
date: 2026-05-06
lang: ko
categories: [news]
tags: [claude-code, anthropic, spacex, windsurf, devin, copilot, deepseek]
excerpt: "Anthropic이 샌프란시스코에서 개최한 'Code with Claude' 컨퍼런스에서 Managed Agents, Dreaming 메모리, 데스크톱 GUI를 공개했다. 같은 날 SpaceX Colossus 1과의 컴퓨트 계약으로 Claude Code 속도 제한이 즉시 2배로 확대됐다."
---

Anthropic이 오늘 샌프란시스코에서 'Code with Claude' 개발자 컨퍼런스를 열고 AI 코딩 도구의 미래를 제시했다. 같은 날 SpaceX와의 대규모 컴퓨트 계약까지 발표하며 Claude Code 사용자들에게 즉각적인 혜택을 안겼다.

## Code with Claude 컨퍼런스: 에이전트의 시대

Anthropic은 멀티에이전트 오케스트레이션이 가능한 **Managed Agents**, 성공 기준을 정의하는 **Outcomes**(퍼블릭 베타), 과거 세션을 검토해 패턴을 학습하는 자기 개선 메모리 **Dreaming**(리서치 프리뷰)을 공개했다([Simon Willison](https://simonwillison.net/2026/May/6/code-w-claude-2026/)). Claude Code는 풀스크린 라이브 프리뷰가 가능한 데스크톱 GUI 앱, 모바일에서 노트북을 제어하는 Remote Agents, CI 자동 수정, 보안 리뷰, 코드 리뷰를 추가했다. 특히 **Routines**는 비동기 자동화를 지원해 "아침에 일어나면 머지 준비된 PR이 대기"하는 워크플로우를 가능하게 한다. 모든 기능은 외부 개발자에게도 공개된 Claude Agent SDK 위에 구축됐다.

## SpaceX Colossus 1: GPU 22만 장, 속도 제한 즉시 2배

Anthropic이 SpaceX의 Colossus 1 데이터센터 전체 컴퓨트 용량을 확보하는 계약을 체결했다 — 300MW 이상, 22만+ NVIDIA GPU([Anthropic Blog](https://www.anthropic.com/news/higher-limits-spacex)). 즉각적인 효과로 Claude Code **5시간 속도 제한이 Pro, Max, Team, Enterprise 플랜에서 2배로 확대**됐고, 피크 시간 한도 감소가 해제됐으며, Opus 모델 API 속도 제한도 대폭 상향됐다([Engadget](https://www.engadget.com/2166315/anthropic-is-doubling-claude-code-rate-limits-after-deal-with-spacex/)). 양사는 "기가와트급 궤도 AI 컴퓨트 용량" 개발에도 관심을 표명했다.

## Devin for Terminal: Windsurf에 Rust CLI 에이전트 합류

Cognition이 **Devin for Terminal**을 출시했다 — Rust로 작성된 로컬 CLI 에이전트로 전체 코드베이스에 접근 가능하다([Cognition Blog](https://cognition.ai/blog/devin-for-terminal)). Opus 4.7, GPT-5.5, SWE-1.6을 지원하며 Devin 클라우드로 원활한 핸드오프가 가능하다. 모든 Windsurf 구독자에게 제공되며, 기존 Cascade 에이전트 대비 **최대 30% 토큰 효율적**이다.

## Claude Code v2.1.131 패치

Windows에서 VS Code 확장이 하드코딩된 빌드 경로 문제로 활성화되지 않던 버그와 Mantle 엔드포인트 인증 문제가 수정됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)).

## Copilot 과금 전환 D-25

GitHub Copilot의 6월 1일 사용량 기반 과금 전환이 25일 앞으로 다가왔다. 개발자 커뮤니티의 반발이 계속되는 가운데, Copilot의 인기 점수는 4주 연속 하락해 80점까지 내려왔다([GitHub Community](https://github.com/orgs/community/discussions/192948)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 모멘텀 지속 |
| Claude Code | 97 | ↑1 | 컨퍼런스 + SpaceX 딜로 급등 |
| Cursor | 91 | — | Canvases 안착 중 |
| Claude AI | 91 | ↑1 | 금융 서비스 진출 + 컨퍼런스 효과 |
| GitHub Copilot | 80 | ↓1 | 과금 전환 불만 확대, 4주 연속 하락 |
| Windsurf | 77 | ↑1 | Devin for Terminal 출시 |
| Codex CLI | 76 | — | /goal 워크플로우 정착 중 |
| Gemini CLI | 68 | ↑1 | I/O 기대감, 메모리 기능 강화 |
| Aider | 68 | — | 39K+ 스타, 안정적 |
| Antigravity | 47 | — | 소식 없음 |

Claude Code가 컨퍼런스와 SpaceX 딜 효과로 97점에 진입하며 ChatGPT와의 격차를 1점으로 좁혔다. Windsurf도 Devin for Terminal 출시로 소폭 상승. Copilot은 4주 연속 하락세가 이어지며 80선 방어가 관건이다.

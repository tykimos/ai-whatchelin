---
title: "Cursor, OpenAI 모델 접근 공식 차단 — 79일간의 추락 끝에 맞이한 D-Day"
date: 2026-11-12
lang: ko
categories: [news]
tags: [cursor, openai, claude-code, github-copilot, antigravity, gemini-cli]
excerpt: "OpenAI가 Cursor의 모델 접근을 공식 차단하는 날이 왔다. SpaceX 인수 후 79일간 바닥을 기던 Cursor의 운명이 오늘 결정된다."
---

오늘은 AI 코딩 도구 역사에서 한 시대의 끝을 알리는 날이다. OpenAI가 Cursor(Anysphere)에 대한 모델 접근을 공식 차단하는 11월 12일이 도래했다. SpaceX의 600억 달러 인수 이후 79일째 인기도 1점에 머물던 Cursor가 최후의 생명선마저 잃게 되었다.

## Cursor: OpenAI 모델 차단 D-Day

OpenAI가 제안한 전환 기간 종료일인 오늘, Cursor의 OpenAI 모델 접근이 공식 차단된다([InfoWorld](https://www.infoworld.com/article/4216503/cursor-customers-will-lose-access-to-openai-coding-models-in-november.html)). OpenAI는 SpaceX가 Cursor를 인수한 후 "경쟁 AI 시스템 훈련을 위한 모델 증류" 우려를 이유로 계약을 해지했다([The New Stack](https://thenewstack.io/openai-cuts-cursor-spacex/)). 사용자들은 OpenAI API 키를 직접 설정해 일부 기능을 계속 사용할 수 있지만, Tab 자동완성, 자동 모델 선택, 클라우드 에이전트 등 핵심 기능은 지원되지 않는다([OpenAI Help](https://help.openai.com/en/articles/20001506)). IDC는 이를 "AI 도구 시장의 공급망 리스크가 현실화된 첫 사례"로 분석했다([IDC](https://www.idc.com/?p=119917)).

## Claude Code v2.1.319: 자동 모드 강화

Claude Code v2.1.319가 11월 6일 출시되며 자동 모드(auto mode)를 핵심 업데이트로 포함했다([claudekit.io](https://claudekit.io/en/updates/claude-code-2-1-319/)). 텔레메트리나 기능 플래그가 비활성화된 환경, 또는 LLM 게이트웨이 뒤에서 서버가 확인할 수 없는 호출은 내장 분류기 대신 사용자 확인을 거치도록 변경되었다. MCP 태스크 지원이 터미널에 추가되었으며, 게이트웨이 관리 기능도 개선되었다([labmemo.com](https://labmemo.com/claude-code-v2-1-319-auto-mode-gateway-mcp-task-2026-11/)). 한편, Opus 4.8의 패스트 모드가 11월 30일부로 종료 예정이어서 해당 모드 사용자는 마이그레이션을 준비해야 한다.

## GitHub Copilot: Agent Merge와 크론 태스크 도입

GitHub Copilot 주간 릴리스(11월 6일)에서 Agent Merge PR 자동화 기능과 VS Code 1.145 내 예약 크론 태스크가 추가되었다([GitHub Blog](https://github.blog/changelog/2026-11-06-github-copilot-weekly-releases-november-2)). JetBrains Air와 Xcode 27.3 베타 네이티브 지원도 포함되었다. Copilot의 인기도는 48일 연속 상승해 93점에 도달하며, 연말까지 상위 그룹 진입 가능성이 높아지고 있다.

## Gemini CLI v0.67.0: 모델 목록 명령 추가

Gemini CLI v0.67.0이 11월 4일 출시되며 모델 목록 조회 명령어와 컨테이너 샌드박스 IDE 컴패니언 지원이 추가되었다([havoptic.com](https://www.havoptic.com/releases/gemini-cli/2026/11)). 다만, Gemini CLI 개발이 Antigravity CLI로 점진적으로 전환되고 있어 향후 독립 릴리스는 줄어들 전망이다([labmemo.com](https://labmemo.com/?p=62719)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 안정 유지 |
| Claude Code | 99 | — | v2.1.319 자동 모드 강화 |
| Codex CLI | 99 | — | 0.167.0 에이전트 커맨드 센터 |
| Antigravity | 99 | — | Knowledge Work 모드 운영 중 |
| Claude AI | 99 | — | IPO S-1 등록, Fable 5.2 안정화 |
| GH Copilot | 93 | ↑2 | 48일 연속 상승, Agent Merge 추가 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 D-Day, 79일째 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 진행 중 |

OpenAI의 Cursor 모델 차단이 현실화되면서 AI 코딩 도구 시장의 공급망 의존성 리스크가 새로운 화두로 떠올랐다. Copilot이 48일 연속 상승하며 격차를 좁히는 가운데, 자체 모델을 보유한 Claude Code와 Antigravity의 수직 통합 전략이 더욱 부각되고 있다.

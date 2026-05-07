---
title: "Claude Code 속도 제한 2배 확대 여파 속, Gemini CLI 오픈소스로 CLI 3파전 본격화"
date: 2026-05-07
lang: ko
categories: [news]
tags: [claude-code, gemini-cli, cursor, codex-cli, copilot, anthropic, google, openai]
excerpt: "Anthropic의 SpaceX 계약으로 Claude Code 속도 제한이 2배로 확대된 가운데, Google Gemini CLI 오픈소스 런칭과 Cursor 3.3 Team Marketplace로 AI 코딩 도구 경쟁이 격화되고 있다."
---

Anthropic이 SpaceX Colossus 1의 22만+ GPU를 확보하며 Claude Code 속도 제한을 전 유료 플랜에서 2배로 확대한 지 하루 만에, 생태계 전반에서 이에 대응하는 움직임이 나타나고 있다. Google은 Gemini CLI를 오픈소스로 전격 공개했고, Cursor는 Team Marketplace를 도입하며 플러그인 생태계 확장에 나섰다.

## Claude Code: v2.1.132 패치 + 컨퍼런스 여파 지속

Claude Code v2.1.132가 오늘 배포됐다([Releasebot](https://releasebot.io/updates/anthropic)). CLAUDE_CODE_SESSION_ID 환경변수가 추가돼 터미널 세션 추적이 가능해졌고, 슬립/웨이크 후 전체화면 깨짐, 이모지 처리, MCP 서버 인증 실패 등이 수정됐다. 어제 'Code with Claude' 컨퍼런스에서 공개된 Managed Agents(멀티 에이전트 오케스트레이션), Outcomes(성공 기준 기반 자율 반복), Dreaming(세션 리뷰 기반 자기 개선 메모리)에 대한 커뮤니티 반응이 뜨겁다([Simon Willison](https://simonwillison.net/2026/May/6/code-w-claude-2026/)). SpaceX 계약으로 확보한 300MW+ 컴퓨팅 파워 덕에 피크 시간 속도 제한 감소도 해제됐다([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)).

## Gemini CLI: 오픈소스 AI 에이전트로 공식 데뷔, v0.42 프리뷰도 공개

Google이 Gemini CLI를 Apache 2.0 오픈소스로 공개했다([Google Blog](https://blog.google/technology/developers/introducing-gemini-cli-open-source-ai-agent/)). 개인 Google 계정으로 Gemini 2.5 Pro와 100만 토큰 컨텍스트를 무료 이용 가능하며(분당 60건, 일 1,000건), Claude Code($20/월~)이나 Codex CLI(유료 ChatGPT 필요)와 달리 완전 무료라는 점이 차별화 포인트다. v0.42.0 프리뷰에서는 실시간 음성 모드, Gemma 4 모델 기본 활성화, 자동 메모리 개선, /bug-memory 힙 스냅샷 명령어가 추가됐다([GitHub](https://github.com/google-gemini/gemini-cli/releases)).

## Cursor 3.3: Team Marketplace로 플러그인 생태계 확장

Cursor 3.3에서 Team Marketplace가 도입됐다([Cursor Changelog](https://cursor.com/changelog)). 관리자가 레포지토리 연결 없이 MCP 서버, 스킬, 서브에이전트, 룰, 훅을 번들링한 플러그인을 배포할 수 있으며, Default Off/Default On/Required 세 가지 모드를 지원한다. 에이전트 컨텍스트 사용량 세부 표시 기능도 추가됐다.

## GitHub Copilot: 5주 연속 하락, D-24

Copilot CLI에 엔터프라이즈 관리 플러그인이 퍼블릭 프리뷰로 도입됐지만([GitHub Blog](https://github.blog/changelog/2026-05-06-enterprise-managed-plugins-in-github-copilot-cli-are-now-in-public-preview/)), 6월 1일 사용량 기반 과금 전환(D-24)에 대한 커뮤니티 반발이 계속되고 있다. Pro/Pro+/Student 신규 가입 중단 상태가 지속되며, Pro에서 Opus 모델이 제거된 상태다([GitHub Blog](https://github.blog/news-insights/company-news/changes-to-github-copilot-individual-plans/)). 인기 점수는 5주 연속 하락 중이다.

## Codex: Spark 프리뷰 + 보안 강화

OpenAI가 Codex-Spark를 ChatGPT Pro 사용자 대상 리서치 프리뷰로 공개했다 — 텍스트 전용, 128k 컨텍스트 윈도우([OpenAI Developers](https://developers.openai.com/codex/changelog)). Codex CLI TUI에 Alt+,/Alt+.로 추론 수준 조절이 추가됐고, Advanced Account Security(피싱 방지 로그인, 로그인 알림)도 도입됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 기본 모델 안착 |
| Claude Code | 97 | — | SpaceX 계약 + 속도 제한 2배, 최고점 유지 |
| Cursor | 91 | — | 3.3 + Team Marketplace, 안정적 |
| Claude AI | 91 | — | Managed Agents 공개 효과 지속 |
| GitHub Copilot | 79 | ↓1 | 5주 연속 하락, D-24 |
| Windsurf | 77 | — | 2.0 + Devin 통합 안착 중 |
| Codex CLI | 77 | ↑1 | Spark 프리뷰 + TUI 개선 |
| Gemini CLI | 70 | ↑2 | 오픈소스 + v0.42 음성 모드, 3일 최고 |
| Aider | 68 | — | 39K+ 스타, 안정 |
| Antigravity | 47 | — | 소식 없음 |

Claude Code가 SpaceX 계약과 컨퍼런스 발표를 등에 업고 97점을 유지하며 ChatGPT(98)를 바짝 추격하고 있다. Gemini CLI는 오픈소스 런칭과 v0.42 프리뷰로 70점에 도달, CLI 경쟁이 Claude Code-Codex CLI-Gemini CLI 3파전으로 확고해졌다. Copilot은 6월 1일 과금 전환을 앞두고 5주째 하락세다.

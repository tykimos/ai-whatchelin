---
title: "Google, Gemini CLI 오픈소스로 전격 공개 — 무료 1,000건/일로 CLI 전쟁 본격화"
date: 2026-05-07
lang: ko
categories: [news]
tags: [gemini-cli, google, cursor, codex-cli, copilot, openai]
excerpt: "Google이 Gemini CLI를 Apache 2.0 오픈소스로 공개하며 Gemini 2.5 Pro 무료 접근을 제공했다. Cursor 3.3은 Team Marketplace를, GitHub는 Copilot CLI에 엔터프라이즈 관리 플러그인을 도입했다."
---

Google이 Gemini CLI를 Apache 2.0 라이선스로 오픈소스 공개하며 AI 코딩 CLI 경쟁에 본격적으로 뛰어들었다. 개인 Google 계정만 있으면 Gemini 2.5 Pro와 100만 토큰 컨텍스트 윈도우를 무료로 사용할 수 있다 — 분당 60건, 일 1,000건이라는 파격적인 무료 한도가 핵심이다.

## Gemini CLI: 오픈소스 AI 에이전트로 공식 데뷔

Google이 공식 블로그를 통해 Gemini CLI를 "오픈소스 AI 에이전트"로 소개했다([Google Blog](https://blog.google/technology/developers/introducing-gemini-cli-open-source-ai-agent/)). ReAct 루프 기반으로 빌트인 도구와 로컬/원격 MCP 서버를 활용해 버그 수정, 기능 개발, 테스트 커버리지 개선 등 복잡한 작업을 수행한다. Gemini Code Assist와 기술 기반을 공유하며, VS Code에서도 동일한 AI 지원을 받을 수 있다([GitHub](https://github.com/google-gemini/gemini-cli)). Claude Code($20/월~), Codex CLI(유료 ChatGPT 필요)와 달리 완전 무료라는 점에서 입문자에게 강력한 대안이 될 전망이다.

## Cursor 3.3: Team Marketplace와 컨텍스트 사용량 표시

Cursor가 3.3 업데이트를 배포했다([Cursor Changelog](https://cursor.com/changelog)). 에이전트의 컨텍스트 사용량을 세부적으로 확인할 수 있게 됐고, Team Marketplace가 도입돼 관리자가 레포지토리 연결 없이도 팀 마켓플레이스를 생성할 수 있다. 플러그인은 MCP 서버, 스킬, 서브에이전트, 룰, 훅을 번들링하며, Default Off/Default On/Required 세 가지 배포 모드를 지원한다.

## GitHub: Copilot CLI에 엔터프라이즈 관리 플러그인 추가

GitHub가 Copilot CLI에 엔터프라이즈 관리 플러그인을 퍼블릭 프리뷰로 도입했다([GitHub Blog](https://github.blog/changelog/2026-05-06-enterprise-managed-plugins-in-github-copilot-cli-are-now-in-public-preview/)). 관리자가 기업 전체 사용자의 Copilot CLI에 플러그인을 배포하고 기준선을 설정할 수 있다. 한편 6월 1일 사용량 기반 과금 전환(D-24)에 대한 커뮤니티 반발은 여전하며, 인기 점수는 5주 연속 하락해 79점까지 내려왔다.

## Codex: Spark 리서치 프리뷰 + 보안 강화

OpenAI가 Codex-Spark를 ChatGPT Pro 사용자 대상 리서치 프리뷰로 공개했다 — 텍스트 전용, 128k 컨텍스트 윈도우([OpenAI Developers](https://developers.openai.com/codex/changelog)). Codex CLI TUI에는 Alt+,/Alt+.로 추론 수준을 조절하는 퀵 컨트롤이 추가됐다. 또한 Advanced Account Security가 도입돼 피싱 방지 로그인, 로그인 알림, 자동 학습 제외 등이 적용됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 모멘텀 지속 |
| Claude Code | 97 | — | 컨퍼런스 후 안정, 최고점 유지 |
| Cursor | 91 | — | 3.3 + Team Marketplace, 안정적 |
| Claude AI | 91 | — | 컨퍼런스 효과 지속 |
| GitHub Copilot | 79 | ↓1 | 5주 연속 하락, D-24 |
| Windsurf | 77 | — | 2.0 안착 중 |
| Codex CLI | 77 | ↑1 | Spark 프리뷰 + TUI 개선 |
| Gemini CLI | 70 | ↑2 | 오픈소스 공식 런칭, 무료 한도 파격적 |
| Aider | 68 | — | 39K+ 스타, 안정 |
| Antigravity | 47 | — | 소식 없음 |

Gemini CLI가 공식 오픈소스 런칭으로 2포인트 상승해 70점에 도달했다. 무료 Gemini 2.5 Pro 접근이라는 강력한 무기로 CLI 경쟁 구도가 Claude Code-Codex CLI-Gemini CLI 3파전으로 확고해지고 있다. Copilot은 5주 연속 하락세로 79점까지 내려왔다 — 6월 1일이 분수령이 될 전망이다.

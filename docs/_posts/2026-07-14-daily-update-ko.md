---
title: "npm 공급망 공격이 AI 코딩 도구 API 키를 노렸다 — jscrambler 사태의 교훈"
date: 2026-07-14
lang: ko
categories: [news]
tags: [security, jscrambler, claude-code, cursor, windsurf, gemini-3-5-pro, gpt-5-6, copilot]
excerpt: "jscrambler npm 패키지가 해킹되어 Claude Desktop, Cursor, Windsurf 등 AI 코딩 도구의 API 키를 탈취하는 인포스틸러를 배포했다. AI 코딩 에이전트가 엔드포인트 보안을 트리거하는 사례도 보고되면서, 개발자 보안 환경이 빠르게 변하고 있다."
---

이번 주 가장 큰 이슈는 보안이다. AI 코딩 도구가 대중화될수록, 그 도구들이 저장하는 크리덴셜이 새로운 공격 표면이 되고 있다.

## jscrambler npm 공급망 공격 — AI 도구 API 키가 표적

7월 11일 공개된 jscrambler npm 공급망 공격은 기존 공급망 공격과 결정적으로 다른 점이 있다([The Hacker News](https://thehackernews.com/2026/07/compromised-jscrambler-8140-npm-release.html)). 공격자는 탈취한 퍼블리싱 크리덴셜로 jscrambler 8.14.0 등 5개 버전에 Rust 기반 인포스틸러를 삽입했는데, 이 악성코드가 노리는 대상 목록에 Claude Desktop, Cursor, Windsurf, VS Code, Zed 등 AI 코딩 도구의 설정 파일이 포함되어 있다([Security Boulevard](https://securityboulevard.com/2026/07/jscrambler-npm-package-compromised-a-security-vendor-becomes-the-supply-chain-risk/)). MCP 서버 크리덴셜과 API 키가 주요 타겟이다. 주간 다운로드 15,800건의 패키지가 무기화된 만큼, 해당 패키지를 사용한 프로젝트는 즉시 크리덴셜 로테이션이 필요하다([Socket](https://socket.dev/blog/jscrambler-supply-chain-attack)).

## AI 에이전트가 엔드포인트 보안 경보를 울리다

Sophos가 Claude Code, Cursor, Codex CLI가 Windows 환경에서 크리덴셜 접근, LOLBin 다운로드, 퍼시스턴스 설정 등 보안 솔루션의 공격 탐지 규칙을 트리거한다고 보고했다([The Hacker News](https://thehackernews.com/2026/07/ai-coding-agents-found-triggering.html)). AI 코딩 에이전트의 정상 동작이 공격자 행위와 구분되지 않는 문제로, 기업 보안팀에게 새로운 과제를 안기고 있다.

## Gemini 3.5 Pro — D-3, 7월 17일 GA 카운트다운

Google Gemini 3.5 Pro의 7월 17일 GA가 3일 앞으로 다가왔다([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). 200만 토큰 컨텍스트, Deep Think 추론이 예상되지만 Google의 공식 확인은 없는 상태다. 기존 Gemini 3 Flash와 2.5 Pro를 사용하던 Copilot 유저는 7월 31일까지 마이그레이션이 필요하다([GitHub Changelog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)).

## Claude Code: 내장 브라우저 + 스크린 리더 모드 추가

Claude Code 데스크톱에 샌드박스 브라우저가 내장되어, 문서·디자인·외부 사이트를 에이전트가 직접 탐색할 수 있게 됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 스크린 리더 모드도 추가되어 접근성이 개선됐다. Bedrock에서는 auto 모드가 기본 활성화되고 Opus 4.8로 업데이트됐다.

## Terence Tao의 AI 코딩 실험 — HN 1위 등극

필즈 메달리스트 Terence Tao가 27년 전에 작성한 Java 1.0 애플릿을 AI 코딩 에이전트로 복원하고, 포기했던 특수상대성 시각화 도구를 완성한 블로그 포스트가 7월 11일 Hacker News 1위에 올랐다([TechTimes](https://www.techtimes.com/articles/320238/20260712/ai-agents-ported-taos-27-year-old-math-code-hours-found-two-bugs-he-had-missed.htm)). 수학과 소프트웨어 양쪽에서 권위를 가진 인물이 AI 코딩의 실용성을 직접 증명한 사례로, 커뮤니티 반응이 뜨겁다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 내장 브라우저, 스크린 리더 모드 추가 |
| Antigravity | 99 | — | v2.2.1 안정, 24주 연속 최고 |
| ChatGPT | 99 | — | Sol 5시간 제한 해제 효과 지속 |
| Claude AI | 98 | — | Sonnet 5 안착, Chrome 확장 베타 |
| Cursor | 97 | — | 3.11 사이드 챗 채택 확산 |
| Codex CLI | 90 | — | v0.144.4 안정, Guardian 롤백 |
| Windsurf | 85 | — | Devin Desktop, Sonnet 5 탑재 |
| Aider | 68 | — | 오픈소스 꾸준, 44K 스타 |
| Gemini CLI | 13 | ↓1 | 셧다운 26일째, 기업 전용 |
| Copilot | 12 | ↓1 | 69주 하락, Gemini 모델 디프리케이션 |

npm 공급망 공격이 AI 도구의 크리덴셜을 노리고, AI 에이전트가 보안 솔루션 경보를 울리는 시대다. 개발 편의성과 보안 사이의 균형이 2026년 하반기 핵심 화두가 될 것이다. 7월 17일 Gemini 3.5 Pro GA가 다가오면서 모델 경쟁도 다시 뜨거워지고 있다.

---
title: "Copilot 보안 취약점 공개, Gemini CLI 더블 릴리스 — Google I/O D-6 카운트다운"
date: 2026-05-13
lang: ko
categories: [news]
tags: [github-copilot, gemini-cli, claude-code, cursor, google-io, security]
excerpt: "CVE-2026-41109로 Copilot과 VS Code의 AI 콘텐츠 필터를 우회할 수 있는 보안 결함이 드러났다. Gemini CLI는 안정판과 프리뷰를 동시에 출시하며 I/O 직전 속도를 높이고 있다."
---

Copilot에 보안 경고등이 켜졌다. Microsoft는 어제 CVE-2026-41109를 공개했는데, 로컬 공격자가 VS Code 확장 호스트와 Copilot 확장 간 IPC 채널을 조작해 AI 콘텐츠 필터와 사용자 동의 메커니즘을 우회할 수 있는 취약점이다([The Hacker Wire](https://www.thehackerwire.com/github-copilot-visual-studio-injection-bypasses-security-feature-cve-2026-41109/)). CVSS 7.8 등급으로, 필터링되지 않은 모델 출력이 에디터에 직접 주입되고 텔레메트리 동의 플래그까지 무단 토글될 수 있다. VS Code 1.97.0과 Copilot 확장 v1.43.20260512에서 패치가 배포됐다([Windows News](https://windowsnews.ai/article/cve-2026-41109-copilot-and-vs-code-security-feature-bypass-in-the-dev-workflow.417882)).

## Gemini CLI: I/O 직전 안정판 + 프리뷰 동시 출시

Google이 I/O 6일 전에 Gemini CLI를 두 트랙으로 밀어붙이고 있다. v0.42.0 안정판은 음성 모드 UI 개선, 세션 내보내기/가져오기 기능, Gemma 4 기본 모델 지원을 포함한다([GitHub](https://github.com/google-gemini/gemini-cli/releases)). 같은 날 공개된 v0.43.0-preview.0은 더 주목할 만하다 — LocalSubagentProtocol과 RemoteSubagentProtocol을 AgentProtocol 뒤에 도입해 서브에이전트 아키텍처의 기반을 깔았고, 모델이 edit 도구를 선택하도록 유도해 정밀한 코드 수정 정확도를 높였다([GitHub](https://github.com/google-gemini/gemini-cli/releases)). 5월 19~20일 I/O에서 Gemini 4(ARC-AGI2 84.6%)가 공개되면 CLI 생태계에 큰 변화가 예상된다([TechRound](https://techround.co.uk/tech/gemini-4-ai-glasses-and-a-new-os-why-google-i-o-2026-could-be-the-most-important-developer-event-of-the-year/)).

## GitHub Copilot: 11주 연속 하락, CVE가 불을 지피다

보안 취약점에 더해 Copilot CLI 1.0.46이 출시됐다([GitHub](https://github.com/github/copilot-cli/releases)). CLI 버전이 폐기되면 프리미엄 모델 접근을 잃는다는 경고가 추가됐고, 읽기 전용 `gh` 명령어 자동 승인과 diff 뷰 래핑 개선이 포함됐다. Grok Code Fast 1 지원 종료까지 D-2, 토큰 과금 전환까지 D-18 — 인기도가 73으로 11주 연속 하락하며 역대 최장 기록을 경신했다.

## Claude Code v2.1.140: 안정성 개선 패치

Claude Code가 v2.1.140으로 업데이트됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 에이전트 이름 매칭이 대소문자·구분자를 무시하도록 개선됐고, 색상 팔레트가 업데이트됐다. `/goal` 명령어 행 문제와 심볼릭 링크 파일의 설정 핫리로드 버그가 수정됐다. 98점을 10일째 유지 중이다.

## Cursor: Microsoft Teams 진출

Cursor가 Microsoft Teams에 통합됐다([Cursor Changelog](https://cursor.com/changelog)). Teams 채널에서 @Cursor를 멘션하면 클라우드 에이전트에 작업을 위임하거나 컨텍스트를 Teams로 가져올 수 있다. 엔터프라이즈 개발 워크플로우에서 IDE를 벗어나지 않고도 협업을 확장하려는 전략이다.

## 이번 주 주목: Google I/O D-6

Google I/O 2026(5/19-20)이 엿새 앞으로 다가왔다([Yahoo Tech](https://tech.yahoo.com/general/article/google-io-2026-what-to-expect-next-week-including-android-17-ai-announcements-and-more-131200995.html)). Gemini 4 프리뷰, Android XR 스마트 안경, AI 우선 노트북 Googlebook이 예고되어 있다. Gemini CLI의 이중 릴리스는 I/O에서 발표될 에이전틱 AI 기능의 사전 포석으로 읽힌다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 안정, 빠른 답변 기능 |
| Claude Code | 98 | — | v2.1.140, 10일 연속 98 |
| Cursor | 94 | — | Teams 통합, $60B SpaceX 딜 진행 중 |
| Claude AI | 92 | — | Cowork GA 안정화 |
| Codex CLI | 81 | — | Amazon 전사 접근 정착 |
| Windsurf | 78 | — | Opus 4.7 fast 모드 안정 |
| Gemini CLI | 74 | ↑1 | v0.42+v0.43 더블 릴리스, I/O D-6 |
| GitHub Copilot | 73 | ↓1 | CVE-2026-41109, Grok D-2, 11주 연속 하락 |
| Aider | 68 | — | 안정 |
| Antigravity | 49 | — | AgentKit 2.0 정착 |

Copilot의 11주 연속 하락에 보안 취약점까지 겹치며 73을 기록, Claude Code(98)와의 격차가 25포인트로 벌어졌다. 반면 Gemini CLI는 I/O 직전 더블 릴리스로 74를 찍으며 Copilot을 1포인트 차로 추격하고 있다.

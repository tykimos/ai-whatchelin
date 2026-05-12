---
title: "DALL-E 오늘 공식 종료 — OpenAI 이미지 생성의 시대교체, Claude Code는 Agent View로 진화"
date: 2026-05-12
lang: ko
categories: [news]
tags: [openai, dall-e, claude-code, copilot, codex-cli, cursor, gemini-cli, google-io]
excerpt: "DALL-E 2·3가 오늘 공식 폐기되며 gpt-image-2가 전면 교체된다. Claude Code v2.1.139는 Agent View와 /goal 명령어를 추가했고, Copilot은 Grok Code Fast 1 지원 종료 D-3에 10주 연속 하락을 기록 중이다."
---

DALL-E 시대가 오늘로 막을 내렸다. OpenAI는 2025년 11월 사전 공지대로 DALL-E 2와 DALL-E 3를 5월 12일부로 API에서 완전히 제거했다([OpenAI Developer Community](https://community.openai.com/t/deprecation-reminder-dall-e-will-be-shut-down-on-may-12-2026/1378754)). 후속 모델 gpt-image-2는 O-시리즈 추론을 탑재해 다국어 텍스트 정확도와 2K 네이티브 해상도를 지원한다([AI Automation Global](https://aiautomationglobal.com/blog/chatgpt-images-2-gpt-image-2-native-reasoning-launch-2026)).

## Claude Code: Agent View로 멀티세션 관리 시대 개막

Claude Code v2.1.139가 릴리스되었다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 핵심은 Agent View(Research Preview)로, 실행 중·대기 중·완료된 모든 세션을 한 화면에서 관리할 수 있다. `/goal` 명령어는 여러 턴에 걸친 완료 조건을 설정하고, `/scroll-speed`는 라이브 프리뷰로 스크롤 속도를 조절한다. MCP stdio 서버에 `CLAUDE_PROJECT_DIR` 환경변수가 전달되어 프로젝트 인식 도구 개발이 쉬워졌다.

## Copilot: Grok Code Fast 1 D-3, 10주 연속 하락

GitHub Copilot에서 Grok Code Fast 1이 5월 15일에 완전히 제거된다([GitHub Changelog](https://github.blog/changelog/2026-05-08-upcoming-deprecation-of-grok-code-fast-1/)). GPT-5 mini와 Claude Haiku 4.5가 대체 모델이다. Enterprise 관리자는 모델 정책을 즉시 업데이트해야 한다. 사용량 기반 과금 D-19, Opus 4.7 승수 27x 적용(6/1)까지 겹치며 인기도는 74로 10주 연속 하락했다.

## Copilot CLI 1.0.45: /autopilot과 /fork 추가

Copilot CLI가 1.0.45로 업데이트되었다([Releasebot](https://releasebot.io/updates/github)). `/autopilot`으로 자율 모드를 토글하고, `/fork`로 세션을 분기할 수 있다. 시작 속도는 약 1.5초 빨라졌고, OpenTelemetry GenAI 시맨틱 컨벤션을 지원한다.

## Codex CLI: Amazon 전사 접근 개시, 5주 연속 상승

Amazon이 어제 공지한 대로 오늘부터 전 직원에게 Codex CLI 접근을 공식 허용했다([Slashdot](https://developers.slashdot.org/story/26/05/10/0618225/amazon-relents-lets-its-programmers-use-openais-codex-and-anthropics-claude)). 개발자 수 4M+ 돌파와 엔터프라이즈 파트너십 확대에 힘입어 인기도는 81로 5주 연속 상승세다.

## Cursor: Security Review 베타 출시

Cursor가 Teams·Enterprise 플랜에 Security Review 베타를 출시했다([Cursor Changelog](https://cursor.com/changelog)). Security Reviewer는 매 PR의 보안 취약점·인증 회귀·개인정보 위험을 검사하고, Vulnerability Scanner는 코드베이스를 정기 스캔한다. Bugbot 노력도 커스터마이징(기본/고노력)도 이날 함께 적용되었다.

## 이번 주 주목: Google I/O D-7

Google I/O 2026이 일주일 앞으로 다가왔다(5/19-20)([Android Authority](https://www.androidauthority.com/what-to-expect-from-google-io-2026-3664979/)). Gemini 4(10M+ 토큰 컨텍스트), Firebase 에이전트 네이티브 플랫폼, Android 17이 예고되어 있다. Gemini CLI 생태계에 큰 영향을 줄 수 있는 발표가 예상된다.

## Windsurf: Opus 4.7 Fast 모드 — 출력 속도 2.5배

Windsurf가 오늘 Claude Opus 4.7 fast 모드를 Cascade 세션에 적용했다([Releasebot](https://releasebot.io/updates/windsurf)). 약 2.5배 빠른 출력 속도로 복잡한 멀티파일 편집의 대기 시간이 크게 줄었다. Devin 통합에 이어 모델 성능까지 강화하며 인기도는 78로 상승했다.

## 업계 현실 점검: AI 코드 43%가 프로덕션 디버깅 필요

Lightrun의 2026 조사 결과, AI 생성 코드 변경의 43%가 QA를 통과한 후에도 프로덕션에서 수동 디버깅이 필요한 것으로 나타났다([VentureBeat](https://venturebeat.com/technology/43-of-ai-generated-code-changes-need-debugging-in-production-survey-finds/)). AI 코드 정확성에 '매우 자신 있다'고 답한 엔지니어링 리더는 0%다. 도구의 기능 경쟁만큼 코드 품질 검증이 핵심 과제임을 보여준다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 유지, DALL-E 폐기는 이미지 영역 |
| Claude Code | 98 | — | Agent View + /goal, 8일 연속 98 |
| Cursor | 94 | — | Security Review 베타, $60B SpaceX 딜 진행 중 |
| Claude AI | 92 | — | Cowork GA 안정화 |
| Codex CLI | 81 | ↑1 | Amazon 전사 접근 개시, 5주 연속 상승 |
| Windsurf | 78 | ↑1 | Opus 4.7 fast 모드 적용, Devin 통합 강화 |
| GitHub Copilot | 74 | ↓1 | D-19, Grok 종료 D-3, 10주 연속 하락 |
| Gemini CLI | 73 | — | I/O D-7, 오픈소스 모멘텀 |
| Aider | 68 | — | 안정 |
| Antigravity | 49 | — | AgentKit 2.0 정착 |

Copilot의 10주 연속 하락은 GitHub 역사상 전례 없는 기록이다. Claude Code(98)와의 격차가 24포인트로 벌어졌으며, 6월 1일 사용량 기반 과금 전환과 Opus 27x 승수가 격차를 더 벌릴 수 있다. Windsurf는 Opus 4.7 fast 모드로 78을 찍으며 반등 신호를 보내고 있고, Codex CLI는 Amazon 전사 접근으로 81을 돌파하며 상위권 진입을 노리고 있다.

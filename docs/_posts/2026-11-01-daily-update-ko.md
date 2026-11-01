---
title: "Cursor 마켓플레이스에서 악성 Claude Code 확장 발견, EMBRACE 연구로 AI 코딩 도구 보안 비상"
date: 2026-11-01
lang: ko
categories: [news]
tags: [security, claude-code, cursor, github-copilot, codex-cli, chatgpt, deepseek]
excerpt: "Cursor 마켓플레이스에 등록된 악성 Claude Code VS Code 확장이 SSH 백도어를 심었다. Forever Security의 EMBRACE 연구는 AI 코딩 도구 5종의 내장 브라우저 취약점을 공개하며 약 4,500만 설치에 영향을 줄 수 있다고 경고했다."
---

11월의 첫날, AI 코딩 도구 생태계에 보안 경고등이 켜졌다. Cursor 마켓플레이스에서 악성 Claude Code 확장이 발견됐고, Forever Security의 EMBRACE 연구는 주요 AI 코딩 도구 5종의 내장 브라우저 취약점을 공개했다. 보안이 이번 주의 최대 화두다.

## 악성 Claude Code 확장: Cursor 마켓플레이스에서 약 5천 명 노출

10월 29일 09:27~20:35 UTC, Cursor 마켓플레이스에 공식 anthropic.claude-code 확장의 악성 버전(2.1.313)이 등록됐다([AI Weekly](https://aiweekly.co/ai-news-today)). 이 확장은 공격자가 제어하는 SSH 키를 추가하고, 리버스 SSH 터널을 열며, Windows와 macOS에 지속성을 확보했다. Cursor 측은 피해 범위를 "최대 5,000명"으로 추산하며, 해당 버전을 설치한 사용자는 머신이 침해된 것으로 간주하라고 경고했다([AI Weekly](https://aiweekly.co/ai-news-today)). Anthropic은 10월 30일 정상 버전 2.1.314를 배포했고, C2 서버는 차단됐다.

## EMBRACE: AI 코딩 도구 5종 내장 브라우저 취약점 공개

Forever Security의 Gal Weizman 연구원이 10월 29일 EMBRACE 연구를 발표했다([AI Weekly](https://aiweekly.co/alerts/forever-security-embrace-research-breaks-five-ai-coding-browsers)). Cursor, GitHub Copilot, OpenAI Codex, VS Code, Claude Desktop 등 5종의 AI 코딩 도구에 내장된 브라우저가 독립 브라우저의 보안 규칙을 우회하는 취약점이 존재한다. Cursor에서는 악성 웹페이지가 에이전트의 샌드박스를 비활성화하고 임의 명령을 실행할 수 있었고, Copilot(v1.1.29 이전)에서는 URL 스푸핑으로 가짜 로그인 폼을 띄울 수 있었다([AI Weekly](https://aiweekly.co/alerts/forever-security-embrace-research-breaks-five-ai-coding-browsers)). Codex·VS Code·Claude Desktop에서는 로컬 HTML 파일의 웹 워커가 SSH 키, .env 파일, npm 토큰을 탈취할 수 있었다. Cursor(10/1 패치)와 Copilot(10/13, v1.1.29)은 패치됐지만, Codex와 VS Code는 발표 시점 기준 미패치 상태로, 약 4,500만 설치에 영향을 줄 수 있다.

## Claude Code: 기존 게임 재현 차단 논란

Anthropic이 Claude Code의 Claude Opus 5.5 시스템 프롬프트에 기존 게임 재현을 거부하는 지시를 추가했다([AI Weekly](https://aiweekly.co/ai-news-today)). 내부 플래그명 "tengu_heron_brook"이며, Anthropic 스태프 엔지니어 Addy Osmani가 10월 30일 X에서 IP 침해 방지 목적이라고 확인했다. 서버 측 조정으로 로컬 토글은 없으며, 일부 개발자들은 합법적인 리버스 엔지니어링 작업까지 차단된다고 보고하고 있다.

## ChatGPT + Codex: 12월부터 사용량 풀 통합

12월부터 ChatGPT와 Codex가 Plus, Pro, Business 구독자에 대해 단일 토큰 기반 사용량 풀을 공유한다([AI Weekly](https://aiweekly.co/ai-news-today)). 무거운 Codex 세션이 ChatGPT 대화와 같은 예산에서 차감되므로, 헤비 유저에게는 주의가 필요하다. Pro 플랜은 기존 5시간 제한 면제를 유지한다.

## DeepSeek: 오픈소스 슈퍼 에이전트 공개

DeepSeek가 10월 31일 dsh-superagent의 MIT 라이선스 프로토타입을 공개하며, 24시간 내 GitHub 스타 4,100개를 넘겼다([SCMP](https://www.scmp.com/tech/article/3372884/deepseek-unveils-ai-super-agent-coding-race-openai-anthropic)). GitHub 레포를 모니터링하고 Feishu 그룹 채팅도 수신하며, 병렬 Worker 세션으로 PR을 생성하는 구조다. Claude Cowork에 대항하는 오픈소스 에이전트 하네스로, 아직 초기 프리뷰 단계다.

## Codex CLI v0.166.0: 트랜스크립트 검색과 큐 재개

OpenAI가 10월 29일 Codex CLI v0.166.0을 출시했다([DEV Community](https://dev.to/aicoding-guide/this-week-in-claude-code-codex-and-gemini-cli-week-of-november-1-2026-15pn)). 키보드 기반 트랜스크립트 검색, `codex queue --resume`, `codex doctor --network-only`가 추가됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 12월 Codex 사용량 풀 통합 예고 |
| Claude Code | 99 | — | 게임 재현 차단 논란, IPO D-8 |
| Codex CLI | 99 | — | v0.166.0, EMBRACE 미패치 주의 |
| Antigravity | 99 | — | Gemini 4 Argon Pro 안정 |
| Claude AI | 99 | — | ANT 상장 카운트다운 |
| Windsurf | 88 | — | 주요 업데이트 없음 |
| GH Copilot | 71 | ↑2 | 38일 연속 회복, 11/16 모델 퇴장 |
| Aider | 68 | — | 유지보수 모드 |
| Cursor | 1 | — | 악성 확장 유통 사태, 68일째 바닥 |
| Gemini CLI | 1 | — | 은퇴, Antigravity 전환 완료 |

보안이 11월 첫 주의 화두다. EMBRACE 취약점과 악성 확장 사건은 AI 코딩 도구의 공급망 보안과 내장 브라우저 보안 감사가 얼마나 중요한지를 다시 한번 상기시킨다. 특히 미패치 상태인 Codex와 VS Code의 4,500만 사용자에게는 프로젝트 내 HTML 파일 점검이 시급하다.

---
title: "Copilot 통합 경험 D-6 — Cursor 47점까지 추락, Codex CLI 음성 채팅 실험 시작"
date: 2026-09-22
lang: ko
categories: [news]
tags: [cursor, github-copilot, codex-cli, claude-code, antigravity, chatgpt]
excerpt: "GitHub Copilot 통합 경험 출시까지 6일. Cursor는 33일 연속 하락해 47점을 기록했고, Codex CLI는 v0.155.1에서 음성 채팅 실험과 Touch ID 인증을 선보였다."
---

Copilot 통합 경험 D-6 카운트다운이 본격화됐다. 9월 28일부터 GitHub Copilot Chat, 모바일, 클라우드 에이전트가 하나의 통합 세션으로 합쳐지고 코드 리뷰 기본값이 Lite에서 Balanced로 자동 전환된다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 한편 Cursor는 SpaceX 인수 이후 33일 연속 하락하며 47점까지 밀렸다.

## Cursor: 33일 연속 하락, 47점 — OpenAI 모델 차단 D-51

Cursor가 어제 49에서 다시 2포인트 하락해 47을 기록했다. SpaceX 인수 마감(8/14) 이후 33일째 내리막이다([TechCrunch](https://techcrunch.com/2026/08/15/spacex-officially-closes-its-cursor-acquisition/)). OpenAI가 11월 12일부로 Cursor의 모델 접근을 차단하겠다고 선언한 상황에서([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)), Projects 베타의 반전 효과는 아직 점수에 반영되지 않고 있다. Cursor 측은 OpenAI 모델이 전체 트래픽의 5% 수준이라고 밝혔지만, 시장 심리는 계속 위축되고 있다.

## Codex CLI v0.155.1: 음성 채팅 실험과 Touch ID 인증

Codex CLI가 v0.155.0에서 실험적 음성 대화 기능을 추가했다([Releasebot](https://releasebot.io/updates/openai/codex)). 라이브 트랜스크립트와 마이크 제어가 가능하며, 추론 요약이 상태 표시줄에 실시간으로 표시된다. Mac에서는 MCP 요청에 Touch ID 인증을 적용할 수 있게 됐다. 이어 v0.155.1에서는 로컬 TUI 세션의 추론 요약을 기본 비활성화하고 명시적 설정을 존중하도록 수정해 프로바이더 호환성 문제를 해결했다([Releasebot](https://releasebot.io/updates/openai/codex)).

## Claude Code: Projects 코디네이터와 Agent Teams 리서치 프리뷰

Anthropic이 9월 17일 Claude Projects를 재설계해 스레드가 작업을 수행하고 코디네이터가 지시하는 병렬 구조를 도입했다([Releasebot](https://releasebot.io/updates/anthropic)). Agent Teams도 리서치 프리뷰로 공개되어, 여러 Claude Code 세션이 팀 구조를 통해 관련 작업을 동시에 수행하고 결과를 공유할 수 있게 됐다. Claude Code v2.1.278은 서버사이드 자동 모드 분류기를 기본값으로 전환해 분류기 오버헤드 비용을 제거했다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)).

## GPT-5.5 은퇴 D-22 — ChatGPT Word 통합 확산 중

GPT-5.5의 ChatGPT·Codex 전면 퇴출까지 22일이 남았다(10/14)([Releasebot](https://releasebot.io/updates/openai/chatgpt)). Microsoft Word 통합은 모든 플랜에서 사용 가능해지며 초안 작성·요약·교정·서식 조정을 사이드바에서 처리할 수 있다. 새 음성→텍스트 모델도 전 플랜에 롤아웃되어 다국어 받아쓰기 정확도가 개선됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Word 통합 확산, GPT-5.5 은퇴 D-22 |
| Claude Code | 99 | — | Projects 코디네이터·Agent Teams 리서치 프리뷰 |
| Claude AI | 99 | — | Fable 5.1 SWE-bench Pro 81.2% 선두 |
| Codex CLI | 99 | — | v0.155.1, 음성 채팅 실험·Touch ID |
| Antigravity | 99 | — | 09-2026 프리뷰 안착, 5월 빌드 D-13 퇴출 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 여파 지속 |
| Aider | 68 | — | 공식 개발 정체, cecli 포크 주도 |
| Cursor | 47 | ↓2 | 33일 연속 하락, OpenAI 차단 D-51 |
| GH Copilot | 1 | — | 통합 경험 D-6 카운트다운 |
| Gemini CLI | 1 | — | 폐쇄 97일째 |

Cursor의 하락세가 멈출 기미가 보이지 않는다. OpenAI 모델 차단까지 51일, Copilot 통합 경험까지 6일 — 두 카운트다운이 AI 코딩 도구 시장의 다음 국면을 결정짓는 변수다.

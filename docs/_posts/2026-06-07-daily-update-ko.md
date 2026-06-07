---
title: "ChatGPT 10억 사용자 돌파, Copilot 49로 추락, Claude Code 장애 대비 fallbackModel 도입"
date: 2026-06-07
lang: ko
categories: [news]
tags: [chatgpt, github-copilot, claude-code, anthropic, gemini-cli, spacex, cursor]
excerpt: "ChatGPT가 월간 활성 사용자 10억 명을 돌파한 같은 날, Copilot은 49로 34주 연속 하락하고, Claude Code는 장애 대비용 fallbackModel 설정을 출시했다. 도쿄 컨퍼런스 D-3, Gemini CLI 종료 D-11."
---

ChatGPT가 월간 활성 사용자(MAU) 10억 명을 돌파하며 역대 가장 빠른 성장을 기록한 날, GitHub Copilot은 49까지 밀리며 34주 연속 하락세를 이어갔다. 한편 Claude Code는 잇따른 장애에 대한 해답으로 fallbackModel 설정을 출시했다.

## ChatGPT: 월간 10억 사용자, 영국에서 광고 시작

ChatGPT가 월간 활성 사용자 10억 명을 넘어섰다([ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). OpenAI는 동시에 영국 Free/Go 사용자 대상으로 광고를 도입하기 시작했으며, 유료 플랜은 광고 없이 유지된다. Plus/Pro 사용자에게는 메모리 용량 2배 확대와 Lockdown Mode(프롬프트 인젝션 방지 보안 설정)가 배포됐다.

## Claude Code v2.1.166-167: fallbackModel로 장애 복원력 확보

Claude Code가 이틀 연속 릴리스를 통해 `fallbackModel` 설정을 도입했다 — 주 모델 과부하 시 최대 세 개의 대체 모델을 순서대로 시도한다([GitHub Releases](https://github.com/anthropics/claude-code/blob/main/CHANGELOG.md)). 이 기능의 필요성은 오늘 바로 입증됐다 — Opus 4.7이 UTC 03:41부터 약 12시간 동안 오류 급증을 겪었으며, 15:41 UTC에 복구됐다([Claude Status](https://status.claude.com/)). 최근 세 차례 장애(6/2, 6/5, 6/7)를 겪은 사용자들에게 fallbackModel은 실질적인 복원력을 제공한다. glob 패턴 deny 규칙과 JetBrains 깜빡임 수정도 함께 출시됐다.

## GitHub Copilot: 49, 34주 연속 하락

Copilot이 **49**를 기록하며 어제 무너진 50선 아래로 더 깊이 빠졌다. 종량제 전환 7일차, 34주 연속 하락이다. Reddit과 개발자 포럼에는 Claude Code와 Codex CLI로의 이전 가이드가 여전히 최상위를 차지하고 있다([Dev.to](https://dev.to/akaranjkar08/switch-from-github-copilot-to-claude-code-migration-guide-2026-28nk)).

## Gemini CLI 종료 D-11: 신뢰 논란 지속

Gemini CLI 종료까지 11일 남았다. 6월 18일 이후 기업 고객만 접근 가능하며, 무료·AI Pro·Ultra 사용자는 차단된다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). "오픈소스로 6,000+ PR을 받아놓고 폐쇄형으로 전환했다"는 커뮤니티 비판이 계속되고 있다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)).

## Code with Claude 도쿄 D-3

Code with Claude 도쿄가 3일 앞으로 다가왔다. 6월 10일 Research·Platform·Code 3트랙, 6월 11일 인디 개발자 데모와 워크숍이 열린다([claude.com](https://claude.com/code-with-claude/tokyo)). 전 세션 라이브스트림과 영어/일본어 동시통역이 제공된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.166-167 fallbackModel, 도쿄 D-3 |
| ChatGPT | 96 | — | MAU 10억 돌파, UK 광고 시작 |
| Cursor | 96 | — | SpaceX $600억 인수 합의, IPO D-5 |
| Claude AI | 95 | — | 6/7 성능 저하 발생·복구 |
| Codex CLI | 87 | — | Sites 프리뷰, GPT-5.3-Codex 6/30 종료 |
| Windsurf | 85 | — | Cascade EOL 7/1, Devin Desktop 안정화 |
| Gemini CLI | 68 | ↓1 | 종료 D-11, 커뮤니티 신뢰 논란 |
| Aider | 68 | — | 오픈소스 CLI 안정 |
| Antigravity | 65 | — | Gemini CLI 이전 수요 흡수 |
| GH Copilot | 49 | ↓1 | 34주 연속 하락, 종량제 7일차 |

ChatGPT 10억 MAU 돌파와 Copilot의 50선 아래 추가 하락이 AI 코딩 도구 시장의 양극화를 선명하게 보여준다. 화요일 Code with Claude 도쿄에서 Anthropic이 어떤 발표를 가져올지가 이번 주 최대 관전 포인트다.

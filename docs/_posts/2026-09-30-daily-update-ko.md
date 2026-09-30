---
title: "DevDay 후폭풍: Dots 안전성 논란, Claude Code Sonnet 5.5 기본 전환, 개발자 90%가 AI 에이전트 사용"
date: 2026-09-30
lang: ko
categories: [news]
tags: [openai, dots, claude-code, anthropic, github-copilot, cursor, jetbrains, coderblock]
excerpt: "DevDay 하루 만에 Dots 안전성 우려가 쏟아지고, Claude Code는 Sonnet 5.5를 기본 모델로 전환했다. JetBrains 조사에서 개발자 90%가 AI 코딩 에이전트를 주 1회 이상 사용한다고 답했다."
---

OpenAI DevDay 2026의 흥분이 채 가시기도 전에, 오늘 업계의 시선은 빠르게 두 가지로 갈렸다 — Dots 에이전트의 안전성 문제와, 나머지 진영의 빠른 반격이다.

## OpenAI Dots: 화려한 데뷔 뒤에 드리운 안전성 그림자

어제 DevDay에서 Sam Altman이 "정말 모든 것을 처리할 수 있는 상시 에이전트"라고 소개한 Dots가 오늘 본격적인 안전성 검증대에 올랐다([Axios](https://www.axios.com/2026/09/30/openai-dots-ai-agent-safety)). OpenAI가 에이전트의 의도하지 않은 행동에 대한 추가 공개를 발표하고, 호주 Medicare 시스템 해킹 건에 대해 공식 사과한 직후의 출시라 논란이 더욱 거세다([CNBC](https://www.cnbc.com/2026/09/30/openai-follows-meta-into-the-red-hot-market-for-personal-agents.html)). 라이브 데모에서도 Holly Li의 Dot이 시연 시간 내에 응답하지 못하는 장면이 그대로 노출되면서, *"항상 켜져 있다는 게 항상 작동한다는 뜻은 아니다"*는 반응이 개발자 커뮤니티에 퍼졌다.

## Claude Code: Sonnet 5.5 기본 모델 전환 + 정상 종료 기능

Anthropic이 Claude Code 2.1.284(9월 28일)에서 기본 모델을 Claude Sonnet 5.5로 전환했다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). 1M 컨텍스트 윈도우와 함께 코딩 태스크에서 Sonnet 5보다 적은 스텝·토큰·도구 호출로 동일한 결과를 달성한다. 또한 5시간 제한에 도달하면 주간 한도에서 소량을 끌어와 진행 중인 작업을 정리하는 '정상 종료' 기능이 추가됐다.

## GitHub Copilot: Sonnet 5.5 탑재, 느린 회복세

GitHub Copilot에도 Claude Sonnet 5.5가 9월 28일부로 정식 추가됐다([GitHub Blog](https://github.blog/changelog/2026-09-28-claude-sonnet-5-5-in-github-copilot/)). Pro, Pro+, Max, Business, Enterprise 전 플랜에서 사용 가능하며, VS Code·JetBrains·Xcode·CLI 등 전 플랫폼으로 확대 중이다. Copilot 점수가 3→5→7로 소폭 반등하고 있지만, 전성기 90에서의 추락을 되돌리기엔 아직 멀다.

## JetBrains 조사: 개발자 90%가 AI 에이전트 주 1회 이상 사용

JetBrains Developer Ecosystem 설문(15,000명+ 전문 개발자 대상, 2026년 5~7월)에서 **90%가 AI 코딩 에이전트를 주 1회 이상, 68%가 매일 사용**한다고 응답했다([JetBrains](https://www.jetbrains.com/lp/devecosystem-2026/)). AI 코딩 도구가 '선택'에서 '기본'으로 전환된 것을 수치로 확인한 셈이다.

## Coderblock.ai: 신규 AI 코딩 플랫폼 공개 출시

이탈리아 스타트업 Coderblock.ai가 오늘 퍼블릭 론칭하며, 단일 프롬프트로 웹앱 전체를 생성하는 플랫폼을 선보였다([Coderblock](https://pasqualepillitteri.it/en/news/19532/coderblock-ai-opens-to-everyone)). GPT-6.1 Sol, Claude Sonnet 5.5, Claude Opus 5.5, Claude Fable 5, DeepSeek V4, GLM 등 6개 모델을 지원하며, 신규 가입 시 20크레딧 무료 제공이다.

## Cursor: 31점, 34일 연속 하락

Cursor는 31점으로 34일 연속 하락을 기록하며, OpenAI 모델 접근 종료(11/12)까지 D-43이 남았다([The Information](https://x.com/theinformation/status/2053490340238164364)). SpaceX 인수 이후 xAI 팀과의 통합 과정에서 인력 유출이 계속되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay 후속 보도 물결, Dots 안전성 논의 |
| Claude Code | 99 | — | Sonnet 5.5 기본 전환, 정상 종료 기능 |
| Codex CLI | 99 | — | GPT-6.1 Sol 지원 예상 |
| Antigravity | 99 | — | 30주 연속 최고점 |
| Claude AI | 99 | — | Fable 5.1 캐시 4배 인하 |
| Windsurf | 88 | — | Devin Desktop 안정세 |
| Aider | 68 | — | 사실상 개발 중단 |
| Cursor | 31 | ↓2 | 34일 연속 하락, D-43 |
| GH Copilot | 7 | ↑2 | Sonnet 5.5 추가, 느린 회복 |
| Gemini CLI | 1 | — | 폐쇄 105일째 |

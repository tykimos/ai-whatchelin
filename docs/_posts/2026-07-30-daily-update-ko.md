---
title: "GitHub Models 오늘 폐쇄, OpenAI 보안 CLI 오픈소스로 맞불"
date: 2026-07-30
lang: ko
categories: [news]
tags: [github-models, codex-security, chatgpt, openai, copilot, gemini-cli]
excerpt: "GitHub Models가 오늘 공식 폐쇄되며 플레이그라운드·모델 카탈로그·API가 모두 사라진다. 같은 날 OpenAI는 Codex Security CLI를 Apache 2.0으로 오픈소스 전환했고, ChatGPT는 음성 기반 에이전트 조율과 헬스 대시보드를 동시에 출시했다."
---

GitHub Models가 오늘 공식적으로 완전 폐쇄되면서 약 1년간 개발자들에게 무료 모델 테스트 환경을 제공하던 서비스가 역사 속으로 사라진다. OpenAI는 같은 날 보안 전용 CLI를 오픈소스로 공개하며 개발자 도구 생태계를 빠르게 확장하고 있다.

## GitHub Models: 오늘부로 완전 폐쇄

GitHub Models가 7월 30일 자로 완전 폐쇄됐다([GitHub Changelog](https://github.blog/changelog/2026-07-01-github-models-is-being-fully-retired-on-july-30-2026/)). 플레이그라운드, 모델 카탈로그, 인퍼런스 API, BYOK 엔드포인트가 전부 접근 불가가 됐으며, 7월 16일과 23일 브라운아웃을 거쳐 예고된 수순이었다([DEV Community](https://dev.to/leobaniak/github-sets-july-30-as-the-hard-shutdown-for-github-models-cmc)). Microsoft는 대체 경로로 Azure AI Foundry를 안내하고 있으나, Llama 3·Mistral·Phi-3를 브라우저에서 바로 시험하던 개발자들에게는 한 시대의 종말이다. 폐쇄 후 서버에 남은 모든 데이터는 영구 삭제되며 별도 내보내기 기간은 없다([Windows News](https://windowsnews.ai/article/github-models-shutdown-windows-teams-have-until-july-30-to-migrate.433587)).

## Codex Security CLI: Apache 2.0 오픈소스 전환

OpenAI가 Codex Security CLI와 SDK를 Apache 2.0 라이선스로 오픈소스 공개했다([CyberSecurity News](https://cybersecuritynews.com/openai-open-sources-codex-security-cli/)). `npm install @openai/codex-security`로 설치해 레포 스캔, 스테이지/언스테이지 변경사항 커밋 전 리뷰, CI/CD 심각도 임계값 게이팅까지 가능하다. 다만 핵심 분석 엔진은 OpenAI 호스팅 서비스에 의존하며, 현재는 승인된 파트너만 접근 가능한 제한 베타 상태다([The Next Web](https://thenextweb.com/news/openai-codex-security-cli-open-source-appsec-anthropic)).

## ChatGPT: 음성 에이전트 조율 + 헬스 대시보드 동시 출시

ChatGPT가 Work와 Codex 데스크톱 앱에 Voice 기능을 확장해, 자연어 음성으로 에이전트 태스크를 시작·중단·전환할 수 있게 됐다([Releasebot](https://releasebot.io/updates/openai/chatgpt)). 별도로 미국 내 Health 체험이 출시돼 건강 기록과 Apple Health 데이터를 연동하고 맥락 기반 건강 질문이 가능해졌다. 폴백 모델도 GPT-5.3 Instant Mini에서 GPT-5.5 Instant Mini로 교체되며 응답 품질이 한 단계 올라갔다([OpenAI Release Notes](https://releasebot.io/updates/openai)).

## Copilot: 81주 연속 하락, 내일 Gemini 모델 퇴장

GitHub Copilot은 81주 연속 하락세를 이어가며 바닥(1점)에 머물고 있다. 내일(7월 31일)에는 Gemini 2.5 Pro와 Gemini 3 Flash 모델이 Copilot 전 경험에서 공식 퇴장한다([GitHub Changelog](https://github.blog/changelog/2026-07-08-github-copilot-in-visual-studio-code-june-2026-releases/)). 다만 Copilot 메트릭 임팩트 대시보드 신규 출시와 에이전트 브라우저 도구 GA 등 플랫폼 자체는 계속 진화하고 있어, 점수 회복 가능성을 완전히 배제하기는 이르다([GitHub Changelog](https://github.blog/changelog/2026-07-22-new-copilot-usage-metrics-impact-dashboard/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 기본, 서브에이전트 3단계 중첩 |
| ChatGPT | 99 | — | Voice for Work, Health 출시, 폴백 모델 업그레이드 |
| Antigravity | 99 | — | 27주 연속 99 진입 |
| Claude AI | 99 | — | 안정 유지 |
| Cursor | 97 | — | Router 지능형 모드, iOS 퍼블릭 베타 |
| Codex CLI | 93 | ↑1 | Security CLI 오픈소스, 보안 생태계 확장 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | — | 81주 하락, GitHub Models 폐쇄 완료 |
| Gemini CLI | 1 | — | 소비자 종료 42일째 |

Codex CLI가 이틀 연속 상승하며 보안 도구 영역까지 확장했다. GitHub Models 폐쇄는 한 시대의 마침표이자, AI 모델 접근 경로가 Azure AI Foundry와 Copilot으로 수렴하는 신호다.

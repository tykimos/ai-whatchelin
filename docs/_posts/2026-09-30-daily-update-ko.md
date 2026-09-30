---
title: "OpenAI Dots 라이브 데모 무대 위에서 멈춤 — 오디오 차단 논란까지"
date: 2026-09-30
lang: ko
categories: [news]
tags: [openai, dots, devday, spacexai, cursor, grok, claude-code, codex-cli, github-copilot]
excerpt: "DevDay 2026 라이브 데모에서 Dots가 무대 위에서 응답을 멈췄고, 공식 스트림 오디오가 정확히 그 순간 잘렸다. 한편 Bloomberg은 SpaceXAI의 Grok-X 4단계 요금제를 보도했고, Claude Code는 v2.1.285를 출시했다."
---

DevDay 2026의 열기가 채 식기도 전에 OpenAI에 민망한 순간이 찾아왔다. 9월 30일 라이브 스트림에서 발표자 Holly Li가 Dots에 사용자 테스트 데이터를 요청하자 에이전트가 응답을 멈췄고, Romain Huet가 음성으로 Dots를 지시하려 하자 "음성 채팅을 시작할 수 없습니다"라는 메시지가 메인 스크린에 떴다([SoapCentral](https://www.soapcentral.com/entertainment/openai-live-demonstration-dots-allegedly-fails-voice-feature-faces-technical-glitch)). 더 논란이 된 것은 공식 스트림 오디오가 데모 실패 시점에 정확히 잘린 뒤 복구됐다는 점이다 — X 사용자 @ns123abc가 자신의 현장 녹화와 공식 스트림을 비교한 영상을 올리며 의도적 차단이라고 주장했고, OpenAI는 아직 해명하지 않았다([AGTP/X](https://x.com/AGTPinsights/status/2105171668725608906)). OpenAI의 Thibault Sottiaux는 "모든 업데이트를 동시에 배포한 탓"이라고만 인정했다([HuggingNews](https://huggingnews.com/ai/update-openai-blames-dots-demo-failures-on-simultaneous-updates-53c443c1)).

## SpaceXAI: Bloomberg, Grok-X 4단계 요금제 보도

Bloomberg이 SpaceXAI의 Grok와 X 구독 통합 계획을 보도했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-09-30/musk-s-spacexai-considers-overhaul-of-pricing-for-grok-x-users)). 무료(사용량 제한), $8 Lite(Grok + 인증 + 광고 감소), 미공개 중간 티어, $100 Ultra(Grok Bot 에이전트 포함) 4단계 구조다. SpaceXAI는 9월 14일 Grok과 Cursor 구독 모델 통합을 예고한 바 있어([TheNextWeb](https://thenextweb.com/news/spacexai-grok-x-subscription-tiers-ultra-lite)), Cursor의 미래 요금 체계가 이 구조에 흡수될 가능성이 높아졌다.

## Claude Code: v2.1.285 — 데스크톱·플러그인·MCP 확장

Anthropic이 Claude Code v2.1.285를 출시했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 새 데스크톱, 플러그인, MCP, 환경 제어 기능이 추가됐고, VSCode와 웹 경험이 개선됐다. 모델·태스크·아티팩트 워크플로우가 강화됐으며, 세션·권한·원격 제어·플랫폼 관련 다수 버그가 수정됐다. 전날 장애에도 불구하고 현재 모든 Claude 시스템은 정상 운영 중이다([Benzinga](https://www.benzinga.com/markets/tech/26/09/62056363/claude-back-online-after-widespread-outage-hits-anthropics-ai-chatbot)).

## Codex CLI: v0.159.2 — Windows 수정 + 풀스크린 UI

Codex CLI가 v0.159.2를 출시해 Windows에서 백그라운드 프로세스 실행 시 콘솔 창이 깜빡이는 문제를 수정했다([GIGAZINE](https://gigazine.net/gsc_news/en/20260930-openai-codex-cli-cloud/)). DevDay에서 공개된 풀스크린 인터페이스, /voice 음성 지시, /usage 분석, 테마 지원, 접이식 diff 등이 v0.159.0에서 정식 탑재된 상태다.

## GitHub Copilot: GPT-6.1 Sol + Sonnet 5.5 모델 추가

GitHub Copilot에 GPT-6.1 Sol과 Claude Sonnet 5.5 모델이 추가됐다([GitHub Changelog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)). 효율성·균형·지능 3단계 자동 모델 선택 기능과 Jira 통합, Project HydraFusion 적응형 모델 오케스트레이션이 함께 출시됐다. 느리지만 꾸준한 회복세다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Dots 데모 실패에도 DevDay 모멘텀 유지 |
| Claude Code | 99 | — | v2.1.285, 장애 완전 복구 |
| Codex CLI | 99 | — | v0.159.2, 클라우드 환경 출시 |
| Antigravity | 99 | — | 30주 연속 최고점 |
| Claude AI | 99 | — | Sonnet 5.5 기본 전환 완료 |
| Windsurf | 88 | — | Devin Desktop 안정세 |
| Aider | 68 | — | 사실상 개발 중단 |
| Cursor | 31 | ↓2 | 34일 연속 하락, Grok-X 통합 임박 |
| GH Copilot | 7 | ↑2 | GPT-6.1 Sol + Sonnet 5.5 추가 |
| Gemini CLI | 1 | — | 폐쇄 105일째 |

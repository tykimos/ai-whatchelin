---
title: "Anthropic 기업 보안센터 출시, OpenAI Dots 정식 개방 — Copilot 42일 연속 상승, Cursor 차단 D-6"
date: 2026-11-06
lang: ko
categories: [news]
tags: [anthropic, claude-code, openai, dots, chatgpt, images, github-copilot, jetbrains, cursor, postman, watermark]
excerpt: "Anthropic이 Claude Enterprise 보안센터를 출시하고 Claude 모델에 워터마킹을 적용했다. OpenAI Dots가 기업 사용자에게 정식 개방되며, Copilot은 JetBrains Air 통합으로 42일 연속 상승 중이다."
---

Anthropic이 기업 보안 도구와 모델 워터마킹이라는 두 가지 굵직한 업데이트를 이번 주 연달아 내놓았다. OpenAI도 개인 에이전트 Dots를 기업 고객에게 정식 개방하며 에이전트 전쟁에 본격 참전했다.

## Anthropic: Claude Enterprise 보안센터 출시

Anthropic이 11월 5일 Claude Enterprise용 보안센터를 출시했다([DEV Community](https://dev.to/hiroki-ii-ai/ai-daily-digest-november-6-2026-openai-ships-gpt-6-cyber-meta-buys-conductor-anthropic-locks-1jij)). 보안센터는 Chat, Cowork, Claude Code 설정을 Anthropic 권장사항과 비교하고 감사 보고서를 내보낼 수 있다. Anthropic은 이것이 가이드라인이지 컴플라이언스 인증은 아니라고 명시했다. 다가오는 IPO(목표 11월 16일 상장, 티커 ANT)를 앞두고 기업 고객 신뢰 확보에 집중하는 모습이다([Invenglobal](https://www.invenglobal.com/articles/27712/anthropic-files-s-1-for-ipo-plans-nasdaq-listing-under-ticker-ant)).

## Anthropic: Claude 모델 워터마킹 시작

11월 3일부터 Claude Mythos 5, Opus 4.7, Sonnet 4.6 텍스트 출력에 보이지 않는 워터마크가 적용되기 시작했다([Releasebot](https://releasebot.io/updates/anthropic)). 2차 적용으로 구형 모델에도 확대될 예정이며, 컴플라이언스 목적으로 워터마크에 의존하는 고객은 기본 설정 유지를 권장받고 있다. AI 생성 텍스트 식별 요구가 강해지는 규제 환경에서 선제적 대응으로 보인다.

## Claude Code: Messages API 스레드 기능 공개 베타

11월 2일 Messages API에 메시지 스레드 기능이 공개 베타로 추가되었다([Releasebot](https://releasebot.io/updates/anthropic)). 에이전트가 긴 세션에서 매 턴마다 새 메시지만 전송할 수 있어 지연시간이 크게 줄어든다. Claude Code의 `claude auth status`에는 로그인 만료 10일 전 경고가 추가되었다.

## OpenAI: Dots 기업용 정식 개방

OpenAI가 11월 4일 개인 에이전트 Dots를 Enterprise, Edu, Healthcare 워크스페이스에 정식 개방했다([OpenAI Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). 워크스페이스 관리자가 접근을 활성화하거나 옵트아웃할 수 있으며, 11월 18일부터 기본 활성화된다. GPT-6 Astra 기반으로 대화 간 지속적으로 작업을 수행하는 상시 에이전트로, 9월 DevDay 발표 이후 약 5주 만의 정식 개방이다([TechCrunch](https://techcrunch.com/2026/09/29/openai-launches-dots-its-bubbly-agentic-avatar/)).

## ChatGPT: Images 2.6 출시, GIF 생성·참조 이미지 저장

OpenAI가 11월 4일 ChatGPT Images 2.6을 출시했다([OpenAI Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). GIF 생성 기능이 추가되어 대화 내에서 짧은 애니메이션을 만들 수 있으며, 참조 이미지를 저장해 이후 대화에서 재사용할 수 있다. Pro와 Business Premium 플랜의 Work/Codex 사용량 한도는 10월 29일 두 배로 증가했다.

## GitHub Copilot: JetBrains Air·Xcode 통합, 42일 연속 상승

GitHub Copilot이 11월 3일 JetBrains Air에서 사용 가능해졌다([GitHub Changelog](https://github.blog/changelog/2026-11-03-github-copilot-is-now-available-in-jetbrains-air)). Xcode 27.3 베타 통합에 이어 48시간 만에 두 번째 IDE 확장이다([9to5Mac](https://9to5mac.com/2026/11/03/xcode-27-3-adds-github-copilot-to-its-built-in-coding-assistant)). 점수는 81점으로 42일 연속 상승하며, 11월 16일 모델 교체(Opus 4.8/5 → Opus 5.5, GPT-5.6 Terra → GPT-6.1 Sol)까지 10일 남았다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)).

## Cursor: OpenAI 차단 D-6, 73일째 바닥

11월 12일 OpenAI 모델 접근 완전 차단까지 6일 남았다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). OpenAI는 SpaceX 인수 후 이용약관 준수에 대한 확신이 없다는 이유를 들었다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). Cursor CEO는 OpenAI 모델이 전체 트래픽의 약 5%에 불과하다고 밝혔으며, Grok 4.7과 Anthropic 모델로 전환을 진행 중이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Images 2.6 출시, Dots 기업 정식 개방 |
| Claude Code | 99 | — | 보안센터 출시, API 스레드 베타 |
| Codex CLI | 99 | — | v0.166.0 안정, GPT-6.1 Terra 지원 |
| Antigravity | 99 | — | 플러그인 마켓플레이스 안정 |
| Claude AI | 99 | — | 워터마킹 적용, IPO 로드쇼 임박 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| GH Copilot | 81 | ↑2 | 42일 연속 상승, JetBrains Air + Xcode |
| Aider | 68 | — | 유지보수 모드 |
| Cursor | 1 | — | OpenAI 차단 D-6, 73일째 바닥 |
| Gemini CLI | 1 | — | 서비스 종료, Antigravity 전환 완료 |

Anthropic과 OpenAI가 동시에 기업 보안·에이전트 기능을 강화하면서, AI 코딩 도구 경쟁의 전선이 '코드 생성'에서 '기업 인프라 통합'으로 확대되고 있다.

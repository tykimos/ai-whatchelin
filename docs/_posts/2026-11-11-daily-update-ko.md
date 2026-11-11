---
title: "Claude Code, Fable 5.2를 기본 모델로 전격 전환 — Copilot은 GPT-6.1 Terra 장착"
date: 2026-11-11
lang: ko
categories: [news]
tags: [claude-code, anthropic, github-copilot, cursor, openai, codex-cli, antigravity]
excerpt: "Anthropic이 Fable 5.2를 출시한 다음 날, Claude Code v2.1.321이 즉시 기본 모델로 채택했다. GitHub Copilot CLI도 GPT-6.1 Terra를 추가하며 모델 경쟁이 가열되고 있다."
---

Anthropic이 Fable 5.2를 공개한 지 하루 만에 Claude Code가 이를 기본 모델로 전환했다. GitHub Copilot CLI도 GPT-6.1 Terra를 장착하며 모델 경쟁이 한층 치열해진 가운데, 내일은 Cursor의 OpenAI 모델 접근이 완전 차단되는 운명의 날이다.

## Claude Code v2.1.321: Fable 5.2 기본 전환, 보안 수정 포함

Claude Code v2.1.321이 11월 10일 출시되며 Claude Fable 5.2를 기본 Fable 모델로 채택했다([ai-tldr.dev](https://ai-tldr.dev/releases/anthropic-claude-code-2-1-321/)). Fable 5.2는 11월 9일 출시된 Anthropic의 최신 코딩 모델로, 5.1 대비 30% 빠른 출력과 20% 인하된 가격($10/$50 → $8/$40 per MTok)이 핵심이다([9to5mac.com](https://9to5mac.com/2026/11/09/anthropic-upgrades-claude-with-new-fable-5-2-model-details-here/)). 기존 Fable 5.1 선택은 `fable` 별칭으로 자동 마이그레이션되며, `/model claude-fable-5-1`으로 수동 복귀 가능하다. MCP OAuth에서 리다이렉트 후 리프레시 토큰이 다른 호스트로 전송되는 보안 취약점도 함께 수정되었다([labmemo.com](https://labmemo.com/claude-code-v2-1-321-fable-5-2-default-security-fixes-2026-11/)).

## GitHub Copilot CLI v1.0.106: GPT-6.1 Terra 모델 추가

Copilot CLI v1.0.106이 11월 6일 출시되며 GPT-6.1 Terra를 모델 피커에 추가했다([newreleases.io](https://newreleases.io/project/npm/@github/copilot/release/1.0.106)). GPT-6.1 Terra는 GPT-6.1 Sol보다 저렴한 일상 에이전틱 코딩 모델로, Pro/Pro+/Max/Business/Enterprise 전 유료 플랜에서 사용 가능하다([github.blog](https://github.blog/changelog/2026-10-26-gpt-6.1-terra-in-github-copilot)). `/code` 명령으로 현재 세션을 VS Code에서 열 수 있으며, `/settings` 통합 대시보드와 세션 `@mentions` 기능도 추가되었다([havoptic.com](https://www.havoptic.com/r/github-copilot-v1.0.106)).

## Cursor: OpenAI 차단 D-1, 78일째 바닥

OpenAI가 Cursor의 모델 접근을 완전 차단하는 날이 내일(11월 12일)이다([CyberNews](https://cybernews.com/ai-news/openai-cursor-spacex-contract-termination/)). SpaceX의 Anysphere 600억 달러 인수 후 촉발된 계약 해지 조항에 따른 것으로, 인기도 1점이 78일째 이어지며 시장 신뢰 회복은 요원하다([RuntimeWire](https://runtimewire.com/article/openai-cuts-cursor-model-access-spacex-acquisition)).

## Antigravity 2.29: Knowledge Work 모드 공개

Google의 Antigravity가 11월 10일 Knowledge Work 오피스 모드를 공개했다([ChainCatcher](https://www.chaincatcher.com/en/article/2303352)). 터미널·Git을 숨기고 리서치·문서 작업에 집중하는 모드로, 기존 2.29의 Remote Agents·Voice Mode에 이은 세 번째 핵심 기능이다. 한편, Antigravity 빌드에서 Gemini 4 Carbon Low/Medium/High 변형이 발견되었지만, 아직 공식 확인은 없다([TestingCatalog](https://pasqualepillitteri.it/en/news/31811/gemini-4-carbon-antigravity-build-low-medium-high)).

## 엔터프라이즈 AI 긴축: Apple $200, Goldman 엔지니어 전용

Apple이 엔지니어의 일일 AI 사용 한도를 $300에서 $200으로 축소하고 $100까지 추가 인하 가능성을 시사했다([Macworld](https://macworld.com/article/3277678/apple-reportedly-slashes-employee-ai-usage-limits-amid-cost-cutting-effort.html)). Goldman Sachs도 Claude Code·GitHub 도구 접근을 엔지니어링 직군으로 제한하며 약 10,000명의 트레이더·뱅커가 접근을 잃었다([Dealroom](https://app.dealroom.co/news/note/goldman-restricts-claude-code-github-for-traders-and-bankers)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 안정 유지 |
| Claude Code | 99 | — | v2.1.321 Fable 5.2 기본 전환 |
| Codex CLI | 99 | — | 0.167.0 에이전트 커맨드 센터 |
| Antigravity | 99 | — | Knowledge Work 모드 공개 |
| Claude AI | 99 | — | Fable 5.2 출시, IPO 로드쇼 진행 |
| GH Copilot | 91 | ↑2 | v1.0.106 GPT-6.1 Terra, 47일 연속 상승 |
| Windsurf | 88 | — | Devin Desktop으로 안정 운영 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 D-1, 78일째 바닥 |
| Gemini CLI | 1 | — | 서비스 종료, Antigravity 전환 완료 |

Claude Code와 Copilot CLI가 각각 Fable 5.2와 GPT-6.1 Terra로 모델 세대교체를 완료하며, 내일 Cursor의 OpenAI 차단이 현실화되는 시점과 겹친다. 도구 간 모델 경쟁이 가속화되는 가운데, 엔터프라이즈 시장의 AI 긴축은 새로운 변수로 작용하고 있다.

---
title: "DeepSeek V4 강제 전환 D-Day, Cursor Router로 비용 60% 절감 시대 개막"
date: 2026-07-24
lang: ko
categories: [news]
tags: [deepseek, cursor, anthropic, claude-security, github-models, copilot, gemini-cli, opus, antigravity]
excerpt: "DeepSeek V4 레거시 엔드포인트가 오늘 폐쇄되고, Cursor Router가 모델 라우팅으로 비용 60% 절감을 달성했다. Opus 4.7 fast mode도 동시 종료."
---

오늘은 AI 개발자들에게 세 건의 굵직한 변화가 동시에 발생한 날이다. DeepSeek V4의 `deepseek-chat`과 `deepseek-reasoner` 레거시 엔드포인트가 UTC 15:59부로 완전 폐쇄됐고([DEV Community](https://dev.to/agdex_ai/deepseek-v4-api-migration-guide-everything-before-the-july-24-2026-deadline-4m30)), Anthropic은 Opus 4.7 fast mode를 종료하고 Opus 4.8 fast mode로 전환을 완료했다. 그리고 이틀 전 출시된 Cursor Router가 빠르게 채택되며 업계의 비용 구조를 바꾸고 있다.

## Cursor Router: 모델 라우팅으로 비용 혁명

Cursor가 7월 22일 출시한 Router는 60만 건 이상의 실시간 요청으로 학습한 지능형 모델 라우터다([Cursor Blog](https://cursor.com/blog/router)). 매 요청의 복잡도와 작업 유형을 분석해 최적의 모델을 자동 선택하고, 단순 작업은 저렴한 모델로, 복잡한 작업만 프론티어 모델로 보낸다. 수십 개 기업 대상 얼리 액세스에서 품질 저하 없이 30-60% 비용 절감을 달성했다([MarkTechPost](https://www.marktechpost.com/2026/07/22/cursor-releases-cursor-router-a-request-level-classifier/)). Teams 플랜에는 기본 적용되며, Enterprise는 관리자가 조직 그룹별로 활성화할 수 있다.

## DeepSeek V4: 레거시 엔드포인트 완전 폐쇄

100만 토큰 컨텍스트와 강화된 에이전트 실행을 갖춘 V4가 안정판으로 올라서면서 기존 모델명이 폐쇄됐다([WaveSpeed](https://wavespeed.ai/blog/posts/blog-deepseek-v4-model-name-migration/)). 마이그레이션은 모델명 한 줄만 바꾸면 되지만, 놓치면 프로덕션이 깨진다. 한편 피크 시간대(베이징 시간 9-12시, 14-18시) API 요금이 2배로 뛰는 '러시아워 가격제'는 API 토큰 시장의 첫 시간대별 가격 차등 사례로 논란 중이다([Servola](https://servola.de/journal/ai-tokens-now-have-a-rush-hour/)).

## Claude Security: 엔터프라이즈 베타 확산 중

어제 공개된 Claude Security가 빠르게 확산 중이다. Opus 4.7 기반 멀티에이전트 스캐너가 Git 히스토리와 파일 간 데이터 플로우를 추적해 타겟 패치까지 생성한다([MarkTechPost](https://www.marktechpost.com/2026/07/22/anthropic-releases-claude-security-plugin-for-claude-code-in-beta-a-multi-agent-vulnerability-scanner-that-runs-in-your-terminal/)). Claude Code 플러그인으로 커밋 전 터미널 스캔이 가능하며, 현재 Enterprise 전용이다([Claude Blog](https://claude.com/blog/claude-security-public-beta)).

## Antigravity CLI v1.1.5: 추론 깊이 실시간 조절

Antigravity CLI가 7월 21일 v1.1.5를 릴리스하며 `/effort` 명령어를 추가했다([Havoptic](https://www.havoptic.com/tools/antigravity-cli)). 속도와 사고 깊이를 실시간으로 트레이드오프할 수 있어, 간단한 작업에서 불필요한 토큰 소모를 줄일 수 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Claude Security 베타 호응, Fable 기본 모델 안정 |
| ChatGPT | 99 | — | GPT-5.6 Sol 안정화, Codex 통합 진행 |
| Antigravity | 99 | — | v1.1.5 /effort 명령어, Go 빌드 안정 |
| Claude AI | 98 | — | Opus 4.8 fast mode 전환 완료 |
| Cursor | 97 | — | Router 출시, 사용량 2배 인상, iOS 안착 |
| Codex CLI | 91 | — | v0.145.0 안정 운영, Bedrock 지원 확대 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | ↓1 | 76주 연속 하락, GitHub Models D-6 |
| Gemini CLI | 1 | ↓1 | 소비자 접근 차단 36일째 |

Cursor Router의 출시가 가장 큰 시장 시그널이다. 모델 라우팅을 통한 30-60% 비용 절감은 "항상 가장 비싼 모델을 쓸 필요 없다"는 메시지를 업계에 던지며, 다른 AI 코딩 도구들도 유사한 접근을 취할 것으로 보인다.

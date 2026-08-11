---
title: "Claude Code, 8월 14일부터 Auto 모드 기본 전환 — AI 에이전트에 '자동 운전석'을 맡긴다"
date: 2026-08-11
lang: ko
categories: [news]
tags: [claude-code, anthropic, meta, chatgpt, openai, devin, copilot]
excerpt: "Anthropic이 Claude Code의 auto 모드를 기본 권한으로 전환한다. 안전 분류기가 유해 행동의 89%를 포착하는 반면 인간 리뷰는 13.6%에 그쳤다는 데이터가 근거다. Meta는 단일 GPU에서 돌아가는 300억 파라미터 오픈웨이트 에이전트를 공개했다."
---

Anthropic이 8월 14일부터 Claude Code의 auto 모드를 Pro·Max·Team 플랜 신규 세션의 기본 권한 모드로 전환한다([TechCrunch](https://techcrunch.com/2026/08/09/anthropic-is-turning-claude-codes-auto-mode-on-by-default/)). 1,053명 유료 사용자 테스트에서 안전 분류기가 유해 행동의 89%를 차단한 반면, 인간 리뷰는 97%의 프롬프트를 습관적으로 승인하며 13.6%만 잡아냈다([Simon Willison](https://simonwillison.net/2026/Aug/8/auto-mode/)). 프롬프트 인젝션 스크리닝과 커스텀 하드 디나이 규칙이 함께 추가됐다. Enterprise·API·AWS·Bedrock는 "한 달 내" 후속 적용 예정이다.

## Claude Code: v2.1.227 릴리스

오늘 배포된 v2.1.227은 만료된 로그인 토큰으로 세션 시작 시 구독 티어 없이 피처 플래그가 평가되던 버그를 수정했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). claude-code-action의 Bash 실행 실패, /tui 되감기 동작, 슬래시 명령 메뉴 개선, 이벤트 루프 지연 감소도 포함됐다. auto 모드 기본 전환을 3일 앞두고 안정성을 다지는 패치다.

## Meta: Muse Glimmer 30B — 단일 GPU 오픈웨이트 에이전트

Meta가 300억 파라미터 오픈웨이트 모델 Muse Glimmer를 Apache 2.0으로 공개했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-10/meta-releases-muse-glimmer-ai-model-people-can-run-on-their-laptop)). 양자화 시 20GB 미만으로 단일 소비자 GPU에서 구동되며, 131K 컨텍스트·100개 이상 언어를 지원한다([Meta AI Research](https://research.meta.ai/blog/introducing-muse-glimmer-open-agentic-model)). 코딩·함수 호출·LLM-as-judge 등 로컬 에이전틱 작업에 최적화됐다. Zuckerberg는 14페이지 에세이에서 분산형 오픈 AI 개발을 옹호했다([CNBC](https://www.cnbc.com/2026/08/10/meta-muse-glimmer-open-weight-ai.html)).

## ChatGPT: 레스토랑 예약 + Voice 파일 업로드

ChatGPT가 OpenTable·Resy·Yelp을 통한 레스토랑 예약 기능을 전 플랜에 출시했다([OpenAI](https://openai.com/products/release-notes/)). 별도로 GPT-Live Voice에 파일 업로드와 Projects 통합이 추가돼 음성 대화 중 문서 분석이 가능해졌다. OpenAI는 같은 날 Daybreak 이니셔티브도 확대해 Blue(GPT-5.6 Sol 사이버 가드레일 제거)와 Red(GPT-5.6-Cyber 전용 모델) 두 티어를 공개했다([techstartups.com](https://techstartups.com/2026/08/10/top-tech-news-today-august-10-2026-apple-google-meta-openai-unitree-more/)).

## Devin Desktop: 대화 공유 + 커스터마이제이션 패널

Devin Desktop이 로컬 에이전트 활성 시 안전 재시작 확인, "Plugins"→"Extensions" 이름 변경, 원격 머신 코드맵 지원 등을 업데이트했다([Releasebot](https://releasebot.io/updates/windsurf)). Devin Local에는 시스템 프롬프트 삭제·시크릿 마스킹이 적용된 대화 공유 기능, 턴 중간 되돌리기, 서브에이전트 섹션이 포함된 커스터마이제이션 패널이 추가됐다.

## GitHub: Actions/Pages 장애 + Auto 모드 투명성

GitHub Actions와 Pages가 8월 6-7일 약 20시간 동안 성능 저하를 겪었다([BigGo Finance](https://finance.biggo.com/news/51fece48-5b5c-4241-9292-3a19f12b6024)). AI 기반 부하와 Azure 마이그레이션 압박이 동시에 작용한 결과다. Copilot 주간 릴리스에서는 Auto 모드가 요청별 사용 모델·AI 크레딧·캐시 정보를 표시하기 시작했고, /side 명령으로 병렬 질문이 가능해졌다([GitHub Blog](https://github.blog/changelog/2026-08-07-github-copilot-weekly-releases-august-3/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Auto 모드 8/14 기본 전환 발표, v2.1.227 |
| ChatGPT | 99 | — | 레스토랑 예약, Daybreak 확대, 레거시 정리 가속 |
| Antigravity | 99 | — | 상한 유지 |
| Claude AI | 99 | — | 50% 부스트 8/19까지 연장 |
| Codex CLI | 99 | — | v0.147.0 플러그인 생태계, 상한 유지 |
| Cursor | 97 | — | Router Auto Intelligence 유지, 신규 릴리스 없음 |
| Windsurf | 85 | — | Devin Desktop 대화 공유 기능 추가 |
| Aider | 68 | — | 2025년 8월 이후 릴리스 없음 |
| Copilot | 1 | — | 91주 하락, Actions 장애, D-21 |
| Gemini CLI | 1 | — | 폐쇄 54일째, Antigravity 완전 대체 |

Claude Code의 auto 모드 기본 전환은 AI 코딩 도구 시장에서 '인간 감독 vs 자동화 효율' 논쟁의 분수령이다. 안전 분류기가 인간보다 6.5배 높은 포착률을 보인다는 데이터가 Anthropic의 근거지만, 커뮤니티 반응은 갈리고 있다. Meta의 Muse Glimmer 30B는 '로컬 AI 에이전트' 트렌드를 한 단계 더 끌어올렸다 — Ollama $65M, DeepSeek 가격 인상에 이어 로컬 실행 수요가 구조적으로 고착화되는 흐름이다.

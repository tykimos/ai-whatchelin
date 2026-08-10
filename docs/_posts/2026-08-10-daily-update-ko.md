---
title: "Ollama $65M 유치로 로컬 AI 900만 개발자 확보 — OpenAI는 레거시 대청소 가속"
date: 2026-08-10
lang: ko
categories: [news]
tags: [ollama, openai, meta, deepseek, copilot, claude-code, cursor]
excerpt: "Ollama가 시리즈 B $65M을 유치하며 월간 활성 개발자 900만을 돌파했다. 같은 날 OpenAI는 레거시 API 엔드포인트 배치 폐쇄를 단행하고, Meta는 단일 GPU에서 돌아가는 300억 파라미터 에이전트를 공개했다."
---

로컬 AI 러너 Ollama가 Theory Venture 주도로 시리즈 B $6,500만을 마감했다([techstartups.com](https://techstartups.com/2026/08/10/top-tech-news-today-august-10-2026-apple-google-meta-openai-unitree-more/)). 월간 활성 개발자 900만 명. 클라우드 API 의존도를 낮추고 로컬에서 오픈웨이트 모델을 돌리려는 수요가 폭발적으로 증가하고 있다는 신호다. DeepSeek 가격 인상 예고가 이 흐름을 더 가속시킬 수 있다.

## OpenAI: 레거시 API 엔드포인트 배치 폐쇄

오늘(8/10) OpenAI가 추가 레거시 API 엔드포인트 배치를 폐쇄했다([openai.com](https://openai.com/products/release-notes/)). 7월 23일 1차 폐쇄에 이은 2차 조치다. o1, o3-mini, GPT-3.5, GPT-4 모델은 10월 23일 완전 은퇴 예정이다. GPT-5.4/5.4 mini도 8월 31일 ChatGPT 인증 Codex에서 제거되고, DALL-E GPT는 8월 30일 종료된다. OpenAI의 GPT-5.6 중심 통합 전략이 더욱 명확해지고 있다.

## Meta: 단일 GPU 300억 파라미터 에이전트 공개

Meta가 단일 GPU에서 구동되는 300억 파라미터 에이전트를 공개했다([techstartups.com](https://techstartups.com/2026/08/10/top-tech-news-today-august-10-2026-apple-google-meta-openai-unitree-more/)). 동시에 Muse Spark 1.1 멀티모달 에이전틱 모델을 퍼블릭 Meta Model API로 제공하며, 가격은 $1.25/$4.25/MTok으로 OpenAI·Anthropic 대비 약 25% 수준이다. 로컬 실행 가능성과 저렴한 클라우드 API를 동시에 제공하는 투트랙 전략이다.

## DeepSeek: 가격 인상 카운트다운 6일째

DeepSeek의 '상당한' 가격 인상 예고가 6일째 시장을 흔들고 있다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-06/deepseek-plans-significant-price-increase-for-its-ai-services)). V4 Flash가 8월 1일 하루에 8조 토큰을 처리하며 컴퓨팅 자원이 포화된 것이 배경이다. 창업자 Jun Song은 "2-10배 인상해도 서양 경쟁사보다 저렴할 것"이라고 밝혔지만, 구체적 인상 폭과 시기는 여전히 미공개([explainx.ai](https://www.explainx.ai/blog/deepseek-api-price-increase-jun-song-august-2026)). Ollama의 로컬 모델 수요가 DeepSeek 의존 개발자들의 대안으로 떠오르고 있다.

## GitHub Copilot: 에이전트 앱 활동 메트릭 API 추가

Copilot 사용량 메트릭 API가 서드파티 에이전트 앱 활동을 추적하기 시작했다([github.blog](https://github.blog/changelog/2026-08-07-copilot-usage-metrics-api-adds-agent-app-activity/)). 엔터프라이즈·조직 1일 및 28일 리포트에서 에이전트별 세션 수, 사용자 시작 인터랙션 수를 확인할 수 있다. 9/1 대규모 모델 폐기까지 D-22.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.226 안정화, 4일 연속 릴리스 후 휴식 |
| ChatGPT | 99 | — | 레거시 API 배치 폐쇄, GPT-5.6 통합 가속 |
| Antigravity | 99 | — | 상한 유지 |
| Claude AI | 99 | — | 50% 부스트 8/19까지 연장 |
| Codex CLI | 99 | — | v0.147.0 플러그인 생태계, 상한 유지 |
| Cursor | 97 | — | Router Auto Intelligence 68% 비용 절감 유지 |
| Windsurf | 85 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 2025년 8월 이후 릴리스 없음 |
| Copilot | 1 | — | 에이전트 메트릭 API 추가에도 D-22 |
| Gemini CLI | 1 | — | 폐쇄 53일째, Antigravity 완전 대체 |

Ollama $65M, Meta 300억 파라미터 로컬 에이전트, DeepSeek 가격 인상 — 세 가지가 동시에 일어나면서 '로컬 AI'가 더 이상 틈새가 아닌 주류로 부상하고 있다. OpenAI의 레거시 정리와 맞물려, AI 코딩 도구 시장은 '클라우드 통합 vs 로컬 분산'이라는 구조적 분기점에 놓였다.

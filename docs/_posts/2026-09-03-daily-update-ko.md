---
title: "GPT-6 Astra 출시 — 그리고 ChatGPT·Claude·Grok이 동시에 다운됐다"
date: 2026-09-03
lang: ko
categories: [news]
tags: [openai, gpt-6, astra, claude, grok, outage, nvidia, hugging-face, cursor, anthropic]
excerpt: "OpenAI가 '역대 최강' GPT-6 Astra를 출시했지만, 같은 날 ChatGPT·Claude·Grok 3대 AI 서비스가 동시에 장애를 겪었다. Nvidia의 Hugging Face 129억 달러 인수도 확정됐다."
---

OpenAI가 오늘 GPT-6 Astra를 출시하며 "AGI 시대에 오신 것을 환영합니다"라고 선언했다([9to5Mac](https://9to5mac.com/2026/09/03/openai-releasing-major-upgrade-to-chatgpt-and-codex-with-gpt-6-astra-details-here/)). 가격은 입력 $10/MTok, 출력 $50/MTok으로, 1,050K 컨텍스트 윈도우와 128K 최대 출력을 지원한다([OpenAI Developers](https://developers.openai.com/api/docs/models/gpt-6-astra)). Terminal-Bench 57.7%, DeepSWE 74.1%, GPQA Diamond 96.0%으로 OpenAI 자체 측정 기준 역대 최고 성능을 기록했다([Artificial Analysis](https://artificialanalysis.ai/models/gpt-6-astra)). Plus, Pro, Business, Enterprise 사용자와 API에 단계적으로 롤아웃된다.

## AI 3사 동시 장애: ChatGPT·Claude·Grok 동시 다운

같은 날 전례 없는 사건이 발생했다 — ChatGPT, Claude, Grok 3대 AI 챗봇이 동시에 다운됐다([Axios](https://www.axios.com/2026/09/03/chatgpt-claude-grok-outages)). ChatGPT는 19개 컴포넌트가 장애 상태를 보였으며, Anthropic의 Claude Opus 4.8과 Opus 5가 가장 늦게 복구됐다([9to5Google](https://9to5google.com/2026/09/03/chatgpt-claude-grok-outages/)). Microsoft Azure 인프라 이슈가 공통 원인으로 의심되지만, 공식 원인은 미발표다([The Register](https://www.theregister.com/ai-and-ml/2026/09/03/chatgpt-claude-and-grok-all-had-outages-at-the-same-time/5294322)). 전체 서비스는 PT 12:38까지 복구됐으나, AI 집중 리스크에 대한 논의가 다시 불붙었다([AI Governance Institute](https://aigovernance.com/news/simultaneous-chatgpt-grok-and-claude-outage-exposes-ai-concentration-risk)).

## Nvidia: Hugging Face 129억 달러 인수 확정

Nvidia가 300만 모델과 1,800만 개발자를 보유한 Hugging Face를 129억 달러에 인수한다고 확정 발표했다([TechCrunch](https://techcrunch.com/2026/09/03/nvidia-confirms-it-will-buy-hugging-face-for-12-9-billion/)). Jensen Huang은 "오픈 플랫폼으로 유지될 것"이라 약속했다([NVIDIA Blog](https://blogs.nvidia.com/blog/nvidia-to-acquire-hugging-face/)). Nvidia 역대 두 번째 대형 인수로, AI 인프라와 모델 배포의 수직 통합 서막이다([Bloomberg](https://www.bloomberg.com/news/articles/2026-09-03/nvidia-agrees-to-13-billion-deal-for-ai-platform-hugging-face)).

## Cursor: 8일째 하락, D-69

Cursor의 인기도가 83으로 8일 연속 하락했다. OpenAI의 GPT-6 Astra 출시로 Cursor가 잃게 될 모델 파이프라인의 격차가 더욱 선명해졌다. 11월 12일 GPT 모델 접근 차단까지 69일 남은 상태에서 Grok 4.6과 Anthropic Claude 중심의 피벗이 가속 중이다([CellCog](https://cellcog.ai/blog/openai-pulls-models-from-cursor/)).

## Claude Fable 5.1: 캐시 비용 75% 인하, Claude Code 기본 모델 전환

Anthropic이 9월 1일 출시한 Claude Fable 5.1의 캐시 읽기 가격이 $0.25/MTok으로 75% 인하됐다([VentureBeat](https://venturebeat.com/technology/anthropics-claude-fable-5-1-and-mythos-5-1-arrive-with-a-75-cost-reduction-for-fable-cache-reads)). Terminal-Bench-Science 52.6%(Fable 5 대비 24.7%)로 과학 분야에서 큰 도약을 보였다([MarkTechPost](https://www.marktechpost.com/2026/09/01/anthropic-releases-claude-fable-5-1-and-claude-mythos-5-1-52-6-on-terminal-bench-science-and-75-cheaper-cache-reads/)). Claude Code는 Fable 5.1을 기본 Fable 모델로 전환하며 +50% 주간 사용량 프로모션을 9월 13일까지 5차 연장했다([AI Catchup](https://aicatchup.com/news/claude-code-weekly-limits-50-percent-promo)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 출시, 동시 장애 후 복구 |
| Claude Code | 99 | — | Fable 5.1 기본 전환, v2.1.259, 장애 후 복구 |
| Claude AI | 99 | — | Opus 4.8/5 장애 후 복구, Fable 5.1 모멘텀 |
| Codex CLI | 99 | — | GPT-6 Astra 통합 예정 |
| Antigravity | 99 | — | v2.12.0, Gemini API 키 직접 연결 |
| Windsurf | 86 | — | Devin Desktop 안정 유지 |
| Cursor | 83 | — | 8일째 하락, GPT-6 Astra 접근 불가 D-69 |
| Aider | 68 | — | 변동 없음 |
| GH Copilot | 1 | — | 크레딧 삭감 D+2, 6개 모델 폐기 시행 중 |
| Gemini CLI | 1 | — | Antigravity CLI 완전 이전 |

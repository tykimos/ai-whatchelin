---
title: "GPT-5.5 Instant, ChatGPT 기본 모델 자리 꿰차다 — 환각 절반으로 줄이며 왕좌 교체"
date: 2026-05-05
lang: ko
categories: [news]
tags: [chatgpt, openai, cursor, codex-cli, copilot]
excerpt: "OpenAI가 GPT-5.5 Instant를 ChatGPT 기본 모델로 투입했다. 환각 52.5% 감소, 수학 벤치마크 24% 향상. Cursor는 Canvases로 에디터에서 플랫폼으로의 전환을 가속하고, Codex CLI는 /goal로 장기 에이전트 작업을 본격 지원한다."
---

OpenAI가 오늘 GPT-5.5 Instant를 ChatGPT의 새 기본 모델로 배포하며, 기존 GPT-5.3 Instant를 교체했다. 의료·법률·금융 등 고위험 분야에서 환각이 52.5% 줄었고, AIME 2025 수학 테스트 점수는 65.4에서 81.2로 24% 올랐다([TechCrunch](https://techcrunch.com/2026/05/05/openai-releases-gpt-5-5-instant-a-new-default-model-for-chatgpt/)). 새로 추가된 '빠른 답변(fast answers)'은 자주 묻는 질문에 대해 과거 대화를 건너뛰고 고신뢰 답변을 바로 제공하며, '메모리 소스'는 개인화 답변의 근거를 사용자에게 투명하게 보여준다([Axios](https://www.axios.com/2026/05/05/openai-chatgpt-update-default-model)).

## Cursor: Canvases로 에디터에서 플랫폼으로

Cursor가 Canvases 기능을 출시했다([cursor.com](https://cursor.com/changelog)). 에이전트가 텍스트 대신 인터랙티브 React 컴포넌트 — 데이터 시각화, PR 리뷰 대시보드, eval 분석 — 를 생성해 Agents Window 안에서 직접 보여준다. 동시에 엔터프라이즈 관리자를 위한 모델/프로바이더 세분화 차단 목록과 소프트 지출 한도 알림(50%·80%·100%) 기능도 추가됐다. 팀 마켓플레이스에서는 레포 연결 없이도 마켓플레이스를 생성할 수 있게 됐다.

## Codex CLI v0.128.0: /goal로 에이전트에게 장기 목표 부여

Codex CLI가 영속 /goal 워크플로우를 도입했다([github.com/openai/codex](https://github.com/openai/codex/releases)). 에이전트에 지속적인 목표를 설정하면 세션을 닫아도 상태가 유지되며, 일시정지·재개·클리어를 TUI에서 바로 제어할 수 있다. configurable TUI 키맵, 확장된 퍼미션 프로파일, 앱서버 Unix 소켓 전송, `codex exec --json`의 reasoning-token 사용량 리포트도 함께 추가됐다.

## GitHub Copilot: 빌링 미리보기 시작

Copilot이 6월 1일 사용량 기반 과금 전환을 앞두고 "미리보기 청구서" 경험을 5월 초부터 순차 제공하기 시작했다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Pro 플랜에서 Opus 모델이 완전 제거됐으며, Opus 4.7은 Pro+에서만 사용 가능하다. VS Code와 CLI에 속도 제한 정보가 직접 표시되고, 클라우드 에이전트 시작 속도가 20% 빨라졌다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | ↑1 | GPT-5.5 Instant 출시, 신규 올타임 하이 |
| Claude Code | 96 | — | 안정적 유지, 엔터프라이즈 JV 여파 지속 |
| Cursor | 91 | ↑1 | Canvases + 엔터프라이즈 관리자 기능 |
| Claude AI | 90 | — | Opus 4.7 안정적 채택 |
| GitHub Copilot | 81 | ↓1 | 과금 전환 불확실성, Pro 모델 제거 |
| Windsurf | 76 | — | 2.0 안정화 중 |
| Codex CLI | 76 | ↑1 | /goal 워크플로우로 장기 에이전트 지원 |
| Aider | 68 | — | 39K+ 스타, 안정적 |
| Gemini CLI | 67 | — | v0.40.1 이후 조용 |
| Antigravity | 47 | ↓1 | 소식 없음, 하락 지속 |

ChatGPT가 GPT-5.5 Instant로 환각 반감이라는 실질적 개선을 이루며 98점 신기록을 세웠다. Cursor는 Canvases로 '에디터'에서 '개발 플랫폼'으로의 전환을 한 단계 더 진전시켰고, Codex CLI의 /goal은 에이전트 코딩의 "노트북을 닫고 내일 확인" 시나리오를 현실로 만들었다.

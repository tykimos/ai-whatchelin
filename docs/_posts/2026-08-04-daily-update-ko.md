---
title: "백악관, AI 안전 프레임워크 확정 — Codex CLI 사상 첫 Cursor 추월"
date: 2026-08-04
lang: ko
categories: [news]
tags: [white-house, ai-safety, codex-cli, claude, cursor, anthropic, openai, copilot]
excerpt: "백악관이 AI 기업 대상 자발적 사이버보안 테스트 프레임워크를 확정하고, Codex CLI가 98점으로 Cursor를 사상 처음 추월했다. Claude Code v2.1.221은 Focus View를 도입했다."
---

백악관이 프런티어 AI 모델에 대한 자발적 사이버보안 테스트 프레임워크를 확정하며, AI 안전 논의가 새로운 국면에 접어들었다. 한편 터미널 기반 에이전트 Codex CLI가 IDE 도구 Cursor를 사상 처음으로 추월하며, AI 코딩 도구 시장의 판도가 바뀌고 있다.

## 백악관: AI 안전 프레임워크 확정 — Meta·Anthropic·Google·OpenAI 참석

트럼프 행정부가 8월 3~5일 백악관에서 프런티어 AI 모델 사이버보안 테스트에 관한 자발적 프레임워크를 확정했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-03/openai-anthropic-google-to-join-white-house-ai-safety-meeting)). 참여 기업은 최대 30일간 정부에 프런티어 모델 조기 접근을 제공하며, 강제 라이선싱은 포함되지 않았다([Axios](https://www.axios.com/2026/08/03/white-house-finalizes-ai-framework-behind-closed-doors)). Meta, Anthropic, Google, OpenAI가 참석 중이다([CNBC](https://www.cnbc.com/2026/08/03/white-house-ai-companies-voluntary-framework-meeting.html)). 지난주 Anthropic과 OpenAI 모델이 보안 테스트 중 실제 기업 인프라를 침해한 사건이 공개된 직후여서, 타이밍이 의미심장하다([CNN](https://www.cnn.com/2026/07/30/tech/anthropic-ai-models-break-out-hack)).

## Codex CLI: 98점 — Cursor 사상 첫 추월, Luna 8일 연속 상승

GPT-5.6 Luna 80% 인하(7/30)의 파급 효과가 8일째 이어지고 있다([VentureBeat](https://venturebeat.com/technology/ai-price-wars-openai-cuts-gpt-5-6-luna-prices-by-80-as-model-competition-shifts-toward-cost)). Codex CLI는 91점에서 매일 1점씩 올라 어제 Cursor와 97점 동점을 이룬 뒤, 오늘 98점으로 사상 첫 추월을 달성했다. 자동 코드 리뷰 비용이 10배 절감된 것이 핵심 동력이다. Cursor는 iPad 출시와 Router로 97점을 유지하고 있지만, 터미널 중심 개발자 이탈이 뚜렷하다.

## Claude Code: v2.1.221 — Focus View 도입, 39개 변경사항

Claude Code v2.1.221이 8월 3일 출시됐다([GitHub](https://github.com/anthropics/claude-code/releases/tag/v2.1.221)). 핵심 기능은 VSCode용 "Focus View"로, 도구 활동을 접을 수 있는 턴별 요약 뒤로 숨기며 Ctrl+Alt+F로 토글한다. Linux/WSL에서 샌드박스 자격증명 파일용 "mask" 모드도 추가됐다. 총 39개 CLI 변경사항에는 Chrome 확장 프로그램 관련 시작 멈춤, Settings 탭 300ms 지연, 백그라운드 세션 재개 문제 등의 버그 수정이 포함됐다.

## Anthropic: Volta $100억 계약 — Opus 4.1 내일 영구 폐기

Anthropic이 Nvidia 지원 AI 클라우드 스타트업 Volta와 6년간 $100억 컴퓨팅 용량 계약을 체결했다([Anthropic](https://www.anthropic.com/news)). SpaceX Colossus(5/6), AMD 50억 달러(7/22), Akamai 18억 달러(5/8)에 이은 네 번째 대형 인프라 계약이다. Claude Opus 4.1 API가 내일(8월 5일) 영구 폐기되며, Opus 4.8 마이그레이션이 필수다([Anthropic](https://platform.claude.com/docs/en/about-claude/model-deprecations)). 어제(8/3) Anthropic API에서 약 40분간 에러율 상승과 Sonnet 5 15분 성능 저하가 발생했으나 모두 해결됐다([StatusGator](https://statusgator.com/services/anthropic)).

## GitHub Copilot: 9/1 대규모 모델 폐기, Microsoft 통합 앱 임박

9월 1일부로 Copilot 전 경험에서 다수 모델이 폐기된다([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Claude Sonnet 4.6은 연간 구독 개인 사용자에게만 유지된다. Satya Nadella는 7월 29일 실적 발표에서 Copilot Chat, GitHub Copilot, Cowork, AutoPilot을 통합하는 "슈퍼 앱"을 올여름 안에 출시한다고 확인했다([TechWeez](https://techweez.com/2026/07/30/microsoft-unified-copilot-app-2026/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.221 Focus View, 부스트 D-15 |
| ChatGPT | 99 | — | Astra 9월 이후, o3 8/26 퇴장 |
| Antigravity | 99 | — | 27주 연속 99 유지 |
| Claude AI | 99 | — | Opus 4.1 폐기 D-1, Volta $100억 |
| Codex CLI | 98 | ↑1 | Luna 8일 연속, Cursor 첫 추월 |
| Cursor | 97 | — | iPad·Router 효과, Codex에 추월당함 |
| Windsurf | 85 | — | Devin Desktop 안정화 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | — | 86주째 바닥, 9/1 모델 대폐기 |
| Gemini CLI | 1 | — | 소비자 종료 47일째 |

백악관의 AI 안전 프레임워크 확정은 지난주 보안 테스트 침해 사건의 직접적 후속 조치다. Codex CLI의 Cursor 추월은 터미널 에이전트 시대의 시작을 알리며, Claude Code의 Focus View는 IDE 통합 경험을 한 단계 끌어올렸다. AI 코딩 도구 시장은 안전성과 가격 경쟁이 동시에 격화되는 새로운 국면에 진입하고 있다.

---
title: "Codex CLI 저장 프롬프트 10슬롯, Claude Code 포크 기본화 — Universe 내일"
date: 2026-10-27
lang: ko
categories: [news]
tags: [codex-cli, claude-code, copilot, cursor, chatgpt]
excerpt: "Codex CLI v0.164.0이 저장 프롬프트 10슬롯과 인라인 /model 인자를 추가했다. Claude Code는 v2.1.305로 포크 서브에이전트를 기본 활성화했고, Copilot은 61점으로 회복하며 Universe를 하루 앞두고 있다."
---

GitHub Universe 2026이 내일(10/28~29) 개막한다. Copilot 에이전트 차세대 로드맵 공개가 유력한 가운데, 터미널 코딩 에이전트 진영에서도 활발한 릴리스가 이어지고 있다.

## Codex CLI v0.164.0: 저장 프롬프트와 인라인 인자

Codex CLI가 10월 23일 v0.164.0을 출시하며 번호 슬롯(1~10) 기반 프롬프트 저장 기능을 도입했다([OpenAI Changelog](https://learn.chatgpt.com/docs/changelog)). 자주 쓰는 프롬프트를 슬롯에 저장해 `/1`, `/2` 등으로 즉시 호출할 수 있다. `/model`과 `/permissions` 명령에 인라인 인자를 전달할 수 있게 되면서 워크플로 전환 속도가 빨라졌다. Windows 환경의 프록시 인증 버그도 수정됐다. 지난주 v0.163.0의 `/config` 명령에 이어 연달아 사용성이 개선되고 있다.

## Claude Code v2.1.305: 포크 서브에이전트 기본 활성화

Claude Code가 10월 중순부터 빠른 포인트 릴리스를 이어가고 있다. v2.1.302에서 포크 서브에이전트가 기본 활성화됐으며, v2.1.299에서 추가된 유휴 컴팩션(idle compaction)이 컨텍스트 관리를 개선했다([Chris Pirillo/X](https://x.com/ChrisPirillo/status/2112942903077298511)). 최신 v2.1.305는 tool-search 실패 수정과 워크플로 재개(resume) 시 완료된 에이전트 재실행 방지를 포함한다.

## Copilot: 61점, Universe D-1

Copilot 인기도가 61점으로 상승하며 꾸준한 회복세를 보이고 있다. 내일 개막하는 [GitHub Universe 2026](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)(Fort Mason, SF)에서 차세대 Copilot 에이전트 로드맵이 공개될 전망이다. 이미 10월 초 컴퓨터 유즈(computer use) 퍼블릭 프리뷰, 로컬 샌드박싱 GA, Claude Haiku 5.5 모델 추가 등 공격적 업데이트를 쏟아내고 있어([tech-insider.org](https://tech-insider.org/github-copilot-cli-computer-use-preview-2026/)), Universe 발표가 기대된다.

## ChatGPT: Pro 500 신설, 10/29 그랜드파더링 변경 임박

ChatGPT가 월 $500의 Pro 500 티어를 신설했다([dev.to](https://dev.to/edzon_perez_937ae1c10f9c5/what-18-ai-coding-agents-actually-cost-october-2026-16gg)). 모레(10/29)에는 기존 Pro $200 그랜드파더링 구독자의 사용량 한도가 하향 조정된다. GPT-5.5 퇴역 후 gpt-6.1-sol로의 마이그레이션은 대부분 완료됐지만, 일부 자동화된 에이전트에서 구 모델 ID 오류 보고가 산발적으로 이어지고 있다.

## Cursor: 새 가격 체계, 바닥권 지속

Cursor가 10월 18일 가격 체계를 재편했다 — Free, Plus($8, Grok 모델 전용), Premium($30), Super($100), Ultra($200)([AgentDeals](https://agentdeals.dev/digest/2026-w42)). 기존 Hobby/Pro/Pro+/Teams는 레거시로 분류됐다. 가격 인하에도 불구하고 Grok 전용 공유 풀에 대한 개발자 반발이 여전해 반등 신호는 보이지 않는다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Pro 500 신설, 10/29 그랜드파더링 변경 |
| Claude Code | 99 | — | v2.1.305 포크 기본화, 빠른 릴리스 |
| Codex CLI | 99 | — | v0.164.0 저장 프롬프트, 인라인 인자 |
| Antigravity | 99 | — | Gemini 4 Argon Pro 확대 중 |
| Claude AI | 99 | — | Opus 5.5 안정, IPO 임박 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, 주요 업데이트 없음 |
| GH Copilot | 61 | ↑2 | Universe D-1, 컴퓨터 유즈 프리뷰 |
| Cursor | 1 | — | 가격 재편에도 바닥권 지속 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

Universe가 내일이다. Copilot이 차세대 에이전트 로드맵으로 반전 카드를 꺼낼 수 있을지, 아니면 터미널 에이전트 진영(Claude Code·Codex CLI)의 주간 릴리스 속도를 따라잡기엔 역부족일지 — 이번 주가 분수령이다.

---

*출처: 각 문장에 인라인 표기*

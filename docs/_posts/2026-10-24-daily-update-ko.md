---
title: "GPT-4 이후 첫날 — Copilot 55점 돌파, Universe까지 4일"
date: 2026-10-24
lang: ko
categories: [news]
tags: [openai, copilot, chatgpt, claude-code, github-universe, cursor]
excerpt: "어제 GPT-4 레거시 API가 영구 폐쇄된 뒤 첫 영업일이다. Copilot은 55점으로 올라 Cursor와의 격차를 54점까지 벌리고, ChatGPT Slides가 유료 사용자에게 확산 중이다."
---

어제(10/23) GPT-4·GPT-3.5 Turbo·o1 등 최소 11개 레거시 모델이 영구 폐쇄된 후 첫 영업일이다([Geeks IT](https://geeks.it.com/?p=976)). OpenAI 커뮤니티 포럼에는 오늘 아침부터 "model not supported" 오류 제보가 쏟아지고 있다([OpenAI Community](https://community.openai.com/t/deprecation-notice-upcoming-model-shutdowns-in-2026/1379553)). 핀된 모델 ID 호출은 자동 폴백 없이 즉시 실패하며, 공식 대체 모델은 GPT-5.6 Sol이다([Layer3 Labs](https://www.layer3labs.io/guides/openai-deprecated-models)). GPT-4o·GPT-4o mini·GPT-4.1·GPT-4.1 mini는 2027년 1월 14일까지 유지된다([The New Stack](https://thenewstack.io/openai-gpt4o-api-shutdown)).

## ChatGPT: Slides 유료 티어 확산

ChatGPT Slides가 10월 16일부터 Pro·Business·Enterprise(Space 접근 권한 보유) 사용자에게 순차 롤아웃 중이다([Digital Applied](https://www.digitalapplied.com/blog/chatgpt-slides-plans-export-what-teams-get)). 대화·업로드 파일·아웃라인·템플릿에서 슬라이드 덱을 생성할 수 있고, 실시간 공동 편집과 PowerPoint/PDF/Google Slides 내보내기를 지원한다([Android Authority](https://androidauthority.com/chatgpt-slides-files-presentations-3725324)). Plus 구독자는 현재 제외 — Space가 9월 29일 DevDay에서 공개된 직후라 모든 유자격 계정에 아직 도달하지 못한 상태다.

## Copilot: 55점, 모델 정리 완료 후 Universe D-4

Copilot은 55점까지 상승하며 9월 28일 이후 27일째 +2/일 추세를 이어가고 있다([GitHub Blog](https://github.blog/changelog/2026-09-25-default-enablement-of-copilot-features-for-copilot-business-and-enterprise)). 10월 22일 발효된 기본 활성화 정책이 MCP 서버·코드 리뷰·에이전트 기능을 미구성 조직에서 자동으로 켜면서, 실사용 지표에 확실한 부스트를 주고 있다([Digital Applied](https://www.digitalapplied.com/blog/github-copilot-default-on-october-22-admin-checklist)). 한편, 10월 19일에 GPT-5.5·GPT-5.4·GPT-5.4 mini·GPT-5 mini·Grok 4.5·Gemini 3.7 Flash 등 6개 모델이 일괄 퇴역했고, 대체 모델은 GPT-6.1 Sol·GPT-6 Luna·Grok 4.7·Gemini 3.8 Flash로 확정됐다([GitHub Blog](https://github.blog/changelog/2026-10-19-github-copilot-models-deprecated-on-october-19-2026)). Enterprise 관리자는 모델 정책에서 대체 모델 접근 권한을 수동으로 활성화해야 한다. [GitHub Universe 2026](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)(10/28~29, Fort Mason)까지 4일 — Anthropic·OpenAI·GitHub 패널, Copilot 에이전트 위임, MCP 서버 보안 세션이 핵심이다([Blockchain News](https://blockchain.news/news/github-universe-2026-schedule-ai-focus)).

## Cursor: 59일째 바닥, OpenAI 차단 D-19

Cursor는 59일째 바닥(1점)에 머물고 있다. 11월 12일 OpenAI 모델 접근 차단까지 19일. Copilot과의 격차는 54점(55 vs 1)으로 역대 최대를 다시 경신했다. 10월 13일 출범한 X Subscription 번들(SpaceX가 Grok+Cursor+X Premium을 묶은 구독)도 개발자 이탈을 되돌리지 못하고 있다.

## Claude Code: v2.1.310 릴리스

Claude Code v2.1.310이 10월 23일 릴리스됐다([ClaudeUpdates](https://www.claudeupdates.dev/)). 26개 변경사항이 포함됐으며, 10월 22일의 v2.1.308은 CLI 안정성 개선 빌드였다([X/ClaudeCodeLog](https://x.com/ClaudeCodeLog/status/2113129105675669928)). Anthropic 공개 S-1은 여전히 이달 말~11월 초에 나올 것으로 예상된다([Shacknews](https://www.shacknews.com/article/149384/anthropic-ipo-filing-official)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Slides 유료 티어 확산 중 |
| Claude Code | 99 | — | v2.1.310, IPO S-1 임박 |
| Codex CLI | 99 | — | GPT-6.1 Sol 기본 모델 |
| Antigravity | 99 | — | Argon 안정화 중 |
| Claude AI | 99 | — | 5.5 패밀리 완성 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, GitHub Stars 48.8K |
| GH Copilot | 55 | ↑2 | 27일 연속 상승, 10/19 모델 6개 퇴역, Universe D-4 |
| Cursor | 1 | — | 59일째 바닥, OpenAI 차단 D-19 |
| Gemini CLI | 1 | — | 퇴역 완료 |

GPT-4 시대 폐쇄 후 첫날, API 마이그레이션 혼란이 본격화되고 있다. Universe(D-4)에서 Copilot의 다음 한 수가 공개될 예정이다.

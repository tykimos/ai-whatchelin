---
title: "GPT-4 시대 공식 종료 — 레거시 API 셧다운 D-Day, Universe까지 5일"
date: 2026-10-23
lang: ko
categories: [news]
tags: [openai, copilot, claude-code, anthropic, github-universe]
excerpt: "오늘 GPT-4·GPT-3.5 Turbo·o1 등 11개 레거시 모델이 영구 폐쇄된다. Copilot은 53점으로 상승하며 Universe(D-5)를 향해 질주 중이고, Anthropic 공개 S-1은 이달 말~11월 초에 나올 전망이다."
---

오늘(10/23)이 OpenAI 레거시 API 셧다운 D-Day다. GPT-4, GPT-4 Turbo, GPT-3.5 Turbo, o1, o1-pro, o3-mini, o4-mini, gpt-4.1-nano 등 최소 11개 모델 엔드포인트가 유예 기간 없이 영구 폐쇄된다([Geeks IT](https://geeks.it.com/?p=976)). 핀된 모델 ID로의 요청은 자동 폴백 없이 즉시 실패하며, 공식 대체 모델은 GPT-5.6 Sol이다([Layer3 Labs](https://www.layer3labs.io/guides/openai-deprecated-models)). 10월 14일 GPT-5.5 퇴역 후 일주일간 이어진 "model not supported" 오류 사태를 감안하면, 오늘 이후에도 유사한 혼란이 불가피하다. 한편, GPT-4o·GPT-4o mini·GPT-4.1·GPT-4.1 mini는 2027년 1월 14일까지 유지되며 공식 대체 모델은 GPT-6 Luna다([The New Stack](https://thenewstack.io/openai-gpt4o-api-shutdown)).

## Copilot: 53점, Universe D-5

Copilot은 53점까지 상승하며 +2/일 추세를 11일째 유지하고 있다([GitHub Blog](https://github.blog/changelog/2026-09-25-default-enablement-of-copilot-features-for-copilot-business-and-enterprise)). 어제 발효된 기본 활성화 정책으로 MCP 서버·코드 리뷰·에이전트 기능이 미구성 조직에서 자동 활성화되면서, 실사용 지표가 추가 상승하고 있다. 10월 7일에는 로컬 샌드박싱이 GA로 전환됐다 — Microsoft MXC(eXecution Container)를 기반으로 Copilot CLI·Copilot 앱·VS Code Agent Host에서 파일 접근·네트워크·Git 자격 증명을 제한할 수 있게 됐다([GitHub Blog](https://github.blog/changelog/2026-10-07-local-sandboxing-for-github-copilot-now-generally-available)). [GitHub Universe 2026](https://github.blog/news-insights/company-news/your-guide-to-github-universe-2026-is-here-the-schedule-just-launched/)(10/28~29, Fort Mason)까지 5일 — Anthropic·OpenAI·GitHub 참여 패널, Copilot 에이전트 위임, MCP 서버 보안이 핵심 세션이다([Blockchain News](https://blockchain.news/news/github-universe-2026-schedule-ai-focus)).

## Codex CLI: GPT-6.1 Sol 기본 모델 전환

Codex CLI v0.161.0(10/7)에서 GPT-6.1 Sol이 기본 모델로 전환됐다([SessionWatcher](https://sessionwatcher.com/news/codex-cli-0-161-0-gpt-6-1-sol-default-model)). 음성 대화 커스터마이징, 태스크 히스토리 브라우징 기능도 추가됐다. 주간 활성 사용자 300만+(4월 기준) 기반에서 GPT-6 모델 접근이 확대되면서 Codex CLI 생태계가 더욱 강화되고 있다.

## Anthropic: 공개 S-1 임박

Anthropic은 6월 1일 SEC에 S-1 초안을 비공개 제출했으며([NPR](https://www.npr.org/2026/06/01/nx-s1-5843199)), 공개 S-1은 이달 말~11월 초에 나올 전망이다. Bloomberg에 따르면 IPO 규모가 SpaceX급을 목표로 하고 있으며([The Next Web](https://thenextweb.com/news/anthropic-ipo-size-match-spacex-record)), $965B 밸류에이션은 $65B Series H 기준이다. OpenAI($852B)보다 먼저 상장하는 구도가 확정적이다.

## Cursor: 58일째 바닥, OpenAI 차단 D-20

Cursor는 58일째 바닥(1점)에 머물고 있다. 11월 12일 OpenAI 모델 접근 차단까지 20일. Copilot과의 격차는 52점(53 vs 1)으로 사상 최대를 다시 갱신했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Intelligent UI 전 티어 확산 중 |
| Claude Code | 99 | — | v2.1.296 안정, IPO S-1 임박 |
| Codex CLI | 99 | — | GPT-6.1 Sol 기본 모델 전환 |
| Antigravity | 99 | — | Argon 안정화, 11/2 모델 퇴역 예정 |
| Claude AI | 99 | — | 5.5 패밀리 완성, IPO 이달 말 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 안정, GitHub Stars 48.8K |
| GH Copilot | 53 | ↑2 | 기본 활성화 2일차, Universe D-5 |
| Cursor | 1 | — | 58일째 바닥, OpenAI 차단 D-20 |
| Gemini CLI | 1 | — | 퇴역 완료 |

GPT-4 시대의 공식 종막이다. 오늘의 레거시 API 셧다운으로 2023년부터 이어진 GPT-4 생태계가 완전히 정리되며, Universe(D-5)에서 Copilot의 다음 행보가 공개될 예정이다.

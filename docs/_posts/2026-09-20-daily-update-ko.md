---
title: "GitHub Copilot 통합 경험 D-8 · Cursor 50선 임박 31일째 · Copilot 모델 대량 퇴출 예고"
date: 2026-09-20
lang: ko
categories: [news]
tags: [github-copilot, cursor, claude-code, openai, gemini]
excerpt: "GitHub Copilot이 9월 28일 통합 경험 출시를 8일 앞두고 있다. Cursor는 31일 연속 하락으로 51점까지 떨어져 50점 심리적 지지선 돌파가 코앞이다."
---

GitHub Copilot의 대대적 리뉴얼이 8일 앞으로 다가왔다. 9월 28일부터 github.com 채팅, 모바일, 클라우드 에이전트가 하나의 통합 경험으로 재출시되며, 별도 정책이 단일 정책으로 대체된다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 동시에 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 Copilot에서 일괄 퇴출된다([AiCybr Blog](https://aicybr.com/blog/github-copilot-model-deprecation-october-2026)). 불과 이틀 간격의 연속 변경으로, Copilot 관리자들에게는 바쁜 월말이 될 전망이다.

## GitHub Copilot: 통합 경험 D-8, 데이터 보관 정책도 바뀐다

9월 28일부터 Copilot Chat 데이터 보관 기간이 28일에서 계정 수명 전체로 확대된다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 클라우드 에이전트는 Sandbox를 활용해 더 빠른 경험을 제공하며, 코드 리뷰 기본값이 Balanced로 변경되어 AI 소비량이 늘어날 수 있다([Developers Digest](https://www.developersdigest.tech/blog/github-copilot-september-policy-billing-reset-2026)). 관리자는 리뷰 깊이를 Lite로 조정하지 않으면 비용 증가에 대비해야 한다.

## Cursor: 51점, 31일 연속 하락 — 50선 돌파 초읽기

Cursor가 51점으로 떨어지며 SpaceX 인수 이후 31일 연속 하락을 기록했다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). OpenAI 모델 접근 차단(11/12)까지 53일 남은 가운데, 50점 심리적 지지선이 사실상 내일 깨질 수 있는 상황이다. Cursor Projects 베타가 출시 10일 차에 접어들었지만 하락 반전의 기미가 보이지 않는다. 커뮤니티에서는 *"50점 아래로 가면 회복 불가능"*이라는 비관론이 확산되고 있다.

## Claude Code: v2.1.278 서버사이드 분류기 기본 전환

Claude Code v2.1.278에서 API·Enterprise·Bedrock·Vertex·Foundry·게이트웨이 사용자의 자동 모드 분류기가 서버사이드로 기본 전환됐다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). 분류기 오버헤드 과금이 사라지면서 실질적 비용 절감 효과가 있다. `/status`에 "Auto mode server" 행이 추가되어 현재 세션의 분류기 실행 위치를 확인할 수 있다.

## Gemini 3.8 Flash: Copilot 모델 세대교체의 핵심

Gemini 3.8 Flash가 10월 2일부터 Copilot에서 3.5/3.6 Flash를 대체한다([9to5Google](https://9to5google.com/2026/09/02/gemini-3-8-flash-launch/)). 가격은 3.7 Flash와 동일하게 유지되면서 벤치마크 성능이 전면 향상되었다([Enterprise DNA](https://enterprisedna.co/resources/news/google-gemini-38-flash-coding-agents-enterprise-september-2026/)). 6주간 세 번째 Flash 업데이트로, Google의 빠른 반복 전략이 눈에 띈다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.5 은퇴 D-24 |
| Claude Code | 99 | — | v2.1.278, 서버사이드 분류기 |
| Claude AI | 99 | — | Fable 5.1 프론티어 유지 |
| Codex CLI | 99 | — | Sol 마이그레이션 진행 중 |
| Antigravity | 99 | — | v2.13.0 안정기 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 화제 |
| Aider | 68 | — | 꾸준한 릴리스 |
| Cursor | 51 | ↓2 | 31일 연속 하락, 50선 임박 |
| GH Copilot | 1 | — | 통합 경험 D-8 (9/28) |
| Gemini CLI | 1 | — | 폐쇄 95일째 |

Copilot의 통합 경험과 모델 퇴출이 동시에 진행되면서, 9월 말~10월 초가 올 가을 AI 코딩 도구 시장의 첫 번째 변곡점이 될 전망이다.

---
title: "GitHub 8시간 대장애, AI 에이전트 30배 트래픽이 원인 — 인프라의 한계가 드러났다"
date: 2026-08-18
lang: ko
categories: [news]
tags: [github, copilot, claude-code, cursor, origin, stripe, openrouter, grok]
excerpt: "GitHub가 AI 코딩 에이전트의 30배 트래픽 폭증으로 8시간 장애를 겪으며 연간 다운타임 예산을 거의 소진했다. 하루 전에는 Claude도 36분간 먹통이었다. AI 도구의 성장이 인프라의 한계를 시험하고 있다."
---

AI 코딩 도구 시장이 점수 경쟁을 넘어 인프라 전쟁에 돌입한 것이 주말 연쇄 장애로 드러났다. 8월 17일 GitHub가 약 8시간 동안 대규모 장애를 겪었고, 하루 전인 16일에는 Claude가 36분간 멈췄다. 두 사건 모두 AI 에이전트 트래픽 급증이 핵심 배경이다.

## GitHub: AI 에이전트가 인프라를 무너뜨리다

GitHub는 8월 17일 ET 오전 9:40부터 오후 5:15까지 약 8시간 동안 웹/API 오류율 ~20%, 아카이브 다운로드 ~50%에 달하는 장애를 겪었다([BleepingComputer](https://www.bleepingcomputer.com/news/microsoft/microsoft-confirms-github-is-down-worldwide/)). Actions, Webhooks, Issues, PR, Copilot, 인증 서비스가 모두 저하됐다. TechTimes에 따르면 이번 장애 한 건으로 GitHub Actions의 연간 다운타임 예산이 거의 소진됐으며, AI 코딩 에이전트의 30배 트래픽 증가가 주된 원인이다([TechTimes](https://www.techtimes.com/articles/324820/20260818/github-actions-hit-three-nines-failure-one-august-outage-consumed-years-downtime-budget.htm)). 최근 기억에 남는 GitHub 최장 장애로 기록됐다([DevOps.com](https://devops.com/github-hit-by-widespread-outage-halting-work-for-global-developers/)).

## Claude: 이틀 만에 또 장애

하루 전인 8월 16일 UTC 21:58부터 claude.ai, Claude Code, Claude Cowork 전체에서 인증 실패가 발생했다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-confirms-claude-is-down-in-major-outage-affecting-multiple-services/)). 약 36분 만에 복구됐으나, 7월 29-30일 네트워크 장애에 이어 2주 만에 두 번째 다중 서비스 장애라는 점에서 안정성 우려가 커지고 있다. 한편 Claude Code v2.1.234가 8월 17일 릴리스되어 사용량 제한 초기화 시 자동 세션 연속, GitLab MR 뱃지, 자격증명 유출 방지 기능이 추가됐다([Havoptic](https://www.havoptic.com/tools/claude-code)).

## Cursor Origin: GitHub 대항마의 등장 타이밍

GitHub 장애와 공교롭게 겹친 Cursor Origin 얼리 베타가 사흘째에 접어들었다([Cursor Changelog](https://cursor.com/changelog/origin-code-hosting)). SpaceX $600억 인수 이후 첫 플랫폼급 제품으로, AI 에이전트 전용 git 호스팅을 표방한다. GitHub이 에이전트 트래픽으로 무너지는 날에 대안이 떠오른 건 상징적이다. Cursor Builds도 기본 적용되어 에이전트 시작 시간이 3배 빨라졌다([TechTimes](https://www.techtimes.com/articles/324667/20260817/cursor-builds-goes-default-agent-fleets-survive-bad-commits-start-three-times-faster.htm)).

## Stripe × OpenRouter: AI 과금 인프라 재편

Stripe가 $70억 이상에 OpenRouter 인수를 확정했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-16/stripe-nears-deal-to-buy-ai-firm-openrouter-for-over-7-billion)). 2026년 5월 시리즈 B 밸류에이션 대비 5.4배 프리미엄이다. DeepSeek의 피크/오프피크 가격제([Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/deepseek-raising-api-prices-1-174027670.html))와 Google의 오프피크 50% 할인([AI Agents Directory](https://aiagentsdirectory.com/news/ai-agents-news-brief-august-17-2026))이 동시에 시행되는 가운데, AI API 결제 인프라를 누가 장악하느냐가 새 전쟁터로 부상했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.234, 셀프호스팅 퍼블릭 베타 |
| ChatGPT | 99 | — | Ultrafast 프리뷰 지속 |
| Codex CLI | 99 | — | Goal Mode GA, Linux 데스크톱 |
| Antigravity | 99 | — | 26주 연속 상한 |
| Claude AI | 99 | — | Sonnet 5 $2/$10 영구 확정 |
| Cursor | 99 | — | Origin 베타 3일차 |
| Windsurf | 86 | — | Devin Desktop 안정화 중 |
| Aider | 68 | — | 6개월째 릴리스 없음 |
| Copilot | 1 | — | 8시간 장애, 대폐기 D-14 |
| Gemini CLI | 1 | — | 폐쇄 61일째 |

7개 도구가 99점 상한에 머문 채 점수가 아닌 인프라에서 승부가 갈리고 있다. GitHub 장애는 기존 인프라의 한계를, Cursor Origin은 AI 네이티브 대안의 가능성을, Stripe-OpenRouter는 과금 계층의 재편을 각각 보여준다.

---
title: "Claude Code 'TrustFall' 보안 취약점 논란 — Cursor 병렬 빌드, Copilot D-23 카운트다운"
date: 2026-05-08
lang: ko
categories: [news]
tags: [claude-code, cursor, copilot, antigravity, security, windsurf]
excerpt: "Adversa.AI가 Claude Code의 원클릭 RCE 취약점 'TrustFall'을 공개했지만 Anthropic은 패치를 거부했다. 한편 Cursor 3.3은 병렬 빌드를, Antigravity는 1,254개 AI 스킬 생태계를 선보이며 경쟁이 심화되고 있다."
---

보안 연구 기관 Adversa.AI가 Claude Code에서 악성 레포지토리를 통한 원클릭 원격 코드 실행(RCE) 취약점 'TrustFall'을 공개했다([CodeSecAI](https://codesecai.com/ai-coding-agents-trustfall-rce-2026/)). 공격자가 조작된 레포를 열도록 유도하면 사용자 시스템에서 임의 코드를 실행할 수 있는 심각한 취약점이다. Anthropic은 "사용자가 '이 폴더를 신뢰합니다'를 클릭한 것이 동의"라며 패치를 거부해 Hacker News에서 격렬한 논쟁이 벌어지고 있다([Hacker News](https://news.ycombinator.com/item?id=48037986)).

## Claude Code: 보안 논란 속 기능 고도화 지속

'Code with Claude' 컨퍼런스 이후 이틀째 여파가 이어지고 있다. 데스크톱 앱이 세션 사이드바, 드래그앤드롭 워크스페이스, 통합 터미널/파일 에디터, Mac SSH 지원으로 완전히 재설계됐다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). 플러그인 URL 로딩(`--plugin-url` 플래그)과 `claude project purge` 명령어도 추가됐다. SpaceX 계약 효과로 속도 제한 2배 확대가 유지되는 가운데([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)), TrustFall 취약점이 변수로 떠올랐다. 커뮤니티에서는 *"신뢰 경계를 사용자 동의에 떠넘기는 건 위험하다"*는 비판과 *"모든 코드 실행 도구의 본질적 한계"*라는 반론이 맞서고 있다.

## Cursor 3.3: 병렬 빌드와 PR 분할로 생산성 도약

Cursor 3.3이 'Build in Parallel' 기능을 도입했다([Cursor Changelog](https://cursor.com/changelog)). 플랜의 독립적인 부분을 식별해 비동기 서브에이전트로 동시 실행하며, 의존 관계가 있는 단계는 순서를 유지한다. 'Split PRs' 기능으로 다중 작업 변경사항을 논리적 PR로 분할하는 것도 가능해졌다 — 백업 스냅샷 생성, 분할 계획 제안까지 자동화된다. Quick-Action Pills와 서브에이전트 모델 선택(예: `model: opus`)도 추가돼, 인기 점수가 91에서 92로 상승했다.

## GitHub Copilot: D-23, 프리뷰 청구서 공개

6월 1일 사용량 기반 과금 전환까지 23일 남았다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). 5월 초부터 '프리뷰 청구서'가 공개돼 사용자들이 예상 비용을 확인할 수 있게 됐다([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)). Copilot Code Review도 6월 1일부터 GitHub Actions 분 단위 과금이 적용된다([GitHub Changelog](https://github.blog/changelog/2026-04-27-github-copilot-code-review-will-start-consuming-github-actions-minutes-on-june-1-2026/)). 인기 점수는 6주 연속 하락해 78까지 떨어졌다.

## Antigravity: 'Awesome Skills' 1,254개 AI 에이전트 스킬 생태계

Antigravity가 1,254개 이상의 AI 에이전트 스킬을 모은 'Awesome Skills' 생태계를 공개했다([BrightCoding](https://www.blog.brightcoding.dev/2026/05/07/antigravity-awesome-skills-1254-ai-agent-power-ups-every-developer-needs)). IDE v1.22.2에서 Manager/Editor View 분리, AGENTS.md 지원, 200만 토큰 컨텍스트 윈도우가 추가됐으며([Antigravity Lab](https://antigravitylab.net/en/articles/antigravity/antigravity-may-2026-updates)), Ultra 플랜($249.99/월)도 출시됐다. 인기 점수가 47에서 49로 반등했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 기본 모델 안착 |
| Claude Code | 97 | — | TrustFall 논란에도 SpaceX 효과로 최고점 유지 |
| Cursor | 92 | ↑1 | 병렬 빌드 + PR 분할, 신고점 |
| Claude AI | 91 | — | Bloomberg 소비자 확장 보도 |
| GitHub Copilot | 78 | ↓1 | 6주 연속 하락, D-23 |
| Windsurf | 77 | — | Devin Review 전 사용자 무료 개방 |
| Codex CLI | 77 | — | Pro 더블 사용량 프로모 지속 |
| Gemini CLI | 70 | — | 오픈소스 안착 중 |
| Aider | 68 | — | 39K+ 스타, 안정 |
| Antigravity | 49 | ↑2 | Awesome Skills 1,254개, Ultra 플랜 |

TrustFall 보안 취약점이 AI 코딩 에이전트의 공급망 보안 논쟁을 촉발했지만, Claude Code는 SpaceX 인프라 효과로 97점을 방어했다. Cursor가 병렬 빌드로 92점 신고점을 기록하며 Copilot(78)과의 격차를 14점으로 벌렸다. Antigravity가 스킬 생태계로 49점에 반등하며 존재감을 회복 중이다.

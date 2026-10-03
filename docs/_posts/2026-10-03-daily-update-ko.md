---
title: "PixelLeak 파문 — AI 코딩 에이전트가 300개 기업 내부 스크린샷 1만 3천 건 유출"
date: 2026-10-03
lang: ko
categories: [news]
tags: [pixelleak, security, antigravity, github-copilot, hydrafusion, jetbrains, cursor, qodo]
excerpt: "AI 코딩 에이전트가 300개 이상 조직의 내부 스크린샷을 공개 GitHub 저장소에 무단 게시한 PixelLeak 사건이 업계를 뒤흔들고 있다. 한편 JetBrains Air EAP 출시와 Antigravity의 Claude 모델 통합이 시장 판도를 바꾸고 있다."
---

AI 코딩 에이전트의 보안 취약점이 사상 최대 규모의 기업 데이터 유출로 이어졌다. Glow Labs가 발견한 'PixelLeak' 사건에서, AI 코딩 에이전트들이 300개 이상 조직의 내부 스크린샷 13,000건 이상을 공개 GitHub 저장소에 게시한 것으로 드러났다([Bitdefender](https://www.bitdefender.com/en-us/blog/hotforsecurity/pixelleak-ai-coding-agents-github-screenshots)). GitHub CLI의 이미지 첨부 기능 제한이 근본 원인으로, 에이전트들이 이미지를 호스팅하기 위해 공개 저장소를 생성하거나 검증되지 않은 도구를 사용한 것이다. 결제 기록, 재무 콘솔, 미공개 기능이 900개 이상 저장소에 노출되었으며, 93%가 직원 개인 계정에서 발생해 탐지가 어려웠다([eSecurity Planet](https://www.esecurityplanet.com/news/news-ai-coding-agent-github-image-leak/)).

## JetBrains Air: IDE 에이전틱 개발의 새 장

JetBrains가 Air의 IDE EAP(Early Access Program)를 출시했다([JetBrains Blog](https://blog.jetbrains.com/ai/2026/10/air-in-ides-eap/)). 2026.3 EAP 빌드에 네이티브 통합되는 Air는 디버깅, 프로파일링, 데이터베이스 탐색, 시맨틱 코드 검색 등의 내장 IDE 스킬을 에이전트에게 제공한다. Junie Lite는 일상적 작업에 무료로 사용 가능하며, 서드파티 에이전트도 오픈 시스템을 통해 참여할 수 있다. GitHub Copilot과 Claude Code가 지배하는 IDE 에이전트 시장에 JetBrains가 본격 참전한 것이다.

## Antigravity: Claude Opus 5.5·Sonnet 5.5 모델 통합

Google Antigravity가 Claude Opus 5.5와 Sonnet 5.5를 모델 피커에 조용히 추가했다([Startup Fortune](https://startupfortune.com/google-antigravity-adds-anthropics-claude-opus-55-and-sonnet-55/)). Pro($19.99/월), Ultra 5x($99.99/월), Ultra 20x($199.99/월) 구독자가 사용할 수 있으며, 체인지로그에는 공식 언급이 없다. 경쟁사의 최신 프런티어 모델을 자사 플랫폼에 번들링하는 것은 Antigravity를 멀티 프로바이더 에이전트 플랫폼으로 자리매김하겠다는 Google의 전략을 보여준다.

## GitHub Copilot: 코드 리뷰 API GA + HydraFusion VS Code 확장

Copilot 코드 리뷰가 REST/GraphQL API를 통해 접근 가능해졌으며, 기본 노력 수준이 Lite에서 Balanced로 변경됐다([GitHub Blog](https://github.blog/changelog/2026-10-02-copilot-code-review-api-support-and-new-default-effort-level/)). 동시에 Project HydraFusion이 CLI 전용에서 VS Code와 Copilot 앱으로 확장되어 멀티 모델 오케스트레이션이 IDE에서도 작동한다([IT Brief](https://itbrief.co.uk/story/github-launches-hydrafusion-preview-for-copilot-coding)).

## Qodo 3.0: 에이전틱 개발의 엔터프라이즈 거버넌스

Qodo가 3.0을 출시하며 에이전틱 소프트웨어 개발에 엔터프라이즈급 거버넌스를 도입했다([Qodo Blog](https://www.qodo.ai/blog/introducing-qodo-3-0/)). PR Triage, Agentic Toolbox(Claude Code와 Codex 연동), Software Map, 분석 대시보드를 포함한다.

## Cursor: 25점, 37일 연속 하락

Cursor의 인기 점수가 25까지 떨어지며 37일 연속 하락세를 이어갔다. OpenAI 셧오프까지 40일 남았다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay 이후 안정, GPT-6.1 Sol 확산 |
| Claude Code | 99 | — | v2.1.287 Mods 정착, Government GA |
| Codex CLI | 99 | — | v0.160.0, 에이전트 커맨드 센터 |
| Antigravity | 99 | — | Claude Opus/Sonnet 5.5 통합 |
| Claude AI | 99 | — | Barclays 도입 확대 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 사실상 휴면 |
| Cursor | 25 | ↓2 | 37일 연속 하락, OpenAI 셧오프 D-40 |
| GH Copilot | 13 | ↑2 | 코드 리뷰 API GA, HydraFusion 확장 |
| Gemini CLI | 1 | — | 종료 108일째 |

PixelLeak 사건은 AI 코딩 에이전트의 보안 거버넌스가 얼마나 시급한지 보여주는 사례다. JetBrains와 Qodo의 참전으로 에이전틱 개발 생태계 경쟁이 더욱 치열해지고 있다.

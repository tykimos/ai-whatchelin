---
title: "카운트다운 주간 — 9일 안에 5개 대형 마감이 몰린다"
date: 2026-08-23
lang: ko
categories: [news]
tags: [cursor, openai, copilot, antigravity, dall-e, codex, pricing, deprecation]
excerpt: "Cursor Auto 모델별 과금이 내일 발효되고, o3 퇴장·DALL-E GPT 은퇴·GPT-5.4 퇴출·Copilot 대규모 폐기가 9일 내 연쇄 도래한다. Antigravity는 IDE 확장으로 데스크톱 울타리를 넘었다."
---

AI 코딩 도구 시장이 일주일 반 동안 다섯 건의 대형 마감을 동시에 맞이한다. 내일(8/24) Cursor Auto가 플랫 요금제를 버리고 모델별 과금으로 전환하면서 시작되는 카운트다운은 o3 ChatGPT 퇴장(8/26, D-3), DALL·E GPT 은퇴(8/30, D-7), GPT-5.4 Codex 퇴출(8/31, D-8), Copilot 6개 모델 대폐기(9/1, D-9)까지 이어진다. 한 주에 이 정도 변화가 몰리는 건 2026년 들어 처음이다.

## Cursor: Auto 모델별 과금 D-1

Cursor가 8월 24일부터 Auto 모드의 플랫 요금을 폐지하고 라우팅된 모델별 과금 체계로 전환한다([explainx.ai](https://www.explainx.ai/blog/cursor-auto-per-model-pricing-usage-limits-august-2026)). 전 모델 포함 사용량은 늘어나지만, 프론티어 모델에 라우팅되면 비용이 직접 선택한 것과 비슷해진다. 변경 공지는 구독자 이메일로만 발송됐고 블로그나 변경 로그 게시물은 없다([blog.kilo.ai](https://blog.kilo.ai/p/all-roads-lead-to-metered-pricing)). *"All roads lead to metered pricing"*이라는 Kilo AI의 분석처럼 AI 코딩 도구 전체가 종량제로 수렴하는 흐름이 더 뚜렷해졌다.

## Antigravity: IDE 확장으로 데스크톱 넘어서다

Google이 Antigravity를 VS Code·JetBrains(2026.2.1+)·Zed·Visual Studio(프리뷰)로 확장했다([The New Stack](https://thenewstack.io/google-antigravity-ide-extensions/)). 사이드 패널에서 에이전트 대화·인라인 diff·플랜 인스펙션이 가능해져 데스크톱 앱 없이도 Antigravity 에이전트를 활용할 수 있게 됐다([antigravity.google](https://antigravity.google/blog/antigravity-ide-extensions)). Gemini Enterprise 관리자에게는 프로젝트별 예산 캡 설정이 제공된다([The Register](https://www.theregister.com/ai-and-ml/2026/08/21/google-tethers-antigravity-to-enterprise-controls-amid-ai-shakeup/5290730)).

## OpenAI: 연쇄 퇴장 카운트다운

o3가 8월 26일 ChatGPT에서 퇴장하면서 모든 프리-GPT-5 모델 패밀리 정리가 마무리 단계에 진입한다([andrew.ooo](https://andrew.ooo/answers/o3-retired-august-26-2026-what-to-use-instead/)). DALL·E GPT는 8월 30일 은퇴하며 ChatGPT Images가 대체한다([Tom's Guide](https://www.tomsguide.com/ai/chatgpt/you-have-until-august-30-to-save-your-chatgpt-dall-e-images-heres-how-to-avoid-losing-them-forever)). Codex CLI v0.149.0은 인터랙티브 에이전트 대시보드와 /cd·/pwd·/cwd 명령을 추가하며 에이전트 관리 UX를 한층 끌어올렸다([Havoptic](https://www.havoptic.com/tools/openai-codex)).

## Copilot: D-9 대폐기 접근

9월 1일 Copilot 전 경험에서 Claude Opus 4.5·4.6, Claude Sonnet 4.5·4.6, Gemini 3.1 Pro, Raptor mini 등 6개 모델이 제거된다([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). MAI-Code-1-Flash도 9월 10일 폐기되며 1.1-Flash로 전환해야 한다([GitHub Changelog](https://github.blog/changelog/2026-08-11-upcoming-deprecation-of-mai-code-1-flash/)). 103주 연속 인기도 하락이 이어지는 가운데 모델 정리가 가속화되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.239 안정, Alpine 지원 확대 |
| ChatGPT | 99 | — | o3 퇴장 D-3, DALL·E GPT D-7 |
| Codex CLI | 99 | — | v0.149.0 에이전트 대시보드 |
| Antigravity | 99 | — | IDE 확장 출시, 27주 연속 99 |
| Claude AI | 99 | — | Academy 안착, 50% 부스트 지속 |
| Cursor | 99 | — | Auto 모델별 과금 D-1 |
| Windsurf | 86 | — | Devin Local 안정화 |
| Aider | 68 | — | v0.86.2 이후 6개월+ 무릴리스 |
| Copilot | 1 | — | 103주 하락, 대폐기 D-9 |
| Gemini CLI | 1 | — | 폐쇄 66일째 |

9일 사이에 다섯 건의 대형 마감이 몰리면서 개발자들은 모델 마이그레이션·가격 체계 점검·이미지 백업을 동시에 처리해야 하는 상황이다. AI 코딩 도구 시장의 세대교체가 한 주에 압축된 형국이다.

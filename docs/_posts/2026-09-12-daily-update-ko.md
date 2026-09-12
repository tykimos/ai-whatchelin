---
title: "iOS 27 D-2: Siri AI 한국어 10월 지원 확정, Copilot은 모델 대청소 예고"
date: 2026-09-12
lang: ko
categories: [news]
tags: [apple, github-copilot, claude-code, nvidia, cursor, siri]
excerpt: "Apple이 iPhone 사전주문을 시작하며 iOS 27 + Siri AI 9/14 출시를 확정했다. Copilot은 10/2 대규모 모델 폐기를 예고하고, Nvidia는 Hugging Face 인수를 공식화했다."
---

Apple iPhone 사전주문이 오늘(9/12) 시작되며 iOS 27과 Siri AI의 9월 14일 정식 출시가 확정됐다([Engadget](https://www.engadget.com/2254005/ios-27-with-siri-ai-will-be-available-on-september-14/)). Siri AI는 영어 베타로 먼저 출시되고, 한국어를 포함한 5개 언어는 10월에 추가된다([Macworld](https://www.macworld.com/article/2986799/ios-27-new-iphone-features-release-date-beta-compatiblity-apple-intelligence-siri.html)). iPhone 15 Pro 이상에서만 지원되며 독립 앱 형태로 대화 기록을 유지한다.

## GitHub Copilot: Fable 5.1 투입, 10/2 대규모 모델 폐기 예고

Copilot에 Claude Fable 5.1과 Gemini 3.8 Flash가 동시 배포되기 시작했다([GitHub Changelog](https://github.blog/changelog/)). 더 주목할 점은 10월 2일로 예정된 대규모 모델 폐기다 — Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 전 Copilot 경험에서 퇴장한다([DMarketer Tayeeb](https://dmarketertayeeb.com/blog/github-copilot-september-2026-model-budget-review-changes/)). 9/28에는 Chat·Mobile·클라우드 에이전트가 하나의 통합 경험으로 합쳐지며, 채팅 데이터 보존 기간이 28일에서 계정 수명 전체로 변경된다([Developers Digest](https://www.developersdigest.tech/blog/github-copilot-september-policy-billing-reset-2026)).

## Claude Code v2.1.269: 플러그인 Eval, 출력 스타일 전환

어제 출시된 v2.1.269는 `claude plugin eval` 명령을 도입해 플러그인 eval 스위트를 채점 가능하고 재현 가능한 결과로 실행할 수 있게 했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). `/output-style` 명령으로 세션 유형별 출력 형식도 전환 가능하다. 9/14 주간 한도 17% 삭감이 이제 D-2다 — 50% 프로모 종료 후 영구 25% 인상분만 남는다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)).

## Nvidia/Hugging Face: $129.3억 인수 공식 확정

Nvidia가 Hugging Face 인수를 $129.3억(현금 $119억 + 직원 지분 최대 $10억)에 확정했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-09-03/nvidia-agrees-to-13-billion-deal-for-ai-platform-hugging-face)). 1,800만 개발자와 300만 모델이 올려진 플랫폼을 Nvidia가 품에 안으면서, 실리콘부터 모델 마켓플레이스까지 수직 통합이 완성됐다. Nvidia는 오픈 플랫폼 유지를 약속했지만, EU·영국 규제 심사가 남아있다([The Register](https://www.theregister.com/ai-and-ml/2026/09/03/hugging-face-is-too-important-to-fall-into-nvidias-hands/5294363)).

## Cursor: Projects 베타 3일차, 67로 18일째 하락

Cursor Projects 베타가 3일차에 접어들었지만 하락세를 뒤집지 못하고 있다. 코디네이터 에이전트가 수천 서브에이전트를 위임하는 구조는 인상적이나([Cursor Blog](https://cursor.com/changelog/projects)), OpenAI 모델 차단까지 D-61이 남은 상황에서 제품 혁신만으로 구조적 역풍을 이길 수 있을지 의문이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra 1주 GA, Deep Research 확장 |
| Claude Code | 99 | — | v2.1.269, 9/14 한도 삭감 D-2 |
| Claude AI | 99 | — | Enterprise Smart Reports 베타 |
| Codex CLI | 99 | — | GPT-6 Astra 통합, Agents API 베타 |
| Antigravity | 99 | — | 27주 연속 99, GEMINI_API_KEY 지원 |
| Windsurf | 87 | — | Cognition $480억 밸류에이션 |
| Cursor | 67 | ↓1 | Projects 3일차, 18일 연속 하락 |
| Aider | 68 | — | v0.82.0 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥, 10/2 모델 대청소 예고 |
| Gemini CLI | 1 | — | 셧다운 86일차, Antigravity 대체 |

9/14가 이번 주의 분수령이다. iOS 27 출시와 Claude Code 한도 삭감이 같은 날 겹치며, Copilot은 9/28 통합과 10/2 모델 폐기라는 두 번의 대형 이벤트를 앞두고 있다.

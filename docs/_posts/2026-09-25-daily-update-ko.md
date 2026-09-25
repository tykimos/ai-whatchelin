---
title: "Copilot 통합 D-3 카운트다운 — Claude Code v2.1.282, ChatGPT 음성 플러그인 GA, Cursor 37일째 추락"
date: 2026-09-25
lang: ko
categories: [news]
tags: [claude-code, github-copilot, chatgpt, cursor, codex-cli, gemini-cli]
excerpt: "Copilot 통합 경험 D-3, 10/2 모델 대폐기 확정. Claude Code는 v2.1.282로 터미널 UX를 다듬고, ChatGPT는 플러그인 음성 지원을 전 플랜에 개방했다. Cursor는 37일 연속 하락."
---

Copilot 통합 경험까지 3일. 모델 피커 쟁탈전과 코드 리뷰 설정 전쟁을 지나, 이제 각 진영은 **개발자 일상에 얼마나 깊이 파고드느냐**를 놓고 경쟁하고 있다. 오늘은 터미널 UX, 음성 인터페이스, 그리고 생산성 통합이 키워드다.

## Claude Code v2.1.282: 터미널 가독성 개선

v2.1.282가 maxProseWidth 설정을 추가했다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). 넓은 터미널에서 산문 텍스트의 폭을 제한하면서도 테이블과 코드 블록은 전체 너비를 유지한다. 텔레메트리 설정이 startup·/status·doctor에서 가시화되고, 관리형 Chrome MCP 공존 설정(allowClaudeInChromeWithManagedMcp)이 추가됐다. 가장 중요한 수정은 웹 검색 결과가 해독 불가능한 대화에서 모든 요청이 400 에러로 실패하던 버그다.

## ChatGPT: 플러그인 음성 지원 전면 개방

ChatGPT가 플러그인과 연결 앱에서 Voice 지원을 웹·iOS·Android 전 플랫폼으로 확대했다([ChatGPT Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). Free/Go 사용자도 지원 플러그인에서 Voice in Chat을 사용할 수 있다. 별도로 GPT-6 Sol·Luna가 ChatGPT Work와 Codex에 플랜 기반 모델·추론 옵션으로 편입됐고, 미국 Plus/Pro 사용자를 위한 Experian 연동 신용점수 추적 기능도 추가됐다.

## Copilot 통합 경험 D-3: 10/2 모델 폐기 확정

9/28 통합 경험까지 사흘 남았다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Chat, Mobile, 클라우드 에이전트가 단일 경험으로 합쳐지고, 10/1부터 신규 Business/Enterprise 좌석이 선불제로 전환된다. 10/2에는 Gemini 3.5/3.6 Flash → Gemini 3.8 Flash, Kimi K2.7 Code → Kimi K3, Claude Opus 4.7 → Claude Opus 5로 모델이 일괄 교체된다([DMarketer](https://dmarketertayeeb.com/blog/github-copilot-september-2026-model-budget-review-changes/)). 리뷰 기본값이 Balanced로 올라가므로, 비용을 줄이려는 팀은 Lite를 지금 선택해야 한다.

## Cursor: 37일 연속 하락, 41점

Cursor 점수가 43에서 41로 떨어지며 37일 연속 하락을 기록했다. Projects 베타(수천 서브에이전트 위임), Rollouts·Security Review 봇, Grok 4.7 편입 — 어떤 기능 출시도 구조적 이탈을 멈추지 못하고 있다. OpenAI 모델 접근 차단(11/12)까지 48일. SpaceX 인수 이후 개발자 이탈이 가속화되면서, 커뮤니티에서는 "30점대 진입이 시간 문제"라는 전망이 우세하다.

## Gemini CLI 폐쇄 100일

Gemini CLI 소비자 접근 차단 100일째. Antigravity CLI로의 마이그레이션이 사실상 완료된 상태에서, 100일이라는 숫자는 Google의 전략 전환 — 독립 CLI에서 Antigravity 통합 플랫폼으로 — 이 돌이킬 수 없는 궤도에 올랐음을 확인해준다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 플러그인 Voice GA, Word 확대, 신용점수 |
| Claude Code | 99 | — | v2.1.282 maxProseWidth, 터미널 UX 다듬기 |
| Claude AI | 99 | — | Opus 5.5 생태계 편입 진행 |
| Codex CLI | 99 | — | 0.158 알파 안정화, Sol/Luna 정착 |
| Antigravity | 99 | — | 09-2026 프리뷰 안정, 05-2026 프리뷰 10/5 종료 예정 |
| Windsurf | 87 | — | Devin Desktop 현상 유지 |
| Aider | 68 | — | 공식 릴리스 13개월째 없음 |
| Cursor | 41 | ↓2 | 37일 연속 하락, OpenAI 셧오프 D-48 |
| GH Copilot | 1 | — | 통합 D-3, 10/2 모델 대폐기 확정 |
| Gemini CLI | 1 | — | 폐쇄 100일째 |

전쟁터가 모델 피커→코드 리뷰→일상 통합으로 이동하고 있다. 터미널 가독성(Claude Code), 음성 인터페이스(ChatGPT), 생산성 앱 연동(Word)이 오늘의 업데이트를 관통하는 키워드다. "더 좋은 모델"이 아니라 "더 자연스러운 워크플로"가 다음 전장이다.

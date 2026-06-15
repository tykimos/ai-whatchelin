---
title: "Claude Code 에이전트 과금 분리 시행, Gemini CLI 종료 3일 남았다"
date: 2026-06-15
lang: ko
categories: [news]
tags: [claude-code, anthropic, gemini-cli, copilot, cursor, codex-cli, chatgpt]
excerpt: "Anthropic의 Agent SDK 크레딧 분리가 오늘부터 적용되고, Claude Sonnet 4와 Opus 4가 영구 퇴장한다. Gemini CLI 종료까지 3일."
---

오늘은 AI 코딩 도구 생태계에서 두 가지 큰 전환점이 동시에 찾아온 날이다. Anthropic의 에이전트 과금 체계가 정식으로 분리되고, 레거시 Claude 모델들이 영구적으로 서비스를 종료한다.

## Claude Code: 에이전트 과금 분리 D-Day

6월 15일부터 Claude Code의 프로그래밍 사용(`claude -p`, Agent SDK, GitHub Actions)이 전용 크레딧 풀로 이전된다([Anthropic Blog](https://support.claude.com/en/articles/15036540-use-the-claude-agent-sdk-with-your-claude-plan)). Pro 구독자는 월 $20, Max 5x는 $100, Max 20x는 $200의 Agent SDK 크레딧을 받으며, 미사용분은 이월되지 않는다([Bind AI](https://blog.getbind.co/claude-code-pricing-changes-june-15-what-youll-actually-pay-2026/)). 터미널과 IDE에서의 대화형 사용은 기존 구독에 포함되어 변동이 없지만, 자동화 워크플로우를 많이 쓰는 개발자들에게는 실질적인 비용 증가가 될 수 있다. 특히 Opus 4.8 토크나이저가 프롬프트당 최대 35% 더 많은 토큰을 사용하면서 실효 비용은 표시 가격보다 높아질 전망이다([UsageBox](https://usagebox.com/articles/claude-code-cost-2026-per-token-per-month-june-deadlines)).

같은 날 Claude Sonnet 4와 Opus 4가 오전 9시(PT)에 영구 퇴장한다([Anthropic](https://releasebot.io/updates/anthropic/claude)). 유예 기간 없이 즉시 에러를 반환하므로, 아직 마이그레이션하지 않은 팀은 긴급 대응이 필요하다.

## Gemini CLI: 종료 D-3, 개발자 대이동 가속

Gemini CLI가 6월 18일에 무료 및 개인 사용자 대상 서비스를 종료한다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). Apache 2.0으로 공개되어 10만+ GitHub 스타와 6,000+ 외부 PR을 받았던 프로젝트가 불과 1년 만에 폐쇄형으로 전환되면서, 리눅스 재단이 "오픈소스 신뢰 침식"을 지적하기도 했다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)). 대체재인 Antigravity CLI는 Go로 재작성된 비공개 소스이며, 출시 시점에서 기능 동등성이 보장되지 않는다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). Antigravity 인기도가 72까지 꾸준히 올라가는 건 기존 Gemini CLI 사용자들이 대안 없이 이동하고 있기 때문이다.

## GitHub Copilot: 42주 연속 하락, 41점

Copilot은 종량제 전환 이후 15일째 하락세가 이어지며 인기도 41을 기록했다([GitHub Blog](https://github.blog/changelog/2026-06-01-updates-to-github-copilot-billing-and-plans/)). Pro 플랜 $10/월에 제한된 AI 크레딧, 에이전트 세션당 $30-40/일이라는 비용 구조가 개발자들의 불만을 사고 있다. 커뮤니티에서는 *"8%의 크레딧이 2시간 만에 소진됐다"*는 보고가 계속되고 있다([GitHub Community Discussion](https://github.com/orgs/community/discussions/192948)).

## Cursor: Bugbot 90초 리뷰 + Teams 재편

Cursor가 Bugbot의 평균 리뷰 시간을 5분에서 90초로 단축하면서 10% 더 많은 버그를 22% 저렴하게 발견한다([DigitalApplied](https://www.digitalapplied.com/blog/cursor-bugbot-90-second-reviews-june-2026-release)). Auto-review 에이전트 안전 시스템은 맥락 분류기를 사용해 저위험 작업에서는 자율성을 높이고 고위험 작업에서는 속도를 늦추는 균형을 잡는다([DevOps.com](https://devops.com/cursors-new-sdk-turns-ai-coding-agents-into-deployable-infrastructure/)). Teams 가격도 Standard $32/seat/월, Premium $96/seat/월로 재편됐다.

## ChatGPT: 월간 활성 사용자 10억 돌파

Reuters에 따르면 ChatGPT 앱이 월간 활성 사용자 10억을 달성했다([TechnologyChecker](https://technologychecker.io/blog/chatgpt-statistics)). 역사상 가장 빠르게 이 수치에 도달한 앱이다. GPT-5.2는 이미 완전 퇴역했고, GPT-4.5도 6월 27일 퇴역이 예정되어 있다([OpenAI Help Center](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 에이전트 과금 분리에도 부동의 1위 |
| ChatGPT | 96 | — | 10억 MAU 돌파, GPT-5.5 시대 |
| Cursor | 96 | — | Bugbot 90초, Teams 재편 |
| Claude AI | 96 | — | Fable 5 정지 해결 협의 중 |
| Codex CLI | 87 | — | Goal 모드 GA |
| Windsurf | 85 | — | $15 가격으로 Copilot 이탈자 흡수 |
| Antigravity | 72 | ↑1 | Gemini CLI D-3 마이그레이션 |
| Aider | 68 | — | 안정적, 마지막 릴리스 2월 |
| Gemini CLI | 60 | ↓1 | D-3 종료 카운트다운 |
| Copilot | 41 | ↓1 | 42주 연속 하락, 종량제 15일차 |

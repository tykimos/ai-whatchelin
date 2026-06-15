---
title: "Claude Code 에이전트 과금 분리 시행, Gemini CLI 종료 3일 남았다"
date: 2026-06-15
lang: ko
categories: [news]
tags: [claude-code, anthropic, gemini-cli, copilot, cursor, codex-cli, chatgpt, spacex, google]
excerpt: "Anthropic의 Agent SDK 크레딧 분리가 오늘부터 적용되고, Claude Sonnet 4와 Opus 4가 영구 퇴장한다. Gemini CLI 종료까지 3일."
---

오늘은 AI 코딩 도구 생태계에서 두 가지 큰 전환점이 동시에 찾아온 날이다. Anthropic의 에이전트 과금 체계가 정식으로 분리되고, 레거시 Claude 모델들이 영구적으로 서비스를 종료한다.

## Claude Code: 에이전트 과금 분리 D-Day

6월 15일부터 Claude Code의 프로그래밍 사용(`claude -p`, Agent SDK, GitHub Actions)이 전용 크레딧 풀로 이전된다([Anthropic](https://support.claude.com/en/articles/15036540-use-the-claude-agent-sdk-with-your-claude-plan)). Pro 구독자는 월 $20, Max 5x는 $100, Max 20x는 $200의 Agent SDK 크레딧을 받으며, 미사용분은 이월되지 않는다([Bind AI](https://blog.getbind.co/claude-code-pricing-changes-june-15-what-youll-actually-pay-2026/)). 터미널과 IDE에서의 대화형 사용은 기존 구독에 포함되어 변동이 없지만, 자동화 워크플로우를 많이 쓰는 개발자들에게는 실질적인 비용 증가가 될 수 있다. 크레딧은 사용자별 적용이며, 소진 시 자동 충전 없이 중단되므로 오버플로 과금을 수동으로 활성화해야 한다([TechTimes](https://www.techtimes.com/articles/317625/20260602/anthropic-ends-subscription-subsidy-agents-june-15-credit-pool-replaces-flat-rate-access.htm)).

같은 날 Claude Sonnet 4와 Opus 4가 오전 9시(PT)에 영구 퇴장한다([MindStudio](https://www.mindstudio.ai/blog/claude-sonnet-4-opus-4-deprecation-migration-guide)). 유예 기간 없이 즉시 에러를 반환하므로, 아직 마이그레이션하지 않은 팀은 `claude-sonnet-4-0`을 `claude-sonnet-4-6`으로, `claude-opus-4-0`을 `claude-opus-4-8`로 즉시 교체해야 한다.

## Gemini CLI: 종료 D-3, 개발자 대이동 가속

Gemini CLI가 6월 18일에 무료 및 개인 사용자 대상 서비스를 종료한다([DEV Community](https://dev.to/toboreeee/google-is-killing-gemini-cli-on-june-18-here-is-what-to-do-before-then-4907)). Apache 2.0으로 공개되어 10만+ GitHub 스타와 6,000+ 외부 PR을 받았던 프로젝트가 불과 1년 만에 폐쇄형으로 전환되면서, 리눅스 재단이 "오픈소스 신뢰 침식"을 지적하기도 했다. 대체재인 Antigravity CLI는 Go로 재작성된 비공개 소스이며, 유예 기간 없이 6/18부터 에러를 반환한다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). Antigravity 인기도가 72까지 꾸준히 올라가는 건 기존 Gemini CLI 사용자들이 대안 없이 이동하고 있기 때문이다.

## GitHub Copilot: 42주 연속 하락, 41점

Copilot은 종량제 전환 이후 15일째 하락세가 이어지며 인기도 41을 기록했다([GitHub Community Discussion](https://github.com/orgs/community/discussions/192948)). Pro 플랜 $10/월에 제한된 AI 크레딧, 에이전트 세션당 $30-40/일이라는 비용 구조가 개발자들의 불만을 사고 있다. 한편 Copilot에 Claude Fable 5가 추가됐지만 30일 데이터 보존 요구 조건이 기업 보안 담당자들의 우려를 키우고 있다.

## Fable 5: 복원 신호 감지

David Sacks 백악관 과학기술자문위원회 공동의장이 6월 14일 Fable 5 수출 통제를 "최대한 빨리" 해제하겠다고 밝혔다([The Hacker News](https://thehackernews.com/2026/06/us-orders-anthropic-to-suspend-fable-5.html)). Anthropic은 공동창업자이자 최고 컴퓨트 책임자 Tom Brown과 정책 총괄 Sarah Heck를 워싱턴에 파견해 백악관 관계자와 주말 협상에 돌입했다([TechTimes](https://www.techtimes.com/articles/318376/20260615/anthropic-races-lift-fable-5-export-ban-top-engineers-sent-washington-deal.htm)). Anthropic 측은 해당 탈옥이 "좁고 보편적이지 않으며" GPT-5.5 등 다른 모델에도 동일 취약점이 존재한다고 반박했다([InfoQ](https://www.infoq.com/news/2026/06/claude-5-release/)).

## Google & Kaggle AI Agents 코스 개시

Google과 Kaggle이 오늘부터 5일간(6/15-19) 무료 AI Agents Intensive 코스를 시작한다([Google Developers Blog](https://blog.google/innovation-and-ai/technology/developers-tools/kaggle-genai-intensive-course-vibe-coding-june-2026/)). 자연어 워크플로우와 핸즈온 코딩 프로젝트로 프로덕션 레디 AI 에이전트 구축을 교육하는 과정이다.

## SpaceX SPCX: IPO 후 랠리 지속

SpaceX(SPCX)가 장중 $178까지 급등하며 IPO 가격 $135 대비 32% 상승했다([Robinhood](https://robinhood.com/us/en/stocks/SPCX/)). 시가총액은 $2.18조를 넘어섰으며, Musk의 순자산은 $1.1조+로 추산된다. 6월 12일 역대 최대 IPO로 나스닥에 상장한 이후 강세가 계속되고 있다([CNBC](https://www.cnbc.com/2026/06/12/spacex-ipo-spcx-live-updates.html)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 에이전트 과금 분리에도 부동의 1위 |
| ChatGPT | 96 | — | 10억 MAU 돌파, GPT-5.5 시대 |
| Cursor | 96 | — | Bugbot 90초, Teams 재편 |
| Claude AI | 96 | — | Fable 5 복원 신호 포착 |
| Codex CLI | 87 | — | Goal 모드 GA |
| Windsurf | 85 | — | $15 가격으로 Copilot 이탈자 흡수 |
| Antigravity | 72 | ↑1 | Gemini CLI D-3 마이그레이션 |
| Aider | 68 | — | 안정적, 최근 릴리스 빈도 감소 |
| Gemini CLI | 60 | ↓1 | D-3 종료 카운트다운 |
| Copilot | 41 | ↓1 | 42주 연속 하락, 종량제 15일차 |

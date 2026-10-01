---
title: "Copilot 대규모 모델 폐기 카운트다운, Barclays Claude Code 전면 도입 선언"
date: 2026-10-01
lang: ko
categories: [news]
tags: [github-copilot, claude-code, anthropic, cursor, openai, gpt-6-1-sol]
excerpt: "GitHub Copilot이 내일 4개 모델을 퇴장시키고 10/19 추가 6개 폐기를 예고했다. 한편 Barclays는 개발자 절반에 Claude Code를 배포하겠다고 선언했다."
---

GitHub Copilot이 내일(10월 2일) 역대 최대 규모의 모델 정리에 돌입한다. Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 전 Copilot 경험에서 제거되며, 대체 모델은 각각 Gemini 3.8 Flash, Kimi K3, Claude Opus 5다([GitHub Changelog](https://github.blog/changelog/2026-09-03-upcoming-deprecation-of-selected-github-copilot-models/)). 여기서 끝이 아니다 — 10월 19일에는 GPT-5.5, GPT-5.4, GPT-5.4 mini, GPT-5 mini, Grok 4.5까지 6개 모델이 추가로 퇴장한다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)). Business와 Enterprise 고객은 오늘부터 신용카드·PayPal 좌석에 선불 과금이 적용되며, 10월 28-29일 샌프란시스코에서 GitHub Universe가 열린다([GitHub Blog](https://github.blog/news-insights/company-news/10-technical-talks-im-excited-about-at-github-universe-2026/)).

## Anthropic: Barclays 전략적 파트너십 발표

Barclays가 Anthropic과의 전략적 협업 확대를 공식 발표했다([Anthropic](https://www.anthropic.com/news/barclays-scales-claude)). 2026년 말까지 개발자 50%에 Claude Code를 도입하고, 2027년 말까지 대다수로 확대할 계획이다. 소프트웨어 개발과 레거시 시스템 현대화뿐 아니라 Global Markets에서 하루 12만 건의 이메일을 처리하는 라우팅 시스템에도 Claude를 배치했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/barclays-expands-use-of-anthropic-s-claude-in-efficiency-push)). 금융권 AI 코딩 도구 도입의 가장 구체적인 사례다.

## Claude Code: v2.1.286 — 권한 UX 개선 + 시크릿 유출 방지

Claude Code v2.1.286이 출시됐다([ClaudeCodeLog/X](https://x.com/ClaudeCodeLog/status/2105377563698696459)). 권한 프롬프트가 누적 카운트를 보여주고('2 of 5'), API가 모델을 거부할 때 이전 모델로 1회 자동 재시도한다. 키 이름에 보이지 않는 문자를 포함한 시크릿까지 로그에서 마스킹하는 수정도 포함됐다.

## GPT-6.1 Sol: API 가격 확정

DevDay에서 발표된 GPT-6.1 Sol의 API 가격이 확정됐다([OpenAI](https://openai.com/index/introducing-gpt-6-1-sol/)). 표준 $2/$10/MTok, 캐시 $0.10/MTok, 27.2만 토큰 초과 시 롱 컨텍스트 요금 $4/$15 적용이며, GPT-6 Astra의 1/5 비용에 근접한 성능을 제공한다. Work와 Codex에서 Plus 이상 전 플랜에 순차 배포 중이다.

## Cursor: 29로 35일 연속 하락

Cursor 인기도가 29로 떨어지며 35일 연속 하락을 기록했다. OpenAI 모델 접근 차단까지 42일 남았고, SpaceXAI의 Grok-X 구독 통합이 다가오면서 독립적 정체성이 더욱 희미해지고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Sol API 가격 확정 |
| Claude Code | 99 | — | v2.1.286, Barclays 대규모 도입 |
| Codex CLI | 99 | — | DevDay 이후 안정세 |
| Antigravity | 99 | — | 31주 연속 최고점 |
| Claude AI | 99 | — | Barclays 파트너십 확대 |
| Windsurf | 88 | — | Devin Desktop 안정세 |
| Aider | 68 | — | 사실상 개발 중단 |
| Cursor | 29 | ↓2 | 35일 연속 하락, D-42 |
| GH Copilot | 9 | ↑2 | 내일 4개 모델 폐기, 서서히 회복 |
| Gemini CLI | 1 | — | 폐쇄 106일째 |

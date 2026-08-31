---
title: "Copilot D-Day 전야, Cursor 89로 4일째 추락 — 9월 1일이 AI 코딩 시장을 갈라놓는다"
date: 2026-08-31
lang: ko
categories: [news]
tags: [copilot, cursor, openai, claude-code, anthropic, codex, antigravity, windsurf, grok]
excerpt: "내일이면 Copilot의 크레딧 삭감과 6개 모델 폐기가 현실이 된다. Cursor는 OpenAI 결별 4일째 89까지 하락했다. Sonnet 5 가격 동결이 확정되며 Anthropic 생태계가 안정을 얻었다."
---

내일이 9월 1일이다. GitHub Copilot의 프로모션 크레딧이 Business 3,000→1,900(37% 삭감), Enterprise 7,000→3,900(44% 삭감)으로 줄어들고, Gemini 3.1 Pro·Claude Opus 4.5/4.6·Claude Sonnet 4.5/4.6·Raptor mini 등 6개 모델이 일괄 폐기된다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 연간 구독 개인 사용자만 Claude Sonnet 4.6을 유지할 수 있고, 나머지는 Claude Sonnet 5·Gemini 3.6 Flash 등으로 전환해야 한다([QATechTools](https://qatechtools.com/2026/08/31/github-copilot-six-model-retirements-september-qa/)). 새 Business/Enterprise 가입도 신용카드·PayPal 결제 조건부로 재개된다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)).

## Cursor: 89로 4일째 하락 — OpenAI 모델 차단 D-73

Cursor가 4일 연속 하락하며 89를 기록했다. OpenAI가 SpaceX 인수를 이유로 11월 12일 모델 접근 차단을 통보한 이후([OpenAI Blog](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/)), 커뮤니티의 신뢰 회복이 지연되고 있다. CEO Michael Truell은 "OpenAI 모델은 트래픽의 약 5%"라며 영향을 축소했지만([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)), Aur0ra 랜섬웨어 사건에 이은 두 번째 신뢰 위기로 개발자 이탈이 가속화되고 있다. Anthropic의 Tom Brown이 "Cursor 내 Claude 컴퓨트를 지속 확대하겠다"고 선언한 것은([WCCFTech](https://wccftech.com/anthropic-pounces-as-openai-abandons-spacexs-cursor-vowing-to-increase-claude-compute-even-as-openai-cites-contract-distrust/)) 긍정적이지만, 99에서 89까지 10포인트 하락은 시장의 불안감을 여실히 보여준다.

## Sonnet 5 가격 동결 확정 — 9월 1일 인상 없다

Anthropic이 Claude Sonnet 5의 $2/$10(입력/출력 MTok) 가격을 영구 확정하며, 9월 1일 예정이던 $3/$15 인상을 공식 철회했다([Enterprise DNA](https://enterprisedna.co/resources/news/anthropic-claude-sonnet-5-pricing-permanent-reversal-august-2026/)). 6월 출시 당시 "8월 31일까지 프로모션"이라 했던 가격이 그대로 표준 가격이 된 셈이다([Medium](https://blurbrahlab.medium.com/claude-sonnet-5-stays-at-2-10-forever-anthropic-cancels-september-price-hike-top-10-ai-518767b90c96)). Claude Code의 50% 프로모션 한도는 9월 14일 종료 후 영구 25% 인상으로 전환된다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)).

## Codex CLI: 브라우저 확장 5개 플랫폼 확대

Codex 브라우저 확장이 Chrome, Edge, Brave, Opera, Vivaldi로 확대되었다([Releasebot](https://releasebot.io/updates/openai/codex)). v0.151.0에서 추가된 MCP 서버 그레이스 기간 설정과 `--approve-for-me` 자동 승인 플래그가 CLI 워크플로우를 한층 매끄럽게 만들었다([Havoptic](https://www.havoptic.com/tools/openai-codex)).

## Antigravity: Guide 스킬·오디오 렌더링 추가

Google Antigravity가 내장 Guide 스킬을 추가해 사용법 안내를 도구 내에서 바로 제공한다([Releasebot](https://releasebot.io/updates/google/antigravity)). .mp3/.wav/.ogg/.m4a 오디오 파일을 사이드바에서 직접 재생할 수 있게 되었고, C++·Python·Protobuf 구문 강조와 파일 감시 최적화로 성능이 개선되었다([Releasebot](https://releasebot.io/updates/google/antigravity)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Sonnet 5 가격 영구 확정, 안정적 최상위 |
| ChatGPT | 99 | — | ChatGPT Images 체제 안착 |
| Codex CLI | 99 | — | 브라우저 확장 5개 플랫폼, v0.151.0 안정 |
| Antigravity | 99 | — | Guide 스킬, 오디오 렌더링 추가 |
| Claude AI | 99 | — | Sonnet 5 $2/$10 영구 확정 |
| Cursor | 89 | ↓2 | OpenAI 셧오프 D-73, 4일째 하락 |
| Windsurf | 86 | — | Devin Desktop 개선, ACU 표시 추가 |
| Aider | 68 | — | 44K+ 스타, 유지보수 모드 |
| Copilot | 1 | — | D-Day 전야: 내일 크레딧 삭감·6개 모델 폐기 |
| Gemini CLI | 1 | — | 폐쇄 74일째 |

9월 1일을 앞두고 AI 코딩 시장의 판도가 명확해지고 있다. Copilot은 크레딧 삭감과 모델 폐기로 재편을 앞두고, Cursor는 OpenAI 결별 여파에서 아직 바닥을 찾지 못했다. 반면 Anthropic은 Sonnet 5 가격 동결로 개발자 신뢰를 확보하며 CLI·IDE·API 전 영역에서 입지를 굳히고 있다.

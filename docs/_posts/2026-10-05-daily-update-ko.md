---
title: "Anthropic, $100M 프론티어 아카데미 발표 — IPO 투자자 데이 D-9, Claude Code 모드 시대 개막"
date: 2026-10-05
lang: ko
categories: [news]
tags: [anthropic, claude-code, copilot, cursor, openai, jetbrains-air]
excerpt: "Anthropic이 1억 달러 규모의 Claude Frontier Academy를 발표하고 IPO 투자자 데이를 9일 앞두고 있다. Claude Code에 모드(Mods) 시스템이 도입됐고, GitHub Copilot은 데스크톱 앱 제어 기능을 공개 프리뷰로 내놨다."
---

Anthropic이 이번 주 공세를 펼쳤다. 1억 달러를 투입해 만 명의 엔지니어를 양성하겠다는 Claude Frontier Academy를 10월 2일 발표했고([CNBC](https://www.cnbc.com/2026/10/02/anthropic-to-invest-100-million-to-train-ai-engineer-talent.html)), Claude Code에는 플러그인의 상위 개념인 '모드(Mods)'가 도입됐다. IPO 투자자 데이가 9일 앞으로 다가온 가운데, GitHub Copilot과 OpenAI도 잇따라 대형 업데이트를 내놓으며 10월 첫째 주를 뜨겁게 달구고 있다.

## Anthropic: $100M Frontier Academy — 만 명의 '프론티어 엔지니어' 양성

Anthropic이 Claude Partner Network 소속 기업들에서 10,000명의 "프론티어 배치 엔지니어"를 2027년 말까지 훈련시키겠다고 발표했다([Anthropic](https://www.anthropic.com/news/claude-frontier-academy)). 1억 달러 규모의 이 프로그램은 기업 AI 인재 격차를 겨냥한 것으로, Barclays는 이미 Claude Code 도입을 개발자 인력의 50%까지 확대할 계획이라고 밝혔다([Anthropic](https://www.anthropic.com/news/barclays-scales-claude)). IPO 직전 타이밍에 맞춘 전략적 발표로, 엔터프라이즈 생태계 락인(lock-in)을 본격화하는 신호다.

## Claude Code: 모드(Mods) 도입 + v2.1.289 보안 패치

10월 1일, Claude Code에 '모드(Mods)' 시스템이 도입됐다([Kingy AI](https://kingy.ai/ai-launch-tracker/claude-code-2-1-287-claude-mods-2026-10-01/)). 모드는 플러그인보다 깊은 레벨에서 동작하는 TypeScript 함수로, 프롬프트 재작성·도구 호출 차단/재시도·권한 요청 승인/거부·시크릿 검열·UI 요소 교체까지 가능하다. 빌트인 모드 "You Should Know"는 사이드 에이전트가 사용자와 Claude가 놓칠 수 있는 사항을 플래그해준다.

이틀 뒤인 10월 3일에는 v2.1.289가 배포돼 4건의 권한 취약점이 패치됐다([mixed-news.com](https://mixed-news.com/en/claude-code-2-1-289-second-route-past-rm-guard-stable-four-builds-behind/)). 환경변수 프리픽스 뒤에 숨긴 삭제 명령, 심링크를 통한 Read deny 우회, 복합 셸 명령의 모드 승인이 deny를 무시하는 문제가 모두 차단됐다.

## GitHub Copilot: Computer Use 공개 프리뷰 + Code Review API 출시

GitHub Copilot이 10월 1일 '컴퓨터 유즈(Computer Use)' 기능을 공개 프리뷰로 내놨다([GitHub Changelog](https://github.blog/changelog/2026-10-01-github-copilot-can-now-interact-with-desktop-apps)). macOS와 Windows의 Copilot CLI 및 Copilot 앱에서 데스크톱 애플리케이션을 직접 조작할 수 있게 됐다 — 클릭, 텍스트 입력, 스크롤, 드래그, 앱 간 워크플로 이동까지 가능하다. API가 없는 레거시 GUI 소프트웨어도 Copilot으로 자동화할 수 있다는 점이 핵심이다.

10월 2일에는 Copilot Code Review가 REST/GraphQL API를 지원하기 시작했으며, 기본 리뷰 수준이 'Balanced'로 변경됐다([GitHub Changelog](https://github.blog/changelog/2026-10-02-copilot-code-review-api-support-and-new-default-effort-level)). 한편, 10월 19일에는 Gemini 3.7 Flash·GPT-5.5·GPT-5.4 등 구형 모델이 일괄 퇴출될 예정이다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october/)).

## Anthropic IPO: 투자자 데이 10월 14일, 목표 밸류에이션 $2조

Anthropic이 10월 14일 샌프란시스코 본사에서 프리IPO 투자자 데이를 개최한다([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/anthropic-is-said-to-plan-pre-ipo-investor-day-as-listing-nears)). 11월 9일 주간 마케팅 개시, 11월 중순 상장이 유력하며 목표 밸류에이션은 최대 $2조로, 성사 시 역대 최대 IPO가 된다([Fortune](https://fortune.com/2026/08/13/anthropic-ipo-2-trillion-october-largest-ever-spacex/)). Morgan Stanley·Goldman Sachs·JPMorgan이 주관사로 선정됐다.

## Cursor: 39일 연속 하락 — OpenAI 셧오프 D-38

Cursor 인기도가 39일째 하락해 21까지 떨어졌다. SpaceX의 $60B Anysphere 인수 후 OpenAI가 모델 접근을 차단하기로 한 11월 12일 데드라인까지 38일 남았다([DevOps.com](https://devops.com/openai-cuts-off-cursors-model-access-after-spacex-acquisition/)). Compile 2026에서 발표한 자체 프론티어 모델·Origin 플랫폼·모바일 앱이 구원투수가 될 수 있을지 주목된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Pro 500 출시, GPT-6.1 Sol 안착 |
| Claude Code | 99 | — | Mods 도입, v2.1.289 보안 패치 |
| Codex CLI | 99 | — | Cloud 모드 확산, Code Review 추가 |
| Antigravity | 99 | — | Gemini CLI 대체 완료, 안정 |
| Claude AI | 99 | — | Frontier Academy $100M, IPO D-9 |
| Windsurf | 88 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 오픈소스 꾸준, 신규 릴리스 없음 |
| Cursor | 21 | ↓2 | 39일 연속 하락, OpenAI 셧오프 D-38 |
| GH Copilot | 17 | ↑2 | Computer Use 프리뷰, Code Review API |
| Gemini CLI | 1 | — | 6월 퇴역, Antigravity 전환 완료 |

이번 주는 Anthropic의 주간이었다. Frontier Academy로 엔터프라이즈 인재 파이프라인을 장악하고, Claude Code Mods로 개발자 생태계를 확장하며, IPO 카운트다운을 본격 시작했다. GitHub Copilot의 Computer Use는 에이전틱 코딩이 IDE를 넘어 데스크톱 전체로 확장되는 전환점이 될 수 있다.

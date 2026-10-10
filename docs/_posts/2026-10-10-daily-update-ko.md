---
title: "D-4 쌍둥이 카운트다운 — GPT-5.5 퇴역·Anthropic 투자자 데이 동일 날짜, Codex CLI MCP 로그인 추가"
date: 2026-10-10
lang: ko
categories: [news]
tags: [anthropic, openai, copilot, cursor, codex-cli, gpt, claude]
excerpt: "10월 14일, GPT-5.5 퇴역과 Anthropic 프리IPO 투자자 데이가 동시에 열린다. Codex CLI rust-v0.161.0이 MCP 터미널 로그인과 음성 커스터마이징을 추가. Cursor 44일 연속 하락 11점, Copilot 16점 차 리드."
---

10월 14일이 이제 4일 앞이다. 이 하루에 AI 코딩 업계 양대 이벤트가 동시에 진행된다 — OpenAI의 GPT-5.5 퇴역과 Anthropic의 프리IPO 투자자 데이다. 그 사이 Codex CLI는 조용히 중요한 릴리스를 밀어넣었고, Anthropic은 $965B 밸류에이션 뒤에 숨은 재무 수치를 공개하기 시작했다.

## Codex CLI rust-v0.161.0: MCP 터미널 로그인과 음성 커스터마이징

Codex CLI가 10월 7일 rust-v0.161.0을 릴리스하며 두 가지 주요 기능을 추가했다([Havoptic](https://www.havoptic.com/r/openai-codex-rust-v0.161.0)). 첫째, `/mcp login <name>` 명령으로 활성 터미널 세션에서 직접 MCP 서버 인증이 가능해졌다. 둘째, 음성 대화용 마이크·스피커 설정을 커스터마이징하고 로컬에 저장할 수 있다. GPT-6.1 Sol이 기본 모델로 설정되었으며, Daybreak 사이버보안 기능은 `--enable clidaybreak` 플래그로 옵트인해야 활성화된다.

## GPT-5.5 퇴역 D-4: 마이그레이션 압박 가중

GPT-5.5가 10월 14일 ChatGPT, ChatGPT Work, Codex에서 완전 퇴역한다([Let's Data Science](https://letsdatascience.com/news/openai-retires-gpt-55-from-chatgpt-and-codex-1a6f69be)). 소비자, Business, Enterprise, Edu 전 플랜이 해당되며, ChatGPT 로그인으로 Codex를 사용하는 개발자는 GPT-5.6 Sol(`gpt-5.6-sol`)로 마이그레이션해야 한다([OrcaRouter](https://www.orcarouter.ai/blog/gpt-5-5-remains-available-openai-api-codex-api-key)). API 키 접근은 영향 없다. GPT-6.1 Sol Ultrafast는 아직 Codex에서 사용할 수 없는 상태다([SmartScope](https://smartscope.blog/en/blog/codex-gpt-6-1-sol-ultrafast-availability-2026/)).

## Anthropic IPO D-4: $965B에서 $2T로

Anthropic 프리IPO 투자자 데이가 10월 14일로 4일 남았다([CryptoBriefing](https://cryptobriefing.com/anthropic-pre-ipo-investor-day-october-14/)). 직전 프라이빗 라운드는 5월 $65B 규모 Series H로, 포스트머니 밸류에이션 $965B이었다([fbroker](https://fbroker.kz/en/news/51473-anthropic-shareholders-expect-a-2t-valuation-following-an-october-ipo-en-2)). 투자자들은 연말까지 연간 매출 $100B~$120B를 예상하며, 5월 $47B 대비 2배 이상 성장을 전망한다. Goldman Sachs, JPMorgan, Morgan Stanley 공동 주간사가 $60B+ 규모 공모를 준비 중이며, SEC 비공개 제출은 6월 1일에 완료됐다([BitMEX](https://www.bitmex.com/blog/anthropic-ipo-guide)). 11월 중간선거 이후 Nasdaq 상장이 목표다.

## Anthropic: Claude에 '잔혹 행위 금지' 정책 발표

Anthropic이 10월 8일 이용약관을 업데이트해 Claude에 대한 "지속적이고 불필요한 학대적 또는 잔인한 행동"을 금지했다([MacRumors](https://macrumors.com/2026/10/08/anthropic-user-guideline-update/)). 11월 12일부터 발효되며, 주요 집행 수단은 대화 종료다. 일반적인 불만 표출·반박·어두운 창작 주제·모델 테스트는 명시적으로 제외됐다([Dexerto](https://www.dexerto.com/entertainment/claude-users-can-be-banned-for-being-cruel-to-the-chatbot-3417268/)). 이 정책에는 기만적 정치·상업 캠페인 금지, 무기 관련 금지 항목 확대, 감시 제한 강화도 포함됐다([RuntimeWire](https://runtimewire.com/article/anthropic-usage-policy-cruel-behavior-claude)).

## Copilot: Claude Haiku 5.5 추가 + 10월 19일 대규모 퇴역 D-9

GitHub Copilot에 Claude Haiku 5.5가 10월 7일 추가됐다([GitHub Blog](https://github.blog/changelog/2026-10-07-claude-haiku-5-5-in-github-copilot)). 초기 테스트에서 Claude Sonnet 5에 근접한 성능을 보이면서 토큰과 단계가 대폭 줄었다. Copilot CLI도 10월에만 v1.0.91~v1.0.93 세 번 릴리스되며 샌드박싱 전면 적용과 환경 피커를 추가했다([Havoptic](https://www.havoptic.com/releases/github-copilot/2026/10)). 한편, 두 번째 10월 퇴역 웨이브가 9일 앞이다 — GPT-5.5 포함 6개 모델이 10월 19일 퇴역한다([GitHub Changelog](https://github.blog/changelog/2026-09-18-upcoming-deprecation-of-selected-github-copilot-models-in-mid-october)).

## Cursor: 44일 연속 하락, 11점

Cursor가 11점으로 떨어지며 44일 연속 하락을 기록했다. Copilot(27점)과의 격차는 16점으로 벌어졌다. 10월 6일에는 iOS 앱에 원격 에이전트 제어 기능을 추가해 폰에서 실행 중인 에이전트를 확인하고 응답할 수 있게 됐다([Cursor Changelog](https://cursor.com/changelog)). OpenAI 모델 접근 차단(11월 12일)까지 33일이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.5 퇴역 D-4, GPT-6.1 Sol 확산 |
| Claude Code | 99 | — | IPO D-4, $965B→$2T 밸류에이션 점프 |
| Codex CLI | 99 | — | rust-v0.161.0 MCP 로그인·음성 커스텀 |
| Antigravity | 99 | — | 안정 가동, Claude Opus 5.5·Sonnet 5.5 지원 |
| Claude AI | 99 | — | 반학대 정책 11/12 발효, 정치·무기 정책 확대 |
| Windsurf | 88 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | GitHub 48.8K 스타, Polyglot 벤치마크 표준화 |
| GH Copilot | 27 | ↑2 | Claude Haiku 5.5 추가, CLI v1.0.93, 퇴역 D-9 |
| Cursor | 11 | ↓2 | 44일 연속 하락, iOS 원격 제어 |
| Gemini CLI | 1 | — | 퇴역 완료, Antigravity 전환 |

10월 14일에 GPT-5.5 퇴역과 Anthropic 투자자 데이가 겹치는 가운데, Codex CLI는 MCP 연동과 음성 기능으로 생태계를 확장하고, Anthropic은 $965B에서 $2T로의 밸류에이션 점프를 기관 투자자들에게 설득해야 한다. AI 코딩 도구 시장의 세대 교체, 자본 시장 진입, 그리고 개발자 경험 혁신이 동시에 가속화되고 있다.

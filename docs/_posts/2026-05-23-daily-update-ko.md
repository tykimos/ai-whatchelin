---
title: "Anthropic $9,000억 — OpenAI를 제치고 세계 최고가 AI 스타트업으로"
date: 2026-05-23
lang: ko
categories: [news]
tags: [anthropic, claude-code, copilot, antigravity, grok-build, security]
excerpt: "Anthropic의 $300억+ 펀딩 라운드가 다음 주 마감 예정이며, TeamPCP 공급망 웜이 Claude Code 설정까지 타깃으로 확대됐다."
---

Anthropic이 AI 산업의 밸류에이션 왕좌를 차지할 준비를 하고 있다. Bloomberg에 따르면 Anthropic은 빠르면 5월 26일 주에 $300억 이상의 투자 라운드를 마감할 예정이며, 프리머니 밸류에이션이 $9,000억을 넘어 OpenAI의 $8,520억을 추월한다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-22/anthropic-to-close-over-30-billion-round-as-soon-as-next-week)). Sequoia Capital, Dragoneer, Altimeter Capital, Greenoaks Capital이 각각 약 $20억씩 공동 리드하며, Founders Fund와 General Catalyst도 참여 예정이다([TechTimes](https://www.techtimes.com/articles/317066/20260523/anthropic-funding-round-top-30b-900b-valuation-would-surpass-openai-most-valuable-ai-startup.htm)). Q2 매출 $109억, 첫 흑자 분기 전망과 맞물려 10월 IPO 가능성까지 열리고 있다.

## Claude Code: v2.1.149 실용 개선 + v2.1.150 인프라 업데이트

Claude Code가 이틀 연속 업데이트를 릴리스했다. v2.1.149(5/22)에서는 `/usage`에 스킬·서브에이전트·플러그인·MCP 서버별 사용량 분석이 추가됐고, `/diff` 상세 뷰에 키보드 스크롤(j/k, PgUp/PgDn)이 지원된다([code.claude.com/changelog](https://code.claude.com/docs/en/changelog)). GFM 체크박스 렌더링도 추가돼 작업 관리가 더 직관적이다. v2.1.150(5/23)은 내부 인프라 개선에 집중했다.

## TeamPCP 공급망 웜: Claude Code까지 타깃

TeamPCP 공급망 공격의 피해 범위가 확대됐다. 악성 Nx Console VS Code 확장이 `~/.claude/settings.json` 내 Claude Code 설정과 GitHub 토큰·AWS 키를 타깃으로 삼은 것이 확인됐다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-may-23-2026)). Mistral AI, 유럽연합 집행위원회, 170+ npm 패키지도 피해자 목록에 올랐다. 해당 확장을 사용한 개발자는 즉시 모든 자격증명을 교체해야 한다.

## Copilot: 19주 연속 하락, 사용량 과금 D-9

GitHub Copilot의 인기도가 19주 연속 하락해 64를 기록했다. 6월 1일 사용량 기반 과금 전환까지 9일 남은 가운데, Copilot 클라우드 에이전트에 Claude Haiku 4.5와 GPT-5.4-mini가 추가돼 저비용 작업을 위한 선택지가 넓어졌다([GitHub Changelog](https://github.blog/changelog/2026-05-18-copilot-cloud-agent-fast-cost-efficient-models-for-simple-tasks/)).

## Antigravity: 롤백 사태 5일째, 52로 하락

Antigravity 2.0 롤백 위기가 5일째 이어지며 인기도가 52로 떨어졌다. I/O 2026 당일 62까지 급등했던 점수가 롤백 사태로 10포인트 하락한 상태다. Google이 하루에 두 번 속도 제한을 3배로 올렸지만 사용자 불만은 여전하다([9to5Google](https://9to5google.com/2026/05/21/google-has-tripled-gemini-usage-limits-for-antigravity-twice/)).

## Grok Build: $99 할인 공세로 시장 진입 가속

xAI가 Grok Build를 첫 6개월간 $99/월에 제공하며 시장 진입을 가속하고 있다 — SuperGrok Heavy($299/월) 대비 67% 할인이다([Engadget](https://www.engadget.com/2173482/xai-coding-agent-grok-build/)). Musk가 직접 X에서 홍보해 총 160만+ 조회수를 기록했다. 8개 병렬 에이전트와 Arena Mode 자동 평가 기능이 차별점이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | 안정 |
| Claude Code | 98 | — | $900B 펀딩 호재 |
| Cursor | 96 | — | 3.5 출시 후 안정 |
| Codex CLI | 87 | ↑1 | Goal 모드 정식 효과 |
| Gemini CLI | 84 | ↓1 | CLI→Antigravity 전환 우려 |
| Windsurf | 81 | — | 안정 |
| GH Copilot | 64 | ↓1 | 19주 연속 하락, D-9 |
| Antigravity | 52 | ↓1 | 롤백 5일째 |

Anthropic의 $9,000억 밸류에이션과 Copilot의 19주 연속 하락은 AI 코딩 도구 시장의 세대교체를 상징한다. 한편 TeamPCP 공급망 공격은 AI 도구가 새로운 보안 공격 표면이 되고 있음을 경고한다.

---

*작성: AI WhatChelin 자동 업데이트 시스템*

---
title: "Copilot SDK GA 출시했지만 개발자 이탈은 멈추지 않는다 — 종량제 5일차, Windsurf 84로 반사이익"
date: 2026-06-05
lang: ko
categories: [news]
tags: [github-copilot, windsurf, devin-desktop, cursor, claude-code, anthropic, gemini-cli, codex-cli, openai, spacex-ipo]
excerpt: "GitHub이 Copilot SDK GA를 발표하며 생태계 확장에 나섰지만, 종량제 전환 후 5일째 개발자 이탈이 계속되고 있다. Windsurf(Devin Desktop)는 $15 가격 효과로 84까지 올랐다."
---

GitHub이 반격 카드를 꺼냈다. Copilot SDK GA를 6개 언어로 출시하고, CLI에 "러버덕" 비판 에이전트와 음성 입력을 추가했다. 하지만 종량제 전환 5일차, 개발자들의 이탈은 멈추지 않고 있다. Copilot 인기도는 **51**로 32주 연속 하락했고, 그 수요를 흡수한 Windsurf(Devin Desktop)는 **84**까지 올랐다.

## GitHub Copilot: SDK GA로 생태계 확장 시도, 그러나 이탈은 계속

GitHub이 Copilot SDK를 GA로 출시했다 — Node.js/TypeScript, Python, Go, .NET, Rust, Java 6개 언어를 지원하며 커스텀 도구와 MCP 연동이 가능하다([GitHub Blog](https://github.blog/changelog/2026-06-02-copilot-sdk-is-now-generally-available/)). 동시에 GPT-4.1이 모든 Copilot 경험에서 완전히 퇴장하고 GPT-5.3-Codex가 기본 모델로 교체됐다([GitHub Changelog](https://github.blog/changelog/2026-06-02-gpt-4-1-deprecated/)). Copilot CLI에는 코드의 맹점을 찾아주는 "러버덕" 비판 에이전트, 프롬프트 스케줄링, 음성 입력이 GA됐다([GitHub Changelog](https://github.blog/changelog/2026-06-02-copilot-cli-improved-ui-rubber-duck-prompt-scheduling-and-voice-input/)).

그러나 SDK 출시에도 불구하고 종량제 반발은 사그라들지 않는다. Reddit에서는 월 비용이 $29에서 $750으로, 심지어 $50에서 $3,000으로 뛸 것이라는 보고가 계속되고 있으며([GitHub Discussion](https://github.com/orgs/community/discussions/192948)), The Register는 "분노한 개발자들이 이탈을 선언"이라 보도했다. Copilot 인기도는 **51**로 32주 연속 하락 — 역대 최저를 다시 경신했다.

## Windsurf (Devin Desktop): $15 가격으로 이탈 수요 흡수, 84 달성

Windsurf가 Devin Desktop으로 리브랜딩된 지 3일째, 인기도가 **84**로 올랐다([Devin Blog](https://devin.ai/blog/windsurf-is-now-devin-desktop/)). $15/월 가격이 Cursor $20 대비 확실한 언더커팅 효과를 보이고 있다. Cascade는 7월 1일 EOL 예정이며, Rust로 재작성된 Devin Local이 토큰 30% 절감 효과와 함께 대체한다. Agent Client Protocol(ACP)을 통해 Codex, Claude Agent 등 외부 에이전트도 에디터 내에서 실행 가능하다([ChatForest](https://chatforest.com/builders-log/windsurf-devin-desktop-rebrand-devin-local-acp-builder-guide/)).

## Anthropic: 에이전트 과금 D-10, IPO 카운트다운

Anthropic의 에이전트 과금 변경이 6월 15일로 10일 앞으로 다가왔다. Agent SDK, `claude -p`, Claude Code GitHub Actions 등 자동화 사용은 별도 월간 크레딧 풀로 분리된다 — Pro $20, Max 5x $100, Max 20x $200([Codersera](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/)). 한편 Anthropic의 S-1 IPO 비밀 신청서가 주목받고 있다 — 5월 매출 런레이트 약 $470억, 밸류에이션 $9,650억으로 메이저 AI 랩 최초의 IPO 신청이다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-june-5-2026)).

## Gemini CLI 종료 D-13: Antigravity CLI 전환 가속

Gemini CLI 종료까지 13일 남았다. 6월 18일 이후 Google AI Pro/Ultra 및 무료 사용자의 요청은 차단되며, 기업/Standard 라이선스 사용자만 유지된다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)). 대체재인 Antigravity CLI는 Go로 작성됐으며 멀티 에이전트 오케스트레이션을 네이티브로 지원한다. 인기도는 **64**로 안정세를 보이고 있다.

## Cursor-SpaceX $600억 인수 합의

SpaceX IPO 로드쇼가 진행 중인 가운데, Cursor가 SpaceX와 $600억 인수 합의를 체결했다는 보도가 나왔다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-june-5-2026)). SpaceX IPO는 주당 $135, 목표 밸류에이션 $1.75조로 6월 12일 나스닥 거래 개시 예정이다. AI 코딩 도구 시장에서의 의미는 아직 불확실하지만, Cursor의 독립성에 대한 우려가 커지고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 에이전트 과금 D-10, Opus 4.8 안정 |
| ChatGPT | 96 | — | GPT-5.5 Instant 스타일 업데이트 |
| Cursor | 96 | — | SpaceX $600억 인수 합의 |
| Claude AI | 95 | — | S-1 IPO 신청, $965B 밸류에이션 |
| Windsurf (Devin Desktop) | 84 | ↑1 | $15 가격으로 Copilot 이탈 흡수 |
| Codex CLI | 87 | — | Sites 프리뷰, 세션 아카이빙 |
| Gemini CLI | 70 | ↓1 | 종료 D-13, 비기업 차단 임박 |
| Aider | 68 | — | Opus 4.8 + Gemini 2.5 지원 추가 |
| Antigravity | 64 | — | Gemini CLI 이전 수요 안정세 |
| GH Copilot | 51 | ↓1 | 32주 연속 하락, SDK GA도 반발 상쇄 못해 |

GitHub은 SDK GA라는 기술적 반격 카드를 꺼냈지만, 개발자 신뢰 회복에는 시간이 필요해 보인다. 종량제 전환의 충격파가 Windsurf의 반사이익으로 이어지는 구도가 굳어지고 있다.

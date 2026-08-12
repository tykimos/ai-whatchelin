---
title: "SpaceX-Cursor 인수 이번 주 마감 가능 — Claude Code auto 모드 D-2, v2.1.228 보안 패치"
date: 2026-08-12
lang: ko
categories: [news]
tags: [cursor, spacex, claude-code, anthropic, copilot, devin-desktop]
excerpt: "SpaceX의 $600억 Cursor 인수가 이번 주 중으로 마감될 수 있다는 보도가 나왔다. Claude Code는 auto 모드 기본 전환을 이틀 앞두고 v2.1.228을 배포해 Remote Control 보안 이슈를 패치했으며, GitHub Copilot은 9월 대폐기를 20일 앞두고 Kimi K3 통합에 집중하고 있다."
---

SpaceX-Cursor $600억 인수가 최종 규제 승인만 남기고 빠르면 이번 주 마감될 수 있다. 8월 9일 내부 미팅에서 Cursor는 직원들에게 "빠르면 다음 주, 늦어도 8월 말"이라고 통보했으며([Seeking Alpha](https://seekingalpha.com/news/4629527-cursor-says-spacex-deal-could-be-done-by-end-of-next-week---report)), SpaceX(SPCX) 주가는 8월 10일 4.23% 상승했다([startuphub.ai](https://www.startuphub.ai/ai-news/ipo-watch/2026/spacex-cursor-acquisition-lockup-2026-08-10)). 인수 확정 시 Cursor 브랜드는 퇴장하고 후속 제품들은 Grok 이름을 채택할 가능성이 높다([PYMNTS](https://www.pymnts.com/news/artificial-intelligence/2026/cursor-brand-name-may-not-survive-spacex-acquisition/)).

## Claude Code: v2.1.228 + auto 모드 D-2

Anthropic이 Claude Code v2.1.228을 배포했다([GitHub](https://github.com/anthropics/claude-code/releases/tag/v2.1.228)). 드문 레이아웃 오류 후 인터랙티브 세션이 리드로잉을 완전히 중단하는 버그를 수정했고, Windows에서 상위 폴더로부터 실행 시 Git을 찾지 못하는 문제를 해결했다. 가장 주목할 만한 수정은 Remote Control /resume이 연결된 세션 간에 대화 데이터를 유출하던 보안 이슈다. 8월 14일 auto 모드 기본 전환까지 이틀 남았으며, 안전 분류기의 89% 포착률(인간 리뷰 13.6% 대비)이 실전 검증될 시점이 코앞이다.

## Claude AI: 음성 모드 전 모델 개방 + M365 쓰기 도구

Claude AI의 음성 모드가 이제 Haiku, Sonnet, Opus 모든 모델에서 사용 가능하다(Fable은 아직 제외)([SlashGear](https://www.slashgear.com/2229323/claude-ai-voice-mode-update-model-choice/)). 기존에는 Haiku 전용이었던 제약이 풀렸다. 한편 Microsoft 365 커넥터에 쓰기 도구가 추가되어 이메일 작성·발송, 캘린더 이벤트 관리, OneDrive·SharePoint 파일 생성·업데이트가 가능해졌다([suprmind.ai](https://suprmind.ai/hub/claude/features/)).

## Cursor: Router가 Fable급 품질을 68% 저렴하게 달성

Cursor Router Auto Intelligence가 Fable급 이상의 사용자 만족도를 68% 낮은 비용으로 달성했다([Releasebot](https://releasebot.io/updates/cursor)). 출시 대비 추가 18% 비용 절감이며, Auto Balance는 Opus 4.8을 능가하면서 41% 비용을 줄였다. Opus 5가 라우팅 믹스에 추가됐다. Google Workspace Plugins(Gmail, Drive, Calendar)도 에이전트에서 직접 사용 가능하다.

## GitHub Copilot: 9/1 대폐기 D-20, Kimi K3 확대

GitHub Copilot의 9월 1일 대규모 모델 폐기까지 20일이 남았다([GitHub Blog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). Claude Sonnet 4.6은 연간 개인 구독자만 유지된다. 한편 Moonshot AI의 오픈웨이트 모델 Kimi K3가 Copilot Pro/Pro+/Max/Business/Enterprise에 GA됐으며, $3/$15/MTok으로 프론티어 에이전틱 코딩 성능을 제공한다([GitHub Blog](https://github.blog/changelog/2026-08-06-kimi-k3-is-now-available-in-github-copilot/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.228 보안 패치, auto 모드 D-2 |
| ChatGPT | 99 | — | GPT-5-Codex-Mini 확산, GPT-5.4 퇴장 D-19 |
| Antigravity | 99 | — | 상한 유지 |
| Claude AI | 99 | — | 음성 모드 전 모델 개방, M365 쓰기 도구 |
| Codex CLI | 99 | — | v0.147.0 플러그인 생태계, 상한 유지 |
| Cursor | 97 | — | SpaceX 인수 이번 주 마감 가능 |
| Windsurf | 85 | — | Devin Local 에디터 컨텍스트 인식 강화 |
| Aider | 68 | — | 2025년 8월 이후 릴리스 없음 |
| Copilot | 1 | — | 92주 하락, 9/1 대폐기 D-20 |
| Gemini CLI | 1 | — | 폐쇄 55일째, Antigravity 완전 대체 |

SpaceX-Cursor 인수가 초읽기에 들어가면서 AI 코딩 도구 시장의 '빅테크 통합' 흐름이 가속화되고 있다. Claude Code는 auto 모드 전환을 앞두고 마지막 안정화 패치에 집중하고 있으며, GitHub Copilot은 대폐기 전 Kimi K3라는 새 모델 카드를 꺼내들었다.

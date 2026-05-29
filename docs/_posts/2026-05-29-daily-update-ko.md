---
title: "Anthropic $650억 마감에 OpenAI 전 서비스 장애 — AI 양강 구도 극명한 대비"
date: 2026-05-29
lang: ko
categories: [news]
tags: [anthropic, claude, openai, copilot, codex-cli, microsoft-build]
excerpt: "Anthropic이 $9,650억 밸류에이션으로 $650억을 마감한 당일, OpenAI는 전 서비스 대규모 장애를 겪었다. Copilot은 25주 연속 하락으로 58에 도달하며 사용량 과금 D-3를 맞이했고, Microsoft는 Build 2026에서 자체 코딩 모델 공개를 예고했다."
---

Anthropic이 $650억 시리즈 H를 $9,650억 포스트머니 밸류에이션으로 마감하며, OpenAI를 넘어 세계 최고 가치 비상장 AI 기업이 됐다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-28/anthropic-raises-at-965-billion-valuation-eclipsing-openai)). 같은 날 OpenAI는 2026년 들어 가장 광범위한 전 서비스 장애를 겪었다 — 두 라이벌의 극명한 대비가 이뤄진 하루였다.

## Anthropic: $1조 클럽 진입 목전

Sequoia, Dragoneer, Altimeter, Greenoaks가 공동 리드했으며, Amazon이 기존 약정 $150억 중 $50억을 투입했다([CNBC](https://www.cnbc.com/2026/05/28/anthropic-open-ai-startup-value.html)). 연간 매출 런레이트가 $470억에 달하며, 10월 IPO 전 마지막 비공개 라운드다([TechCrunch](https://techcrunch.com/2026/05/28/anthropic-raises-65-billion-nears-1t-valuation-ahead-of-ipo/)). Opus 4.8 패스트 모드는 이전 모델 대비 3배 저렴해졌으며, Mythos급 모델을 수주 내 전체 고객에게 공개할 계획도 밝혔다([VentureBeat](https://venturebeat.com/technology/anthropics-claude-opus-4-8-is-here-with-3x-cheaper-fast-mode-and-near-mythos-level-alignment)).

## OpenAI: 전 서비스 대규모 장애

OpenAI가 5월 29일 ChatGPT, API, DALL-E, Codex, Sora, 로그인 시스템 전반에 걸쳐 장애를 겪었다([BusinessUpturn](https://www.businessupturn.com/technology/chatgpt-down-openai-users-report-widespread-problems-with-api-app-and-login-on-may-29)). 사용자들은 "too many concurrent connections" 오류를 보고했으며, 당일 내 복구됐다. Anthropic의 $650억 라운드 마감과 같은 날 발생해 극명한 대조를 이뤘다.

## Microsoft Build D-4: 자체 코딩 모델 임박

Microsoft가 Build 2026(6월 2-3일)에서 GitHub Copilot용 자체 코딩 모델을 공개할 예정이다([The Information](https://www.theinformation.com/newsletters/ai-agenda/microsoft-release-new-coding-model-next-week-comeback-attempt)). 코딩 특화·추론 특화·자체 에이전트 등 다양한 모델이 포함되며, Mustafa Suleyman 팀이 4월 OpenAI 훈련 제한에서 해방된 후 첫 결과물이다. MSFT 주가는 보도에 ~3% 상승했다([Reuters/TradingView](https://www.tradingview.com/news/reuters.com,2026:newsml_L4N4251NM:0-microsoft-to-release-new-coding-model-next-week-the-information-reports/)).

## Claude Code v2.1.153: 36건 변경

/model이 새 세션 기본값으로 저장되며, 플러그인 마켓플레이스에 skipLfs 옵션이 추가됐다([code.claude.com/changelog](https://code.claude.com/docs/en/changelog)). Bedrock·Vertex 사용자의 'Opus (1M context)' 모델 피커 선택 불가 회귀 버그(v2.1.129 이후)를 포함해 25건 이상 버그가 수정됐다.

## Opus 4.8: GA 수시간 만에 오류 급증, 6분 해결

Opus 4.8이 GitHub Copilot과 AWS에서 GA된 지 수시간 만인 08:39 UTC에 오류가 급증했다([AI Weekly](https://aiweekly.co/alerts/anthropic-opus-48-hits-errors-hours-after-aws-launch)). Anthropic이 08:45 UTC까지 수정을 적용해 6분 만에 해결했지만, 출시 당일 도입한 개발자들이 짧은 장애를 경험했다.

## GitHub Copilot: 25주 연속 하락, D-3

Copilot 인기도가 58까지 떨어지며 역대 최저치를 경신했다([GitHub Docs](https://docs.github.com/en/copilot/how-tos/manage-and-track-spending/prepare-for-your-move-to-usage-based-billing)). 6월 1일 사용량 기반 과금까지 3일 — 코드 완성은 무료 유지되나 에이전트·채팅은 AI 크레딧을 소모한다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 + $650억, Mythos 임박 |
| Cursor | 96 | — | 안정, Build 전 관망세 |
| Codex CLI | 88 | — | v0.135.0, 자율 에이전트 진화 |
| Windsurf | 81 | — | Devin 통합 안정화 |
| Gemini CLI | 77 | ↓1 | 종료 D-20, 이탈 지속 |
| Antigravity | 58 | ↑1 | v2.0.0 패치 후 회복세 |
| GH Copilot | 58 | ↓1 | 25주 최저, 과금 전환 D-3 |
| ChatGPT | 97 | ↓1 | 전 서비스 장애 영향 |
| Claude AI | 95 | — | $9,650억, IPO 임박 |
| Aider | 68 | — | 안정, 오픈소스 기반 |

Copilot의 추락과 Antigravity의 바닥 반등이 58에서 교차한다 — 전혀 다른 궤도에서 같은 점수가 의미하는 바는 다르다. Build 2026에서 Microsoft 자체 코딩 모델이 반전 카드가 될 수 있을까.

---

*출처: 각 문장에 인라인 표기*

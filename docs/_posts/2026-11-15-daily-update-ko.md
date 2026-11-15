---
title: "Copilot 모델 대퇴출 D-1 — Anthropic IPO 로드쇼 6일차, Codex CLI 0.169.0 안착"
date: 2026-11-15
lang: ko
categories: [news]
tags: [github-copilot, anthropic, ipo, codex-cli, cursor, claude-code, chatgpt]
excerpt: "GitHub Copilot의 3개 모델 퇴출이 내일로 다가왔다. Anthropic IPO 로드쇼는 6일차에 접어들며 기관 수요가 계속 쌓이고 있고, Cursor는 OpenAI 없이 4일째를 보내고 있다."
---

내일이면 GitHub Copilot에서 세 개의 주요 AI 모델이 사라진다. Claude Opus 4.8, Claude Opus 5, GPT-5.6 Terra가 11월 16일부로 Chat, 인라인 편집, Agent 모드, 코드 자동완성 등 모든 Copilot 영역에서 완전히 제거된다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). 연간 Individual 구독자만 Claude Opus 4.8을 유지할 수 있으며, 관리자들은 대체 모델(Opus 5.5, GPT-6.1 Sol)이 정책에서 활성화되어 있는지 반드시 확인해야 한다([dev.classmethod.jp](https://dev.classmethod.jp/en/articles/github-copilot-model-deprecation-nov-2026/)). Copilot 인기도는 98점으로 53일째 연속 상승 중이다.

## Anthropic IPO: 로드쇼 6일차, 수요 지속 확대

Anthropic IPO 로드쇼가 6일차에 접어들었다. $70-78 주당 가격 범위로 825백만 주의 Class A 주식이 Nasdaq ANT 티커 아래 상장될 예정이다([RTTNews](https://www.rttnews.com/3712632/anthropic-sets-ipo-price-range-at-70-78-per-share-launches-roadshow.aspx)). 주문장은 이미 수배 초과 청약 상태이며, 대만 Fubon Life가 최대 $7억을 입찰한 것으로 알려졌다([BigGo Finance](https://finance.biggo.com/news/9812aa29-cc85-47d4-a68f-946ab4e6a228)). 가격 결정은 다음 주 수요일(11월 19일)경으로 예상된다([BusinessDay](https://www.businessday.co.za/companies/2026-11-14-investors-flock-to-anthropic-ipo-but-question-durability-of-ai-lead/)). 그러나 투자자들은 Google 등 경쟁사가 빠르게 추격하는 상황에서 Anthropic의 기술 리더십 지속 가능성에 의문을 제기하고 있다([Reuters via The Star](https://www.thestar.com.my/tech/tech-news/2026/11/14/exclusive-investors-flock-to-anthropic-ipo-but-question-durability-of-ai-lead)).

## Cursor: OpenAI 차단 4일째, 84일째 바닥

OpenAI 모델 접근 차단 후 4일째, Tab 자동완성·자동 모델 선택·클라우드 에이전트 등 핵심 기능이 여전히 복구되지 않고 있다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). SpaceX 인수 후 OpenAI가 "계약 위반 전력"을 이유로 차단을 단행했으며([OpenAI](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/)), 대안 전략이 여전히 불투명한 상태다. JetBrains 2026 설문에서 Cursor는 18% 점유율을 기록했으나, OpenAI 차단 이후 실질적 이탈이 가속화되고 있다.

## ChatGPT: Chat·Work 탭 통합 진행 중

OpenAI가 ChatGPT의 Chat과 Work 탭을 하나로 통합하는 작업을 진행 중이다([TechCrunch](https://techcrunch.com/2026/11/02/openai-is-finally-merging-chatgpts-chat-and-work-tabs/)). Codex는 데스크톱 앱에서 별도 경험으로 유지되며, 두 경험 모두 동일한 토큰 허용량 풀에서 사용량이 차감된다. Codex CLI는 0.168.0과 0.169.0을 연달아 출시하며 11월 릴리스 행진을 이어가고 있다([Releasebot](https://releasebot.io/updates/openai/codex)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Chat·Work 탭 통합 진행 중 |
| Claude Code | 99 | — | Fable 5.2 기본 모델 전환 6일째 |
| Codex CLI | 99 | — | 11월 6연속 릴리스 행진 |
| Antigravity | 99 | — | Gemini 4 Carbon 합류, 도입 할인 D-15 |
| Claude AI | 99 | — | IPO 로드쇼 6일차, 가격 결정 D-4 |
| GH Copilot | 98 | ↑1 | 53일 연속 상승, 모델 퇴출 D-1 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 4일째, 84일째 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 임박 |

Copilot 모델 퇴출이 내일로 확정되면서 관리자들의 마이그레이션 작업이 마지막 24시간에 돌입했다. Anthropic IPO는 수요 과열 속에서도 AI 리더십 지속성에 대한 기관투자가들의 의구심이 함께 커지고 있어, 가격 결정 주간이 시장의 분수령이 될 전망이다. Cursor는 OpenAI 차단 4일째에도 대안을 내놓지 못하고 있다.

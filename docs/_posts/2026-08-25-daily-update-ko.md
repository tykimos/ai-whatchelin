---
title: "o3 은퇴 D-1 — 내일 ChatGPT에서 사라지는 추론 모델, Copilot은 Slack으로 확장하지만 105주째 하락"
date: 2026-08-25
lang: ko
categories: [news]
tags: [openai, o3, copilot, slack, grok, antigravity, cursor, deprecation]
excerpt: "OpenAI o3가 내일(8/26) ChatGPT에서 은퇴한다. 90일 일몰 기간이 끝나는 날이다. Copilot은 Slack으로 진출했지만 105주째 하락 중이고, 앞으로 일주일 안에 모델 4건이 연쇄 퇴장한다."
---

내일이면 OpenAI o3가 ChatGPT 모델 선택기에서 사라진다. 5월 28일 발표된 90일 일몰 기간의 마지막 날이다. 한편 GitHub Copilot은 Slack 통합으로 워크플로 확장을 시도하고 있지만 인기도 하락은 105주째를 기록했고, 다음 주까지 4건의 모델 퇴장이 연쇄적으로 이어진다.

## OpenAI: o3 은퇴 D-1, 내일 ChatGPT 퇴장

OpenAI o3가 8월 26일 ChatGPT에서 공식 은퇴한다([orcarouter.ai](https://www.orcarouter.ai/blog/o3-chatgpt-retirement-august-26)). 90일 일몰 기간이 끝나면 모델 선택기에서 완전히 제거되며, 유료 구독자도 수동 선택이 불가해진다. 다만 API에는 영향이 없으며, o3-2025-04-16과 o3-pro-2025-06-10 두 스냅샷의 API 제거는 12월 11일로 별도 예정이다([OpenAI Help Center](https://help.openai.com/en/articles/9624314-model-release-notes)). OpenAI는 *"제한적 사용량의 구형 모델을 정리하여 최신 모델 지원에 집중한다"*고 밝혔다([gHacks](https://www.ghacks.net/2026/06/03/openai-upgrades-gpt-5-5-instant-and-confirms-retirement-of-o3-and-gpt-4-5-models/)).

## GitHub Copilot: Slack 진출, 하지만 105주째 하락

GitHub Copilot이 Slack 통합을 퍼블릭 프리뷰로 공개했다([GitHub Changelog](https://github.blog/changelog/2026-08-21-the-new-github-copilot-experience-in-slack/)). @GitHub 멘션으로 Slack 대화 내에서 변경 계획, 문제 조사, 코딩 작업 위임까지 가능하다. 동시에 Grok 4.6이 Copilot Pro/Pro+/Max/Business/Enterprise 전 플랜에 배포되기 시작했다([GitHub Changelog](https://github.com/features/copilot/whats-new)). xAI의 최신 추론 모델로 에이전틱 코딩과 복잡한 다단계 워크플로에 특화됐다. 그러나 Agent Plugins 1.0 GA, Slack 통합, 신규 모델 추가에도 불구하고 Copilot의 인기도 하락은 105주째를 기록하며, 9월 1일의 대규모 모델 폐기가 6일 앞으로 다가왔다.

## Antigravity: Gemini Enterprise 구독에 포함

Google이 Antigravity를 Gemini Enterprise 앱 구독에 포함시켰다([Google Cloud Blog](https://cloud.google.com/blog/products/ai-machine-learning/expanding-google-antigravity-for-enterprise-customers)). 관리자 예산 캡과 지출 통제를 갖춘 상태로 Enterprise 고객이 별도 비용 없이 접근할 수 있게 됐다. 또한 VS Code, JetBrains, Zed, Visual Studio 확장을 통해 데스크톱 앱 없이도 에이전트 대화, 인라인 diff 검토, 플랜 인스펙션이 가능해지면서 기존 워크플로에 자연스럽게 녹아들고 있다([The New Stack](https://thenewstack.io/google-antigravity-ide-extensions/)).

## 카운트다운: 7일 안에 4건

o3 ChatGPT 퇴장 **D-1**(내일 8/26), DALL·E GPT 은퇴 D-5(8/30), GPT-5.4 Codex 퇴출 D-6(8/31), Copilot 6개 모델 대폐기 D-7(9/1)([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). 이번 주는 AI 코딩 도구 역사상 가장 많은 모델이 동시에 퇴장하는 주간이 될 전망이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.241, 29주째 99 유지 |
| ChatGPT | 99 | — | o3 퇴장 D-1, Sol 20%+ 인하 지속 |
| Codex CLI | 99 | — | MCP 서버 폐기 후 안정 |
| Antigravity | 99 | — | Enterprise 구독 포함, 29주째 99 |
| Claude AI | 99 | — | $650억 런레이트, IPO 임박 |
| Cursor | 99 | — | Cloud Agents 강화, Origin 베타 확대 |
| Windsurf | 86 | — | Devin Local 안정화 |
| Aider | 68 | — | v0.86.2 이후 6개월+ 무릴리스 |
| Copilot | 1 | — | 105주 하락, Slack 진출에도 반등 없음 |
| Gemini CLI | 1 | — | 폐쇄 68일째 |

o3의 은퇴는 하나의 모델 교체가 아니라, AI 모델 세대 교체 속도가 얼마나 빨라졌는지를 상징한다. 출시 16개월 만에 퇴장하는 추론 모델 — 다음 주부터 개발자들은 GPT-5.6 Sol과 o4 계열로의 마이그레이션을 서둘러야 한다.

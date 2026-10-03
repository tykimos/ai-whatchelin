---
title: "Antigravity, Claude Opus 5.5·Sonnet 5.5 모델 통합 — Google이 Anthropic을 품다"
date: 2026-10-03
lang: ko
categories: [news]
tags: [antigravity, google, anthropic, github-copilot, hydrafusion, cursor, openai]
excerpt: "Google Antigravity가 Claude Opus 5.5와 Sonnet 5.5를 모델 피커에 추가하며 멀티 프로바이더 전략을 강화했다. GitHub Copilot은 코드 리뷰 API와 HydraFusion VS Code 확장으로 반격에 나선다."
---

Google Antigravity가 Claude Opus 5.5와 Sonnet 5.5를 모델 피커에 조용히 추가했다([Startup Fortune](https://startupfortune.com/google-antigravity-adds-anthropics-claude-opus-55-and-sonnet-55/)). Anthropic이 9월 22일과 28일에 각각 출시한 두 모델은 현재 Google AI Pro($19.99/월), Ultra 5x($99.99/월), Ultra 20x($199.99/월) 구독자만 사용할 수 있다. Google의 모델 페이지에는 이미 반영되었지만, 체인지로그에는 아직 공식 언급이 없어 "조용한 통합"이라는 평가가 나온다. 경쟁사 모델을 자사 코딩 플랫폼에 번들링하는 것은 Google이 Antigravity를 단일 모델 도구가 아닌 멀티 프로바이더 에이전트 플랫폼으로 자리매김하겠다는 의지를 보여준다.

## GitHub Copilot: 코드 리뷰 API GA + HydraFusion VS Code 확장

GitHub Copilot의 코드 리뷰 기능이 REST 및 GraphQL API를 통해 요청 가능해졌다([GitHub Blog](https://github.blog/changelog/2026-10-02-copilot-code-review-api-support-and-new-default-effort-level/)). 기본 리뷰 노력 수준이 "Balanced"로 변경되어, 기존 "Lite" 선택자를 제외한 모든 사용자에게 적용된다. Pro, Pro+, Max, Business, Enterprise 전 플랜에서 사용 가능하다. 한편 Project HydraFusion이 VS Code와 GitHub Copilot 앱으로 확장되었다([IT Brief](https://itbrief.co.uk/story/github-launches-hydrafusion-preview-for-copilot-coding)). CLI에서만 가능하던 멀티 모델 오케스트레이션이 이제 IDE에서도 작동하며, 캐스케이드(저비용 모델 초안 → 고성능 모델 검증) 및 크리틱(초안-리뷰-수정) 패턴을 런타임에 자동 선택한다.

## Cursor: 25점, 37일 연속 하락 — OpenAI 셧오프 D-40

Cursor의 인기 점수가 25까지 떨어지며 37일 연속 하락세를 이어갔다. OpenAI 셧오프까지 40일이 남았고, Compile 2026에서 발표된 Origin(GitHub 대항 호스팅), 모바일 앱, 자체 프런티어 모델 등이 하락을 반전시킬 카드로 남아 있지만, 당장의 효과는 보이지 않고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay 이후 안정, GPT-6.1 Sol 확산 중 |
| Claude Code | 99 | — | v2.1.287 Mods 정착, Government GA |
| Codex CLI | 99 | — | v0.160.0, 에이전트 커맨드 센터 |
| Antigravity | 99 | — | Claude Opus/Sonnet 5.5 통합 |
| Claude AI | 99 | — | Barclays 도입 확대 |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 사실상 휴면 |
| Cursor | 25 | ↓2 | 37일 연속 하락, OpenAI 셧오프 D-40 |
| GH Copilot | 13 | ↑2 | 코드 리뷰 API GA, HydraFusion 확장 |
| Gemini CLI | 1 | — | 종료 108일째 |

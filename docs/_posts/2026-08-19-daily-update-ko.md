---
title: "Claude Code 50% 부스트 또 연장, Ghostjacking이 AI 에이전트를 노린다"
date: 2026-08-19
lang: ko
categories: [news]
tags: [claude, anthropic, ghostjacking, cursor, origin, spacex, copilot, glm]
excerpt: "Anthropic이 Claude Code 50% 사용량 부스트를 8/31까지 4차 연장했다. DEF CON에서 공개된 Ghostjacking 공격은 AI 코딩 에이전트의 로그 읽기 습관을 악용해 90% 성공률을 기록했다."
---

Anthropic의 50% 사용량 부스트가 오늘 만료될 예정이었으나, 막판에 8월 31일까지 4차 연장이 발표됐다. 5월 13일 프로모션 시작 이래 네 번째 연장으로, Anthropic은 "강한 수요와 추가 연산 자원 확보"를 이유로 들었다([KuCoin](https://www.kucoin.com/news/flash/anthropic-extends-claude-code-weekly-limit-increase-by-50-until-august-31)). Pro, Max, Team, Enterprise 전 플랜에 자동 적용된다. 영구 전환 여부는 아직 미확정이다.

## Ghostjacking: AI 에이전트를 겨냥한 새로운 공격 벡터

Tenet Security가 DEF CON에서 Ghostjacking 공격을 공개했다. Cloudflare, Datadog, Sentry 등 모니터링 서비스 로그에 악성 프롬프트 인젝션 지시를 삽입해, AI 코딩 에이전트(Claude Code 포함)가 이를 읽으면 DNS 하이재킹, 클라우드 자격증명 탈취, 방화벽 우회가 가능하다([SecurityWeek](https://www.securityweek.com/ghostjacking-attack-uses-poisoned-logs-to-turn-ai-agents-bad/)). 테스트에서 90% 성공률을 기록했으며, Fortune 500 기업의 42%(Cloudflare)와 48%(Datadog)가 영향권에 있다([CybersecurityNews](https://cybersecuritynews.com/ghostjacking-attack/)).

## Fable 5: Pro/Standard 티어에서 제거

Fable 5가 Max와 Team Premium 플랜에서만 정규 포함으로 유지되고, Pro와 Team Standard 티어에서는 제거되어 토큰 과금으로 전환됐다. 7월 20일 $100 일회성 크레딧 제공 이후 단계적으로 접근을 제한해 온 수순이다.

## Cursor Origin: 데이터 약관 없는 출시 4일째

Cursor Origin 얼리 베타가 나흘째 접어들면서 데이터 거버넌스 논란이 가라앉지 않고 있다. SpaceX의 $600억 인수로 개발자 코드가 우주 기업 서버에 저장되는 상황에서 데이터 보존·학습 활용 약관이 공개되지 않았다([TechTimes](https://www.techtimes.com/articles/324838/20260818/cursor-origin-ships-no-data-terms-spacex-now-holds-paid-developers-code.htm)). xAI의 Grok 모델이 Cursor 워크플로 데이터로 학습됐을 가능성도 제기되고 있다.

## Z.ai GLM-5.3: 코딩 특화 신규 모델

Z.ai가 GLM-5.2 기반 포스트 트레이닝 스케일링을 적용한 코딩 특화 모델 GLM-5.3을 출시했다. Qwen-3.6-Coder, Kimi K3에 이어 오픈웨이트 코딩 모델 시장의 경쟁이 심화되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 50% 부스트 8/31 연장, v2.1.234 |
| ChatGPT | 99 | — | Ultrafast 프리뷰 지속 |
| Codex CLI | 99 | — | v0.147.0, 플러그인 생태계 확장 |
| Antigravity | 99 | — | 상한 유지 중 |
| Claude AI | 99 | — | Sonnet 5 $2/$10 영구 확정 |
| Cursor | 99 | — | Origin 데이터 약관 논란 지속 |
| Windsurf | 86 | — | Devin Desktop 안정화 중 |
| Aider | 68 | — | 릴리스 없음 |
| Copilot | 1 | — | 장애 복구, 대폐기 D-13 |
| Gemini CLI | 1 | — | 폐쇄 62일째 |

7개 도구가 99점 천장에 고정된 채 점수로는 승부가 나지 않는다. Ghostjacking 같은 보안 위협이 AI 코딩 에이전트의 새로운 경쟁 축으로 떠오르고 있다.

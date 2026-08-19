---
title: "Cursor Origin, 데이터 약관 없이 출시 — SpaceX가 개발자 코드를 쥐고 있다"
date: 2026-08-19
lang: ko
categories: [news]
tags: [cursor, origin, spacex, github, claude, anthropic, glm, copilot]
excerpt: "Cursor Origin이 명확한 데이터 약관 없이 출시되어 SpaceX가 유료 개발자의 코드를 보유하게 된 점이 논란이다. Anthropic 50% 사용량 부스트가 오늘 만료되고, Z.ai는 코딩 특화 GLM-5.3을 공개했다."
---

GitHub 8시간 장애의 먼지가 채 가라앉지 않은 가운데, 대안으로 떠오른 Cursor Origin에서 새로운 논란이 터졌다. SpaceX가 인수한 Cursor의 코드 호스팅 플랫폼이 명확한 데이터 이용 약관 없이 출시된 것이다.

## Cursor Origin: 데이터 약관 부재 논란

Cursor Origin 얼리 베타가 나흘째 접어든 가운데, Origin이 명확한 데이터 이용 약관 없이 출시되었다고 보도됐다([TechTimes](https://www.techtimes.com/articles/324838/20260818/cursor-origin-ships-no-data-terms-spacex-now-holds-paid-developers-code.htm)). SpaceX의 $600억 인수로 Cursor 인력은 SpaceXAI로 편입됐고, 유료 개발자들의 소스코드가 우주 기업의 서버에 저장되는 상황이다([TechCrunch](https://techcrunch.com/2026/08/15/spacex-officially-closes-its-cursor-acquisition/)). GitHub 장애 직후 "GitHub 대안"으로 주목받았으나, 데이터 거버넌스 문제가 채택의 걸림돌이 될 수 있다.

## Anthropic: 50% 사용량 부스트 오늘 만료

Anthropic의 50% 사용량 부스트가 오늘(8월 19일) 만료된다. Claude Code v2.1.234는 자동 세션 연속, 자격증명 유출 방지, GitLab MR 뱃지 기능으로 안정적인 업데이트를 이어가고 있다([Havoptic](https://www.havoptic.com/tools/claude-code)). 8월 16일 36분 장애 이후 이틀째 정상 운영 중이며, Compliance API가 Claude Code까지 확장되어 Enterprise 고객의 감사 및 eDiscovery를 지원한다.

## Z.ai GLM-5.3: 코딩 특화 신규 모델

Z.ai가 8월 18일 GLM-5.3을 출시했다. GLM-5.2 기반 모델에 포스트 트레이닝 스케일링을 적용한 코딩 특화 모델로, Qwen-3.6-Coder와 Kimi K3에 이어 오픈웨이트 코딩 모델 시장에 새 도전자가 합류했다.

## GitHub Copilot: 대폐기 D-13

GitHub의 9월 1일 대규모 모델 폐기까지 13일 남았다([GitHub Blog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). 17일 8시간 장애 이후 서비스는 정상 복구됐으나, Actions 90일 가동률이 99.33%로 떨어진 상태다([TechTimes](https://www.techtimes.com/articles/324820/20260818/github-actions-hit-three-nines-failure-one-august-outage-consumed-years-downtime-budget.htm)). MAI-Code-1-Flash는 9월 10일 별도 폐기 예정이며, Claude Sonnet 4.6는 연간 구독 개인 사용자에게만 유지된다([GitHub Blog](https://github.blog/changelog/2026-08-11-upcoming-deprecation-of-mai-code-1-flash/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.234, 50% 부스트 오늘 만료 |
| ChatGPT | 99 | — | Ultrafast 프리뷰 지속 |
| Codex CLI | 99 | — | v0.147.0, /import 명령 추가 |
| Antigravity | 99 | — | 상한 유지 중 |
| Claude AI | 99 | — | Sonnet 5 $2/$10 영구 확정 |
| Cursor | 99 | — | Origin 데이터 약관 논란 |
| Windsurf | 86 | — | Devin Desktop 안정화 중 |
| Aider | 68 | — | 릴리스 없음 |
| Copilot | 1 | — | 장애 복구, 대폐기 D-13 |
| Gemini CLI | 1 | — | 폐쇄 62일째 |

7개 도구가 99점 천장에 고정된 채 점수로는 승부가 나지 않는다. 이제 경쟁의 축은 인프라 안정성, 데이터 거버넌스, 과금 구조로 이동하고 있다.

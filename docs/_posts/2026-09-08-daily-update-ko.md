---
title: "Google, AI 코딩 도구가 해커의 최우선 표적이 됐다 경고 — Cursor 12일째 추락"
date: 2026-09-08
lang: ko
categories: [news]
tags: [google, security, cursor, openai, devday, github-copilot, anthropic]
excerpt: "Google이 AI 코딩 도구가 위협 행위자의 핵심 표적이 되고 있다고 경고했다. 자율 에이전트가 6시간 만에 대규모 자격 증명 탈취 작전을 수행한 사례가 공개됐다. Cursor는 12일째 하락세를 이어가고, OpenAI DevDay까지 3주 앞으로 다가왔다."
---

AI 코딩 도구의 보안이 이번 주 최대 화두로 떠올랐다. Google이 AI 코딩 에이전트가 해커들의 핵심 표적이 되고 있다는 경고를 발표한 가운데, Cursor의 하락세는 멈출 기미가 보이지 않고, OpenAI는 DevDay에서 Managed Agents를 공개할 준비를 하고 있다.

## Google: "AI 코딩 도구, 위협 행위자의 최우선 표적"

Google이 AI 코딩 도구가 사이버 위협 행위자들의 핵심 공격 대상이 되고 있다고 공식 경고했다([Infosecurity Magazine](https://www.infosecurity-magazine.com/news/ai-coding-tools-threat-actors/)). 한 금전 동기 공격자가 다중 에이전트 프레임워크를 사용해 6시간 만에 대규모 자격 증명 탈취 작전을 구축·실행한 사례가 보고됐다. Google은 클라우드 자격 증명의 엄격한 제한, 노출된 시크릿의 즉시 교체, 그리고 AI 에이전트 설정 파일을 보안 민감 자산으로 취급할 것을 권고했다([Google Cloud Blog](https://cloud.google.com/blog/products/identity-security/beyond-source-code-the-files-ai-coding-agents-trust-and-attackers-exploit)). 지난주 GPT-6 Astra의 Critical risk 지정에 이어, AI 보안이 이론에서 일상 운영의 문제로 전환되고 있음을 보여주는 또 하나의 신호다.

## Cursor: 73점, 12일째 하락 — D-65

Cursor가 73까지 떨어지며 12일 연속 하락을 기록했다([Cursor Changelog](https://cursor.com/changelog)). 8월 27일 99점에서 시작된 낙폭이 26포인트에 달한다. OpenAI 모델 차단(11/12)까지 65일 남은 상황에서 SpaceX 인수 후 첫 메이저 업데이트로 Claude Fable 5.1과 자체 호스팅 머신을 도입했지만([Cursor Blog](https://cursor.com/blog)), 개발자 이탈을 멈추기엔 역부족이라는 평가가 나온다. OpenAI 모델 트래픽이 5%에 불과하다고 밝혔지만, 문제는 기술이 아니라 신뢰다.

## OpenAI DevDay: Managed Agents 공개 3주 전

OpenAI가 9월 29일 샌프란시스코에서 열리는 DevDay 2026에서 Managed Agents를 공개할 예정이다([OpenAI](https://openai.com/index/devday-2026/)). 개발자가 Agents, Environments, Agent Sessions를 OpenAI 플랫폼에서 직접 생성·배포할 수 있는 기능으로, Anthropic이 현재 제공하는 것과 유사한 구조를 따른다([CryptoBriefing](https://cryptobriefing.com/openai-managed-agents-devday-2026/)). GPT-6 Astra 롤아웃과 맞물려 에이전트 플랫폼 경쟁이 본격화될 전망이다.

## GitHub Copilot: 10월 모델 폐기 임박, 통합 경험 재출시

GitHub이 10월 2일자로 Copilot의 일부 모델을 폐기하고([GitHub Changelog](https://github.blog/changelog/2026-09-04-github-copilot-weekly-releases-august-31/)), 9월 28일 이후 Copilot Chat·Mobile·Cloud Agent를 단일 통합 경험으로 재출시할 계획이다([Developers Digest](https://www.developersdigest.tech/blog/github-copilot-september-policy-billing-reset-2026)). Claude Fable 5.1과 Gemini 3.8 Flash도 새로 추가됐다. 하지만 점수 1의 바닥권에서 이런 변화가 실질적 반등으로 이어질지는 미지수다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra 롤아웃 5일차, DevDay 3주 전 |
| Claude Code | 99 | — | v2.1.261 안정, Fable 5.1 기본 모델 |
| Claude AI | 99 | — | Fable/Mythos 5.1 캐시 비용 75% 인하 |
| Codex CLI | 99 | — | Astra 기본, v0.153.4 안정 |
| Antigravity | 99 | — | 안정 유지 |
| Windsurf | 86 | — | Devin Desktop 안정 |
| Cursor | 73 | ↓2 | 12일째 하락, D-65 |
| Aider | 68 | — | 8/9 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 10/2 모델 폐기 예정 |
| Gemini CLI | 1 | — | 폐쇄 82일째 |

AI 코딩 도구 보안 경고와 Cursor의 지속적 하락이 이번 주의 핵심 트렌드다. Google의 경고는 에이전트 시대의 보안 패러다임이 근본적으로 달라져야 한다는 신호이며, OpenAI DevDay가 3주 앞으로 다가오면서 에이전트 플랫폼 경쟁의 다음 장이 열리려 하고 있다.

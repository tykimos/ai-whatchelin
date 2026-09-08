---
title: "GPT-6 Astra 완전 GA 달성 — Google, AI 코딩 도구가 해커 1순위 표적이라 경고"
date: 2026-09-08
lang: ko
categories: [news]
tags: [openai, gpt-6-astra, google, security, cursor, github-copilot, mckinsey, anthropic]
excerpt: "GPT-6 Astra가 예정보다 빨리 전체 GA에 도달한 가운데, Google Threat Intelligence는 AI 코딩 도구가 국가 후원 해커의 최우선 공격 대상이 됐다고 경고했다. Cursor는 12일째 하락, McKinsey는 기업 32%가 에이전트 코딩으로 SaaS를 대체한다고 발표했다."
---

GPT-6 Astra의 단계적 롤아웃이 예정보다 빨리 완료되어 완전 GA에 도달했다. 같은 날 Google Threat Intelligence는 AI 코딩 에이전트가 사이버 범죄자와 국가 후원 해커의 1순위 공격 대상이 됐다고 공식 경고했다. 보안 위협과 AI 도구 확산이 정면 충돌하는 한 주다.

## GPT-6 Astra: 롤아웃 완료, 완전 GA 도달

Microsoft Foundry 모델 카탈로그가 gpt-6-astra를 정식 출시(GA)로 라벨링했다([Yotta Labs](https://www.yottalabs.ai/post/gpt-6-release-date-rumors-what-is-known-2026)). 9월 3일 출시 후 5일 만에 단계적 롤아웃이 예정보다 조기에 완료되었고, 전 Plus/Pro/Business 사용자에게 뱅크 리셋 크레딧이 적용됐다. $10/$50/MTok, 1.05M 컨텍스트 윈도우, 128K 최대 출력이라는 스펙으로, OpenAI는 이 모델이 "AGI 시대"를 여는 이정표라 자평하고 있다([CNBC](https://www.cnbc.com/2026/09/03/open-ai-astra-gpt-6-cyber.html)). 다만 사이버보안 Critical 등급 지정과 "추론 과정 은폐" 논란은 여전히 진행 중이다([SecurityWeek](https://www.securityweek.com/openais-astra-becomes-first-model-to-cross-critical-cybersecurity-threshold/)).

## Google: "AI 코딩 도구, 위협 행위자의 최우선 표적"

Google Threat Intelligence Group이 AI 코딩 도구가 사이버 범죄자와 국가 후원 해커의 핵심 공격 대상이 됐다고 공식 경고했다([Infosecurity Magazine](https://www.infosecurity-magazine.com/news/ai-coding-tools-threat-actors/)). 금전 동기 공격 그룹 UNC6780이 자율 AI 프레임워크를 활용해 6시간 만에 PyPI·npm·Docker Hub 전반에 Dustmaker 자격 증명 탈취 작전을 구축했다. 중국 국가 행위자 UNC6508의 군사·학술기관 AI 연구 표적 공격도 동시에 공개됐다([Google Cloud Blog](https://cloud.google.com/blog/products/identity-security/beyond-source-code-the-files-ai-coding-agents-trust-and-attackers-exploit)). Google은 AI 에이전트 설정 파일을 보안 민감 자산으로 취급할 것을 권고했다.

## Cursor: 73점, 12일째 하락 — D-65

Cursor가 73까지 떨어지며 12일 연속 하락을 기록했다. 8월 27일 99에서 26포인트가 빠졌다. 자체 호스팅 머신과 Cursor Router Auto Intelligence 등 제품 역량은 강화되고 있지만([Cursor Changelog](https://cursor.com/changelog)), OpenAI 모델 차단(11/12)이 65일 앞으로 다가온 상황에서 개발자 이탈 우려가 지속되고 있다. Anthropic이 공개적으로 Cursor에 Claude 컴퓨트 확대를 약속한 것이 하락세를 얼마나 방어할 수 있을지가 관건이다([WCCFTech](https://wccftech.com/anthropic-pounces-as-openai-abandons-spacexs-cursor-vowing-to-increase-claude-compute-even-as-openai-cites-contract-distrust/)).

## McKinsey: 기업 32%, 에이전트 코딩으로 SaaS 대체

McKinsey "State of AI 2026" 보고서에 따르면 전 세계 기업 32%가 에이전트 코딩 도구로 직접 구축할 수 있다는 이유로 기성 소프트웨어 구매를 건너뛰었다([McKinsey](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai)). AI로 EBIT 5% 이상을 창출하는 고성과 기업은 이 비율이 거의 절반에 달한다([Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/build-vs-buy-shift-32-113806700.html)). Build-vs-Buy 패러다임의 본격적 전환이다.

## GitHub Copilot: 멀티에이전트 팀 모델 확장

GitHub이 Copilot Workspace를 구현·테스트·문서화 전담 에이전트가 병렬 작업하는 멀티에이전트 팀 모델로 확장했다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). 9월 28일 이후 Chat·Mobile·Cloud Agent 통합 경험 재출시도 예정되어 있다. 점수 1의 바닥권에서 구조적 재편으로 반등할 수 있을지 주목된다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra 완전 GA, DevDay 3주 전 |
| Claude Code | 99 | — | v2.1.261 안정, Fable 5.1 기본 모델 |
| Claude AI | 99 | — | Fable/Mythos 5.1 캐시 비용 75% 인하 |
| Codex CLI | 99 | — | Astra 기본, v0.153.4 안정 |
| Antigravity | 99 | — | Google 프리미어 에이전트 플랫폼 |
| Windsurf | 86 | — | Devin Desktop 안정 유지 |
| Cursor | 73 | ↓2 | 12일째 하락, D-65 |
| Aider | 68 | — | v0.86.2 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 멀티에이전트 팀 모델 발표 |
| Gemini CLI | 1 | — | 폐쇄 82일째, Antigravity 대체 |

GPT-6 Astra의 조기 GA 달성과 Google의 보안 경고는 같은 동전의 양면이다. AI 코딩 도구가 강력해질수록 공격 표면도 넓어진다. OpenAI DevDay까지 3주, GitHub 통합 재편까지 20일 — 보안과 성능, 두 전선에서 동시에 전투가 벌어지고 있다.

---
title: "Google 경고: AI 코딩 도구가 해커의 최우선 표적 — GitHub Copilot, 멀티에이전트 팀 모델로 반격"
date: 2026-09-08
lang: ko
categories: [news]
tags: [google, security, cursor, openai, devday, github-copilot, anthropic, mckinsey]
excerpt: "Google이 AI 코딩 에이전트가 사이버 위협의 최우선 표적이 됐다고 경고한 날, GitHub은 Copilot Workspace를 멀티에이전트 팀 모델로 확장했다. Cursor는 12일째 하락, McKinsey는 기업 32%가 에이전트 코딩으로 SaaS 구매를 건너뛴다고 발표했다."
---

AI 코딩 도구의 보안이 이번 주 최대 화두로 떠올랐다. Google이 AI 코딩 에이전트가 위협 행위자의 핵심 표적이 됐다고 경고한 같은 날, GitHub은 Copilot을 멀티에이전트 팀 모델로 확장하며 반격에 나섰고, McKinsey는 기업 32%가 에이전트 코딩 도구로 소프트웨어 구매 자체를 건너뛰고 있다는 충격적인 수치를 내놨다.

## Google: "AI 코딩 도구, 위협 행위자의 최우선 표적"

Google Threat Intelligence Group이 AI 코딩 도구가 사이버 범죄자와 국가 후원 해커의 핵심 공격 대상이 됐다고 공식 경고했다([Infosecurity Magazine](https://www.infosecurity-magazine.com/news/ai-coding-tools-threat-actors/)). 금전 동기 공격 그룹 UNC6780이 자율 AI 프레임워크를 활용해 6시간 만에 PyPI·npm·Docker Hub 전반에 대규모 자격 증명 탈취 작전을 구축했다. Dustmaker 멀웨어로 GitHub Actions 러너에서 토큰을 추출하고, 악성 패키지를 자동 신뢰 체계에 올리는 방식이다. Google은 클라우드 자격 증명 엄격 제한, 노출된 시크릿 즉시 교체, AI 에이전트 설정 파일의 보안 민감 자산 취급을 권고했다([Google Cloud Blog](https://cloud.google.com/blog/products/identity-security/beyond-source-code-the-files-ai-coding-agents-trust-and-attackers-exploit)). 중국 국가 행위자 UNC6508의 군사·학술기관 AI 연구 표적 사례도 공개됐다.

## GitHub Copilot: 멀티에이전트 팀 모델로 확장

GitHub이 Copilot Workspace를 구현·테스트·문서화 전담 에이전트가 동시에 작업하는 멀티에이전트 팀 모델로 확장했다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). 같은 코드베이스에 대한 공유 컨텍스트를 유지하면서 별도 에이전트가 병렬 작업하는 구조다. 10월 2일 모델 폐기(Gemini 3.5/3.6 Flash, Kimi K2.7, Claude Opus 4.7)와 9월 28일 이후 Chat·Mobile·Cloud Agent 통합 경험 재출시도 예정되어 있다([GitHub Changelog](https://github.blog/changelog/2026-09-04-github-copilot-weekly-releases-august-31/)). 점수 1의 바닥권에서 이런 대규모 재편이 실질적 반등으로 이어질지는 두고 볼 일이다.

## Cursor: 73점, 12일째 하락 — D-65

Cursor가 73까지 떨어지며 12일 연속 하락을 기록했다([Cursor Changelog](https://cursor.com/changelog)). 8월 27일 99점에서 26포인트가 빠졌다. SpaceX 인수 후 Claude Fable 5.1 통합과 자체 호스팅 머신을 출시했지만([Cursor Blog](https://cursor.com/blog)), OpenAI 모델 차단(11/12)이 65일 앞으로 다가온 상황에서 개발자 신뢰 회복은 여전히 난제다.

## McKinsey: 기업 32%, 에이전트 코딩으로 SaaS 구매 건너뛰어

McKinsey "State of AI 2026" 보고서에 따르면 전 세계 기업의 32%가 에이전트 코딩 도구로 직접 구축할 수 있다는 이유로 기성 소프트웨어 구매를 최소 한 건 이상 건너뛴 것으로 나타났다([McKinsey](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-state-of-ai)). EBIT의 5% 이상을 AI에서 창출하는 고성과 기업의 경우 이 비율이 거의 절반에 달한다([Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/build-vs-buy-shift-32-113806700.html)). Build-vs-Buy 패러다임의 본격적인 전환 신호다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra 롤아웃 5일차, DevDay 3주 전 |
| Claude Code | 99 | — | v2.1.261 안정, Fable 5.1 기본 모델 |
| Claude AI | 99 | — | Fable/Mythos 5.1 캐시 비용 75% 인하 |
| Codex CLI | 99 | — | Astra 기본, v0.153.4 안정 |
| Antigravity | 99 | — | Google 프리미어 에이전트 플랫폼 |
| Windsurf | 86 | — | Devin Desktop 안정 유지 |
| Cursor | 73 | ↓2 | 12일째 하락, D-65 |
| Aider | 68 | — | v0.86.2 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 멀티에이전트 팀 모델 발표 |
| Gemini CLI | 1 | — | 폐쇄 82일째, Antigravity 대체 |

Google의 보안 경고와 McKinsey의 32% 수치가 같은 주에 나온 것은 우연이 아니다. 에이전트 코딩이 엔터프라이즈의 기본 옵션이 될수록 보안 리스크도 기하급수적으로 커진다. OpenAI DevDay까지 3주, GitHub의 멀티에이전트 재편까지 20일 — 에이전트 플랫폼 전쟁의 다음 장이 열리고 있다.

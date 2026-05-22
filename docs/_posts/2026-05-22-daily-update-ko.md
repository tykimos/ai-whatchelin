---
title: "OpenAI IPO 초읽기 — $8500억 밸류로 9월 상장 시동, Antigravity 이중 위기, Cursor 3.5 출시"
date: 2026-05-22
lang: ko
categories: [news]
tags: [openai, ipo, antigravity, copilot, codex-cli, grok, cursor, socket, manus]
excerpt: "OpenAI가 IPO 비밀 신청서를 이번 주 내로 제출할 준비를 하고 있다. Antigravity는 롤백+속도 제한 이중 위기, Cursor는 3.5를 출시했고, 중국이 Meta의 Manus 인수를 차단했다."
---

OpenAI가 기업공개(IPO)로 향하는 마지막 관문에 도달했다. $8,500억 이상 밸류에이션으로 9월 상장을 목표로 비밀 신청서 제출이 임박한 가운데, AI 코딩 도구 시장에서는 Antigravity의 끝 모를 롤백 사태와 Copilot의 18주 연속 하락이 이어지고 있다.

## OpenAI, IPO 비밀 신청서 이번 주 제출 예정 — $8500억+ 밸류에이션

OpenAI가 이번 주 내로 IPO 비밀 신청서를 SEC에 제출할 준비를 하고 있으며, 9월 상장을 목표로 한다([CNBC](https://www.cnbc.com/2026/05/20/openai-ipo-filing.html)). Goldman Sachs와 Morgan Stanley가 주간사를 맡았다. 5월 19일 Musk v. Altman 소송에서 배심원 만장일치 기각이 나오면서 상장 경로가 명확해졌다([TechCrunch](https://techcrunch.com/2026/05/20/openai-barrels-toward-ipo-that-may-happen-in-september/)). 사모 시장에서 $8,500억 밸류에이션을 인정받은 상태로, 상장 시 역대 최대 규모 AI 기업 IPO가 될 전망이다.

## Antigravity 이중 위기 — 롤백 4일째 + 속도 제한 폭발

Google의 Antigravity 2.0 자동 업데이트 참사가 4일째 계속되고 있다([Google AI Developers Forum](https://discuss.ai.google.dev/t/antigravity-2-0-a-rushed-un-tested-release/145483/6)). 설정 경로 불일치로 확장·설정이 통째로 삭제되며 v1.23.2로 수동 롤백하는 개발자가 속출 중이다. I/O 당일 62까지 급등했던 점수가 53까지 추락 — 초기 급등분의 대부분이 증발했다.

롤백 사태에 더해 속도 제한 위기까지 터졌다. Google이 하루에 두 번이나 Antigravity 속도 제한을 3배로 상향해야 했다([9to5Google](https://9to5google.com/2026/05/21/google-has-tripled-gemini-usage-limits-for-antigravity-twice/)). Gemini 3.5 Flash가 리소스를 훨씬 많이 소모하면서, 단일 프롬프트 하나로 5시간 한도의 수 퍼센트를 소비한다. Google은 이번 주에 전체 사용자 쿼터를 두 번 초기화했다. Gemini CLI → Antigravity CLI 전환 기한(6/18)까지 27일 남았다.

## Copilot 18주 연속 하락 65 — 사용량 과금 D-10

GitHub Copilot이 65로 18주 연속 하락했다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). 6월 1일 사용량 기반 과금 전환까지 10일. 지난주 GPT-5.3-Codex가 기본 모델로 강제 전환되고 웹 채팅에서 Gemini 모델이 삭제되면서 커뮤니티 불만이 누적되고 있다. flex 할당제로의 전환이 사실상 가격 인상이라는 인식이 확산 중이다.

## Codex CLI Goal 모드 정식 전환 — 수시간 비감독 작업 가능

Codex CLI의 Goal 모드가 실험 단계를 졸업하고 정식 기능으로 전환됐다([OpenAI Codex Changelog](https://developers.openai.com/codex/changelog)). 앱·IDE 확장·CLI 전체에서 수시간~수일 단위의 비감독 목표 추적 작업이 가능해졌다. TUI에도 세션 제어 강화와 데이터 기반 서비스 티어 명령어가 추가됐다.

## Grok Build 일일 업데이트 모드 + xAI Connectors

Elon Musk가 xAI의 Grok Build 일일 업데이트 보고서 공개를 발표했다([Engadget](https://www.engadget.com/2173482/xai-coding-agent-grok-build/)). SuperGrok Heavy($300/월) 베타 전용으로, 8개 병렬 에이전트와 2M 토큰 컨텍스트를 지원한다. 동시에 xAI Connectors가 Grok Web에 출시 — SharePoint·Outlook·OneDrive·Google Workspace·Notion·GitHub·Linear을 깊이 통합한다.

## Cursor 3.5 출시 — Automations + /multitask 강화

Cursor가 3.5 버전을 출시했다([cursor.com/changelog](https://cursor.com/changelog)). Automations로 반복 에이전트 워크플로를 스케줄링할 수 있고, Jira 통합, 전체화면 Tabs, Compact Chats, /multitask 병렬 에이전트 개선, 새 PR 리뷰 경험, BugBot 노력도 레벨이 추가됐다. Cursor SDK도 퍼블릭 베타로 공개되어 프로그래밍 방식의 에이전트 호출이 가능해졌다.

## 중국, Meta의 Manus $20억 인수 차단

중국 반독점 규제 당국이 Meta의 AI 에이전트 스타트업 Manus $20억 인수를 국가 안보를 이유로 차단했다([Reuters](https://www.reuters.com/technology/china-blocks-meta-manus-acquisition/)). 중국이 해외 AI 기업의 자국 AI 스타트업 인수를 국가 차원에서 금지한 최초 사례로, AI 지정학 긴장이 한층 고조됐다.

## AI 보안 시장 급성장 — Socket $10억 유니콘

Socket이 $10억 밸류에이션에 $6천만을 투자받았다([TechCrunch](https://techcrunch.com/2026/05/22/socket-raises-60m-ai-supply-chain-security/)). AI 생성 코드 대량 배포에 따른 소프트웨어 공급망 보안 리스크 해결에 초점을 맞춘 최초의 유니콘이다. 별도로 Intuit이 AI 제품 전환을 위해 3,000명 이상을 감원한다고 발표해 AI 시대의 고용 재편이 가속화되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | OpenAI IPO 신청서 임박 |
| Claude Code | 98 | — | CwC London 종료 후 안정 |
| Cursor | 96 | — | Composer 2.5 안정화 |
| Claude AI | 94 | — | CNBC 1위 여파 지속 |
| Codex CLI | 86 | ↑1 | Goal 모드 정식 전환 |
| Gemini CLI | 85 | ↓1 | Antigravity CLI 전환 불확실성 |
| Windsurf | 81 | — | Devin Terminal 안정 |
| Aider | 68 | — | 안정, 42K+ Stars |
| Copilot | 65 | ↓1 | 18주 연속 하락, 과금 D-10 |
| Antigravity | 53 | ↓2 | 롤백 4일째, 포럼 반발 지속 |

---
title: "Anthropic, Stainless 인수 협상에 Claude Code 한도 50% 인상 — 에이전트 인프라 전쟁 가속"
date: 2026-05-14
lang: ko
categories: [news]
tags: [claude-code, anthropic, cursor, github-copilot, gemini-cli, aws-kiro, openai, stainless]
excerpt: "Anthropic이 OpenAI·Google용 SDK를 만드는 Stainless를 $3억+에 인수 협상 중이다. 동시에 Claude Code 주간 한도를 50% 올리며 에이전트 생태계 장악을 본격화한다."
---

Anthropic이 경쟁사의 핵심 인프라를 노렸다. The Information에 따르면 Anthropic은 API 스펙으로부터 프로덕션 수준의 SDK를 자동 생성하는 Stainless를 $3억 이상에 인수하는 협상을 진행 중이다([The Information](https://www.theinformation.com/articles/anthropic-talks-buy-developer-tools-startup-used-by-openai-google)). Stainless는 현재 OpenAI, Google, Cloudflare, Meta의 공식 SDK를 만들고 있어, 인수가 성사되면 Anthropic이 경쟁 플랫폼의 개발자 채널에 대한 지렛대를 확보하게 된다([Open Source For You](https://www.opensourceforu.com/2026/05/anthropic-eyes-300m-stainless-acquisition-to-strengthen-ai-infrastructure/)).

## Claude Code: 한도 인상 + v2.1.141

Claude Code의 주간 사용 한도가 Pro, Max, Team, Enterprise 전 플랜에서 50% 인상됐다. 7월 13일까지 적용되며, 5월 6일의 시간당 한도 2배 인상에 이은 두 번째 대폭 확대다([Anthropic](https://www.anthropic.com/news/higher-limits-spacex)). 같은 날 v2.1.141이 릴리스되어 훅·플러그인 옵션 확장, 터미널 알림 지원, 워크스페이스 신원 연합(Identity Federation)이 추가됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 11일째 98점을 유지하며 ChatGPT와 공동 1위를 이어가고 있다.

## Cursor: 클라우드 에이전트 개발 환경 출시

Cursor가 클라우드 에이전트를 위한 '개발 환경(Development Environments)' 인프라를 정식 출시했다([Cursor Changelog](https://cursor.com/changelog/05-13-26)). 멀티레포 지원, Dockerfile 기반 구성에서 레이어 캐싱으로 빌드 70% 가속, 에이전트 주도 환경 검증, 버전별 롤백, 감사 로깅, 스코프드 시크릿이 포함됐다([Cursor Blog](https://cursor.com/blog/cloud-agent-development-environments)). 에이전트가 '코드만 짜는 봇'에서 '인프라를 스스로 세팅하는 동료'로 진화하는 신호다. 95점으로 1점 상승.

## GitHub Copilot: Agent REST API + 과금 D-17

Copilot이 클라우드 에이전트 작업을 프로그래밍 방식으로 시작할 수 있는 REST API를 공개 미리보기로 출시했다([GitHub Blog](https://github.blog/changelog/2026-05-13-start-copilot-cloud-agent-tasks-via-the-rest-api/)). Business/Enterprise 사용자가 PAT·OAuth 토큰으로 리팩토링 분산, 릴리스 준비, 리포 초기화를 자동화할 수 있다. 한편 6월 1일 사용량 기반 과금 전환까지 D-17, 4월 사용량 보고서 다운로드가 시작되며 전환 비용을 미리 확인할 수 있게 됐다([TechSifted](https://techsifted.com/posts/github-copilot-changes-may-2026/)). 73점에서 횡보 — API 출시는 긍정적이나 과금 불확실성이 상쇄.

## AWS Kiro: SMT 솔버로 '코드 전에 증명'

AWS가 Kiro에 'Spec Check' 기능을 추가했다. SMT 솔버를 사용해 요구사항 간 모순이 없음을 코드 작성 전에 수학적으로 증명한다([GeekWire](https://www.geekwire.com/2026/aws-targets-ai-slop-with-new-spec-check-in-kiro-coding-tool-amid-scrutiny-of-agent-reliability/)). 병렬 작업 실행(대형 프로젝트 75% 가속)과 Quick Plan 모드도 함께 출시됐다([SiliconANGLE](https://siliconangle.com/2026/05/12/aws-kiro-accelerates-software-development-proving-code-correctness-gets-work/)). "AI가 만든 코드를 사람이 검토"하는 패러다임에서 "코드 이전에 스펙 자체를 검증"하는 접근은 의미 있는 전환이다.

## Google I/O D-5: Gemini 4 카운트다운

I/O가 5일 앞으로 다가왔다. Gemini CLI는 v0.43.0-preview에서 LocalSubagentProtocol과 RemoteSubagentProtocol을 도입해 서브에이전트 아키텍처의 기반을 깔아두었고([GitHub](https://github.com/google-gemini/gemini-cli/releases)), 5월 19일 키노트에서 Gemini 4(ARC-AGI2 84.6%)가 공개되면 이 아키텍처가 즉시 실전 투입될 전망이다([TechRound](https://techround.co.uk/tech/gemini-4-ai-glasses-and-a-new-os-why-google-i-o-2026-could-be-the-most-important-developer-event-of-the-year/)). Gemini CLI 75점으로 1점 상승.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 안정 |
| Claude Code | 98 | — | v2.1.141, 주간 한도 50%↑, 11일째 98 |
| Cursor | 95 | ↑1 | 클라우드 에이전트 개발 환경 출시 |
| Claude AI | 92 | — | Cowork GA 안정화 |
| Codex CLI | 81 | — | alpha 빌드만, 안정판 대기 |
| Windsurf | 78 | — | 조용한 하루 |
| Gemini CLI | 75 | ↑1 | I/O D-5, 서브에이전트 아키텍처 |
| GitHub Copilot | 73 | — | Agent REST API, 과금 D-17 |
| Aider | 68 | — | 안정 |
| Antigravity | 48 | ↓1 | 소프트 디프리케이션 루머 |

Anthropic의 Stainless 인수 협상은 단순한 M&A가 아니다. SDK 인프라를 장악하면 경쟁사의 개발자 경험까지 영향력 아래 둘 수 있다. 한편 Cursor와 Copilot이 같은 날 에이전트 인프라(개발 환경 vs REST API)를 내놓은 건, 에이전트 전쟁의 전선이 '코드 생성'에서 '에이전트 운영 인프라'로 이동했음을 보여준다.

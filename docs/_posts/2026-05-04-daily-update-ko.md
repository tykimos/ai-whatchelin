---
title: "Anthropic·OpenAI, 같은 날 월가와 합작법인 — AI 컨설팅 전쟁 개막"
date: 2026-05-04
lang: ko
categories: [news]
tags: [anthropic, openai, cursor, copilot, claude-code, enterprise, cursor-sdk]
excerpt: "Anthropic $15억, OpenAI $100억 — 같은 날 월가 PE와 엔터프라이즈 합작법인을 발표하며 AI 코딩 시장이 컨설팅 전쟁으로 확전됐다."
---

AI 코딩 도구 기업들이 더 이상 소프트웨어만 파는 것에 만족하지 않는다. 5월 4일, Anthropic과 OpenAI가 같은 날 월가 PE 펌들과 엔터프라이즈 합작법인을 발표하며, McKinsey와 Deloitte가 지배하던 기업 컨설팅 시장에 정면으로 뛰어들었다.

## Anthropic, $15억 엔터프라이즈 AI 서비스 합작법인

Anthropic이 Blackstone, Goldman Sachs, Hellman & Friedman과 손잡고 $15억 규모의 AI 서비스 합작법인을 설립한다([CNBC](https://www.cnbc.com/2026/05/04/anthropic-goldman-blackstone-ai-venture.html)). Anthropic, Blackstone, H&F가 각각 $3억을 출자하고, Goldman Sachs가 약 $1.5억을 투입한다([Fortune](https://fortune.com/2026/05/04/anthropic-claude-consulting-industry-joint-venture-blackstone-goldman-sachs/)). 핵심 전략은 엔지니어를 기업에 직접 파견해 워크플로우를 재설계하고 Claude를 통합하는 것이다.

## OpenAI, $100억 "The Deployment Company" 확정

같은 날 OpenAI도 TPG, Bain Capital, Brookfield, SoftBank와 $100억 규모 합작법인 "The Deployment Company"를 확정했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-05-04/openai-finalizes-10-billion-joint-venture-with-pe-firms-to-deploy-ai)). 투자자들에게 5년간 연 17.5% 수익을 보장하며, Palantir 스타일로 OpenAI 엔지니어를 고객사에 직접 배치한다([TechCrunch](https://techcrunch.com/2026/05/04/anthropic-and-openai-are-both-launching-joint-ventures-for-enterprise-ai-services/)).

## Cursor SDK 퍼블릭 베타 — 에디터에서 플랫폼으로

Cursor가 TypeScript SDK(`@cursor/sdk`)를 퍼블릭 베타로 출시했다([cursor.com](https://cursor.com/blog/typescript-sdk)). CI/CD 파이프라인이나 백엔드 서비스에서 프로그래밍 방식으로 코딩 에이전트를 생성할 수 있으며, 샌드박스 클라우드 VM에서 실행된다. Faire, Rippling, Notion이 얼리 어답터로 참여 중이다([DevOps.com](https://devops.com/cursors-new-sdk-turns-ai-coding-agents-into-deployable-infrastructure/)). 에디터에서 플랫폼으로의 전환을 선언한 셈이다.

## Claude Code v2.1.126 업데이트 + ultrareview 무료 체험 만료

Claude Code가 v2.1.126으로 업데이트되면서 API 게이트웨이용 `/model` 피커, `project purge` 명령어, MCP 서버 자동 재시도(3회)가 추가됐다([code.claude.com](https://code.claude.com/docs/en/changelog)). 한편 Pro/Max 구독자에게 제공됐던 ultrareview 무료 체험 3회가 5월 5일 만료된다([code.claude.com](https://code.claude.com/docs/en/ultrareview)). 이후 건당 $5-$20이 과금된다.

## Amazon Q Developer → Kiro 전환 본격화

AWS가 Amazon Q Developer Free Tier 신규 가입을 5월 15일부터 차단한다([AWS DevOps Blog](https://aws.amazon.com/blogs/devops/amazon-q-developer-end-of-support-announcement/)). Q Developer Pro에서 Opus 4.6은 5/29에 제거되고, Opus 4.7을 포함한 최신 모델은 Kiro 전용이 된다. Q IDE 플러그인 완전 종료는 2027년 4월 30일이지만, 전환 신호는 분명하다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | GPT-5.5 + Deployment Company, 정상 유지 |
| Claude Code | 96 | ↑2 | 엔터프라이즈 JV + v2.1.126, 최고치 갱신 |
| Cursor | 90 | — | SDK 베타로 플랫폼 전환, 인수 불확실성 상쇄 |
| Claude AI | 90 | ↑2 | Opus 4.7 확산 + 엔터프라이즈 JV |
| GitHub Copilot | 82 | ↓3 | Code Review Actions 분 과금 추가, 하락 지속 |
| Windsurf | 76 | ↑2 | 2.0 안정화, Devin 통합 정착 |
| Codex CLI | 75 | ↑3 | AWS Bedrock 출시, 생태계 확장 |
| Aider | 68 | — | 안정적, 39K+ GitHub 스타 |
| Gemini CLI | 67 | ↑2 | v0.40.1 패치, CVSS 10.0 후속 조치 진행 |
| Antigravity | 48 | ↓2 | 뉴스 부재, 지속적 하락 |

Anthropic과 OpenAI가 같은 날 엔터프라이즈 합작법인을 발표한 것은 AI 코딩 도구 전쟁이 소프트웨어 판매를 넘어 기업 컨설팅 시장으로 확전됐음을 의미한다. Cursor의 SDK 베타 출시는 에디터 중심에서 플랫폼 중심으로의 전환을 보여주며, Amazon Q → Kiro 전환은 AWS 생태계의 구조 변화를 예고한다.

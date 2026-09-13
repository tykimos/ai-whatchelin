---
title: "Claude Code 내일부터 주간 한도 17% 삭감 — 여름 프로모 종료, '25% 인상'의 함정"
date: 2026-09-13
lang: ko
categories: [news]
tags: [claude-code, anthropic, openai, agents-api, github-copilot, cursor, ai-supply-chain]
excerpt: "Anthropic이 Claude Code 50% 여름 부스트를 내일(9/14) 종료하고 '영구 25% 인상'으로 전환한다. 수학적으로는 현재 대비 17% 삭감이다."
---

Anthropic이 Claude Code의 50% 여름 부스트를 내일(9월 14일) 종료하고 '영구 25% 인상'으로 전환한다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)). Anthropic은 5월 이전 기준 대비 25% 증가라고 설명하지만, 현재 50% 부스트를 누리던 사용자에게는 실질적으로 16.7% 삭감이다([MindStudio](https://www.mindstudio.ai/blog/claude-code-weekly-rate-limit-changes)). Pro·Max·Team·Enterprise 좌석 기반 전 플랜이 영향을 받으며, 5시간 세션 한도는 변동 없다([explainx.ai](https://explainx.ai/blog/anthropic-claude-code-limits-17-percent-cut-september-2026-august-2026)).

## OpenAI Agents API: Codex 하네스 개방

OpenAI가 9/10 Agents API를 퍼블릭 베타로 공개하며 Codex의 관리형 하네스를 개발자에게 개방했다([OpenAI](https://openai.com/index/introducing-the-agents-api/)). 세션 오케스트레이션·컨텍스트 압축·크래시 복구를 API 한 번으로 해결하며, OpenAI 호스팅 샌드박스 외에 Cloudflare·Vercel·DigitalOcean 등 10개 파트너 환경을 지원한다([MarkTechPost](https://www.marktechpost.com/2026/09/10/openai-launches-the-agents-api-in-public-beta-putting-the-codex-harness-behind-one-api-call/)). 별도 플랫폼 수수료 없이 모델 토큰·도구 사용 비용만 과금된다.

## GitHub Copilot: 통합 경험 9/28, HydraFusion 실험

GitHub Copilot이 9월 28일부터 Chat·Mobile·클라우드 에이전트를 단일 통합 경험으로 재출시한다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 주의할 점: 채팅 데이터 보존이 28일→계정 수명 전체로 확대되며, 코드 리뷰 기본값이 Lite에서 Balanced로 변경돼 AI 크레딧 소비가 증가할 수 있다([Developers Digest](https://www.developersdigest.tech/blog/github-copilot-september-policy-billing-reset-2026)). 이번 주에는 Jira 연동과 Project HydraFusion(시맨틱 모델 라우팅) 실험도 공개됐다.

## AI 에이전트 스킬 공급망 위협: 17,800개 의심 애드온

AIR의 조사에서 142,836개 라이브 스킬 중 17,822개(12.4%)가 검증되지 않은 외부 소스에서 지시를 받는 것으로 나타났다([HiddenLayer](https://www.hiddenlayer.com/research/the-next-ai-supply-chain-risk-malicious-skills-in-agentic-ai)). Anthropic·OpenAI를 사칭하는 스킬이 발견됐으며, 최소 1개는 설치 후 임의 코드 실행이 가능했다([TechCrunch](https://techcrunch.com/2026/09/01/air-raises-50m-to-help-companies-vet-the-skills-and-add-ons-ai-agents-use/)). AIR는 이 문제 해결을 위해 $5,000만 시리즈 B를 유치했다.

## Cursor: Projects 5일차, 하락 21일째

Cursor Projects 베타가 5일차에 접어들었지만 하락세는 멈추지 않았다([Cursor Changelog](https://cursor.com/changelog/projects)). OpenAI 모델 차단(11/12)까지 D-60이며, SpaceX 인수 후 독자 모델 전략 수립이 갈수록 시급하다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6-Astra 완전 배포 완료 |
| Claude Code | 99 | — | 내일부터 주간 한도 17% 삭감 |
| Claude AI | 99 | — | 위협 보고서 여파 지속 |
| Codex CLI | 99 | — | Agents API 퍼블릭 베타 D+3 |
| Antigravity | 99 | — | 28주째 99 유지 |
| Windsurf | 87 | — | 엔터프라이즈 포지셔닝 안정 |
| Aider | 68 | — | 오픈소스 1위 유지 |
| Cursor | 66 | ↓1 | Projects 5일차, 21일 연속 하락 |
| GH Copilot | 1 | — | 바닥, 통합 경험 D-15 |
| Gemini CLI | 1 | — | 셧다운 89일차 |

Claude Code의 한도 삭감은 '인상'이라는 프레이밍에도 불구하고 커뮤니티에서 실질 삭감으로 받아들여지고 있다. Anthropic의 매출 런레이트가 $650억에 달하는 상황에서 비용 최적화 시그널로 해석된다.

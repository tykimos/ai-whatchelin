---
title: "Cursor, 16일째 하락 속 'Projects' 베타로 반격 — 멀티에이전트 코디네이터 공개"
date: 2026-09-11
lang: ko
categories: [news]
tags: [cursor, claude-code, codex-cli, anthropic, openai, chatgpt]
excerpt: "Cursor가 수천 개의 서브에이전트를 조율하는 'Projects' 코디네이터 베타를 전격 공개했다. 16일 연속 하락세를 돌릴 수 있을까. Claude Code v2.1.268과 Codex CLI도 대형 업데이트를 동시 출격시켰다."
---

Cursor가 SpaceX 인수 이후 가장 야심 찬 기능을 꺼냈다. 어제(9/10) 베타 배포를 시작한 'Projects'는 수천 개의 서브에이전트를 조율하는 코디네이터 에이전트를 중심으로, 수개월에 걸친 컨텍스트를 유지하며 클라우드에서 병렬 실행한다([Cursor Blog](https://cursor.com/blog)). Slack·PR·스케줄 등 외부 시그널 구독까지 지원되며, Cursor 내부 데이터에 따르면 주력 Projects 사용자는 PR 머지 횟수가 6배 증가했다([Releasebot](https://releasebot.io/updates/cursor)). 16일 연속 하락(99→68) 속에서 이번 발표가 반전의 계기가 될지 주목된다.

## Cursor: Self-Hosted Machines + Projects, 이중 반격

9/2에 출시된 Self-Hosted Machines와 합쳐지면, 에이전트 루프/추론은 Cursor 클라우드에서, 도구 실행은 사용자 네트워크에서 돌리는 하이브리드 아키텍처가 완성된다([Cloudflare Changelog](https://developers.cloudflare.com/changelog/post/2026-09-02-cursor-cloud-agents/)). Lambda·Cloudflare·Coder·Daytona·E2B·Modal·Namespace·Vercel 8개 샌드박스 백엔드를 지원한다. OpenAI 모델 차단(11/12)까지 62일 남았지만, 제품력으로 심리적 이탈을 붙잡겠다는 전략이 선명하다.

## Claude Code v2.1.268: 게이트웨이 가격 평준화, 플러그인 관리 강화

오늘 출시된 v2.1.268은 로그인 클라이언트에 게이트웨이 가격 평준화를 적용하고, `gatewayInternalNetworks` 관리자 설정을 추가했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 플러그인 install/uninstall/update/enable/disable에 JSON 출력을 지원해 자동화 파이프라인 통합이 쉬워졌다. v2.1.265에서 발생한 HTTP 400 회귀(서드파티 엔드포인트 호환 문제)도 수정됐다. 9/14 주간 한도 17% 삭감 D-3이 코앞이다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)).

## Codex CLI: GPT-6 Astra 통합, Worktree 세션 실험 시작

어제(9/10) 출시된 Codex CLI 대형 업데이트가 GPT-6 Astra를 모델 피커와 Amazon Bedrock에 정식 통합했다([Gradually.ai](https://www.gradually.ai/en/changelogs/codex-cli/)). 실험적 `--worktree` 플래그로 격리된 Git 체크아웃에서 작업할 수 있으며, 인라인 질문 응답 기능으로 Codex가 작업 중에도 질문에 답한다. OpenAI는 같은 날 Agents API 퍼블릭 베타도 공개했다 — Codex 하네스의 세션·오케스트레이션·컨텍스트 압축을 개발자에게 개방한 것이다.

## Anthropic: 위협 보고서와 Enterprise Smart Reports 동시 발표

Anthropic이 오늘 위협 정보 보고서를 발표해 Claude Code가 자율 드론 군집 킬 소프트웨어 개발에 사용됐음을 공개했다([Anthropic](https://www.anthropic.com/threat-intelligence-report-september-2026)). 최신 모델이 "생물무기 지원 임계값을 더 이상 밑돈다고 단정할 수 없다"는 공식 선언은 주요 AI 기업 최초다([TechTimes](https://www.techtimes.com/articles/327308/20260911/anthropic-threat-report-ai-models-near-bioweapons-threshold-drone-kill-software-emerges.htm)). 한편, Claude Enterprise Smart Reports 베타가 조용히 출시돼 팀 사용량·비용·반복 패턴을 분석하고 공유 스킬로 패키징하는 기능을 제공한다([Releasebot](https://releasebot.io/updates/anthropic/claude)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra GA 1주차, Deep Research 확장 |
| Claude Code | 99 | — | v2.1.268, 위협 보고서, 9/14 한도 삭감 D-3 |
| Claude AI | 99 | — | Enterprise Smart Reports 베타 |
| Codex CLI | 99 | — | GPT-6 Astra 통합, worktree 실험, Agents API 베타 |
| Antigravity | 99 | — | /boost 안정, GEMINI_API_KEY 지원 |
| Windsurf | 87 | — | Cognition $48B 밸류에이션 (시리즈 E 9/8 마감) |
| Cursor | 68 | ↑1 | Projects 베타로 16일 연속 하락 중 1p 반등 |
| Aider | 68 | — | v0.82.0 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 10월 3연타 D-17 |
| Gemini CLI | 1 | — | 폐쇄 85일째, Antigravity 대체 |

Cursor Projects가 반등의 단초가 될지, 아니면 하락 추세의 속도만 늦출지는 다음 주가 판가름한다. OpenAI 모델 차단이라는 구조적 악재가 해소되지 않는 한, 제품 혁신만으로 심리를 완전히 돌리기는 어렵다.

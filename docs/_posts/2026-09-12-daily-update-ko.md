---
title: "Anthropic, AI 모델 생물무기 임계점 첫 공식 인정 — 코딩 도구 샌드박스 보안도 흔들"
date: 2026-09-12
lang: ko
categories: [news]
tags: [anthropic, claude-code, openai, codex-cli, cursor, devin, security]
excerpt: "Anthropic이 주요 AI 기업 최초로 모델이 생물무기 지원 임계점에 도달했다고 인정했다. 같은 주에 Claude Code·Codex·Cursor 전반에서 샌드박스 탈출 취약점이 공개됐다."
---

Anthropic이 9월 10일 공개한 위협 인텔리전스 보고서에서 주요 AI 기업 최초로 "최신 Claude 모델이 더 이상 생물무기 지원 임계점 이하라고 가정할 수 없다"고 공식 인정했다([Anthropic](https://www.anthropic.com/threat-intelligence-report-september-2026)). 2025년 12월~2026년 8월 사이 Claude Haiku, Sonnet, Opus 모델이 사이버 작전, 감시, 사기 등 7개 영역에서 악용된 사례를 상세히 기록했으며, 이란·러시아 연계 행위자들이 무기 연구에 Claude를 활용한 정황도 포착됐다([TechTimes](https://www.techtimes.com/articles/327308/20260911/anthropic-threat-report-ai-models-near-bioweapons-threshold-drone-kill-software-emerges.htm)). Fable·Mythos 모델에서는 악용 사례가 발견되지 않았다.

## 코딩 도구 샌드박스 보안: 연쇄 취약점 공개

스텔스 스타트업 Accomplish이 Claude Code·OpenAI Codex·Cursor에서 샌드박스 탈출 취약점을 공개했다([UpstartsMedia](https://www.upstartsmedia.com/p/accomplish-claims-leaky-sandboxes-in-claude-codex-cursor)). 별도로 악성 `.git` 설정 파일을 통해 Claude Code·Codex·Cursor 등 AI 에이전트에서 공격자 코드를 실행할 수 있는 취약점도 보고됐다([TheHackerNews](https://thehackernews.com/2026/09/malicious-git-configs-can-make-claude.html)). Cursor는 CVE-2026-48124를 v3.0.0에서 패치했지만, Anthropic은 보고 후 약 50일간 미패치 상태였다([BleepingComputer](https://www.bleepingcomputer.com/news/security/cursor-codex-gemini-cli-antigravity-hit-by-sandbox-escapes/amp/)). AI 코딩 도구의 보안이 편의성만큼 빠르게 성숙하지 못하고 있다는 경고다.

## OpenAI: GPT-5.3-Codex-Spark 다음 주 퇴장, Agents API 퍼블릭 베타

OpenAI가 GPT-5.3-Codex-Spark를 다음 주(9/14~) 퇴장시킨다고 발표했다 — 2월 출시 후 약 7개월 만이다([X/thsottiaux](https://x.com/thsottiaux/status/2098300998968357218)). 한편 9/10 출시된 Agents API 퍼블릭 베타는 Codex 하니스를 단일 API 호출로 노출해 세션 오케스트레이션·컨텍스트 압축·복구를 관리형으로 제공한다([MarkTechPost](https://www.marktechpost.com/2026/09/10/openai-launches-the-agents-api-in-public-beta-putting-the-codex-harness-behind-one-api-call/)). 자체 호스팅 샌드박스와 Cloudflare·Vercel·E2B 등 파트너 환경도 지원한다.

## Cognition: Devin Fusion, Desktop·CLI로 확장

Cognition이 6월 발표한 듀얼 모델 아키텍처 Fusion을 9/11부터 Devin Desktop과 CLI로 확장했다([Cognition](https://cognition.com/blog/local-fusion)). 프론티어 모델이 계획하고 저비용 모델이 실행하는 구조로, FrontierCode 벤치마크에서 프론티어급 성능을 유지하면서 비용을 최대 39% 절감한다([CryptoBriefing](https://cryptobriefing.com/cognition-devin-fusion-multi-model-coding-agent/)). Cognition 내부 엔지니어링 팀 PR의 88%가 Fusion 자동 라우팅으로 처리됐다.

## GitHub Copilot: 10/2 모델 대청소 D-20

Copilot에 Claude Fable 5.1과 Gemini 3.8 Flash 배포가 시작됐지만, 진짜 뉴스는 10/2 모델 폐기다 — Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 퇴장한다([DMarketer Tayeeb](https://dmarketertayeeb.com/blog/github-copilot-september-2026-model-budget-review-changes/)). 9/28에는 Chat·Mobile·클라우드 에이전트가 통합 경험으로 합쳐지고 채팅 데이터 보존이 28일→계정 수명으로 변경된다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)).

## Cursor: Projects 베타 3일차, 하락 19일째

Cursor Projects 베타가 코디네이터 에이전트 구조로 주목받고 있으나 하락세를 뒤집지 못했다([Cursor Blog](https://cursor.com/changelog/projects)). 오늘 점수 67로 19일 연속 하락이며, OpenAI 모델 차단까지 D-61이 남은 상황이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Astra 1주 GA, Deep Research 확장 |
| Claude Code | 99 | — | v2.1.269, 샌드박스 보안 취약점 공개 |
| Claude AI | 99 | — | 위협 보고서: 생물무기 임계점 인정 |
| Codex CLI | 99 | — | Agents API 퍼블릭 베타, Spark 퇴장 예고 |
| Antigravity | 99 | — | 27주 연속 99, 샌드박스 탈출 취약점 해당 |
| Windsurf | 87 | — | Cognition $480억 밸류에이션 |
| Cursor | 67 | ↓1 | Projects 3일차, 19일 연속 하락 |
| Aider | 68 | — | v0.82.0 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥, 10/2 모델 대청소 D-20 |
| Gemini CLI | 1 | — | 셧다운 87일차, Antigravity 대체 |

보안이 이번 주의 키워드다. Anthropic의 생물무기 임계점 인정과 코딩 도구 전반의 샌드박스 취약점 공개가 겹치며, AI 도구의 보안 성숙도에 대한 업계 차원의 재점검이 시작됐다.

---
title: "Anthropic, Claude Tag로 Slack에 AI 팀원 투입 — Codex SSD 버그 85% 수정, Fable 5 의회 기한 이틀 앞으로"
date: 2026-06-24
lang: ko
categories: [news]
tags: [anthropic, claude-tag, openai, codex-security, codex-cli, copilot, antigravity, gemini-cli, fable-5, kiro]
excerpt: "Anthropic이 Claude Tag를 출시해 Slack에서 AI 팀원과 협업하는 시대를 열었다. Codex CLI의 640TB SSD 버그가 85% 수정됐고, Fable 5 수출통제에 대한 의회 답변 기한이 이틀 앞으로 다가왔다."
---

Anthropic이 어제 Claude Tag를 출시하며 AI 협업의 단위를 개인 대화에서 팀 채널로 확장했다([Fortune](https://fortune.com/2026/06/23/anthropic-claude-tag-virtual-employee-tool-slack/)). 팀원들이 Slack 채널에서 @Claude를 태그하면 작업을 분해하고 독립적으로 처리한 뒤 결과를 돌려주는 방식이다. Anthropic 내부에서는 이미 제품팀 코드 변경의 65%를 Claude Tag가 승인·반영하고 있다([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-23/anthropic-wants-claude-to-be-your-new-slack-coworker)). Enterprise와 Team 고객 대상 리서치 프리뷰로 시작하며, 기존 Claude in Slack 연동은 8월 3일 종료 예정이다.

## Claude 서비스 장애: 이틀 연속 발생 후 해소

Claude가 6월 23일과 24일 이틀 연속 장애를 겪었다. 23일에는 모든 모델과 플랫폼에서 오후 2시 19분(UTC)부터 오류율이 급증해 미국에서만 7,119건의 장애 보고가 접수됐다([TechRadar](https://www.techradar.com/news/live/claude-down-june-23-2026)). 24일에는 Opus 4.8에서 1시간 40분간 오류율 상승이 발생했다([StatusGator](https://statusgator.com/services/anthropic/claude-code)). 현재는 모두 해소된 상태지만, Claude Tag 출시 직후의 장애라는 점에서 인프라 부하 우려가 나오고 있다.

## Codex CLI: 640TB SSD 버그, 85% 수정 완료

Codex CLI의 SQLite 로거가 연간 640TB를 SSD에 기록하는 치명적 버그가 부분 수정됐다. 6월 23일 세 건의 PR이 머지되어 로그의 85%를 줄이는 패치가 v0.142.0과 v0.143.0에 포함됐다([SecurityOnline](https://securityonline.info/codex-ssd-wear-issue-fix/)). 다만 The Register에 따르면 OpenAI의 공식 대응이 늦었다는 비판이 이어지고 있으며, Windows 사용자는 여전히 RAM 리다이렉트 우회가 불가능한 상태다([The Register](https://www.theregister.com/ai-and-ml/2026/06/23/openai-codex-bombards-ssds-with-needless-write-operations-costing-millions/5260402)).

## OpenAI Daybreak 대규모 확장: Codex Security + GPT-5.5-Cyber

OpenAI가 Daybreak 사이버보안 프로그램을 대폭 확장했다. Codex 안에서 직접 취약점을 발견·검증·패치할 수 있는 Codex Security 플러그인, 신뢰된 방어자 전용 GPT-5.5-Cyber 정식 버전, 그리고 Trail of Bits와 협력한 Patch the Planet 이니셔티브가 핵심이다([OpenAI](https://openai.com/index/daybreak-securing-the-world/)). Codex Security는 3월 프리뷰 이후 3만 개 코드베이스에서 3천만 건의 커밋을 스캔하고 50만 건을 자동 수정했다([Security Boulevard](https://securityboulevard.com/2026/06/openai-expands-daybreak-with-codex-security-and-gpt-5-5-cyber-updates/)).

## Copilot: 50주 연속 하락, 32점 — 종량제 24일차

GitHub Copilot의 인기도가 32점으로 50주 연속 하락이라는 기록을 세웠다. 종량제 전환 24일차로, $39 Pro+ 플랜에서 2시간 만에 월 크레딧 8%를 소진했다는 보고가 이어지고 있다([GitHub Community](https://github.com/orgs/community/discussions/192948)). 시장 점유율도 3월 67%에서 51%로 급감했다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)).

## Fable 5: 차단 12일차, 의회 답변 기한 D-2

Fable 5 수출통제 차단 12일째. 4명의 초당파 의원이 6월 18일 상무장관에게 보낸 공식 서한의 답변 기한이 6월 26일로 이틀 앞으로 다가왔다([explainx.ai](https://www.explainx.ai/blog/us-government-bans-fable-5-mythos-5-anthropic-export-control-2026)). 100명 이상의 사이버보안 전문가도 Fable 5 제한 해제를 촉구하는 서한을 발표했다([ThePlanetTools](https://theplanettools.ai/blog/cybersecurity-experts-letter-lift-fable-5-restrictions-2026)). Polymarket 7월 1일 복원 확률은 57%를 유지하고 있으나, 6월 26일 답변이 분기점이 될 전망이다.

## Gemini CLI 셧다운 7일차 — Antigravity 82

Gemini CLI 개인 사용자 차단이 7일째 이어지면서, Antigravity가 82를 기록하며 7주 연속 상승세를 유지하고 있다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)). Google은 antigravity.google/docs/gcli-migration에서 마이그레이션 문서를 제공하고 있다.

## Kiro: AWS Summit에서 iOS 앱 공개

AWS가 뉴욕 서밋에서 Kiro iOS 앱 얼리 액세스를 발표했다([DevOps.com](https://devops.com/aws-previews-ios-app-to-manage-kiro-ai-coding-workflows/)). 스마트폰에서 코딩 세션을 시작하고 변경 사항을 승인할 수 있으며, Amazon Q Developer의 2027년 4월 지원 종료가 예고되면서 Kiro로의 전환이 본격화될 전망이다.

## OpenAI·Broadcom, 커스텀 AI 칩 "Jalapeno" 공개

OpenAI가 Broadcom과 9개월 만에 공동 개발한 첫 번째 커스텀 추론 칩 "Jalapeno"를 오늘 공개했다([TechCrunch](https://techcrunch.com/2026/06/24/openai-unveils-its-first-custom-chip-built-by-broadcom/)). LLM 추론에 최적화된 설계로 와트당 성능이 크게 향상됐으며, 2026년 말 초기 배치를 목표로 하고 있다([CNBC](https://www.cnbc.com/2026/06/24/openai-and-broadcom-reveal-jalapeno-first-ai-chip-in-partnership.html)). Nvidia 의존도를 줄이려는 OpenAI의 인프라 전략이 본격화되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Claude Tag 출시, Opus 4.8 안정 |
| ChatGPT | 96 | — | GPT-5.6 7월 출시 전망 |
| Claude AI | 96 | — | 이틀 연속 장애 후 해소, Claude Tag 긍정적 |
| Cursor | 96 | — | SpaceX $60B 인수 Q3 완료 예정 |
| Codex CLI | 87 | — | SSD 버그 85% 수정, Daybreak 확장 |
| Windsurf | 85 | — | Devin Desktop 안정, Cascade 7/1 종료 |
| Antigravity | 82 | ↑1 | Gemini CLI D+7 이전 흡수, 7주 연속 상승 |
| Aider | 68 | — | 오픈소스 안정 유지 |
| Gemini CLI | 40 | ↓2 | 셧다운 7일차, 기업 전용 |
| Copilot | 32 | ↓1 | 50주 연속 하락, 종량제 24일차 |

---
title: "보안 폭풍의 주 — Plugin4Shell에 이어 샌드박스 탈출까지, AI 코딩 도구 4종 이중 피격"
date: 2026-09-20
lang: ko
categories: [news]
tags: [security, plugin4shell, sandbox-escape, github-copilot, cursor, claude-code, codex-cli, gemini, antigravity]
excerpt: "Plugin4Shell 제로클릭 RCE에 이어 Pillar Security의 샌드박스 탈출 연구까지 — 한 주 만에 두 번의 보안 경보가 AI 코딩 도구 생태계를 뒤흔들고 있다."
---

AI 코딩 도구 업계에 전례 없는 '보안 폭풍의 주'가 이어지고 있다. 9월 17일 공개된 Plugin4Shell 제로클릭 RCE에 이어, Pillar Security가 Cursor·Codex·Gemini CLI·Antigravity 4종의 샌드박스 탈출 취약점을 공개하면서 한 주 만에 두 차례 보안 경보가 울렸다([BleepingComputer](https://www.bleepingcomputer.com/news/security/cursor-codex-gemini-cli-antigravity-hit-by-sandbox-escapes/)).

## Plugin4Shell: 패치 속도가 신뢰를 결정했다

AIR Security가 공개한 Plugin4Shell은 플러그인 로딩 경로의 SHA-피닝을 우회하는 제로클릭 RCE로, Claude Code·Codex·Copilot·Gemini CLI 4개 도구에 영향을 미쳤다([Cybersecurity News](https://cybersecuritynews.com/plugin4shell-zero-click-rce/)). Anthropic은 Claude Code v2.1.179에서, OpenAI는 Codex v0.146.0에서 즉시 패치했지만, Microsoft는 Copilot 패치를 아직 내놓지 않았고 Google은 Gemini CLI 지원 종료를 이유로 패치 불가를 통보했다([The Hacker News](https://thehackernews.com/2026/09/plugin4shell-lets-repository-owners.html)).

## 샌드박스 탈출: AI 에이전트가 규칙을 지키면서 탈출하는 법

Pillar Security의 연구팀은 Cursor·Codex·Gemini CLI·Antigravity에서 재현 가능한 샌드박스 탈출 4가지 패턴을 발견했다([The Next Web](https://thenextweb.com/news/ai-coding-agents-sandbox-escapes-pillar)). 에이전트는 샌드박스 규칙을 모두 준수하면서도, 외부의 신뢰된 도구가 나중에 실행하는 파일을 작성하는 방식으로 탈출한다. Cursor는 CVE-2026-48124로 추적되어 v3.0.0에서 수정됐고, OpenAI는 Codex v0.95.0 패치와 함께 고위험 바운티를 지급했다([BleepingComputer](https://www.bleepingcomputer.com/news/security/cursor-codex-gemini-cli-antigravity-hit-by-sandbox-escapes/)). 반면 Google은 Antigravity 취약점 2건의 심각도를 낮게 재분류하고 패치하지 않았다([Techzine](https://www.techzine.eu/news/security/143038/researchers-bypass-sandbox-security-in-cursor-codex-and-gemini-cli/)).

## GitHub Copilot: 통합 경험 D-8, 모델 대규모 퇴출 예고

Copilot 통합 경험이 9월 28일 출시를 8일 앞두고 있다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 9월 18일 주간 릴리스에서는 Sentry 캔버스와 자동 모델 선택 3단계 티어(efficiency/balance/intelligence)가 도입됐다([GitHub Changelog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)). 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 일괄 퇴출된다.

## Claude Code: 서버사이드 분류기 + AGENTS.md 상호운용

Claude Code v2.1.278에서 API·Enterprise·Bedrock·Vertex·Foundry·게이트웨이 전체 사용자의 자동 모드 분류기가 서버사이드로 기본 전환되어 분류기 오버헤드 과금이 사라졌다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). v2.1.277에서는 AGENTS.md 지원이 추가되어 Codex CLI 프로젝트와의 상호운용성이 확보됐다. 한편 Anthropic은 Claude가 자사 모델 R&D의 26%를 주도하고 있으며 사내에서 3만 개 이상의 에이전트가 동시 운영 중이라고 밝혔다([AI Weekly](https://aiweekly.co/ai-news-today)).

## Cursor: 51점, 31일 연속 하락 — 50선 돌파 초읽기

SpaceX 인수($600억) 이후 31일 연속 하락해 51점을 기록한 Cursor에 샌드박스 탈출 취약점까지 공개되면서 악재가 겹쳤다([CNBC](https://www.cnbc.com/2026/06/16/spacex-spcx-cursor-acquisition-ipo.html)). OpenAI 모델 접근 차단(11/12)까지 53일이 남았고, Codex CLI의 `/import` 마이그레이션 지원이 탈출 심리를 가속하고 있다([Releasebot](https://releasebot.io/updates/openai/codex)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.5 은퇴 D-24 |
| Claude Code | 99 | — | v2.1.278 서버사이드 분류기, Plugin4Shell 즉시 패치 |
| Claude AI | 99 | — | Fable 5.1 프론티어, R&D 26% 주도 |
| Codex CLI | 99 | — | /import 마이그레이션, 샌드박스 패치 완료 |
| Antigravity | 99 | — | 샌드박스 취약점 미패치 논란 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 화제 |
| Aider | 68 | — | 꾸준한 릴리스, 39K+ 스타 |
| Cursor | 51 | ↓2 | 31일 연속 하락 + CVE-2026-48124 |
| GH Copilot | 1 | — | 통합 경험 D-8, Plugin4Shell 미패치 |
| Gemini CLI | 1 | — | 폐쇄 95일째, 보안 패치 불가 |

한 주 만에 Plugin4Shell과 샌드박스 탈출, 두 가지 구조적 취약점이 연달아 터졌다. Anthropic과 OpenAI의 신속 패치 vs Google·Microsoft의 지연 대응이 도구 선택의 핵심 기준으로 부상하고 있다.

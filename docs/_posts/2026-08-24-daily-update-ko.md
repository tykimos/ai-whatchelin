---
title: "Cursor 종량제 선언, Ox Alpha 미스터리 모델 퇴장 — Codex MCP 폐기와 Nokia 2만명 배포까지"
date: 2026-08-24
lang: ko
categories: [news]
tags: [cursor, openai, copilot, ox-alpha, codex-cli, anthropic, nokia, pricing, deprecation]
excerpt: "Cursor Auto 모드의 플랫 요금이 오늘 사라졌다. AI 코딩 도구 시장 전체가 종량제로 수렴하는 가운데, Codex CLI는 MCP 서버를 폐기하고, Nokia는 엔지니어 2만 명을 Cursor에 배치했다."
---

AI 코딩 도구 시장의 과금 체계가 또 한 번 뒤집혔다. Cursor가 오늘(8/24) Auto 모드의 플랫 요금을 공식 폐지하고 모델별 과금으로 전환하면서, 업계 전체가 종량제로 수렴하는 흐름이 더 뚜렷해졌다. 한편 Codex CLI는 MCP 서버 명령을 폐기하며 도구 에코시스템을 정리하고 있고, Anthropic은 매출 런레이트 $650억을 기록하며 IPO 카운트다운에 들어갔다.

## Cursor: Auto 모델별 과금 공식 발효

Cursor Auto 모드가 오늘부터 라우팅된 모델의 개별 요금을 적용한다([explainx.ai](https://www.explainx.ai/blog/cursor-auto-per-model-pricing-usage-limits-august-2026)). 기존에는 Auto로 라우팅되면 단일 플랫 요금이 적용됐지만, 이제 Opus 5, Fable 5 등 프론티어 모델 사용 시 해당 모델의 토큰 단가가 그대로 부과된다. 전 모델의 포함 사용량은 늘었지만, 고성능 모델을 자주 쓰는 개발자에게는 실질 비용 상승이 불가피하다. 한편 Nokia가 엔지니어 20,000명 이상을 Cursor에 배치하며 역대 최대 규모의 엔터프라이즈 배포를 기록했다([blog.logrocket.com](https://blog.logrocket.com/ai-dev-tool-power-rankings/)). Kilo AI는 *"all roads lead to metered pricing"*이라며 AI 코딩 도구 전체의 종량제 수렴을 분석했다([blog.kilo.ai](https://blog.kilo.ai/p/all-roads-lead-to-metered-pricing)).

## Codex CLI: MCP 서버 폐기 + v0.149.0 대시보드

Codex CLI의 `codex mcp-server` 명령이 오늘 공식 폐기됐다. 사용자는 Codex 앱 서버 또는 Codex plugin for Claude Code로 전환해야 한다([releasebot.io](https://releasebot.io/updates/openai/codex)). 이는 OpenAI가 도구 에코시스템을 통합하려는 방향을 보여준다. v0.149.0(8/20)에서는 인터랙티브 에이전트 대시보드가 추가돼 에이전트 검색·시작·관리가 한 화면에서 가능해졌고, v0.148.0(8/18)에서는 TUI 대화를 Markdown으로 내보내는 `/export`와 세션 포킹 `codex exec fork`가 도입됐다([havoptic.com](https://www.havoptic.com/tools/openai-codex)).

## Ox Alpha: 정체불명 프론티어 모델, 무료 접근 마지막 날

8월 20일 OpenRouter에 등장한 스텔스 모델 Ox Alpha의 무료 접근이 오늘 종료된다([SiliconANGLE](https://siliconangle.com/2026/08/23/nobody-knows-who-built-ai-coding-model-ox-alpha-or-where-the-code-goes/)). 1M 토큰 컨텍스트, 텍스트·이미지·비디오 입력을 지원하는 이 모델은 출시 하루 만에 수십억 토큰의 트래픽을 처리했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-23/mystery-ai-model-ox-alpha-draws-developers-with-free-access)). "stealth" 명의로만 등록돼 있으며, Reddit에서는 Z.ai GLM 계열이라는 추측이 지배적이다([Manifold](https://manifold.markets/Sketchy/who-is-behind-ox-alpha-the-mysterio)). 코드가 어디로 가는지 알 수 없다는 보안 우려도 제기되고 있다.

## Anthropic: $650억 런레이트, 하드웨어 진출

Anthropic의 연간 매출 런레이트가 $650억에 도달했다. 5월의 $470억 대비 38% 급등이다([Fortune](https://fortune.com/2026/08/18/anthropic-annual-revenue-run-rate-65-billion/)). 2026년 말 $1,000-1,200억 목표에 IPO 제출이 임박한 것으로 전망된다. 8월 22일에는 Google 칩 베테랑을 영입하며 자체 AI 하드웨어 설계에 본격 진출했다([TechCrunch](https://techcrunch.com/2026/08/17/anthropics-annualized-revenue-surges-to-65b/)).

## 카운트다운: 8일 안에 4건

o3 ChatGPT 퇴장 D-2(8/26), DALL·E GPT 은퇴 D-6(8/30), GPT-5.4 Codex 퇴출 D-7(8/31), Copilot 6개 모델 대폐기 D-8(9/1)이 줄줄이 기다린다([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). Copilot은 104주 연속 인기도 하락을 기록 중이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.241, 28주 연속 99 |
| ChatGPT | 99 | — | o3 퇴장 D-2, Sol 20%+ 인하 지속 |
| Codex CLI | 99 | — | v0.149.0 대시보드, MCP 서버 폐기 |
| Antigravity | 99 | — | IDE 확장 안착, 28주 연속 99 |
| Claude AI | 99 | — | Academy 안착, $650억 런레이트 |
| Cursor | 99 | — | Auto 종량제 발효, Nokia 2만명 배포 |
| Windsurf | 86 | — | Devin Local 안정화 |
| Aider | 68 | — | v0.86.2 이후 6개월+ 무릴리스 |
| Copilot | 1 | — | 104주 하락, 대폐기 D-8 |
| Gemini CLI | 1 | — | 폐쇄 67일째 |

Cursor의 종량제 전환과 Codex의 MCP 폐기는 AI 코딩 도구 시장이 성숙기에 접어들고 있음을 보여준다. 다음 주 연쇄 마감 속에서 개발자들의 도구 재편이 본격화될 전망이다.

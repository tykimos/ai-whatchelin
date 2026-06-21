---
title: "GPT-5.6 출시 확률 급락, Grok V9-Medium 훈련 완료 — AI 코딩 전쟁의 새 판이 열린다"
date: 2026-06-21
lang: ko
categories: [news]
tags: [gpt-5.6, grok, fable-5, gemini-cli, antigravity, copilot, opencode, spcx]
excerpt: "GPT-5.6 예측시장이 90%에서 22%로 급락했다. xAI의 Grok V9-Medium 1.5T 파라미터 모델이 훈련을 마쳤고, Gemini CLI 셧다운 3일째 파이프라인 장애가 확산되고 있다."
---

어제까지 90%에 달하던 GPT-5.6의 6월 22~28일 출시 확률이 하루 만에 22%로 급락했다. 동시에 xAI의 Grok V9-Medium이 1.5조 개 파라미터 훈련을 완료하며, AI 코딩 도구 시장의 판도가 다시 요동치고 있다.

## GPT-5.6: 예측시장 급반전 — 90%에서 22%로

GPT-5.6의 6월 22~28일 출시 확률이 Polymarket에서 **22%**로 급락했다([Polymarket](https://polymarket.com/event/when-will-gpt-5pt6-be-released)). 불과 어제까지 90%였던 수치가 하룻밤 만에 뒤집힌 것이다. "6월 28일까지 미출시" 계약이 77%로 우세하며, 6월 30일까지를 포함해도 78%에 머물고 있다. OpenAI 수석 과학자 Pachocki가 "의미 있는 개선"이라 평가한 iris-alpha 코드명의 모델은 1.5M 컨텍스트 윈도우를 갖출 것으로 예상되나, 출시 시점은 7월 이후로 밀릴 가능성이 높아졌다([TechTimes](https://www.techtimes.com/articles/318492/20260616/gpt-56-openai-chief-scientist-calls-it-meaningful-leap-june-launch-nears.htm)).

## Grok V9-Medium: 1.5T 파라미터 훈련 완료 — Cursor 데이터 활용

xAI가 Grok V9-Medium 모델의 훈련을 완료했다([TechTimes](https://www.techtimes.com/articles/317328/20260528/grok-ai-new-model-triples-parameter-count-targets-coding-lead-release-expected-mid-june.htm)). 현재 프로덕션 모델의 3배인 1.5조 개 파라미터 규모이며, SpaceX의 $600억 Cursor 인수 합의로 확보한 실제 개발자 워크플로우 데이터로 훈련됐다. 6월 중순 공개 출시가 예상되어 있어 수일 내 등장할 수 있다. Grok Build CLI v0.2.51에서는 worktree 지원과 /code-review 명령어가 이미 추가돼 인프라 준비도 착착 진행 중이다([x.ai](https://x.ai/build/changelog)).

## Fable 5 정지 9일째 — 복원 확률 57%, 여전히 불투명

Fable 5 정지가 9일째에 접어들었다. Polymarket 기준 7월 1일 이전 복원 확률은 57%, 7월 17일 이전은 75%다([Polymarket](https://polymarket.com/event/claude-fable-5-restored-for-us-customers-by-20260613193753196)). Anthropic 국제사업 총괄 Chris Ciauri는 "수일 내 복원에 매우 확신한다"고 밝혔으나([TechTimes](https://www.techtimes.com/articles/318668/20260618/fable-5-export-ban-day-six-anthropic-opens-seoul-office-vows-models-back-days.htm)), 백악관은 모든 탈옥 취약점 제거를 전제 조건으로 요구하고 있어 보안 전문가들 사이에서 기술적으로 불가능하다는 지적이 나온다. Fable 5의 공백 속에서 GPT-5.6마저 지연되면서, Opus 4.8이 사실상 유일한 최전선 코딩 모델로 버티고 있다.

## Gemini CLI 셧다운 3일째 — 파이프라인 장애 확산

6월 18일 공식 종료 이후 3일째, Gemini CLI를 호출하던 CI/CD 파이프라인에서 HTTP 410 에러가 계속되고 있다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). MCP `serverUrl` 필드명 변경으로 인한 사일런트 장애가 가장 위험하며, Docker 컨테이너·cron 작업·Makefile에 하드코딩된 `gemini` 호출이 모두 깨졌다. 대체제 Antigravity CLI(`agy`)는 무료 일간 요청 20회로 제한되어 Gemini CLI의 1,000회/일에서 98% 감소했다([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)).

## Copilot 48주 연속 하락 — 35점, 종량제 21일차

GitHub Copilot 인기도가 **35**로 48주 연속 하락을 이어갔다. 종량제 전환 21일차로, Pro 플랜 $10/월에 포함된 크레딧이 에이전틱 세션 한 번으로 거의 소진되는 상황이다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). 일부 사용자는 기존 대비 10~100배 비용 증가를 경험하고 있으며, 직접 API 접근이나 OpenRouter·RooCode·LM Studio로의 이탈이 가속화되고 있다([NxCode](https://www.nxcode.io/resources/news/github-copilot-getting-worse-2026-developers-switching)).

## OpenCode 176K 스타 돌파 — 오픈소스 코딩 에이전트 1위

OpenCode가 GitHub 스타 176K를 넘어서며 가장 많이 채택된 오픈소스 코딩 에이전트 자리를 굳혔다([GitHub](https://github.com/anomalyco/opencode/releases)). 월간 활성 사용자 750만, 75개 이상 모델 프로바이더 지원, MIT 라이선스의 에어갭 배포까지 가능한 이 도구는 Gemini CLI 종료 후 이탈하는 개발자들의 유력한 대안으로 부상하고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5 D-9, Opus 4.8 단독 최전선 |
| ChatGPT | 96 | — | GPT-5.6 출시 지연 가능성 |
| Cursor | 96 | — | SpaceX 인수 Q3 완료 예정 |
| Claude AI | 96 | — | 서울 오피스 파트너십 가동 |
| Codex CLI | 87 | — | v0.141.0 안정화 |
| Windsurf | 85 | — | $15 가격 Copilot 이탈 흡수 |
| Antigravity | 79 | ↑1 | Gemini CLI D+3 마이그레이션 |
| Aider | 68 | — | 오픈소스 안정 |
| Gemini CLI | 46 | ↓2 | 셧다운 D+3, 하락 지속 |
| Copilot | 35 | ↓1 | 48주 하락, 종량제 D-21 |

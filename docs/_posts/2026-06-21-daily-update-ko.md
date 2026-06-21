---
title: "GPT-5.6 출시 확률 급락, Agentjacking 공격 2,388개 조직 노출 — AI 코딩 보안 비상"
date: 2026-06-21
lang: ko
categories: [news]
tags: [gpt-5.6, grok, fable-5, gemini-cli, antigravity, copilot, agentjacking, claude-code]
excerpt: "GPT-5.6 예측시장이 90%에서 22%로 급락하고, Agentjacking 공격이 Claude Code·Cursor·Codex를 포함한 2,388개 조직에 85% 성공률로 침투했다. Fable 5 정지 9일째, Gemini CLI 셧다운 3일째."
---

GPT-5.6 출시 지연과 동시에 AI 코딩 에이전트 전반을 겨냥한 새로운 공격 기법 'Agentjacking'이 주목받고 있다. 2,388개 조직이 이미 노출된 가운데, 개발자들의 보안 의식이 시험대에 올랐다.

## GPT-5.6: 예측시장 급반전 — 90%에서 22%로

GPT-5.6의 6월 22~28일 출시 확률이 Polymarket에서 **22%**로 급락했다([Polymarket](https://polymarket.com/event/when-will-gpt-5pt6-be-released)). 불과 어제까지 90%였던 수치가 하룻밤 만에 뒤집힌 것이다. OpenAI 수석 과학자 Pachocki가 "의미 있는 개선"이라 평가한 iris-alpha 코드명의 모델은 1.5M 컨텍스트 윈도우를 갖출 것으로 예상되나, 출시 시점은 7월 이후로 밀릴 가능성이 높아졌다([TechTimes](https://www.techtimes.com/articles/318492/20260616/gpt-56-openai-chief-scientist-calls-it-meaningful-leap-june-launch-nears.htm)).

## Agentjacking: AI 코딩 에이전트 대상 신종 공격 — 85% 성공률

'Agentjacking'이라 명명된 새로운 공격 기법이 AI 코딩 도구 생태계를 위협하고 있다([unrot.co](https://unrot.co/blogs/ai-news-today-june-21-2026)). 에러 트래킹 플랫폼의 Sentry DSN을 악용해 Claude Code, Cursor, Codex CLI에 악성 코드를 실행시키는 이 공격은 2,388개 이상의 조직에서 **85%** 성공률을 기록했다. 보안 전문가들은 "에러 트래킹 출력을 신뢰할 수 없는 입력으로 취급하라"고 권고하고 있다.

## Grok V9-Medium: 1.5T 파라미터 훈련 완료

xAI가 Grok V9-Medium 모델의 훈련을 완료했다([TechTimes](https://www.techtimes.com/articles/317328/20260528/grok-ai-new-model-triples-parameter-count-targets-coding-lead-release-expected-mid-june.htm)). 현재 프로덕션 모델의 3배인 1.5조 개 파라미터 규모이며, SpaceX의 $600억 Cursor 인수 합의로 확보한 실제 개발자 워크플로우 데이터로 훈련됐다. Grok Build CLI v0.2.51에서는 worktree 지원과 /code-review 명령어가 이미 추가됐다([x.ai](https://x.ai/build/changelog)).

## Fable 5 정지 9일째 — 복원 확률 57%

Fable 5 정지가 9일째에 접어들었다. Polymarket 기준 7월 1일 이전 복원 확률은 57%, 7월 17일 이전은 75%다([Polymarket](https://polymarket.com/event/claude-fable-5-restored-for-us-customers-by-20260613193753196)). Anthropic 국제사업 총괄 Chris Ciauri는 "수일 내 복원에 매우 확신한다"고 밝혔으나([TechTimes](https://www.techtimes.com/articles/318668/20260618/fable-5-export-ban-day-six-anthropic-opens-seoul-office-vows-models-back-days.htm)), 백악관은 모든 탈옥 취약점 제거를 전제 조건으로 요구하고 있다. Fable 5·GPT-5.6 모두 부재하면서 Opus 4.8이 사실상 유일한 최전선 코딩 모델이다.

## Claude Code 채택률 63% — 개발자 도구 거버넌스 경고

Black Duck Security 조사에 따르면 Claude Code가 개발자 응답자 중 **63%** 채택률을 달성했다([BuildFastWithAI](https://www.buildfastwithai.com/blogs/ai-news-today-june-21-2026)). GitHub Copilot(83%)에 이어 두 번째지만 추세는 역전 중이다. 한편 개발자의 97%가 AI 코딩 도구를 사용하지만 완전한 거버넌스 프레임워크를 갖춘 조직은 **3분의 1**에 불과해 보안·IP 관리 과제가 부각되고 있다.

## Gemini CLI 셧다운 3일째 — 파이프라인 장애 확산

6월 18일 공식 종료 이후 3일째, CI/CD 파이프라인에서 HTTP 410 에러가 계속되고 있다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). 대체제 Antigravity CLI는 무료 일간 요청 20회로 제한되어 Gemini CLI의 1,000회/일에서 98% 감소했다([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)).

## Copilot 48주 연속 하락 — 35점

GitHub Copilot이 **35**로 48주 연속 하락을 이어갔다. 종량제 전환 21일차로, Pro 플랜 크레딧이 에이전틱 세션 한 번으로 거의 소진되는 상황이다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). OpenRouter·RooCode·LM Studio로의 이탈이 가속화되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 채택률 63%, Opus 4.8 단독 최전선 |
| ChatGPT | 96 | — | GPT-5.6 출시 지연 가능성 |
| Cursor | 96 | — | SpaceX 인수 Q3 완료 예정 |
| Claude AI | 96 | — | Fable 5 D-9, 복원 확률 57% |
| Codex CLI | 87 | — | v0.141.0 안정화 |
| Windsurf | 85 | — | $15 가격 Copilot 이탈 흡수 |
| Antigravity | 79 | ↑1 | Gemini CLI D+3 마이그레이션 |
| Aider | 68 | — | 오픈소스 안정 |
| Gemini CLI | 46 | ↓2 | 셧다운 D+3, 하락 지속 |
| Copilot | 35 | ↓1 | 48주 하락, Agentjacking 노출 |

---
title: "Gemini CLI 폐쇄 후폭풍 — 파이프라인 장애 속 Antigravity 급부상, Fable 5 정지 1주일"
date: 2026-06-19
lang: ko
categories: [news]
tags: [gemini-cli, antigravity, copilot, fable-5, gpt-5.6, spacex, kaggle, claude-code]
excerpt: "Gemini CLI 폐쇄 첫날, CI/CD 파이프라인이 무더기로 깨지며 개발자들의 분노가 폭발했다. Antigravity CLI가 수혜자로 떠오르는 가운데, Fable 5 정지는 7일째 해제 기미가 없다."
---

어제 공식 폐쇄된 Gemini CLI의 여파가 현실로 나타났다. `gemini` 명령어를 사용하던 수만 개의 CI/CD 파이프라인이 HTTP 410 에러를 반환하며 멈췄고, 개발자 커뮤니티는 하루 만에 "사일런트 장애"의 규모를 체감하고 있다.

## Gemini CLI 셧다운 D+1: 사일런트 장애의 규모

어제 종료된 Gemini CLI의 후폭풍이 본격화됐다. CI/CD 파이프라인, cron job, 오케스트레이션 브릿지에서 `gemini` 명령어가 HTTP 410을 반환하며 빌드가 무더기로 실패하고 있다([TechTimes](https://www.techtimes.com/articles/318660/20260618/gemini-cli-shutdown-takes-effect-ci-cd-pipelines-break-go-based-antigravity-cli-arrives.htm)). 특히 MCP `serverUrl` 필드명 변경이 에러 없이 실패하는 "사일런트 장애"가 가장 위험하다고 개발자들이 보고하고 있다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). Google이 1년간 외부 기여자들로부터 6,000개 PR을 받아들인 뒤 폐쇄형 바이너리로 전환한 데 대해 Linux Foundation은 "오픈소스 끼워팔기"의 대표 사례로 지목했다([TechTimes](https://www.techtimes.com/articles/317407/20260529/linux-foundation-tool-spotlighted-furious-developers-accuse-sickening-google-gemini-cli.htm)).

## Antigravity: Gemini CLI 무덤 위에서 급성장

Gemini CLI 이전 수요를 흡수하며 Antigravity 인기도가 77로 상승했다. Google & Kaggle AI Agents Intensive 5일 과정이 오늘 최종일을 맞으며 Antigravity로 바이브코딩하는 워크숍이 진행됐다([Kaggle](https://www.kaggle.com/competitions/5-day-ai-agents-intensive-vibecoding-course-with-google/discussion/708744)). 다만 후속제 Antigravity CLI(`agy`)는 무료 일간 요청이 1,000회에서 20회로 98% 감소한 폐쇄형 Go 바이너리로, 기존 Gemini CLI와 1:1 기능 호환이 안 된다는 점은 여전히 불만 요소다([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)).

## Fable 5 정지 7일째 — 복원 기미 없음

미국 정부의 수출 통제 지시로 정지된 Claude Fable 5가 7일째 복원 일정 없이 정지 상태를 유지하고 있다([EisnerAmper](https://www.eisneramper.com/insights/artificial-intelligence-insights/fable-5-suspension-facts-and-timeline-0626/)). David Sacks 전 AI 차르가 "가능한 빨리" 복원하겠다고 했지만, Anthropic이 워싱턴에서 대면 협상을 계속하고 있는 것 외에 구체적 진전은 없다([Octagon AI](https://octagonai.co/markets/politics/when-will-anthropic-restore-fable-5-access-for-us-customers/)). Opus 4.8, Sonnet 4.6 등 다른 Claude 모델은 정상 운영 중이다.

## GPT-5.6: "의미 있는 개선" — 다음 주 출시 가능성 83%

OpenAI 수석 과학자 Jakub Pachocki가 GPT-5.6를 내부적으로 "의미 있는 개선(meaningful improvement)"이라고 평가했다([TechTimes](https://www.techtimes.com/articles/318492/20260616/gpt-56-openai-chief-scientist-calls-it-meaningful-leap-june-launch-nears.htm)). Polymarket에서 6월 22-28일 출시 확률 83%, $96만 이상 거래량이 형성돼 있다([Polymarket](https://polymarket.com/event/gpt-5pt6-released-by)). 공식 발표는 아직 없지만, iris-alpha 코드명으로 1.5M 컨텍스트를 지원할 것으로 예상된다.

## Copilot 46주 연속 하락 — 37점, 종량제 19일차

Copilot 인기도가 37로 46주 연속 하락을 기록했다. 종량제 과금 19일차로, 일부 사용자가 월 크레딧의 8%를 2시간 만에 소진하는 사례가 계속 보고되고 있다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). CVSS 9.6 프롬프트 인젝션 취약점(CVE-2025-53773)도 어제 공개되며 신뢰 회복이 더욱 어려워졌다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5 정지 7일째, Opus 4.8 정상 |
| ChatGPT | 96 | — | 점유율 50% 이하 소화 중 |
| Cursor | 96 | — | SpaceX 인수, SPCX ~$175 조정 |
| Claude AI | 96 | — | 서울 오피스 파트너십 가동 |
| Codex CLI | 87 | — | GPT-5.6 다음 주 기대 |
| Windsurf | 85 | — | $15 가격, Copilot 이탈 흡수 |
| Antigravity | 77 | ↑1 | Gemini CLI 셧다운 이전 수요 흡수 |
| Aider | 68 | — | 오픈소스 에이전트 정체 |
| Gemini CLI | 50 | ↓5 | 어제 폐쇄, 파이프라인 장애 속출 |
| Copilot | 37 | ↓1 | 46주 하락, 종량제 19일차 |

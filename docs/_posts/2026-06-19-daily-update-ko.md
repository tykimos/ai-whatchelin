---
title: "SK Telecom이 Fable 5 금지 촉발 — 환불 마감 D-1, 트럼프 G7서 '잘 되고 있다'"
date: 2026-06-19
lang: ko
categories: [news]
tags: [fable-5, sk-telecom, gemini-cli, antigravity, copilot, gpt-5.6, kaggle, claude-code]
excerpt: "Fable 5 금지의 방아쇠를 당긴 주인공이 SK Telecom으로 드러났다. 환불 마감이 내일로 다가온 가운데, 트럼프 대통령이 G7에서 처음으로 '협상이 잘 되고 있다'고 발언했다."
---

Fable 5 정지 사태 7일째, 오늘 가장 큰 뉴스는 금지의 원인이 된 한국 통신사가 SK Telecom으로 특정됐다는 것이다. 동시에 Gemini CLI 셧다운 D+1의 파이프라인 장애가 현실로 나타나며, AI 코딩 도구 시장의 격변이 계속되고 있다.

## Fable 5: SK Telecom이 금지 촉발한 원인으로 특정

백악관이 Anthropic의 Fable 5·Mythos 5를 정지시킨 직접적 원인이 SK Telecom으로 밝혀졌다([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/sk-telecom-named-as-the-korean-carrier-at-the-center-of-anthropics-mythos-export-controls)). SK Telecom은 6월 초 Anthropic의 Project Glasswing 사이버보안 프로그램을 통해 Mythos 5 접근 권한을 획득했는데, 백악관이 이 회사의 중국 연계 이력에 우려를 표명하며 접근 차단을 요청했고, Anthropic이 즉시 이행했다([Korea JoongAng Daily](https://www.koreajoongangdaily.com/business/white-house-officials-pin-anthropic-ai-export-block-on-korean-telecom-report/12726842)). 특히 이번 사태는 Anthropic이 바로 같은 주에 서울 오피스를 여는 시점에 벌어진 것이어서 상황이 극도로 아이러니하다.

환불 마감이 내일(6월 20일)이다. 6월 9일~14일 사이 플랜 구매 또는 업그레이드한 사용자만 대상이며, 기한은 6월 20일 23:59 PT다([TechJack Solutions](https://techjacksolutions.com/ai-brief/fable-5-refund-window-closes-june-20-what-anthropics-billing/)). Anthropic 국제사업 총괄은 서울 오피스 오프닝에서 "수일 내 복원에 매우 확신한다"고 밝혔고([TechTimes](https://www.techtimes.com/articles/318668/20260618/fable-5-export-ban-day-six-anthropic-opens-seoul-office-vows-models-back-days.htm)), 트럼프 대통령도 G7 에비앙 현장에서 기자들에게 "협상이 잘 되고 있다(going fine)"고 발언해 금지령 관련 첫 대통령 코멘트를 남겼다. Kalshi 예측시장은 7월 1일 전 복원 확률을 57%로 보고 있다.

## Gemini CLI 셧다운 D+1: 사일런트 장애가 가장 위험

어제 공식 폐쇄된 Gemini CLI의 후폭풍이 본격화됐다. `gemini` 명령어를 사용하던 CI/CD 파이프라인, cron job, 오케스트레이션 브릿지에서 HTTP 410 에러가 무더기로 발생하고 있다([TechTimes](https://www.techtimes.com/articles/318660/20260618/gemini-cli-shutdown-takes-effect-ci-cd-pipelines-break-go-based-antigravity-cli-arrives.htm)). MCP `serverUrl` 필드명 변경이 에러 없이 통과하는 사일런트 장애가 가장 위험한 것으로 보고되고 있다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). 후속제 Antigravity CLI(`agy`)는 무료 일간 요청이 1,000회에서 20회로 98% 감소한 폐쇄형 Go 바이너리다([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)). Antigravity 인기도는 77로 상승하며 이전 수요를 흡수 중이다.

## GPT-5.6: 다음 주 출시 가능성 83%

OpenAI 수석 과학자 Pachocki가 GPT-5.6를 "의미 있는 개선(meaningful improvement)"이라고 평가했다([TechTimes](https://www.techtimes.com/articles/318492/20260616/gpt-56-openai-chief-scientist-calls-it-meaningful-leap-june-launch-nears.htm)). Polymarket에서 6월 22-28일 출시 확률이 83%를 기록하고 있으며, iris-alpha 코드명에 1.5M 컨텍스트 윈도우가 예상된다([AIxploria](https://www.aixploria.com/en/ai-radar/gpt-5-6-codex-leak-polymarket-june-release/)). 공식 발표는 아직 없다.

## Copilot 46주 연속 하락 — 37점, 종량제 19일차

Copilot 인기도가 37로 46주 연속 하락을 기록했다. 종량제 과금 19일차로, 일부 사용자가 월 크레딧의 8%를 2시간 만에 소진하는 사례가 지속되고 있다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). 어제 공개된 CVSS 9.6 프롬프트 인젝션 취약점(CVE-2025-53773)도 신뢰 회복에 악재다.

## Kaggle AI Agents Intensive 최종일 — 캡스톤 프로젝트 시작

Google & Kaggle AI Agents Intensive 5일 과정이 최종일을 맞았다. 오늘 프로토타입-투-프로덕션 세션이 진행되며, 캡스톤 프로젝트가 공개돼 7월 6일까지 제출 가능하다([Kaggle](https://www.kaggle.com/competitions/5-day-ai-agents-intensive-vibecoding-course-with-google)). 완료 시 Kaggle 프로필에 배지와 수료증이 부여된다.

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

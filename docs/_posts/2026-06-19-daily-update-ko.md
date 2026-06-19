---
title: "SK Telecom이 Fable 5 금지 촉발 — 환불 D-1, Gemini CLI 사망 후 파이프라인 대란"
date: 2026-06-19
lang: ko
categories: [news]
tags: [fable-5, sk-telecom, gemini-cli, antigravity, copilot, gpt-5.6, kaggle, claude-code, codex-cli, cursor, windsurf]
excerpt: "Fable 5 금지 7일째, SK Telecom이 원인으로 특정됐다. Gemini CLI 셧다운 D+1 파이프라인 장애가 현실화되고, Cursor Automations GA와 Codex CLI v0.141.0이 출시됐다."
---

Fable 5 정지 7일째, 금지를 촉발한 한국 통신사가 SK Telecom으로 확인됐다. Gemini CLI 셧다운 다음 날 CI/CD 파이프라인이 대거 깨지고 있으며, AI 코딩 도구 시장은 또 한번 요동치고 있다.

## Fable 5: SK Telecom이 금지 촉발, 환불 마감 내일

Fable 5·Mythos 5 수출 통제의 방아쇠를 당긴 주인공이 SK Telecom으로 특정됐다([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/sk-telecom-named-as-the-korean-carrier-at-the-center-of-anthropics-mythos-export-controls)). SK Telecom은 6월 초 Anthropic의 Project Glasswing 사이버보안 프로그램을 통해 Mythos 5 접근 권한을 획득했으나, 백악관이 중국 연계 이력에 우려를 표명하며 접근 차단을 요청했다([Korea JoongAng Daily](https://www.koreajoongangdaily.com/business/white-house-officials-pin-anthropic-ai-export-block-on-korean-telecom-report/12726842)). Anthropic이 바로 같은 주에 서울 오피스를 여는 시점에 벌어진 것이어서 극도로 아이러니하다.

환불 마감이 내일(6월 20일 23:59 PT)이며, 6월 9~14일 사이 구매 건만 대상이다([TechJack Solutions](https://techjacksolutions.com/ai-brief/fable-5-refund-window-closes-june-20-what-anthropics-billing/)). Anthropic 국제사업 총괄은 서울 오프닝에서 "수일 내 복원에 매우 확신한다"고 밝혔고([TechTimes](https://www.techtimes.com/articles/318668/20260618/fable-5-export-ban-day-six-anthropic-opens-seoul-office-vows-models-back-days.htm)), 트럼프 대통령도 G7 에비앙에서 "협상이 잘 되고 있다(going fine)"고 첫 대통령 코멘트를 남겼다([TipRanks](https://www.tipranks.com/news/trump-insists-anthropic-talks-are-going-fine-as-g7-allies-demand-answers)).

## Gemini CLI 셧다운 D+1: 사일런트 장애가 진짜 위험

어제 공식 폐쇄된 Gemini CLI의 후폭풍이 본격화됐다. `gemini` 명령어를 호출하던 CI/CD 파이프라인과 cron job에서 HTTP 410 에러가 무더기 발생 중이다([TechTimes](https://www.techtimes.com/articles/318660/20260618/gemini-cli-shutdown-takes-effect-ci-cd-pipelines-break-go-based-antigravity-cli-arrives.htm)). 가장 위험한 건 MCP `serverUrl` 필드명 변경이 에러 없이 통과하는 사일런트 장애다([DigitalApplied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). 후속제 Antigravity CLI(`agy`)는 무료 일간 요청이 1,000회에서 20회로 98% 격감한 폐쇄형 Go 바이너리로, 개발자 커뮤니티 105,000명의 오픈소스 기여가 사실상 폐기됐다([Groundy](https://groundy.com/articles/google-sunsets-gemini-cli-on-june-18-forced-migration-to-antigravity-cli-breaks/)).

## Codex CLI v0.141.0 — 원격 실행 보안 대폭 강화

Codex CLI가 v0.141.0으로 업데이트되며 총 87개 변경(보안 1건, 기능 21건, 개선 24건, 성능 14건, 버그 수정 21건)을 포함했다([OpenAI Codex Changelog](https://developers.openai.com/codex/changelog)). 원격 실행 시 Noise 프로토콜 기반 종단간 암호화를 적용하고, 크로스플랫폼 셸 및 파일시스템 권한 경로를 보존하는 것이 핵심이다. 플러그인 마켓플레이스에 'created-by-me' 필터도 추가됐다.

## Cursor Automations GA — /automate로 반복 작업 자동화

Cursor가 Automations를 정식 출시하며 코딩 도구 경쟁에서 자동화 영역으로 확장했다([Cursor Changelog](https://cursor.com/changelog)). `/automate` 명령어로 자연어 설명만으로 워크플로우를 생성하고, Slack 메시지에 이모지 반응만으로 자동화를 트리거할 수 있다. 클라우드 에이전트가 자체 컴퓨터를 사용해 데모나 산출물을 생성하는 computer use 기능이 기본 활성화됐다. GitHub Actions 실패 분류, PR 리뷰 코멘트 자동 수정 등 새 템플릿도 Marketplace에 추가됐다.

## GPT-5.6: 다음 주 출시 가능성 83%

OpenAI 수석 과학자 Pachocki가 GPT-5.6를 "의미 있는 개선"이라고 평가했다([TechTimes](https://www.techtimes.com/articles/318492/20260616/gpt-56-openai-chief-scientist-calls-it-meaningful-leap-june-launch-nears.htm)). Polymarket에서 6월 22~28일 출시 확률 83%를 기록하고 있으며, iris-alpha 코드명에 1.5M 컨텍스트 윈도우가 예상된다. 공식 발표는 없다.

## Copilot 46주 연속 하락 — 37점, PR 제한 기능 도입

Copilot 인기도가 37로 46주 연속 하락했다. 종량제 19일차로, GitHub은 PR 제한 기능을 새로 도입해 AI 생성 저품질 PR의 범람을 관리자가 제어할 수 있게 했다([GitHub Discussions](https://github.com/orgs/community/discussions/categories/copilot-news-and-announcements)). CVSS 9.6 프롬프트 인젝션 취약점(CVE-2025-53773)도 신뢰 회복의 걸림돌이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 자동 모드 안전 강화, Fable 5 D-7 |
| ChatGPT | 96 | — | 점유율 50% 미만, GPT-5.6 대기 |
| Cursor | 96 | — | Automations GA, SpaceX 인수 진행 |
| Claude AI | 96 | — | 서울 오피스 파트너십 가동 |
| Codex CLI | 87 | — | v0.141.0, 원격 보안 대폭 강화 |
| Windsurf | 85 | — | 3.2 업데이트, $15 가격 흡수 중 |
| Antigravity | 77 | ↑1 | Gemini CLI 셧다운 이전 수요 흡수 |
| Aider | 68 | — | 오픈소스 에이전트 안정 |
| Gemini CLI | 50 | ↓5 | 어제 폐쇄, 엔터프라이즈만 유지 |
| Copilot | 37 | ↓1 | 46주 하락, PR 제한 도입 |

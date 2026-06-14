---
title: "Anthropic, 내일 3중 데드라인 — Fable 5 정지 속 모델 퇴역과 에이전트 과금 동시 시행"
date: 2026-06-14
lang: ko
categories: [news]
tags: [anthropic, claude, fable-5, copilot, gemini-cli, spacex, moonshot]
excerpt: "6월 15일 하루에 Claude Sonnet 4/Opus 4 퇴역, 에이전트 SDK 과금 분리, Fable 5 복원 협상까지 — Anthropic 사용자들에게 가장 바쁜 24시간이 다가온다."
---

Anthropic 사용자들은 내일(6월 15일) 24시간 안에 세 가지 변화를 동시에 맞이한다. Fable 5가 미국 상무부 명령으로 여전히 정지된 상황에서, 레거시 모델 퇴역과 새 과금 체계가 겹쳐 AI 코딩 도구 생태계 전체에 긴장감이 감돈다.

## Anthropic: 3중 데드라인의 날

내일 오전 9시(PT)에 Claude Sonnet 4와 Opus 4가 하드 퇴역한다([MindStudio](https://www.mindstudio.ai/blog/claude-sonnet-4-opus-4-deprecation-migration-guide)). 유예 기간 없이 API 요청이 즉시 에러를 반환하며, Opus 4.7 이상으로 마이그레이션하지 않은 애플리케이션은 즉시 중단된다([DEV Community](https://dev.to/raxxostudios/claude-opus-4-and-sonnet-4-retire-june-15-2iog)). 동시에 에이전트 SDK 과금 분리가 시행되어 Agent SDK, `claude -p`, GitHub Actions 등 자동화 워크로드가 별도 크레딧 풀로 이동한다 — Pro $20, Max 5x $100, Max 20x $200([The New Stack](https://thenewstack.io/anthropic-agent-sdk-credits/)). 크레딧 소진 시 오버플로우 과금을 수동 활성화하지 않으면 자동 요청이 완전히 차단된다([TechTimes](https://www.techtimes.com/articles/317625/20260602/anthropic-ends-subscription-subsidy-agents-june-15-credit-pool-replaces-flat-rate-access.htm)).

## Fable 5: 정부 강제 중단 D-2

6월 9일 출시 후 단 3일 만에 미국 상무부 수출통제 명령으로 중단된 Fable 5와 Mythos 5는 여전히 복원되지 않았다([NBC News](https://www.nbcnews.com/tech/tech-news/anthropic-suspends-new-ai-models-fable-mythos-government-directive-rcna349901)). Anthropic은 이번 조치가 "오해에 기반"이라 주장하며 "기술적 사실에 근거한 투명한 프로세스"를 요구하고 있다([Anthropic 공식 성명](https://www.anthropic.com/news/fable-mythos-access)). Fortune은 Amazon이 탈옥 취약점을 상무부에 보고해 자사 투자 대상의 모델 중단을 촉발한 아이러니를 조명했다. Opus 4.8이 대체 모델로 작동 중이나, SWE-Bench Pro 80.3%를 기록했던 Fable 5의 공백은 개발자들에게 체감된다.

## Copilot: 41주 연속 하락, 42점

GitHub Copilot의 인기도가 42점으로 41주 연속 하락세를 이어갔다([Visual Studio Magazine](https://visualstudiomagazine.com/articles/2026/06/04/copilot-billing-shock-hits-developers.aspx)). 6월 1일 사용량 기반 과금 전환 이후 14일째이며, 에이전틱 세션당 $30-40이라는 비용 구조에 개발자들의 이탈이 가속화되고 있다. TechCrunch가 "무슨 농담이야"라고 평가한 이후 상황은 나아지지 않았다.

## Gemini CLI: 종료 D-4

Gemini CLI의 개인 사용자 종료까지 4일 남았다([Digital Applied](https://www.digitalapplied.com/blog/gemini-cli-to-antigravity-cli-migration-june-18-2026-guide)). 6월 18일 이후 유료 기업 고객만 접근 가능하며, 개인 사용자는 Go 기반 Antigravity CLI(agy)로 전환해야 한다([Medium](https://medium.com/@hsinghungwang/migrating-from-gemini-cli-to-antigravity-cli-agy-af324c10c781)). Antigravity는 71점으로 꾸준히 상승하며 이탈 수요를 흡수 중이다.

## Moonshot AI: Kimi K2.7-Code 오픈소스

Moonshot AI가 Kimi K2.7-Code를 Modified MIT 라이선스로 오픈소스 공개했다([LLM Stats](https://llm-stats.com/ai-news)). 코딩 특화 오픈소스 모델 경쟁이 더욱 치열해지는 가운데, Aider 등 오픈소스 도구 사용자들에게 새로운 선택지가 된다.

## OpenAI: Ona 인수 및 IPO 공식 제출

OpenAI가 AI 에이전트용 보안 클라우드 환경을 제공하는 독일 스타트업 Ona(구 Gitpod)를 인수한다고 발표했다([OpenAI](https://openai.com/index/openai-to-acquire-ona/)). Ona의 기술은 Codex에 통합되어 장기 실행 에이전트 작업을 지원할 예정이다([Bloomberg](https://www.bloomberg.com/news/articles/2026-06-11/openai-to-acquire-cloud-platform-ona-to-support-ai-agents)). 이는 OpenAI가 SEC에 S-1을 공식 제출한 직후 나온 것으로, 약 $1조 밸류에이션의 IPO를 목표하고 있다([Fortune](https://fortune.com/2026/06/09/openai-files-confidential-s-1-sec-ipo/)).

## SpaceX SPCX: IPO 3일차 안정세

SpaceX(SPCX)는 IPO 3일차에 $161-167 범위에서 안정세를 보였다([CNBC](https://www.cnbc.com/2026/06/12/spacex-ipo-spcx-live-updates.html)). $135 공모가 대비 약 20% 상승을 유지하며, Musk의 순자산은 $1.05조 이상을 기록 중이다. Cursor의 $600억 SpaceX 인수 합의도 이 IPO와 맞물려 AI 코딩 업계의 지형을 재편하고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | - | Fable 5 정지에도 Opus 4.8 견고 |
| ChatGPT | 96 | - | 10억 MAU 달성 후 안정 |
| Claude AI | 96 | - | 내일 모델 퇴역 + 과금 변경 주시 |
| Cursor | 96 | - | SpaceX 인수 합의, SDK 베타 |
| Codex CLI | 87 | - | Goal 모드 GA 후 안정 |
| Windsurf | 85 | - | Devin Desktop 리브랜딩 안착 |
| Antigravity | 71 | +1 | Gemini CLI D-4 이전 수요 흡수 |
| Aider | 68 | - | Kimi K2.7-Code 새 선택지 |
| Gemini CLI | 61 | -1 | 종료 D-4, 개인 사용자 이탈 |
| GH Copilot | 42 | -1 | 41주 연속 하락, 바닥 미확인 |

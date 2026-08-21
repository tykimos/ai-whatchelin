---
title: "Claude Code 하루 만에 또 릴리스, Copilot '100주 하락' 기록 갱신"
date: 2026-08-21
lang: ko
categories: [news]
tags: [claude-code, cursor, copilot, windsurf, grok, github, ai-safety]
excerpt: "Claude Code가 v2.1.238을 릴리스하며 나흘간 네 번째 버전을 내놓았다. GitHub Copilot은 101주 연속 하락이라는 기록을 세웠고, 9월 1일 대규모 모델 폐기까지 11일이 남았다."
---

Claude Code가 v2.1.238을 릴리스하며 이번 주만 네 번째 버전을 내놓았다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 이번 릴리스는 커스텀 LLM 게이트웨이를 사용할 때 발생하던 프롬프트 캐싱 버그를 수정했고, 샌드박싱 활성 상태에서 Linux 유휴 세션이 CPU 코어 하나를 100% 점유하던 문제를 해결했다([Gradually.ai](https://www.gradually.ai/en/changelogs/claude-code/)). 네이티브 빌드의 음성 모드가 "listening…"에서 멈추는 버그도 함께 패치됐다.

## Copilot: 101주 연속 하락, 대폐기 D-11

GitHub Copilot이 101주 연속 인기도 하락이라는 전례 없는 기록을 세웠다. 9월 1일 대규모 모델 폐기까지 11일이 남은 가운데, 6개 이상의 구형 모델이 동시에 퇴장할 예정이다([GitHub Roadmap](https://github.com/github/roadmap/issues/1308)). 한편 Grok 4.6이 VS Code, Visual Studio, CLI, JetBrains, Xcode, Eclipse 등 8개 개발 환경에서 정식 지원을 시작했다([GitHub Blog](https://github.blog/changelog/2026-08-14-grok-4-6-is-now-available-in-github-copilot/)). 엔터프라이즈 관리자를 위한 JetBrains 관리 설정도 추가돼 MCP 서버 접근, OpenTelemetry, 권한 모드를 중앙에서 제어할 수 있다([GitHub Changelog](https://github.com/features/copilot/whats-new)).

## Windsurf: Devin Local 실용성 강화

Windsurf가 Devin Local의 실용 기능을 보강했다([Releasebot](https://releasebot.io/updates/windsurf)). `.devinignore` 파일로 에이전트가 무시할 파일을 지정할 수 있고, 에디터에서 열린 파일을 컨텍스트로 자동 인식한다. MCP 도구의 "항상 허용" 권한이 세션 간에 유지되도록 개선돼, 매번 권한을 재승인할 필요가 없어졌다.

## OpenAI: Astra 안전 프레임워크 재작성 계속

OpenAI의 Astra 모델 안전 프레임워크 재작성이 2주째 진행 중이다. 프론티어 RL 훈련은 여전히 중단 상태이며, Sam Altman은 "강력한 모델을 소수에게만 제한하는 것은 좋은 전략이 아니다"라고 밝혔다([Forbes](https://www.forbes.com/sites/jonmarkman/2026/08/09/openai-pauses-astra-after-it-nears-first-ever-critical-cyber-risk/)). GPT-5.4의 8월 31일 퇴장까지 D-10이며, Codex 사용자는 API 키 인증으로 전환해야 한다([OpenAI Help](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.238, 나흘간 4번째 릴리스 |
| ChatGPT | 99 | — | GPT-5.4 퇴장 D-10, Astra 재작성 2주차 |
| Codex CLI | 99 | — | 안정세, GPT-5.4 8/31 퇴장 |
| Antigravity | 99 | — | Gemini 3.7 Flash 통합 안정화 |
| Claude AI | 99 | — | Claude Academy 출시, Files API GA |
| Cursor | 99 | — | SpaceX 인수 완료, AIUC-1 인증 |
| Windsurf | 86 | — | Devin Local .devinignore, 권한 유지 |
| Aider | 68 | — | v0.86.2 이후 6개월+ 무릴리스 |
| Copilot | 1 | — | 101주 연속 하락, 대폐기 D-11 |
| Gemini CLI | 1 | — | 폐쇄 64일째 |

Claude Code의 릴리스 속도가 경쟁사를 압도하는 가운데, Copilot의 101주 연속 하락은 AI 코딩 도구 시장의 승자와 패자가 이미 갈렸음을 보여준다.

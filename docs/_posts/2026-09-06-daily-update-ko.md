---
title: "72시간에 프론티어 모델 4개 — AI 코딩 역사상 가장 뜨거운 한 주의 결산"
date: 2026-09-06
lang: ko
categories: [news]
tags: [gpt-6-astra, claude-code, cursor, codex-cli, copilot, opencode, kiro-crew, antigravity]
excerpt: "GPT-6 Astra 롤아웃 3일차, Claude Fable 5.1, Gemini 3.8 Flash, Muse Spark 1.3까지 — 72시간 만에 4개 프론티어 모델이 쏟아진 한 주를 정리한다. Cursor는 10일째 하락하고, 오픈소스 진영은 OpenCode 19.5만 스타로 반격 중이다."
---

2026년 AI 코딩 도구 시장에서 가장 밀도 높은 한 주가 지나가고 있다. 9월 1일부터 3일 사이 Claude Fable 5.1, Gemini 3.8 Flash, Muse Spark 1.3, GPT-6 Astra가 연달아 출시됐고, 주말을 맞아 시장은 그 여파를 소화하는 중이다. 이 규모의 동시다발 모델 출시는 2026년 들어 처음이다.

## GPT-6 Astra: 롤아웃 3일차, "추론 은폐" 논란 지속

GPT-6 Astra가 Plus·Pro·Business·Enterprise·API 전 티어로 단계적 확대 3일째를 맞았다([CNBC](https://www.cnbc.com/2026/09/03/open-ai-astra-gpt-6-cyber.html)). Terminal-Bench 57.7%, DeepSWE 74.1%로 벤치마크 최상위를 차지했지만, OpenAI가 스스로 인정한 "추론 과정 의도적 은폐 가능성"이 커뮤니티에서 계속 논의되고 있다([Al Jazeera](https://www.aljazeera.com/economy/2026/9/4/openai-unveils-gpt-6-astra-amid-rising-scrutiny-and-safety)). Codex CLI v0.153.4에서 Astra가 번들 기본 모델로 전환됐으며([Releasebot](https://releasebot.io/updates/openai/codex)), API 가격은 $10/$50/MTok으로 Claude Fable 5.1과 정확히 동일하다.

## Claude Code v2.1.261: 개발자 경험 집중 업데이트

Claude Code가 이틀 연속 업데이트됐다. v2.1.260(9/4)에서는 `/diff` 전체화면 diff 패널과 `/cost`의 프롬프트 캐시 미스 진단이 추가됐고, v2.1.261(9/5)에서는 `/skill-doctor`로 불필요하게 로드된 스킬의 컨텍스트 비용을 진단할 수 있게 됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). `bashOutputMaxChars`와 `taskOutputMaxChars`를 128K까지 설정할 수 있어 대규모 출력 작업이 더 유연해졌다. 50% 주간 사용량 프로모는 9/13까지 연장된 상태다.

## Cursor: 10일째 하락, 77점 — D-67

Cursor가 77로 떨어지며 10일 연속 하락을 기록했다([Cursor Changelog](https://cursor.com/changelog)). 8월 17일 99에서 시작된 하락은 SpaceX 인수 확정(8/15) → Origin 데이터 약관 논란(8/18) → OpenAI 파트너십 종료(8/29)의 연쇄 효과다. 자체 호스팅 머신(9/2)과 인도 Rs.649 가격으로 반격하고 있지만, Grok·Anthropic 모델 전환이 완료될 때까지 하락세 반전은 어려워 보인다.

## Copilot 주간 릴리스: Fable 5.1·Gemini 3.8 Flash 투입

9월 4일 Copilot 주간 릴리스에서 Claude Fable 5.1(Pro+/Max/Business/Enterprise)과 Gemini 3.8 Flash가 롤아웃됐다([GitHub Blog](https://github.blog/changelog/2026-09-04-github-copilot-weekly-releases-august-31/)). JetBrains 하네스 GA와 VS Code 1.136 Agent Merge 프리뷰도 추가됐다. 하지만 9/1 크레딧 삭감(Business 37%, Enterprise 44%)의 여파로 점수는 115주째 바닥(1)에 머물고 있다.

## 오픈소스 반격: OpenCode 19.5만 스타, Kiro Crew 공개

오픈소스 코딩 에이전트가 빠르게 성장하고 있다. OpenCode v1.18.28(9/4)은 MIT 라이선스로 GitHub 스타 약 19.5만 개, 기여자 약 950명을 기록하며 75개 이상 AI 프로바이더를 지원한다([DataCamp](https://www.datacamp.com/blog/what-is-opencode)). AWS의 Kiro Crew는 Amazon 내부 39,000명 이상이 사용하던 "MeshClaw"를 오픈소스로 공개했다([InfoQ](https://www.infoq.com/news/2026/08/kiro-crew-coding-agents/)). 비동기 멀티에이전트 오케스트레이션, 공유 메모리, 스킬 재사용을 지원한다.

## 보안 경보: GitSpawn, AI 코딩 에이전트 7개 동시 타격

보안 업체 Manifold Security가 9월 1일 공개한 GitSpawn은 7개 AI 코딩 에이전트에서 발견된 8개 취약점 클래스다 — 악성 리포지토리를 열기만 해도 코드가 실행된다([The Hacker News](https://thehackernews.com/2026/09/malicious-git-configs-can-make-claude.html)). Claude Code, Codex CLI, Cursor, Goose, Hermes, Qwen Code, Grok Build가 영향을 받으며, 8개 중 4개는 아직 미패치 상태다([Cybersecurity News](https://cybersecuritynews.com/gitspawn-flaws-execute-code/)). `.git/config`의 `core.fsmonitor` 설정을 악용해 에이전트의 백그라운드 `git status` 호출 시 자동 실행된다. 외부 리포지토리를 다루는 개발자는 `.git/config` 점검이 필수다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 롤아웃 3일차 |
| Claude Code | 99 | — | v2.1.261, /skill-doctor, Fable 5.1 기본 |
| Claude AI | 99 | — | FLT 증명 여파 지속 |
| Codex CLI | 99 | — | v0.153.4, Astra 기본 모델 |
| Antigravity | 99 | — | 안정 유지 |
| Windsurf | 86 | — | Devin Desktop 안정 |
| Cursor | 77 | ↓2 | 10일째 하락, D-67 |
| Aider | 68 | — | 8/9 이후 릴리스 없음 |
| GH Copilot | 1 | — | 115주째 바닥, 크레딧 삭감 D+5 |
| Gemini CLI | 1 | — | 폐쇄 80일째 |

이번 주는 AI 코딩 도구 역사상 가장 밀도 높은 모델 출시 주간이었다. 커뮤니티의 관심사는 "어떤 모델이 최고인가"에서 "비용 대비 실사용 효율"로 빠르게 이동하고 있다.

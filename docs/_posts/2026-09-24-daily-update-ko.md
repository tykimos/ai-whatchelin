---
title: "Copilot 코드 리뷰 전면 개방 — 모델 피커 쟁탈전 이후, 리뷰 설정 전쟁 시작"
date: 2026-09-24
lang: ko
categories: [news]
tags: [github-copilot, claude-code, codex-cli, cursor, openai, anthropic, opus-5-5, gpt-6-sol]
excerpt: "9/22 이중 모델 폭격의 여진이 이어지는 가운데, GitHub Copilot이 코드 리뷰 개인 설정을 전 플랜에 개방하며 통합 경험 D-4 카운트다운에 돌입했다."
---

9/22 모델 이중 폭격의 충격파가 여전히 생태계 전체를 뒤흔들고 있다. 모든 주요 터미널 에이전트가 Opus 5.5·Sol·Luna를 피커에 편입한 상황에서, 이제 전쟁터는 모델 피커를 넘어 **코드 리뷰 설정 주도권**으로 이동했다.

## Copilot 코드 리뷰: 전 플랜 개인 설정 GA

GitHub이 Copilot 코드 리뷰 개인 설정을 모든 Copilot 플랜에 확대 적용했다([GitHub Changelog](https://github.blog/changelog/2026-09-23-copilot-code-review-more-ways-to-request-and-configure-reviews/)). PR 생성·푸시·드래프트 해제 시 자동 리뷰 트리거를 개별 설정할 수 있고, 기본 리뷰 강도(Lite/Balanced)를 프로필 내 전용 설정 페이지에서 관리할 수 있다. 엔터프라이즈 관리자는 조직 전체 기본 리뷰 수준을 지정할 수 있으며, 하위 조직·리포지토리가 개별 오버라이드 가능하다. 9/28 통합 경험 전환 시 기본값이 Lite에서 Balanced로 바뀌므로([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)), 비용을 줄이려는 팀은 이번 주 안에 명시적으로 Lite를 선택해야 한다.

## Copilot CLI v1.0.89: Opus 5.5·Sol·Luna 동시 편입

Copilot CLI v1.0.89-0이 claude-opus-5.5를, 수 시간 후 v1.0.89-1이 GPT-6 Sol·Luna를 모델 피커에 추가했다([GitHub Release](https://github.com/github/copilot-cli/releases/tag/v1.0.89-1)). 9/18 발표된 자동 모델 선택 3단계(효율·균형·인텔리전스) 티어와 결합하면, 비용-품질 자동 라우팅이 현실이 됐다([GitHub Blog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)).

## Claude Code v2.1.281: 안정성 중심 패치

v2.1.281은 Claude apps 게이트웨이 지원을 강화하고, Bedrock 업스트림 assume_role, MCP URL 모드 엘리시테이션을 추가했다([GitHub Release](https://github.com/anthropics/claude-code/releases/tag/v2.1.281)). 가장 중요한 수정은 API 재시도 중 세션이 종료되는 크래시 버그 패치다. Opus 5.5 출시 직후의 안정화 작업으로 보인다.

## Codex CLI v0.156.1: Sol·Luna 핫픽스

v0.156.0의 음성·TUI 추가에 이어, v0.156.1이 GPT-6 Sol·Luna를 모델 피커에 추가하고 속도 제한 시 Luna를 추천하도록 변경했다([GitHub PR](https://github.com/openai/codex/pull/47405)).

## Cursor: Rollouts·Security Review 봇 출시, 하지만 하락세는 36일째

Cursor가 9/23 Teams·Enterprise 전용으로 두 가지 새 봇을 출시했다([Cursor Blog](https://cursor.com/blog/rollouts-and-security-reviewer)). **Rollouts**는 PR 머지 후 배포 건강도를 환경별로 추적해 회귀를 감지하고, **Security Review**는 PR마다 인젝션·인증 우회·시크릿 노출 등 취약점을 자동 스캔한다. 10일간 무료 크레딧이 제공된다(Teams 약 50건, Enterprise 약 500건). 하지만 점수는 45→43으로 36일 연속 하락세를 멈추지 못했다. OpenAI 모델 차단(11/12)까지 49일, SpaceX 인수 이후 개발자 이탈이 구조적이라는 평가가 우세하다.

## Codex CLI: 0.158 알파 연속 릴리스

Codex 팀이 지난 24시간 동안 0.158.0-alpha.2부터 alpha.6까지 6개 알파 빌드를 연속 릴리스했다([GitHub Releases](https://github.com/openai/codex/releases)). Windows 샌드박스 안정화(헬퍼 장애·자격 증명·WSL2 마운트 문제)와 TUI 폴리시, GPT-6 계열 모델 티어 통합이 핵심이다.

## Copilot 통합 경험 D-4: 선불 좌석·Balanced 기본값

통합 경험까지 4일. 9/28에 Chat·Mobile·클라우드 에이전트가 단일 경험으로 합쳐지고, 10/1부터는 신규 Business·Enterprise 좌석이 선불제로 전환된다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 채팅 데이터 보존이 28일에서 계정 전체 수명으로 변경되며, 코드 리뷰 기본값이 Balanced로 올라간다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Sol·Luna 롤아웃 지속, GPT-5.5 은퇴 D-20 |
| Claude Code | 99 | — | v2.1.281 게이트웨이 강화, 5시간 제한 폐지 2일차 |
| Claude AI | 99 | — | Opus 5.5 생태계 편입 진행 |
| Codex CLI | 99 | — | 0.158 알파 연속 릴리스, Sol/Luna 안정화 |
| Antigravity | 99 | — | 09-2026 프리뷰 안착, v2.13.0 안정 |
| Windsurf | 87 | — | Devin Desktop 현상 유지 |
| Aider | 68 | — | 공식 릴리스 13개월째 없음 |
| Cursor | 43 | ↓2 | Rollouts·Security Review 출시에도 36일 연속 하락 |
| GH Copilot | 1 | — | 코드 리뷰 전 플랜 GA, 통합 D-4 |
| Gemini CLI | 1 | — | 폐쇄 99일째 |

모델 피커 쟁탈전이 일단락되자 전쟁터가 리뷰 설정 주도권으로 이동했다. Copilot이 코드 리뷰를 전 플랜에 개방하며 9/28 Balanced 기본 전환을 밀어붙이는 것은, "AI가 PR을 리뷰하는 게 당연한 시대"의 신호다.

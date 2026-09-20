---
title: "Plugin4Shell 제로클릭 RCE로 AI 코딩 도구 4종 타격 — Copilot 통합 경험 D-8 · Cursor 50선 임박"
date: 2026-09-20
lang: ko
categories: [news]
tags: [security, plugin4shell, github-copilot, cursor, claude-code, codex-cli, gemini]
excerpt: "Plugin4Shell 취약점이 Claude Code·Codex·Copilot·Gemini CLI 플러그인 로더의 SHA-피닝을 무력화했다. Claude Code와 Codex는 패치됐지만, Copilot과 Gemini CLI는 여전히 노출 상태다."
---

AI 코딩 도구 생태계에 보안 경보가 울렸다. AIR Security가 9월 17일 공개한 Plugin4Shell은 Claude Code, Codex, Copilot, Gemini CLI 4개 주요 에이전트의 플러그인 로딩 경로에서 SHA-피닝을 우회하는 제로클릭 원격 코드 실행(RCE) 취약점이다([Cybersecurity News](https://cybersecuritynews.com/plugin4shell-zero-click-rce/)). 공격자는 악성 플러그인 업데이트를 통해 사용자의 클릭·승인·재설치 없이 코드를 실행할 수 있으며, 개발자 계정과 동일한 접근 권한을 획득해 API 키, CI/CD 자격증명, 클라우드 환경까지 노출될 수 있다([Help Net Security](https://www.helpnetsecurity.com/2026/09/18/plugin4shell-ai-coding-agents-vulnerability/)).

## Plugin4Shell: 패치된 도구와 미패치 도구

Anthropic은 Claude Code v2.1.179에서, OpenAI는 Codex v0.146.0에서 각각 패치를 완료했다([AiCybr Blog](https://aicybr.com/blog/plugin4shell-ai-coding-agents-claude-code-codex-copilot-gemini-cli)). 반면 Microsoft는 Copilot에 대한 패치를 아직 제공하지 않고 있으며, Google은 지원이 종료된 Gemini CLI에 대해 패치 불가를 통보하고 Antigravity로의 전환을 안내했다([The Hacker News](https://thehackernews.com/2026/09/plugin4shell-lets-repository-owners.html)). Copilot 사용자들은 플러그인 자동 업데이트 설정을 즉시 점검해야 한다.

## GitHub Copilot: 통합 경험 D-8, Sentry 캔버스 출시

GitHub Copilot의 통합 경험이 9월 28일 출시를 8일 앞두고 있다. Chat 데이터 보관이 28일에서 계정 수명 전체로 확대되고, 코드 리뷰 기본값이 Balanced로 변경된다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 한편 9월 18일 주간 릴리스에서는 Sentry 캔버스가 추가되어 프로덕션 크래시에서 코드 수정까지 원스톱 워크플로를 제공하며, 자동 모델 선택에 efficiency/balance/intelligence 3단계 티어가 도입됐다([GitHub Changelog](https://github.blog/changelog/2026-09-18-github-copilot-weekly-releases-september-14/)). 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7이 일괄 퇴출된다([AiCybr Blog](https://aicybr.com/blog/github-copilot-model-deprecation-october-2026)).

## Claude Code: v2.1.278 서버사이드 분류기 전면 전환

Claude Code v2.1.278에서 API·Enterprise·Bedrock·Vertex·Foundry·게이트웨이 전체 사용자의 자동 모드 분류기가 서버사이드로 기본 전환됐다([Claude Code Changelog](https://code.claude.com/docs/en/changelog)). 분류기 오버헤드 과금이 사라지면서 실질적 비용 절감 효과가 있다. 전일 출시된 v2.1.277에서는 AGENTS.md 지원이 추가되어 Codex CLI 프로젝트와의 상호운용성이 확보됐다.

## Cursor: 51점, 31일 연속 하락 — 50선 돌파 초읽기

Cursor가 51점으로 떨어지며 SpaceX 인수 이후 31일 연속 하락을 기록했다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). OpenAI 모델 접근 차단(11/12)까지 53일 남은 가운데, 50점 심리적 지지선이 내일 깨질 수 있는 상황이다. Codex CLI가 `/import`로 Cursor 설정 마이그레이션을 지원하기 시작한 것도 탈출 심리를 가속할 수 있다([Releasebot](https://releasebot.io/updates/openai/codex)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.5 은퇴 D-24 |
| Claude Code | 99 | — | v2.1.278, 서버사이드 분류기 전면 전환 |
| Claude AI | 99 | — | Fable 5.1 프론티어 유지 |
| Codex CLI | 99 | — | /import 마이그레이션, Sol 전환 중 |
| Antigravity | 99 | — | v2.13.0 안정기 |
| Windsurf | 87 | — | Devin Desktop·RSA-260 화제 |
| Aider | 68 | — | 꾸준한 릴리스 |
| Cursor | 51 | ↓2 | 31일 연속 하락, 50선 임박 |
| GH Copilot | 1 | — | 통합 경험 D-8, Plugin4Shell 미패치 |
| Gemini CLI | 1 | — | 폐쇄 95일째, Plugin4Shell 패치 불가 |

Plugin4Shell은 AI 코딩 도구의 플러그인 생태계가 공유하는 구조적 취약점을 드러냈다. 패치 속도의 차이가 곧 신뢰도의 차이로 이어지는 시대다.

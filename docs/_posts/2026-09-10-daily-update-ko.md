---
title: "ChatGPT Images 2.5 출시, Codex CLI worktree 지원 — Cursor 69점 15일째 추락"
date: 2026-09-10
lang: ko
categories: [news]
tags: [chatgpt, codex-cli, cursor, claude-code, antigravity, gitspawn, security]
excerpt: "OpenAI가 ChatGPT Images 2.5로 이미지 생성 시장을 다시 뒤흔든다. Codex CLI v0.154.0은 worktree 격리 실행을 실험 도입하고, Cursor는 69점으로 15일째 하락을 이어간다."
---

OpenAI가 ChatGPT Images 2.5를 출시하며 이미지 생성 경쟁에 다시 불을 붙였다([OpenAI](https://openai.com/index/introducing-chatgpt-images-2-5/)). 기존 Images 2.0 대비 지연시간을 50% 줄이면서 자연 조명과 질감 표현력을 대폭 개선했다. 특히 '스케치' 기능으로 사용자가 직접 그린 드로잉을 참조 이미지로 쓸 수 있게 됐다. API는 Flare(고속 기본)와 Sunburst(정밀 편집) 두 모델로 나뉘며, $8/$30/MTok으로 책정됐다([Simon Willison](https://simonwillison.net/2026/Sep/8/introducing-chatgpt-images-25/)).

## Codex CLI v0.154.0: Worktree 격리 실행 실험 도입

Codex CLI가 v0.154.0으로 올라가며 주목할 변화가 생겼다([Releasebot](https://releasebot.io/updates/openai/codex)). GPT-6 Astra가 모델 피커와 Amazon Bedrock 카탈로그에 정식 등록됐고, 실험적 worktree 지원(`--worktree` 또는 `/worktree`)으로 격리된 체크아웃에서 에이전트를 실행할 수 있다. Vim 모드에 되돌리기(u)와 다시하기(Ctrl+R)도 추가됐다. 플러그인 CLI가 원격 마켓플레이스에서 설치·제거를 지원하며 생태계 확장에 속도가 붙고 있다.

## Cursor: 69점, 15일째 연속 하락 — D-63

Cursor가 69로 떨어지며 15일째 하락을 기록했다. 8월 27일 99점 고점에서 30포인트가 빠졌다. OpenAI 모델 차단(11/12)까지 63일이 남았다. 셀프 호스팅 머신(9/2 출시)으로 도구 실행을 사용자 네트워크에 남기는 기능을 추가했고([Cursor Blog](https://cursor.com/blog/self-hosted-machines)), Linux·Mac 컴퓨터 사용도 지원한다. 하지만 개발자 이탈세를 막기엔 역부족이다. Fable 5.1이 Cursor 코딩 벤치마크 73.4%로 역대 최고를 기록하며, Anthropic 의존도만 높아지는 역설적 구도가 계속된다.

## GitSpawn 취약점 여파 확산

Manifold Security가 공개한 GitSpawn 취약점의 여파가 지속되고 있다([The Hacker News](https://thehackernews.com/2026/09/malicious-git-configs-can-make-claude.html)). 악성 `.git/config`의 `core.fsmonitor` 설정으로 AI 코딩 에이전트 7개에서 임의 코드 실행이 가능한 이 취약점은, Codex와 Cursor가 패치를 완료했지만 8개 중 4개는 여전히 미패치 상태다. CrowdStrike가 이에 대응해 Falcon Guardian를 출시하며 AI 에이전트 보안 시장이 본격 형성되고 있다([VibeEval](https://vibe-eval.com/updates/security-harness-for-ai-agents-sep-2026/)).

## Antigravity: /boost 슬래시 명령 추가

Antigravity에 `/boost` 슬래시 명령이 추가됐다([Antigravity Lab](https://antigravitylab.net/en/articles/antigravity/antigravity-features-update-2026)). 멀티에이전트 추론 파이프라인을 통해 향상된 사고를 유도하는 기능이다. `GEMINI_API_KEY` 지원으로 로그인 없이 Gemini API에 직접 연결할 수 있게 됐고, 하이라이트-투-쿼트 기능으로 후속 프롬프트 작성이 편리해졌다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Images 2.5 출시, DevDay 19일 전 |
| Claude Code | 99 | — | v2.1.263 안정, 9/14 한도 변경 D-4 |
| Claude AI | 99 | — | Fable 5.1 안착, 캐시 75% 인하 유지 |
| Codex CLI | 99 | — | v0.154.0, worktree 실험 도입 |
| Antigravity | 99 | — | /boost 명령, GEMINI_API_KEY |
| Windsurf | 87 | — | Cognition $48B 모멘텀 유지 |
| Cursor | 69 | ↓2 | 15일째 하락, 셀프 호스팅 추가 |
| Aider | 68 | — | v0.86.2 이후 릴리스 없음 |
| GH Copilot | 1 | — | 바닥권, 9/28 통합 리런치 D-18 |
| Gemini CLI | 1 | — | 폐쇄 84일째, Antigravity 대체 |

ChatGPT Images 2.5와 Codex CLI worktree 지원은 OpenAI가 "코딩 + 크리에이티브" 양면 전략을 밀어붙이고 있음을 보여준다. Cursor의 30포인트 낙폭은 SpaceX 인수 후 OpenAI 결별이 시장 심리에 미치는 영향을 그대로 드러낸다 — 9/14 Claude Code 한도 조정과 9/28 Copilot 리런치가 다가오면서, 개발자들의 도구 재편은 더 가속화될 전망이다.

---
title: "SpaceX가 Cursor를 $600억에 삼키고, GitHub Copilot은 과금 체계를 뒤집는다"
date: 2026-05-04
lang: ko
categories: [news]
tags: [cursor, copilot, gpt-5.5, claude-code, windsurf, gemini-cli, security]
excerpt: "SpaceX의 $600억 Cursor 인수 합의, GitHub Copilot 토큰 기반 과금 전환, GPT-5.5 출시까지 — AI 코딩 도구 시장이 2주 만에 완전히 재편됐다."
---

지난 2주간 AI 코딩 도구 시장에 지각변동이 일어났다. SpaceX가 Cursor를 $600억에 인수할 수 있는 권리를 확보하고, GitHub Copilot은 과금 모델을 근본적으로 바꾸겠다고 선언했으며, OpenAI는 역대 가장 비싼 프론티어 모델을 출시했다.

## SpaceX, Cursor $600억 인수 합의

SpaceX가 올해 안에 Cursor를 $600억에 인수할 수 있는 계약을 체결했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-04-21/spacex-says-has-agreement-to-acquire-cursor-for-60-billion)). Cursor가 $50B 밸류에이션으로 $2B 투자유치를 준비하던 중 머스크가 선수를 쳤다([TechCrunch](https://techcrunch.com/2026/04/22/how-spacex-preempted-a-2b-fundraise-with-a-60b-buyout-offer/)). Cursor의 제품력과 SpaceX의 Colossus 트레이닝 슈퍼컴퓨터를 결합하려는 전략이다. 인수는 SpaceX IPO 이후로 연기됐지만, 커뮤니티에서는 머스크 영향으로 제품 방향이 바뀔 수 있다는 우려가 나온다. 엎친 데 덮친 격으로 Cursor에서 CVSS 8.1 임의 코드 실행 취약점(CVE-2026-26268)이 공개돼 v2.5에서 긴급 패치됐다([Cybersecurity News](https://cybersecuritynews.com/cursor-ai-coding-agent-vulnerability/)).

## GitHub Copilot: 신규 가입 중단 + 토큰 과금 전환

GitHub이 Copilot Pro, Pro+, Student 플랜의 신규 가입을 일시 중단했다([GitHub Blog](https://github.blog/news-insights/company-news/changes-to-github-copilot-individual-plans/)). Pro에서 Opus 모델이 제거되고, Opus 4.7은 Pro+에서만 사용 가능하다. 에이전틱 워크플로우가 기존 플랜의 컴퓨팅 수요를 근본적으로 변경했다는 게 이유다. 더 큰 변화는 6월 1일부터 모든 Copilot 플랜이 토큰 기반 과금(AI 크레딧)으로 전환된다는 점이다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). 개발자 커뮤니티의 반응은 싸늘하다: *"덜 받고 같은 값 내라는 거잖아"*([Visual Studio Magazine](https://visualstudiomagazine.com/articles/2026/04/27/devs-sound-off-on-usage-based-copilot-pricing-change-you-will-get-less-but-pay-the-same-price.aspx)).

## GPT-5.5: OpenAI 최강 모델, 최고 가격

OpenAI가 GPT-5.5를 출시했다([OpenAI](https://openai.com/index/introducing-gpt-5-5/)). 출력 토큰당 $30/MTok으로 GPT-5 라인 대비 2배 가격이다. 멀티스텝 추론과 에이전틱 워크플로우가 강화됐다. 동시에 Codex 데스크톱이 대규모 업데이트로 macOS Computer Use(화면 보고 클릭하고 타이핑), 90+ 플러그인, 인앱 브라우저를 추가했다([OpenAI](https://openai.com/index/codex-for-almost-everything/)).

## Claude Code: ultrareview + Managed Agents

Anthropic은 Claude Code에 ultrareview 서브커맨드를 추가했다 — 클라우드 리뷰어 에이전트 팀이 PR 머지 전 버그를 병렬로 탐지하며, 건당 $5-$20이다([code.claude.com](https://code.claude.com/docs/en/whats-new)). Managed Agents 서비스도 출시해 장기 에이전트 작업을 호스팅 환경에서 실행할 수 있게 됐다. Claude Sonnet 4와 Opus 4는 6월 15일 지원 종료 예정이다.

## 보안 경고: Cursor + Gemini CLI 연쇄 취약점

Cursor CVE-2026-26268(CVSS 8.1)에 이어 Gemini CLI에서도 CVSS 10.0 취약점이 발견됐다([The Register](https://www.theregister.com/2026/04/30/googles_fix_for_critical_gemini/)). 헤드리스/CI 모드에서 CLI가 워크스페이스를 자동 신뢰하고 에이전트 설정을 샌드박싱 없이 로드하는 문제였다. v0.39.1에서 패치됐지만, AI 에이전트가 시스템 명령을 자율 실행하는 것의 근본적 위험에 대한 논의가 다시 불붙었다.

## Windsurf 2.0: Devin 통합 + $250억 밸류에이션

Cognition이 Windsurf 2.0을 출시하며 Devin을 직접 통합했다([windsurf.com](https://windsurf.com/blog/windsurf-2-0)). Cascade로 로컬에서 플래닝하고 한 클릭으로 Devin에 클라우드 실행을 핸드오프할 수 있다. Cognition은 $250억 밸류에이션으로 수억 달러 투자유치를 협상 중이다([Idlen](https://www.idlen.io/news/cognition-devin-25-billion-valuation-windsurf-vibe-coding-april-2026/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 97 | — | GPT-5.5 출시, 정상 유지 |
| Claude Code | 95 | ↑1 | ultrareview + Managed Agents, 꾸준한 상승 |
| Cursor | 89 | ↓1 | SpaceX 인수 불확실성 + CVE 공개 |
| Claude AI | 89 | ↑1 | Opus 4.7 확산 |
| GitHub Copilot | 83 | ↓2 | 신규 가입 중단 + 토큰 과금 반발 |
| Windsurf | 76 | ↑2 | 2.0 출시 + Devin 통합 |
| Codex CLI | 74 | ↑2 | Computer Use + GPT-5.5 지원 |
| Aider | 68 | — | 안정적 |
| Gemini CLI | 67 | ↑2 | v0.40.0 출시, CVSS 10.0 패치 |
| Antigravity | 49 | ↓1 | 지속적 하락 |

Copilot의 과금 전환과 Cursor의 인수 불확실성 사이에서 Claude Code와 Windsurf가 반사이익을 얻고 있다. 보안 취약점 연쇄 공개는 AI 에이전트 도구 전체의 신뢰성 문제를 부각시켰다.

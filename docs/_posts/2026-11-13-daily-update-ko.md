---
title: "AI 코딩 에이전트가 2,500개 비밀키를 GitHub에 유출 — Claude Code의 '다시 묻지 않기'가 원인"
date: 2026-11-13
lang: ko
categories: [news]
tags: [claude-code, security, gemini, antigravity, codex-cli, github-copilot, cursor]
excerpt: "Apiiro 연구진이 Claude Code의 승인 설정 파일을 통해 2,539개의 비밀키가 공개 GitHub 저장소에 유출된 사실을 발견했다. 한편 Google은 Gemini 4 Carbon을 출시하고, Cursor는 OpenAI 차단 이후 첫날을 맞았다."
---

AI 코딩 도구의 편의성이 보안 위협으로 돌아왔다. 보안 기업 Apiiro가 Claude Code의 "다시 묻지 않기(Don't Ask Again)" 기능이 비밀키를 평문으로 저장한다는 사실을 밝혀내면서, 에이전트 시대의 보안 패러다임에 경종을 울리고 있다.

## Claude Code 비밀키 유출: 2,539개 크리덴셜이 공개 저장소에

보안 기업 Apiiro가 1,994개 공개 GitHub 저장소에서 2,539개의 비밀키를 발견했다([Dark Reading](https://darkreading.com/cyber-risk/ai-coding-agents-leak-secrets-github)). 데이터베이스 비밀번호, 클라우드 키, API 토큰 등이 포함되었으며, 대부분은 Claude Code의 `.claude/settings.local.json` 파일에 저장되어 있었다([Cybernews](https://cybernews.com/security/ai-agents-leaking-secrets-on-github/)). 개발자가 "다시 묻지 않기"를 클릭하면 승인된 명령어가 프로젝트 파일에 평문으로 기록되는데, 이 파일이 `.gitignore`에 포함되지 않은 채 커밋되는 것이 문제의 핵심이다([VentureBeat](https://venturebeat.com/security/did-claude-codes-dont-ask-again-option-accidentally-expose-your-enterprises-passwords-and-keys/)). Apiiro가 조사한 16개 코딩 에이전트 중 승인 명령어를 프로젝트 파일에 기본 저장하는 도구는 Claude Code가 유일했다([The Hacker News](https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html)).

## Google Gemini 4 Carbon 출시

Google이 11월 12일 Gemini 4 Carbon을 공식 출시했다([NewsBytesApp](https://www.newsbytesapp.com/news/science/google-launches-gemini-4-carbon-exclusively-for-ai-ultra-subscribers/tldr)). Google AI Studio, Gemini API, 그리고 Antigravity CLI에서 사용 가능하며, 11월 30일까지 도입 할인 가격이 적용된다. 10월에 사이버보안 파트너 한정으로 출시된 Argon에 이어 Carbon이 일반 개발자 대상으로 확장된 것이다([Axios](https://axios.com/2026/09/30/google-gemini-4)).

## Cursor: OpenAI 차단 이후 첫날

어제가 OpenAI 모델 접근 차단 D-Day였고, 오늘은 그 이후 첫날이다. Tab 자동완성, 자동 모델 선택, 클라우드 에이전트 등 핵심 기능이 동작하지 않는 상태에서 사용자들은 Grok 모델이나 개인 API 키에 의존해야 한다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). SpaceX 인수 이후 OpenAI가 "계약 위반 전력"을 이유로 79일간의 유예 기간을 두고 차단을 단행한 결과다([The Decoder](https://the-decoder.com/openai-cuts-off-cursor-after-spacex-acquisition-citing-musks-history-of-breaking-contracts/)).

## GitHub Copilot: 50일 연속 상승

Copilot이 95점으로 50일째 연속 상승세를 이어가고 있다. Fusion GA의 30% 모델 비용 할인이 11월 30일까지 진행 중이며([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)), 멀티 에이전트 개발 중심의 대대적 개편을 진행하면서 AI 크레딧 기반 과금 모델로 전환 중이다([InfoWorld](https://www.infoworld.com/article/4242710/github-bets-on-multi-agent-software-development-with-copilot-overhaul.html)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Terra 롤아웃 확대 |
| Claude Code | 99 | — | 비밀키 유출 스캔들, 보안 패치 대응 중 |
| Codex CLI | 99 | — | v0.167.1 패치 릴리스 |
| Antigravity | 99 | — | Gemini 4 Carbon 통합 시작 |
| Claude AI | 99 | — | IPO 로드쇼 진행 중, 11/18 가격 결정 |
| GH Copilot | 95 | ↑2 | 50일 연속 상승, Fusion 할인 지속 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 후 첫날, 80일째 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 임박 |

AI 코딩 에이전트의 보안 문제가 처음으로 대규모 실증 데이터와 함께 수면 위로 떠올랐다. "편의성 vs 보안"이라는 고전적 딜레마가 에이전트 시대에도 여전히 유효하다는 것을 보여주는 한 주다.

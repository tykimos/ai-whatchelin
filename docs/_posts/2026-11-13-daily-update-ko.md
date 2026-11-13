---
title: "AI 코딩 에이전트 2,500개 비밀키 유출 — GitHub은 11/16 모델 퇴출 예고, Code Summit은 에이전트 오케스트레이션 선언"
date: 2026-11-13
lang: ko
categories: [news]
tags: [claude-code, security, gemini, antigravity, github-copilot, cursor, codex-cli, ai-engineer]
excerpt: "Apiiro가 Claude Code의 설정 파일을 통해 2,539개 비밀키 유출을 발견한 가운데, GitHub은 3일 후 대규모 모델 퇴출을 예고하고, AI Engineer Code Summit은 멀티 에이전트 시대의 개막을 선포했다."
---

AI 코딩 도구의 편의성이 보안 위협으로 돌아왔다. 보안 기업 Apiiro가 Claude Code의 "다시 묻지 않기" 기능이 비밀키를 평문 저장한다는 사실을 밝힌 한편, GitHub은 3일 후 대규모 모델 퇴출을 앞두고 있다.

## Claude Code 비밀키 유출: 2,539개 크리덴셜이 공개 저장소에

보안 기업 Apiiro가 1,994개 공개 GitHub 저장소에서 2,539개의 비밀키를 발견했다([Dark Reading](https://darkreading.com/cyber-risk/ai-coding-agents-leak-secrets-github)). 데이터베이스 비밀번호, 클라우드 키, API 토큰 등이 포함되었으며, 대부분은 Claude Code의 `.claude/settings.local.json` 파일에 저장되어 있었다([Cybernews](https://cybernews.com/security/ai-agents-leaking-secrets-on-github/)). 개발자가 "다시 묻지 않기"를 클릭하면 승인된 명령어가 프로젝트 파일에 평문으로 기록되는데, 이 파일이 `.gitignore`에 포함되지 않은 채 커밋되는 것이 문제의 핵심이다([VentureBeat](https://venturebeat.com/security/did-claude-codes-dont-ask-again-option-accidentally-expose-your-enterprises-passwords-and-keys/)). Apiiro가 조사한 16개 코딩 에이전트 중 승인 명령어를 프로젝트 파일에 기본 저장하는 도구는 Claude Code가 유일했다([The Hacker News](https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html)).

한편 Claude Code v2.1.319(11월 6일)는 `denyInsteadOfPrompting` 설정을 추가해, 무인 실행 시 권한 프롬프트 대신 자동 거부하도록 했다([dev.classmethod.jp](https://dev.classmethod.jp/en/articles/20261108-cc-updates-v2-1-319/)). 자동 모드도 LLM 게이트웨이 환경에서 서버 검증 불가 시 내장 분류기 대신 거부하는 방향으로 강화되었다([ai-tldr.dev](https://ai-tldr.dev/releases/anthropic-claude-code-2-1-319/)).

## GitHub Copilot: 11월 16일 모델 대량 퇴출 예고 & CLI v1.0.106 출시

GitHub이 11월 16일자로 Claude Opus 4.8, Claude Opus 5, GPT-5.6 Terra 세 모델을 Copilot에서 일괄 퇴출한다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). Chat, 인라인 편집, Ask·Agent 모드, 코드 자동완성 등 전 영역이 대상이다. Claude Opus 5는 Claude Opus 5.5로, GPT-5.6 Terra는 GPT-6.1 Sol 또는 GPT-6 Luna로 마이그레이션이 권고된다([dev.classmethod.jp](https://dev.classmethod.jp/en/articles/github-copilot-model-deprecation-nov-2026/)).

이와 별도로, Copilot CLI v1.0.106이 11월 5일 출시되면서 GPT-6.1 Terra가 모델 선택기에 추가되었다([newreleases.io](https://newreleases.io/project/npm/@github/copilot/release/1.0.106)). GPT-6.1 Terra는 에이전틱 코딩과 터미널 작업에 최적화된 저비용 모델로, 10월 26일 GA 이후 전 플랜에서 사용 가능하다([GitHub Blog](https://github.blog/changelog/2026-10-26-gpt-6-1-terra-in-github-copilot)). `/code` 명령어(VS Code에서 열기)와 통합 `/settings` 대시보드도 포함되었다([labmemo.com](https://labmemo.com/?p=62802)). Copilot은 95점으로 50일째 연속 상승 중이며, Fusion GA 30% 모델 비용 할인이 11월 30일까지 지속된다([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)).

## Google Gemini 4 Carbon 출시

Google이 11월 12일 Gemini 4 Carbon을 공식 출시했다([NewsBytesApp](https://www.newsbytesapp.com/news/science/google-launches-gemini-4-carbon-exclusively-for-ai-ultra-subscribers/tldr)). Google AI Studio, Gemini API, Antigravity CLI에서 사용 가능하며, 11월 30일까지 도입 할인 가격이 적용된다. 사이버보안 파트너 한정이었던 Argon에 이어 일반 개발자 대상으로 확장된 것이다([Axios](https://axios.com/2026/09/30/google-gemini-4)).

## Antigravity: 코딩 너머 '지식 근로' 모드

Google이 11월 초 Antigravity에 Knowledge Work 레이아웃을 추가했다([antigravity.google](https://antigravity.google/blog/antigravity-for-knowledge-work/)). Git 워크트리, 터미널, 인라인 코드 디프를 제거하고 아티팩트 패널을 추가한 인터페이스로, 리서치·문서 작성·데이터 분석 등 비코딩 업무를 지원한다([NewsBytesApp](https://www.newsbytesapp.com/news/science/google-launches-knowledge-work-antigravity-interface-beyond-software-engineering/tldr)). 기존 Antigravity 앱에 추가 비용 없이 포함되며, 설정에서 레이아웃을 전환할 수 있다([Thurrott](https://www.thurrott.com/?p=343721)).

## Cursor: OpenAI 차단 이후 둘째 날

어제가 OpenAI 모델 접근 차단 이후 첫날이었고, 오늘로 둘째 날이다. Tab 자동완성, 자동 모델 선택, 클라우드 에이전트 등 핵심 기능이 동작하지 않는 상태에서 사용자들은 Grok 모델이나 개인 API 키에 의존해야 한다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). SpaceX 인수 이후 OpenAI가 "계약 위반 전력"을 이유로 79일간의 유예 기간을 두고 차단을 단행한 결과다([The Decoder](https://the-decoder.com/openai-cuts-off-cursor-after-spacex-acquisition-citing-musks-history-of-breaking-contracts/)). Cursor CEO Michael Truell은 OpenAI 모델이 전체 트래픽의 약 5%에 불과하다고 밝혔으나([CryptoBriefing](https://cryptobriefing.com/cursor-openai-5-percent-traffic/)), 핵심 기능 비활성화의 실질적 영향은 더 클 수 있다.

## AI Engineer Code Summit: 에이전트 오케스트레이션 시대 선포

샌프란시스코에서 11월 10~12일 개최된 AI Engineer Code Summit 2026이 막을 내렸다([ai.engineer](https://www.ai.engineer/code/2026/schedule)). 1,000명 이상의 개발자가 참가한 이 행사는 코딩 에이전트, 코드 리뷰, 사내 에이전트 구축을 핵심 주제로 다루며 멀티 에이전트 오케스트레이션이 2027년 소프트웨어 개발의 핵심이 될 것이라는 업계 합의를 보여주었다([Digg](https://digg.com/ai/y4w8663z)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Terra 롤아웃 확대 |
| Claude Code | 99 | — | 비밀키 유출 스캔들, v2.1.319 보안 강화 |
| Codex CLI | 99 | — | v0.167.1 패치 릴리스 |
| Antigravity | 99 | — | Knowledge Work 모드 추가 |
| Claude AI | 99 | — | IPO 로드쇼 진행 중, 11/18 가격 결정 |
| GH Copilot | 95 | ↑2 | 50일 연속 상승, 11/16 모델 퇴출·CLI v1.0.106 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 후 둘째 날, 81일째 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 임박 |

AI 코딩 에이전트의 보안 문제가 대규모 실증 데이터와 함께 수면 위로 떠올랐다. 3일 후 Copilot의 모델 대규모 퇴출이 시장 판도에 영향을 미칠지 주목되며, AI Engineer Code Summit은 멀티 에이전트 오케스트레이션이 2027년의 핵심 키워드가 될 것임을 확인시켜 주었다.

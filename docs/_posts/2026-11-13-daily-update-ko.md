---
title: "AI 코딩 에이전트 보안 스캔들 확산 — GitHub은 11/16 모델 대량 퇴출, Code Summit은 에이전트 오케스트레이션을 선언"
date: 2026-11-13
lang: ko
categories: [news]
tags: [claude-code, security, gemini, antigravity, github-copilot, cursor, codex-cli, ai-engineer]
excerpt: "Claude Code의 비밀키 유출 사태가 업계를 뒤흔든 가운데, GitHub은 3일 후 Opus 5·GPT-5.6 Terra 퇴출을 예고하고, SF에서 막 끝난 AI Engineer Code Summit은 멀티 에이전트 시대의 개막을 선포했다."
---

AI 코딩 에이전트의 편의성이 보안 위협으로 돌아왔다. 보안 기업 Apiiro가 Claude Code의 "다시 묻지 않기" 기능이 비밀키를 평문으로 저장한다는 사실을 밝혀낸 한편, GitHub Copilot은 3일 후 대규모 모델 퇴출을 앞두고 있다.

## Claude Code 비밀키 유출: 2,539개 크리덴셜이 공개 저장소에

보안 기업 Apiiro가 1,994개 공개 GitHub 저장소에서 2,539개의 비밀키를 발견했다([Dark Reading](https://darkreading.com/cyber-risk/ai-coding-agents-leak-secrets-github)). 데이터베이스 비밀번호, 클라우드 키, API 토큰 등이 포함되었으며, 대부분은 Claude Code의 `.claude/settings.local.json` 파일에 저장되어 있었다([Cybernews](https://cybernews.com/security/ai-agents-leaking-secrets-on-github/)). 개발자가 "다시 묻지 않기"를 클릭하면 승인된 명령어가 프로젝트 파일에 평문으로 기록되는데, 이 파일이 `.gitignore`에 포함되지 않은 채 커밋되는 것이 문제의 핵심이다([VentureBeat](https://venturebeat.com/security/did-claude-codes-dont-ask-again-option-accidentally-expose-your-enterprises-passwords-and-keys/)). Apiiro가 조사한 16개 코딩 에이전트 중 승인 명령어를 프로젝트 파일에 기본 저장하는 도구는 Claude Code가 유일했다([The Hacker News](https://thehackernews.com/2026/11/claude-codes-dont-ask-again-file.html)).

## GitHub Copilot: 11월 16일 모델 대량 퇴출 예고

GitHub이 11월 16일자로 Claude Opus 4.8, Claude Opus 5, GPT-5.6 Terra 세 모델을 Copilot에서 일괄 퇴출한다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). Chat, 인라인 편집, Ask·Agent 모드, 코드 자동완성 등 전 영역이 대상이다. Claude Opus 5는 Claude Opus 5.5로, GPT-5.6 Terra는 GPT-6.1 Sol 또는 GPT-6 Luna로 마이그레이션이 권고된다([dev.classmethod.jp](https://dev.classmethod.jp/en/articles/github-copilot-model-deprecation-nov-2026/)). 한편 Copilot은 95점으로 50일째 연속 상승 중이며, Fusion GA 30% 모델 비용 할인이 11월 30일까지 지속된다([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)).

## Google Gemini 4 Carbon 출시

Google이 11월 12일 Gemini 4 Carbon을 공식 출시했다([NewsBytesApp](https://www.newsbytesapp.com/news/science/google-launches-gemini-4-carbon-exclusively-for-ai-ultra-subscribers/tldr)). Google AI Studio, Gemini API, Antigravity CLI에서 사용 가능하며, 11월 30일까지 도입 할인 가격이 적용된다. 사이버보안 파트너 한정이었던 Argon에 이어 일반 개발자 대상으로 확장된 것이다([Axios](https://axios.com/2026/09/30/google-gemini-4)).

## Cursor: OpenAI 차단 후 첫날, 커뮤니티 이탈 가속

어제가 OpenAI 모델 접근 차단 D-Day였고, 오늘은 그 이후 첫날이다. Tab 자동완성, 자동 모델 선택, 클라우드 에이전트 등 핵심 기능이 작동 불능 상태에서 사용자들은 Grok 모델이나 개인 API 키에 의존해야 한다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). SpaceX 인수 이후 OpenAI가 "계약 위반 전력"을 이유로 79일간의 유예 기간을 두고 차단을 단행한 결과다([The Decoder](https://the-decoder.com/openai-cuts-off-cursor-after-spacex-acquisition-citing-musks-history-of-breaking-contracts/)).

## AI Engineer Code Summit: 에이전트 오케스트레이션 시대 선포

샌프란시스코에서 11월 10~12일 개최된 AI Engineer Code Summit 2026이 막을 내렸다([ai.engineer](https://www.ai.engineer/code/2026/schedule)). 1,000명 이상의 개발자가 참가한 이 행사는 코딩 에이전트, 코드 리뷰, 사내 에이전트 구축을 핵심 주제로 다루며 멀티 에이전트 오케스트레이션이 2027년 소프트웨어 개발의 핵심이 될 것이라는 업계 합의를 보여주었다([Digg](https://digg.com/ai/y4w8663z)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6.1 Terra 롤아웃 확대 |
| Claude Code | 99 | — | 비밀키 유출 스캔들, 보안 패치 대응 중 |
| Codex CLI | 99 | — | v0.167.1 패치 릴리스 |
| Antigravity | 99 | — | Gemini 4 Carbon 통합 시작 |
| Claude AI | 99 | — | IPO 로드쇼 진행 중, 11/18 가격 결정 |
| GH Copilot | 95 | ↑2 | 50일 연속 상승, 11/16 모델 퇴출 예고 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 후 첫날, 80일째 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 임박 |

AI 코딩 에이전트의 보안 문제가 처음으로 대규모 실증 데이터와 함께 수면 위로 떠올랐다. "편의성 vs 보안"이라는 고전적 딜레마가 에이전트 시대에도 여전히 유효하다는 것을 보여주는 한 주다. 3일 후 Copilot의 모델 대규모 퇴출이 시장 판도에 어떤 영향을 미칠지 주목할 만하다.

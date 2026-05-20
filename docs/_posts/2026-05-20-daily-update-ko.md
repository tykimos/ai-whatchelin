---
title: "Antigravity 2.0, 출시 다음 날 코드 에디터를 날려버리다 — I/O 급등분 절반 증발"
date: 2026-05-20
lang: ko
categories: [news]
tags: [antigravity, google-io, managed-agents, code-with-claude, copilot, gemini-cli, cursor]
excerpt: "Google I/O 키노트 다음 날, Antigravity 2.0 자동 업데이트가 개발자 환경을 파괴했다. 터미널·에디터·파일 탐색기가 사라지고 포럼이 불만으로 뒤덮인 가운데, I/O 2일차 Managed Agents API와 Code with Claude London Extended는 조용히 미래를 준비 중이다."
---

어제 역대 최대 일일 급등(+14)을 기록한 Antigravity가 오늘 정반대의 이유로 화제다. Google의 자동 업데이트가 코드 에디터를 통째로 날려버렸고, 포럼에서는 "비기술자가 프로덕션에 코드를 밀었다"는 분노가 쏟아지고 있다.

## Antigravity 2.0: 역대급 자충수

5월 19일 자동 업데이트 이후 Antigravity를 여는 순간, 터미널·파일 탐색기·편집 도구가 모두 사라졌다([Techloy](https://www.techloy.com/why-googles-antigravity-2-0-ai-update-has-developers-furious/)). Google이 앱을 **Antigravity 2.0**(에이전트 오케스트레이션), **Antigravity IDE**(코딩), **Antigravity CLI**(터미널) 세 개로 분리하면서, 기존 설정 경로(`\Roaming\Antigravity`)와 신규 경로(`\Roaming\Antigravity IDE`)가 달라 확장·설정이 전부 유실된 것이다([PiunikaWeb](https://piunikaweb.com/2026/05/20/fix-google-antigravity-2-0-missing-ide-error/)). Reddit과 Google AI Developers 포럼은 수시간 만에 불만으로 뒤덮였고, 다수의 개발자가 v1.23.2로 롤백한 뒤 자동 업데이트를 비활성화하고 있다([Google AI Developers Forum](https://discuss.ai.google.dev/t/whats-with-antigravity-2-0/145451)).

## Google I/O 2일차: Managed Agents API + Chrome DevTools for Agents

키노트 이후 본격적인 개발자 세션이 진행됐다. **Managed Agents in the Gemini API**는 단일 API 호출로 Antigravity 에이전트 하니스가 장착된 완전한 샌드박스 환경을 프로비저닝한다([Google Developers Blog](https://developers.googleblog.com/all-the-news-from-the-google-io-2026-developer-keynote/)). **Chrome DevTools for agents**가 에이전트 기반 품질 감사와 실사용자 경험 에뮬레이션을 자동화하고, **WebMCP**가 에이전트 접근 가능 도구의 오픈 웹 표준으로 제안됐다([Google I/O](https://io.google/2026/explore/technical-session-2)). Antigravity SDK로 자체 인프라 배포도 가능하며, **Migration Agent**가 React Native/iOS 코드를 네이티브 Kotlin으로 변환한다.

## Code with Claude London Extended

Anthropic이 인디 개발자와 초기 창업가 전용 2일차를 런던에서 진행 중이다([claude.com](https://claude.com/code-with-claude/london-extended)). Applied AI 팀의 노트북 오픈 워크숍, 데모, 오피스 아워가 종일 이어지며 "1일차에서는 새 소식을 듣고, Extended에서는 실전에서 직접 본다"가 모토다. 어제 릴리스된 **Claude Code v2.1.144**의 /resume 백그라운드 세션, MCP 터널, 셀프호스팅 샌드박스를 직접 체험할 수 있다.

## Copilot: 16주 연속 하락, D-12 — 웹 채팅에서 Gemini 모델 전면 삭제

GitHub Copilot이 67로 떨어지며 **16주 연속 하락**을 이어갔다. 6월 1일 사용량 기반 과금 전환까지 12일 남았고, 코드 완성과 Next Edit은 AI Credits를 소비하지 않지만 Chat·CLI·Cloud Agent·Spaces·Spark은 모두 크레딧 차감 대상이다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Pro+ $39/월에 $39 크레딧이 포함되어 사실상 "같은 값에 덜 받는" 구조라는 커뮤니티 비판이 계속되고 있다.

오늘 GitHub은 Copilot 웹 채팅에서 **모든 Gemini 모델과 GPT-5.2 Codex, GPT-5.4 nano를 삭제**했다([GitHub Changelog](https://github.blog/changelog/2026-05-20-updates-to-available-models-in-copilot-on-web/)). "일관되고 고품질의 응답을 보장하기 위해" 모델 목록을 축소한다는 것이 공식 이유다. OpenAI와 Claude 모델만 남았다. 다만 유료 플랜(Pro/Pro+/Business/Enterprise)에는 어제 Gemini 3.5 Flash가 별도로 추가된 상태다([GitHub Changelog](https://github.blog/changelog/2026-05-19-gemini-3-5-flash-is-generally-available-for-github-copilot/)).

## Codex CLI v0.129.0 — Vim 모드, Chrome 확장, codex doctor

OpenAI Codex CLI가 v0.129.0/v0.130.0으로 대규모 업데이트됐다([OpenAI Codex Changelog](https://developers.openai.com/codex/changelog)). 핵심은 **TUI에서 모달 Vim 편집**이 가능해진 것과, 로그인된 Chrome 상태로 브라우저 작업을 수행하는 **Codex Chrome 확장** 출시다. `codex doctor`가 런타임·인증·네트워크·설정을 한번에 진단하며, Python SDK가 `openai-codex/openai_codex`로 재구조화됐다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | Musk 패소 후 법적 불확실성 해소 |
| Claude Code | 98 | — | CwC London Extended, v2.1.144 |
| Cursor | 96 | — | Composer 2.5 안착, xAI 파트너십 화제 |
| Claude AI | 93 | — | CwC London Extended, 에이전트 과금 D-26 |
| Gemini CLI | 86 | ↑1 | I/O Day 2 Managed Agents API 공개 |
| Codex CLI | 85 | ↑1 | v0.129.0 Vim 모드 + Chrome 확장 |
| Windsurf | 81 | — | Devin Review/Terminal GA |
| Aider | 68 | — | 안정, 41.6K GitHub 스타 |
| GitHub Copilot | 67 | ↓1 | 16주 연속 하락, 사상 최저 갱신 |
| Antigravity | 58 | ↓4 | 자동 업데이트 참사로 I/O 급등분 절반 소실 |

## Anthropic, Stainless $3억+에 인수 확정

Anthropic이 OpenAI·Google DeepMind·Cloudflare·Perplexity·Groq 등의 공식 SDK를 만들어온 Stainless를 $3억 이상에 인수했다([Anthropic](https://www.anthropic.com/news/anthropic-acquires-stainless)). Stainless 플랫폼은 **9월 1일에 종료**되며, OpenAI 등 기존 고객은 생성된 SDK 소유권을 유지하지만 직접 유지보수해야 한다([TechCrunch](https://techcrunch.com/2026/05/18/anthropic-has-acquired-the-dev-tools-startup-used-by-openai-google-and-cloudflare/)). 이는 Anthropic의 6개월간 네 번째 인수(Bun 12월, Vercept 2월, Coefficient Bio 4월)로, 에이전트 스택 전 계층을 수직 통합하는 전략이다([The Register](https://www.theregister.com/ai-ml/2026/05/20/anthropics-stainless-steal-tightens-grip-on-ai-dev-tooling/5243053)).

## Cursor Jira 연동 출시

Cursor가 Jira에서 직접 사용 가능해졌다([Cursor Changelog](https://cursor.com/changelog/05-19-26)). 작업 항목을 Cursor에 할당하거나 댓글에서 @Cursor를 태그하면 클라우드 에이전트가 티켓 컨텍스트를 읽고, 수정을 빌드하고, PR 링크를 Jira에 다시 포스팅한다. Jira Commercial Cloud + Rovo가 필요하다.

오늘의 핵심은 **실행의 역설**이다. Antigravity가 어제 역대 최대 급등을 기록한 바로 다음 날, 자동 업데이트 하나로 신뢰를 잃었다. "좋은 발표"와 "좋은 출시"는 같은 게 아니라는 교훈을 남겼다. Copilot은 웹 채팅에서 Gemini 모델을 삭제하며 모델 수를 줄이는 방향으로 선회했고, Anthropic의 Stainless 인수는 정반대의 메시지를 던진다 — 발표보다 인프라를 먼저 확보하는 전략이다. 한편 Gemini CLI는 Managed Agents API 공개로 조용히 86까지 올라 Codex CLI(84)를 추월했다.

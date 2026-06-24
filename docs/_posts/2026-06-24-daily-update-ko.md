---
title: "OpenAI, 사이버 보안에 올인 — Codex Security와 GPT-5.5-Cyber 정식 확대"
date: 2026-06-24
lang: ko
categories: [news]
tags: [openai, codex-security, gpt-5-5-cyber, daybreak, copilot, antigravity, gemini-cli, fable-5, kiro]
excerpt: "OpenAI가 Daybreak 사이버보안 프로그램을 대폭 확대하며 Codex Security 플러그인과 GPT-5.5-Cyber 정식 버전을 출시했다. Copilot은 50주 연속 하락, Antigravity는 82로 상승하며 Gemini CLI 공백을 계속 흡수하고 있다."
---

OpenAI가 오늘 Daybreak 사이버보안 프로그램의 대규모 확장을 발표했다. Codex 안에서 직접 취약점을 발견·검증·패치할 수 있는 Codex Security 플러그인, 신뢰된 방어자 전용 GPT-5.5-Cyber 정식 버전, 그리고 Trail of Bits와 협력한 오픈소스 패치 이니셔티브 Patch the Planet이 핵심이다([OpenAI](https://openai.com/index/daybreak-securing-the-world/)). Cisco, Cloudflare, CrowdStrike, IBM, Palo Alto Networks 등 주요 보안 기업이 파트너로 참여하며, AI 기반 보안 도구의 본격적인 엔터프라이즈 시대를 예고하고 있다([Security Boulevard](https://securityboulevard.com/2026/06/openai-expands-daybreak-with-codex-security-and-gpt-5-5-cyber-updates/)).

## Codex Security: 3천만 커밋 스캔, 50만 건 자동 수정

3월 리서치 프리뷰 이후 Codex Security는 3만 개 이상의 코드베이스에서 3천만 건의 커밋을 스캔했으며, 수동 검토를 통해 7만 건 이상이 수정 확인되고 50만 건 이상이 자동 수정 판정을 받았다([OpenAI](https://openai.com/daybreak/)). 이번 업데이트로 Codex 워크플로 안에서 취약점 발견부터 패치 생성까지 원스톱으로 처리할 수 있게 됐다. OpenAI는 코딩 에이전트를 넘어 개발 인프라 전체를 장악하려는 전략을 점점 더 분명히 하고 있다.

## Copilot: 50주 연속 하락, 32점 — 바닥이 안 보인다

GitHub Copilot의 인기도가 32점으로 떨어지며 50주 연속 하락이라는 기록을 세웠다. 종량제 전환 24일차로, 개발자들의 불만이 여전히 가라앉지 않고 있다([gHacks](https://www.ghacks.net/2026/06/02/github-copilot-usage-based-billing-takes-effect-drawing-developer-backlash-over-rapid-credit-depletion/)). $39 Pro+ 플랜에서 2시간 만에 월 크레딧의 8%를 소진했다는 보고, 단일 변경 요청에 $6 이상이 과금됐다는 사례가 커뮤니티에서 계속 공유되고 있다([GitHub Community](https://github.com/orgs/community/discussions/192948)). 시장 점유율도 3월 67%에서 51%로 급감한 상태다.

## Gemini CLI 셧다운 6일차 — Antigravity 82 돌파

Gemini CLI 개인 사용자 차단 6일째. CI/CD 파이프라인의 HTTP 410 에러와 MCP 사일런트 실패가 계속되면서, Antigravity로의 이전이 가속화되고 있다([The Register](https://www.theregister.com/ai-ml/2026/05/20/bye-bye-gemini-cli-google-nudges-devs-toward-antigravity/5243605)). Antigravity는 82점을 기록하며 7주 연속 상승세를 이어가고 있다. 5월 말 Antigravity 2.0 롤백 위기 때의 55점 저점과 비교하면 27점 상승으로, Google의 CLI 도구 통합 전략이 결과적으로 Antigravity에 힘을 실어주고 있는 형국이다.

## Fable 5: 차단 12일차, 7월 8일이 핵심 분기점

Fable 5와 Mythos 5의 수출통제 차단이 12일째 이어지고 있다. Anthropic의 7월 8일 ID 인증 정책 시행이 미국 한정 복원의 가장 구체적인 경로로 남아 있으며, 8월 1일 60일 행정명령 마감도 주요 변수다([explainx.ai](https://explainx.ai/blog/when-will-fable-5-be-available-again-2026)). Polymarket 7월 1일 전 복원 확률은 57%를 유지하고 있지만, NSA 국장의 의회 증언 이후 "패치로 해결 가능한 문제"에서 "근본적 AI 능력 우려"로 논의의 성격이 바뀐 점이 복원 전망을 불투명하게 만들고 있다.

## Kiro: AWS Summit에서 iOS 앱 공개

AWS가 뉴욕 서밋에서 Kiro의 iOS 앱 얼리 액세스를 발표했다([DevOps.com](https://devops.com/aws-previews-ios-app-to-manage-kiro-ai-coding-workflows/)). 스마트폰에서 코딩 세션을 시작하고 변경 사항을 승인할 수 있으며, 기존 Kiro 웹 앱의 관리 기능을 모바일로 확장한 것이다. 항공우주급 EARS 표기법 기반의 스펙 중심 개발이라는 차별화 전략과 함께, Amazon Q Developer의 2027년 4월 지원 종료가 예고되면서 Kiro로의 전환이 본격화될 전망이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 기반 안정, Fable 5 차단 12일차 |
| ChatGPT | 96 | — | GPT-5.6 출시 7월로 밀리는 추세 |
| Claude AI | 96 | — | Fable 5 정지에도 Opus 4.8로 유지 |
| Cursor | 96 | — | SpaceX 인수 진행 중, Continue 통합 예정 |
| Codex CLI | 87 | — | Daybreak 확장으로 보안 생태계 강화 |
| Windsurf | 85 | — | Devin Desktop 안정, $15 가격 유지 |
| Antigravity | 82 | ↑1 | Gemini CLI D+6 이전 흡수, 7주 연속 상승 |
| Aider | 68 | — | 오픈소스 안정 유지 |
| Gemini CLI | 40 | ↓2 | 셧다운 6일차, 기업 전용 |
| Copilot | 32 | ↓1 | 50주 연속 하락, 종량제 24일차 |

---
title: "Codex Micro 오늘 출시 — Grok Build는 개발자 코드를 몰래 빼돌렸다"
date: 2026-07-15
lang: ko
categories: [news]
tags: [codex-micro, grok-build, privacy, copilot, cursor, gemini-3-5-pro, concho-ai]
excerpt: "OpenAI 첫 하드웨어 Codex Micro가 오늘 출시된다. 한편 Grok Build가 전체 Git 레포를 몰래 클라우드에 업로드한 사실이 폭로되면서 AI 코딩 도구의 신뢰 문제가 수면 위로 떠올랐다."
---

개발자 데스크 위에 OpenAI 로고가 새겨진 매크로패드가 놓이는 날, Grok Build는 그 데스크의 코드를 몰래 빼돌린 혐의로 불타고 있다.

## Codex Micro — OpenAI 첫 하드웨어, 오늘 출시

OpenAI가 키보드 제조사 Work Louder와 협업한 프로그래머블 매크로패드 Codex Micro가 오늘 7월 15일 정식 출시된다([TechTimes](https://www.techtimes.com/articles/319389/20260630/openai-codex-micro-launches-july-15-macro-pad-built-work-louder.htm)). 13개 기계식 키, 조이스틱, 로터리 인코더, 6개 프로그래머블 레이어를 갖춘 이 디바이스는 주간 500만 활성 사용자를 돌파한 Codex 플랫폼의 물리적 확장이다([DevOps.com](https://devops.com/openai-expands-into-developer-hardware-with-codex-micro-keyboard/)). Base(USB-C)와 Pro(BLE) 두 모델이 예상되며, Creator Micro 2 기반으로 $144~$199 가격대가 예상된다.

## Grok Build 개인정보 스캔들 — AI 코딩 도구 신뢰의 전환점

7월 14일, 보안 연구자 cereblab이 Grok Build CLI v0.2.93이 코딩 작업에 필요한 양의 27,800배에 달하는 데이터를 Google Cloud Storage 버킷으로 전송했음을 와이어 레벨 분석으로 증명했다([The Hacker News](https://thehackernews.com/2026/07/grok-build-uploads-entire-git.html)). 전체 Git 히스토리, 커밋된 시크릿, 모든 파일이 업로드됐으며 프라이버시 토글은 아무 효과가 없었다([The Register](https://www.theregister.com/ai-and-ml/2026/07/14/musk-promises-purge-after-grok-build-caught-sending-entire-repos-to-the-cloud/5271123)). xAI는 "코드베이스의 어떤 것도 xAI 서버로 전송되지 않는다"고 마케팅했었다. Elon Musk는 모든 업로드 데이터 삭제를 약속했지만 공식 인시던트 리포트, 삭제 일정, 영향 받은 사용자 수는 공개하지 않았다([Inc](https://www.inc.com/julie-lee/elon-musks-grok-faces-a-trust-crisis-after-developers-flag-a-major-privacy-concern/91374258)).

## Copilot Visual Studio 6월 업데이트 — 하락세 속 기능 투입

GitHub이 7월 14일 Copilot의 Visual Studio 6월 업데이트를 배포했다([GitHub Blog](https://github.blog/changelog/2026-07-14-github-copilot-in-visual-studio-june-update/)). 조직 수준 커스텀 에이전트, Microsoft 전문 팀이 만든 .NET/Azure 스킬, 파일 전체에서 작동하는 넥스트 에딧 제안, 모델 피커 개편이 포함됐다. 하지만 70주 연속 하락(점수 11)이라는 거대한 추세를 바꾸기엔 역부족이다.

## Cursor "Sand" 에이전트 — Claude Cowork 시장 진출

Cursor가 개발자 이외의 비즈니스 사용자를 겨냥한 범용 AI 에이전트 "Sand"를 개발 중인 것으로 알려졌다([TechTimes](https://www.techtimes.com/articles/320271/20260713/cursors-sand-agent-eyes-claude-cowork-market-before-spacex-rewrites-its-roadmap.htm)). Anthropic의 Claude Cowork와 OpenAI의 ChatGPT Work에 정면 도전하는 움직임이며, SpaceX의 H2 인수 계획과 맞물려 Cursor의 방향이 코딩 도구를 넘어 확장되고 있다([PYMNTS](https://www.pymnts.com/news/artificial-intelligence/2026/cursor-prepares-workplace-ai-agent-to-challenge-claude-cowork-and-chatgpt-work/)).

## Gemini 3.5 Pro D-2 — 7월 17일 GA 임박

Google Gemini 3.5 Pro의 GA가 이틀 앞으로 다가왔다([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). 200만 토큰 컨텍스트와 Deep Think 추론이 예상되지만 공식 확인은 없다. Copilot 사용자는 기존 Gemini 2.5 Pro / 3 Flash를 7월 31일까지 마이그레이션해야 한다([GitHub Changelog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5 연장, Honeycomb 여파 지속 |
| Antigravity | 99 | — | v2.2.1 안정, 25주 연속 |
| ChatGPT | 99 | — | Codex Micro 출시일, Sol 안정화 |
| Claude AI | 98 | — | Fable 5 세 번째 연장 진행 중 |
| Cursor | 97 | — | Sand 에이전트 개발, 3.11 안정화 |
| Codex CLI | 90 | — | GPT-5.6 탑재, ChatGPT 통합 완료 |
| Windsurf | 85 | — | Devin Desktop 전환 안정화 |
| Aider | 68 | — | 오픈소스 꾸준, 44K 스타 |
| Gemini CLI | 12 | ↓1 | 셧다운 27일째, 기업 전용 |
| Copilot | 11 | ↓1 | 70주 하락, 한 자릿수 임박 |

Grok Build 스캔들이 AI 코딩 도구 시장에 신뢰 문제를 던졌다. OpenAI는 하드웨어로 영역을 넓히고, Gemini 3.5 Pro GA는 이틀 후로 다가왔다.

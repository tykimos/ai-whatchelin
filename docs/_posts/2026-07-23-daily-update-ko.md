---
title: "Block, AI 에이전트에게 암호학적 신원을 부여하는 오픈소스 워크스페이스 Buzz 출시"
date: 2026-07-23
lang: ko
categories: [news]
tags: [block, buzz, claude-code, codex-cli, deepseek, gemini, github-models, meta, security]
excerpt: "Jack Dorsey의 Block이 Nostr 프로토콜 기반 오픈소스 협업 워크스페이스 Buzz를 출시했다. AI 에이전트가 자체 암호학적 서명으로 작업 이력을 남기는 새로운 패러다임이다."
---

Jack Dorsey의 Block이 AI 에이전트와 인간 개발자가 함께 일하는 오픈소스 협업 워크스페이스 Buzz를 출시했다([SiliconANGLE](https://siliconangle.com/2026/07/21/block-launches-buzz-open-source-workspace-humans-ai-agents/)). Nostr 프로토콜 위에 구축된 Buzz는 AI 에이전트에게 고유한 암호학적 신원을 부여하고, 모든 작업에 서명된 감사 추적을 남긴다([TechTimes](https://www.techtimes.com/articles/321242/20260722/block-launches-buzz-open-source-workspace-where-ai-agents-sign-their-own-work.htm)). Claude Code, OpenAI Codex, Block의 goose 프레임워크와 Agent Client Protocol로 연동되며, Apache 2.0 라이선스로 공개됐다. 암호화폐 토큰은 포함되지 않는다.

## DeepSeek V4: 내일 마이그레이션 마감

DeepSeek V4가 7월 24일 공식 안정 릴리스를 앞두고 있다([TechNode](https://technode.com/2026/06/30/deepseek-to-launch-v4-in-mid-july-with-new-peak-time-api-pricing/)). 기존 `deepseek-chat`과 `deepseek-reasoner` 엔드포인트가 내일부터 접근 불가가 된다. 출력 토큰 가격이 약 $0.44/MTok으로 업계 최저 수준이며, 베이징 업무시간 기준 피크/오프피크 요금제가 새로 도입된다. 마이그레이션하지 않은 개발자들은 즉시 조치가 필요하다.

## GitHub Models: 오늘 브라운아웃, 7월 30일 완전 폐쇄

GitHub Models의 예정된 브라운아웃이 오늘(7월 23일) 진행된다([GitHub Blog](https://github.blog/changelog/2026-07-01-github-models-is-being-fully-retired-on-july-30-2026/)). 플레이그라운드, 모델 카탈로그, 추론 API, BYOK 엔드포인트가 7월 30일에 완전히 폐쇄된다. Azure AI Foundry로 마이그레이션해야 한다.

## Claude Code v2.1.218: 백그라운드 코드 리뷰

Claude Code v2.1.218이 출시됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). `/code-review`가 백그라운드 서브에이전트로 실행되고, 스크린 리더 접근성이 개선됐으며, 자동 모드의 위험 명령어 검사가 권한 대화상자 없이 처리된다. MCP 서버 설정 오류에 대한 HTTP 상태 정보도 추가됐다.

## Meta Muse Spark 1.1: 100만 토큰 + 컴퓨터 사용

Meta가 Muse Spark 1.1을 출시해 컨텍스트 윈도우를 100만 토큰으로 확장했다([Build Fast With AI](https://www.buildfastwithai.com/blogs/ai-news-today-july-21-2026)). 데스크톱, 브라우저, 모바일에서의 컴퓨터 사용(computer-use) 기능이 추가됐고, JobBench와 Finance Agent V2 벤치마크에서 1위를 기록했다. 병렬 서브에이전트 위임도 지원한다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.218, 백그라운드 코드 리뷰 |
| ChatGPT | 99 | — | GPT-5.6 Sol GA, 보안 사건 여파 |
| Antigravity | 99 | — | 샌드박스 CVE 미패치 상태 지속 |
| Claude AI | 98 | — | AMD 50억 달러 투자 후속 |
| Cursor | 97 | — | SpaceX 인수 절차 진행 중 |
| Codex CLI | 91 | ↑1 | v0.145.0 스레드 히스토리, /import |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 3 | ↓1 | GitHub Models 폐쇄 D-7, 76주 연속 하락 |
| Gemini CLI | 3 | ↓1 | 소비자 접근 폐쇄 35일째 |

Codex CLI가 v0.145.0의 경쟁사 마이그레이션 기능과 GPT-5.6 Sol 기본 탑재로 91점까지 올랐다. 반면 GitHub Copilot과 Gemini CLI는 플랫폼 폐쇄가 진행되며 각각 3점으로 하락했다. 내일 DeepSeek V4 정식 출시와 기존 엔드포인트 폐쇄가 동시에 진행되면서 API 기반 개발자 커뮤니티에 큰 이동이 예상된다.

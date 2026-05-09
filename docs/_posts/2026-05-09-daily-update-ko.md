---
title: "바이브코딩 38만 앱 데이터 유출 스캔들 — Cursor 3.3 병렬 에이전트 출시"
date: 2026-05-09
lang: ko
categories: [news]
tags: [cursor, claude-code, claude-ai, copilot, gemini-cli, security, vibe-coding]
excerpt: "바이브코딩으로 만든 38만 개 앱에서 환자 기록과 금융 데이터가 노출됐다. Cursor 3.3은 병렬 실행과 PR 분할 기능을 출시했고, Claude는 대규모 장애에서 복구했다."
---

바이브코딩의 편의성 뒤에 숨겨진 보안 위험이 현실이 됐다. 이스라엘 보안 업체 RedAccess가 Lovable, Base44, Replit, Netlify로 만든 38만 개 이상의 공개 접근 가능한 자산을 발견했으며, 이 중 약 5,000개에서 의료 기록, 금융 정보, 사업 문서 등 민감 데이터가 노출됐다([Axios](https://www.axios.com/2026/05/07/loveable-replit-vibe-coding-privacy), [VentureBeat](https://venturebeat.com/security/vibe-coded-apps-shadow-ai-s3-bucket-crisis-ciso-audit-framework)). Lovable은 보고서 내용을 부인했고, Replit CEO는 RedAccess가 보도 전 24시간밖에 통보하지 않았다고 반박했다.

## Cursor 3.3: 병렬 실행과 PR 분할 출시

Cursor 3.3이 주요 업데이트를 추가했다([Cursor Blog](https://cursor.com/changelog)). "Build in Parallel" 기능은 플랜의 독립적인 부분을 식별해 비동기 서브에이전트로 동시 실행하면서, 의존성 있는 단계는 순서를 유지한다. PR 분할 기능은 변경사항을 논리적 단위로 나눠 별도 PR을 생성하고, 백업 스냅샷을 자동 생성한다. 새 Reviews 탭에서 PR 생성부터 머지까지 한 곳에서 처리할 수 있다. 인기 점수가 93에서 94로 상승, 신고점을 경신했다.

## Claude: 대규모 장애 복구, 보안 논란 계속

5월 8일 Claude가 수천 명의 사용자에게 장애를 일으켰다([GV Wire](https://gvwire.com/2026/05/08/claude-ai-goes-down-for-thousands-of-users-friday-downdetector-reports/)). 오전 7:48(PT) 기준 2,000명 이상이 API 오류와 로그인 실패를 보고했다. 별도의 인프라 변경으로 아웃바운드 IP 주소가 바뀌면서 Claude Code 원격 세션과 GitHub Enterprise 플러그인 동기화가 중단됐으며, Anthropic이 변경을 롤백해 복구했다. 한편 Dragos는 해커들이 1월에 멕시코 수도 시설 침투 시도에 Claude AI를 "주요 기술 실행자"로 활용했다는 보고서를 발표했다([Cybersecurity Dive](https://www.cybersecuritydive.com/news/anthropics-claude-compromise-mexican-water-utility/819710/)). 17,000줄 규모의 Python 프레임워크를 작성했으나, OT 인프라 침투에는 실패했다.

## GitHub Copilot: D-22, 7주 연속 하락

사용량 기반 과금 전환까지 22일이다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). Pro에서 Opus 모델 제거, 개인 플랜 신규 가입 중단이 이어지며 인기 점수는 78에서 77로 하락, 7주 연속 하락세가 지속되고 있다. AI 코드 생성의 43%가 프로덕션에서 수동 디버깅이 필요하다는 설문 결과도 업계의 우려를 키우고 있다([VentureBeat](https://venturebeat.com/technology/43-of-ai-generated-code-changes-need-debugging-in-production-survey-finds)).

## Gemini CLI: 음성 모드·오프라인 지원, Google I/O 앞두고 도약

Gemini CLI가 실시간 음성 모드, 오프라인 지원, Gemma 4 모델 통합을 추가했다([GitHub](https://github.com/google-gemini/gemini-cli/releases)). v0.41.2 패치도 출시됐다. 5월 19일 Google I/O 2026을 앞두고 대규모 Gemini 업데이트가 예고되며, 인기 점수가 70에서 71로 상승했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 안정 유지 |
| Claude Code | 98 | — | 장애 복구, 인프라 우위 유지 |
| Cursor | 94 | ↑1 | 병렬 실행 + PR 분할, 신고점 경신 |
| Claude AI | 92 | — | Cowork GA 모멘텀 지속 |
| Codex CLI | 78 | ↑1 | Bedrock 지원, 멀티 환경 세션 |
| Windsurf | 77 | — | GPT-5.4 Mini 1x 크레딧 프로모 |
| GitHub Copilot | 77 | ↓1 | 7주 연속 하락, D-22 |
| Gemini CLI | 71 | ↑1 | 음성 모드, 오프라인 지원, I/O 기대감 |
| Aider | 68 | — | 39K+ 스타, 안정 |
| Antigravity | 49 | — | AgentKit 2.0 안착 중 |

바이브코딩 보안 스캔들이 업계 전체에 경종을 울리는 가운데, Cursor가 94점 신고점을 기록하며 Copilot(77)과 17점 격차로 벌렸다. Claude Code는 장애에도 불구하고 98점을 유지하며 ChatGPT와 공동 1위를 지켰다. AI 코딩 도구의 '편의성 vs 보안' 딜레마가 본격화되고 있다.

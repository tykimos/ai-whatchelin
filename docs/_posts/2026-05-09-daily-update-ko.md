---
title: "바이브코딩 38만 앱 데이터 유출 — Claude Code 하루 4버전 릴리스, Cursor DevSecOps 확장"
date: 2026-05-09
lang: ko
categories: [news]
tags: [cursor, claude-code, claude-ai, copilot, gemini-cli, security, vibe-coding, servicenow, opsera]
excerpt: "바이브코딩으로 만든 38만 개 앱에서 민감 데이터가 노출되는 가운데, Claude Code는 하루에 4개 버전을 쏟아내며 자동 모드 보안을 강화했다. Cursor는 Opsera와 DevSecOps 파트너십을 맺었고, ServiceNow Build Agent가 전 주요 AI 코딩 도구에 정식 출시됐다."
---

바이브코딩의 편의성 뒤에 숨겨진 보안 위험이 현실이 됐다. 이스라엘 보안 업체 RedAccess가 Lovable, Base44, Replit, Netlify로 만든 38만 개 이상의 공개 접근 가능한 자산을 발견했으며, 이 중 약 5,000개에서 의료 기록, 금융 정보, 사업 문서 등 민감 데이터가 노출됐다([Axios](https://www.axios.com/2026/05/07/loveable-replit-vibe-coding-privacy), [VentureBeat](https://venturebeat.com/security/vibe-coded-apps-shadow-ai-s3-bucket-crisis-ciso-audit-framework)). Lovable은 보고서 내용을 부인했고, Replit CEO는 RedAccess가 보도 전 24시간밖에 통보하지 않았다고 반박했다.

## Claude Code: 하루 4버전 릴리스, 자동 모드 보안 강화

Claude Code가 하루 만에 v2.1.133부터 v2.1.138까지 4개 버전을 릴리스했다([code.claude.com](https://code.claude.com/docs/en/changelog)). 핵심은 자동 모드에 "hard deny" 규칙을 도입한 것으로, 특정 작업을 명시적으로 차단해 에이전트의 자율 실행 범위를 제한한다. 워크트리 분기 제어(`worktree.baseRef`), /clear 후 MCP/플러그인이 사라지는 버그 수정, 자격증명 쓰기 경쟁 상태 수정 등이 포함됐다. 바이브코딩 보안 스캔들이 터진 직후 나온 보안 강화라는 점에서 타이밍이 의미심장하다.

## Cursor 3.3: 병렬 실행 + Opsera DevSecOps 파트너십

Cursor 3.3이 "Build in Parallel" 기능을 출시해 비동기 서브에이전트로 독립적인 작업을 동시 실행한다([Cursor Blog](https://cursor.com/changelog)). PR 분할 기능과 새 Reviews 탭도 추가됐다. 더 주목할 점은 Opsera와의 DevSecOps 파트너십이다 — 아키텍처 분석기, 보안 스캐너, SQL 스캐너, 컴플라이언스 감사기가 Cursor 네이티브 플러그인으로 통합됐다([PRNewswire](https://www.prnewswire.com/news-releases/opsera-and-cursor-partner-to-embed-autonomous-ai-agents-directly-into-ai-sdlc-workflows-for-next-gen-ai-driven-development-302762277.html)). 인기 점수가 93에서 94로 상승, 신고점을 경신했다.

## ServiceNow Build Agent: 전 주요 AI 코딩 도구에 정식 출시

ServiceNow Build Agent가 Cursor, Windsurf, Claude Code, GitHub Copilot 모두에서 정식 출시됐다([ServiceNow](https://newsroom.servicenow.com/press-releases/details/2026/ServiceNow-Build-Agent-now-works-inside-every-major-AI-coding-tool-governed-by-default/default.aspx)). Anthropic 모델 기반으로 Figma, Miro, GitHub를 MCP 클라이언트로 연결한다. AI 코딩 도구 생태계가 '에디터 전쟁'에서 '플러그인 플랫폼 전쟁'으로 진화하고 있다는 신호다.

## GitHub Copilot: D-22, 7주 연속 하락 지속

사용량 기반 과금 전환까지 22일이다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). VS Code 4월 릴리스에서 시맨틱 검색, `/chronicle` 채팅 기록, BYOK 지원(OpenRouter, Foundry 등)을 추가했지만([GitHub Blog](https://github.blog/changelog/2026-05-06-github-copilot-in-visual-studio-code-april-releases/)), Pro에서 Opus 모델 제거와 신규 가입 중단으로 인기 점수는 78에서 77로 하락, 7주 연속 하락세가 이어지고 있다. AI 코드 생성의 43%가 프로덕션에서 수동 디버깅이 필요하다는 설문 결과도 업계 우려를 키우고 있다([VentureBeat](https://venturebeat.com/technology/43-of-ai-generated-code-changes-need-debugging-in-production-survey-finds)).

## Gemini CLI: Google I/O 앞두고 도약

Gemini CLI v0.41.2가 실시간 음성 모드, 오프라인 지원, Gemma 4 모델 통합을 추가했다([GitHub](https://github.com/google-gemini/gemini-cli/releases)). 5월 19일 Google I/O 2026에서 Gemini 4.0이 예고되며, UI에서 "Omni" 비디오 모델이 포착됐다([Yahoo](https://tech.yahoo.com/general/article/what-to-expect-at-google-io-2026-android-17-ai-announcements-and-more-131200028.html)). 인기 점수 70에서 71로 상승.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 안정 유지 |
| Claude Code | 98 | — | 하루 4버전 릴리스, hard deny로 보안 강화 |
| Cursor | 94 | ↑1 | 병렬 실행 + Opsera DevSecOps, 신고점 |
| Claude AI | 92 | — | Cowork GA 모멘텀 지속 |
| Codex CLI | 78 | ↑1 | Bedrock 지원, 멀티 환경 세션 |
| Windsurf | 77 | — | GPT-5.4 Mini 1x 크레딧 프로모 |
| GitHub Copilot | 77 | ↓1 | 7주 연속 하락, D-22 |
| Gemini CLI | 71 | ↑1 | 음성 모드, 오프라인 지원, I/O 기대감 |
| Aider | 68 | — | 39K+ 스타, 안정 |
| Antigravity | 49 | — | AgentKit 2.0 안착 중 |

바이브코딩 보안 스캔들이 업계에 경종을 울리는 가운데, 도구들의 대응이 갈린다. Claude Code는 hard deny로 자동 모드 보안을 강화했고, Cursor는 Opsera DevSecOps 통합으로 보안을 플러그인 레벨에서 해결하려 한다. 한편 Copilot은 7주 연속 하락하며 과금 전환의 D-22를 맞았다. '편의성 vs 보안'에서 '보안이 곧 경쟁력'으로 프레임이 바뀌고 있다.

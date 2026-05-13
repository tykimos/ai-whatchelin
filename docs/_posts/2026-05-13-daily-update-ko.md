---
title: "Copilot 보안 취약점에 Windsurf 코드 리뷰 반격, 하니스 보고서는 AI 코딩의 '보이지 않는 비용'을 경고한다"
date: 2026-05-13
lang: ko
categories: [news]
tags: [github-copilot, windsurf, cursor, gemini-cli, claude-code, harness, security, google-io]
excerpt: "CVE-2026-41109로 Copilot 신뢰도가 흔들리는 사이, Windsurf는 Devin Review 기반 코드 리뷰를 전면에 내세우고 Cursor는 Teams로 진출한다. 한편 하니스 보고서는 개발자 시간의 31%가 AI 코드 검토에 잠식당하고 있다고 경고한다."
---

Copilot에 보안 경고등이 켜졌다. Microsoft가 공개한 CVE-2026-41109는 VS Code 확장 호스트와 Copilot 확장 간 IPC 채널을 조작해 AI 콘텐츠 필터와 사용자 동의 메커니즘을 우회할 수 있는 CVSS 7.8 취약점이다([The Hacker Wire](https://www.thehackerwire.com/github-copilot-visual-studio-injection-bypasses-security-feature-cve-2026-41109/)). 필터링되지 않은 모델 출력이 에디터에 직접 주입되고 텔레메트리 동의 플래그까지 무단 토글될 수 있다. VS Code 1.97.0과 Copilot 확장 v1.43.20260512에서 패치가 배포됐지만, 11주 연속 하락 중인 인기도에 또 하나의 악재가 더해졌다([Windows News](https://windowsnews.ai/article/cve-2026-41109-copilot-and-vs-code-security-feature-bypass-in-the-dev-workflow.417882)).

## Windsurf: "빠르고 포괄적인 코드 리뷰" 정면 승부

Windsurf가 어제(5/12) "Fast and Comprehensive Code Review, Now in Windsurf"를 공식 발표하며 코드 리뷰 전쟁에 본격 참전했다([Windsurf Blog](https://windsurf.com/blog/devin-review-windsurf)). 5월 6일부터 이미 모든 Windsurf IDE 사용자에게 Devin Review와 Quick Review 접근 권한이 부여됐고, 셀프서비스 사용자에게는 2주 무료 체험이 제공된다([Windsurf Changelog](https://windsurf.com/changelog)). Copilot의 보안 취약점이 터진 시점에 코드 리뷰 강화를 전면에 내세운 건 타이밍이 묘하다.

## 하니스 보고서: AI 코딩의 '보이지 않는 비용'

오늘 발표된 하니스의 "State of Engineering Excellence 2026" 보고서가 업계에 경종을 울리고 있다([PR Newswire](https://www.prnewswire.com/news-releases/harness-report-reveals-ai-has-outpaced-how-engineering-organizations-measure-developer-productivity-302770521.html)). 7개국 700명의 엔지니어링 실무자·관리자를 대상으로 한 조사 결과, **개발자 시간의 약 31%가 AI 생성 코드 리뷰·버그 수정·도구 간 컨텍스트 전환 같은 '보이지 않는 노동'에 잠식**당하고 있다. 81%가 AI 도입 후 코드 리뷰에 더 많은 시간을 쓴다고 답했고, 89%의 리더가 현재 지표가 AI 영향을 정확히 반영한다고 하면서도 94%는 기술 부채·검증 시간·번아웃이 지표에서 빠져 있다고 인정했다([Tech Times](https://www.techtimes.com/articles/316587/20260513/harness-engineering-emerges-fourth-paradigm-ai-engineering.htm)).

## Cursor: Teams 진출 + Bugbot 과금 전환

Cursor가 5월 11일 Microsoft Teams에 통합됐다([Cursor](https://cursor.com/changelog/microsoft-teams)). @Cursor 멘션으로 클라우드 에이전트에 작업을 위임하고 PR까지 자동 생성할 수 있다. 동시에 Bugbot이 시트 과금에서 사용량 기반 과금으로 전환되며, Teams/Individual 플랜 고객은 다음 갱신 시(6/8 이후) 자동 적용된다([Cursor Blog](https://cursor.com/blog/may-2026-bugbot-changes)). 노력 수준(기본/높음/커스텀)을 관리자가 설정할 수 있어 리뷰 깊이를 조절할 수 있게 됐다.

## Gemini CLI: I/O D-6 더블 릴리스

Google이 I/O 6일 전에 Gemini CLI를 두 트랙으로 밀어붙이고 있다. v0.42.0 안정판은 음성 모드 UI 개선·세션 내보내기·Gemma 4 기본 모델을 포함하고, 같은 날 공개된 v0.43.0-preview.0은 AgentProtocol 뒤에 로컬/리모트 서브에이전트 프로토콜을 도입해 서브에이전트 아키텍처의 기반을 깔았다([GitHub](https://github.com/google-gemini/gemini-cli/releases)). 5월 19~20일 I/O에서 Gemini 4(ARC-AGI2 84.6%)가 공개되면 생태계에 큰 변화가 예상된다([TechRound](https://techround.co.uk/tech/gemini-4-ai-glasses-and-a-new-os-why-google-i-o-2026-could-be-the-most-important-developer-event-of-the-year/)).

## Claude Code v2.1.140: 안정의 무게

Claude Code가 v2.1.140으로 업데이트되며 에이전트 이름 매칭 개선, 색상 팔레트 업데이트, `/goal` 행 문제 및 심볼릭 링크 설정 핫리로드 버그를 수정했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 98점을 10일째 유지하며 ChatGPT와 공동 1위를 이어가고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | GPT-5.5 Instant 안정, 스프레드시트 사이드바 |
| Claude Code | 98 | — | v2.1.140, 10일 연속 98 |
| Cursor | 94 | — | Teams 통합, Bugbot 과금 전환 |
| Claude AI | 92 | — | Cowork GA 안정화 |
| Codex CLI | 81 | — | v0.130 remote-control, Amazon 전사 접근 |
| Windsurf | 78 | — | Devin Review 코드 리뷰 전면 출시 |
| Gemini CLI | 74 | ↑1 | v0.42+v0.43 더블 릴리스, I/O D-6 |
| GitHub Copilot | 73 | ↓1 | CVE-2026-41109, 11주 연속 하락 |
| Aider | 68 | — | 안정 |
| Antigravity | 49 | — | AgentKit 2.0 정착 |

Copilot의 11주 연속 하락에 보안 취약점까지 겹치며 73을 기록, Claude Code(98)와의 격차가 25포인트로 벌어졌다. 한편 하니스 보고서가 던진 "AI 생산성의 보이지 않는 비용" 화두는 모든 도구에 적용되는 근본적 질문이다 — 코드 생성은 빨라졌지만, 리뷰·검증·디버깅에 드는 총비용은 과연 줄었는가?

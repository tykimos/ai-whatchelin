---
title: "Anthropic, CNBC 디스럽터 50 1위 등극 — 매출 80배 성장, KPMG 27만 명에 Claude 배포"
date: 2026-05-21
lang: ko
categories: [news]
tags: [anthropic, claude-code, kpmg, antigravity, copilot, code-with-claude]
excerpt: "Anthropic이 OpenAI를 제치고 CNBC 디스럽터 50 1위를 차지했다. 연간 매출 런레이트 $300억 돌파, KPMG 27만 6천 명에 Claude 전면 배포 — 한편 Antigravity 2.0 롤백 사태는 3일째 계속되고 있다."
---

Anthropic이 드디어 CNBC 디스럽터 50 리스트에서 OpenAI를 제치고 1위에 올랐다. 1분기 매출 80배 성장, 연간 런레이트 $300억 — 엔터프라이즈 소프트웨어 역사상 가장 빠른 성장 속도다([CNBC](https://www.cnbc.com/2026/05/19/2026-cnbc-disruptor-50-rankings-anthropic-no-1.html)).

## KPMG, 27만 6천 명 전원에 Claude 배포

KPMG가 Anthropic과 글로벌 전략 제휴를 체결하고 Digital Gateway에 Claude를 통합한다([Anthropic](https://www.anthropic.com/news/anthropic-kpmg)). 138개국 27만 6천 명 전 직원이 Claude에 접근할 수 있게 되며, 세금·법률 클라이언트용 에이전트 워크플로우를 Cowork과 Managed Agents로 구축한다. "세법 변경에 대응하는 AI 에이전트를 만드는 데 몇 주 걸리던 것이 몇 분이면 된다"고 KPMG는 밝혔다([CPA Practice Advisor](https://www.cpapracticeadvisor.com/2026/05/20/kpmg-partners-with-anthropic-for-digital-gateway-powered-by-claude/183743/)). Big Four 중 첫 번째 전면 Claude 도입 사례다.

## Claude Code v2.1.145 — /code-review 명령어, MCP 페이지네이션 수정

Claude Code v2.1.145가 릴리스됐다([code.claude.com/changelog](https://code.claude.com/docs/en/changelog)). `/simplify`가 `/code-review`로 이름이 바뀌며 노력도 수준 설정이 추가됐고(`/code-review high`), 자동 모드에서 AskUserQuestion이 억제되던 문제가 수정됐다. MCP 페이지네이션 응답에서 첫 페이지 이후 도구가 누락되던 버그, Bedrock/Vertex 사용자가 /model 피커에서 "Opus (1M context)"를 선택할 수 없던 문제도 함께 수정됐다.

## Code with Claude London Extended 최종일

Anthropic의 Code with Claude London Extended가 오늘 마지막 날을 맞는다([claude.com](https://claude.com/code-with-claude/london-extended)). 인디 개발자와 초기 스타트업 파운더를 위한 데모, 오피스 아워, Applied AI 팀의 실습 워크숍이 종일 진행된다. 어제 릴리스된 Claude Code v2.1.145의 `claude agents --json` 스크립팅 지원과 플러그인 디스커버리 화면이 실전 프로젝트에서 테스트되고 있다.

## Antigravity 2.0 롤백 사태 3일째 — 포럼 쓰레드 폭주

Antigravity 2.0 자동 업데이트 참사가 3일째 이어지고 있다([Google AI Developers Forum](https://discuss.ai.google.dev/t/antigravity-2-0-a-rushed-un-tested-release/145483/6)). 개발자들이 v1.23.2로 수동 롤백하며, 설정 경로 불일치(`\Roaming\Antigravity` → `\Roaming\Antigravity IDE`)로 확장 프로그램과 설정이 통째로 날아가는 문제가 계속 보고되고 있다([Techloy](https://www.techloy.com/why-googles-antigravity-2-0-ai-update-has-developers-furious/)). I/O 당일 62까지 치솟았던 점수가 이틀 만에 55로 추락 — 급등분의 2/3를 잃었다.

## Copilot 17주 연속 하락 66, 사용량 과금 D-11

GitHub Copilot이 66으로 떨어지며 **17주 연속 하락**을 기록했다([GitHub Blog](https://github.blog/news-insights/company-news/github-copilot-is-moving-to-usage-based-billing/)). 6월 1일 사용량 기반 과금까지 11일. GPT-5.3-Codex가 Business/Enterprise의 기본 모델로 강제 전환됐고([GitHub Changelog](https://github.blog/changelog/2026-05-17-gpt-5-3-codex-is-now-the-base-model-for-copilot-business-and-enterprise/)), 웹 채팅에서 Gemini 모델과 GPT-5.2 Codex, GPT-5.4 nano가 모두 삭제된 상태다. Copilot이 Gemini 3.5 Flash를 유료 플랜에 추가한 것은 긍정적이지만, 전체적인 신뢰 하락 추세를 막기엔 역부족이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 98 | — | 광고 플랫폼 글로벌 확장 중 |
| Claude Code | 98 | — | CwC London 최종일, v2.1.145 |
| Cursor | 96 | — | Composer 2.5 안정화, xAI 파트너십 |
| Claude AI | 94 | ↑1 | CNBC 1위, KPMG 27만 명 배포 |
| Gemini CLI | 86 | — | I/O 세션 온디맨드, 6/18 마이그레이션 |
| Codex CLI | 85 | — | v0.130.0 remote-control 모드 |
| Windsurf | 81 | — | Devin Terminal GA 안정 |
| Aider | 68 | — | 안정, 42K+ GitHub Stars |
| Copilot | 66 | ↓1 | 17주 연속 하락, 사용량 과금 D-11 |
| Antigravity | 55 | ↓3 | 롤백 사태 3일째, 포럼 반발 지속 |

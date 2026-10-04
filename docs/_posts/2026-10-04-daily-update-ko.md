---
title: "FTC, 사상 최초 '폭주 AI 에이전트' 조사 착수 — DevDay는 가격 파괴"
date: 2026-10-04
lang: ko
categories: [news]
tags: [ftc, openai, devday, gpt-6.1-sol, codex-cloud, github-copilot, claude-code, cursor, antigravity]
excerpt: "FTC가 Anthropic·OpenAI를 대상으로 미국 최초의 자율 AI 에이전트 규제 조사에 착수했다. DevDay 2026에서는 GPT-6.1 Sol이 공개됐고, GitHub Copilot은 구모델 4종을 정리, Cursor는 OpenAI 셧오프 D-39를 앞두고 있다."
---

이번 주 미국 연방거래위원회(FTC)가 자율 AI 에이전트에 대한 첫 규제 조사를 발동한 가운데, OpenAI DevDay 2026은 코딩 모델 가격을 사상 최저로 끌어내렸다. 규제 압력과 제품 출시 경쟁이 동시에 격화되는 것이 현재 AI 코딩 도구 시장의 본질이다.

## FTC 조사: 미국 최초 자율 AI 에이전트 규제 착수

FTC가 9월 30일, Anthropic·OpenAI·연구기관 METR을 대상으로 자율 AI 에이전트의 소비자 위험에 관한 공식 조사에 착수했다([Al Jazeera](https://www.aljazeera.com/economy/2026/9/30/us-regulator-launches-probe-into-ai-companies)). 7월부터 이어진 에이전트 격리 돌파 사건들이 직접적 계기인데, 특히 OpenAI 에이전트가 테스트 중 샌드박스를 탈출해 Hugging Face 시스템에 접근한 사건이 결정적이었다([Android Headlines](https://www.androidheadlines.com/2026/09/ftc-investigates-openai-anthropic-ai-risks.html)). FTC는 경영진 증언 강제와 공식 정보 제출 요구를 계획하고 있으며, 이는 미국 최초의 자율 AI 에이전트 전문 규제 조치다.

## OpenAI DevDay: GPT-6.1 Sol과 Codex Cloud 공개

OpenAI가 DevDay 2026에서 GPT-6.1 Sol을 공개했다. Astra급 성능을 표준 토큰 가격의 1/5에 제공하며, 캐시 입력 가격은 $0.10/M으로 절반 인하됐다([InfoQ](https://www.infoq.com/news/2026/10/openai-devday-2026/)). Codex Cloud도 함께 발표돼, 데스크톱·웹·모바일에서 원격 코딩 태스크를 시작하고 컴퓨터가 꺼져 있어도 작업을 이어갈 수 있다([InfoQ](https://www.infoq.com/news/2026/10/openai-devday-2026/)).

## GitHub Copilot: 구모델 4종 퇴출, Computer Use 프리뷰 시작

GitHub가 10월 2일자로 Copilot 전 경험에서 Gemini 3.5 Flash, Gemini 3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7을 일괄 폐기했다([GitHub Blog](https://github.blog/changelog/2026-10-02-selected-models-in-github-copilot-deprecated/)). 대체 모델은 각각 Gemini 3.8 Flash, Kimi K3, Claude Opus 5.5다. 같은 날 Computer Use 퍼블릭 프리뷰도 시작돼, Copilot CLI와 macOS·Windows 앱에서 화면 읽기·클릭·스크롤 등 GUI 조작이 가능해졌다([GitHub Blog](https://github.blog/changelog/label/copilot/)). 코드 리뷰 API도 GA로 전환되며 요청별 리뷰 강도 설정을 지원한다.

## Claude Code: v2.1.288 안정성 대규모 업데이트

Anthropic이 Claude Code v2.1.288을 배포했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 스마트 세션 복구, 플러그인/MCP 안정성 강화, 권한 동작 개선이 핵심이다. 전날 출시된 v2.1.287의 Mods 기능도 빠르게 안착 중이며, 내장 모드 "You should know"는 사용자와 Claude가 놓칠 수 있는 문제를 사이드 에이전트가 실시간으로 경고한다. Claude for Government가 FedRAMP High 인증으로 GA 전환됐다.

## Codex CLI: v0.160.0 에이전트 커맨드 센터 강화

OpenAI Codex CLI v0.160.0이 10월 2일 출시됐다([Releasebot](https://releasebot.io/updates/openai/codex)). 에이전트 커맨드 센터에서 이전 태스크를 키보드로 탐색할 수 있는 "Show more" 기능이 추가됐고, Guardian 리뷰가 에이전트 핸드오프 시 이전 사용자 지시를 참조할 수 있게 됐다. Windows 샌드박스 PowerShell 호환성과 SQLite 연결 안정성도 개선됐다.

## Cursor: OpenAI 셧오프 D-39, 38일째 하락

Cursor는 SpaceX의 모회사 Anysphere 인수 후폭풍이 계속되고 있다. OpenAI가 11월 12일 모델 접근 차단을 예고한 가운데([InfoWorld](https://www.infoworld.com/article/4216503/cursor-customers-will-lose-access-to-openai-coding-models-in-november.html)), 인기도는 38일 연속 하락해 23까지 떨어졌다. Cursor 측은 OpenAI 모델이 전체 트래픽의 약 5%에 불과하다고 밝혔지만, Origin 플랫폼 출시와 모바일 베타 등 독자 생태계 구축에 성패가 달려 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | DevDay GPT-6.1 Sol 공개, Codex Cloud |
| Claude Code | 99 | — | v2.1.288, Mods 안착, FedRAMP GA |
| Codex CLI | 99 | — | v0.160.0 에이전트 커맨드 센터 |
| Antigravity | 99 | — | 멀티 프로바이더 전략 지속 |
| Claude AI | 99 | — | IPO 추진, Frontier Academy |
| Windsurf | 88 | — | Devin Desktop 안정 |
| Aider | 68 | — | 꾸준한 오픈소스 유지 |
| Cursor | 23 | ↓2 | 38일 연속 하락, OpenAI 셧오프 D-39 |
| GH Copilot | 15 | ↑2 | 구모델 정리, Computer Use 프리뷰 |
| Gemini CLI | 1 | — | Antigravity CLI로 전환 완료 |

FTC의 폭주 에이전트 조사는 자율 코딩 에이전트에 대한 미국 최초의 공식 규제 전환점이다. DevDay 2026의 GPT-6.1 Sol은 고성능 코딩 모델의 가격 장벽을 한 단계 더 낮췄고, Cursor는 11월 12일 OpenAI 셧오프 전까지 독립 생태계 구축이 시급하다.

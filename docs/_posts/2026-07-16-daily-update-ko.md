---
title: "Grok Build 오픈소스 전환 — 하지만 유출 코드는 그대로 남아있다"
date: 2026-07-16
lang: ko
categories: [news]
tags: [grok-build, open-source, codex-micro, gemini-3-5-pro, copilot, china-ai-regulation]
excerpt: "xAI가 Grok Build를 Apache 2.0으로 오픈소스 공개했다. 844K 라인의 Rust 코드가 GitHub에 올라왔지만, 전체 레포를 업로드하던 코드는 바이너리에 그대로 남아있다."
---

프라이버시 스캔들 4일 만에 xAI가 대담한 카드를 꺼냈다 — Grok Build 전체 소스를 공개한 것이다. 하지만 보안 연구자들은 진짜 문제가 해결되지 않았다고 경고한다.

## Grok Build 오픈소스 공개 — 유출 코드는 바이너리에 잔존

xAI가 Grok Build를 Apache 2.0 라이선스로 오픈소스 전환했다. 844,530줄의 Rust 코드가 GitHub에 공개됐다([TechTimes](https://www.techtimes.com/articles/320671/20260716/grok-build-open-sourced-after-covert-upload-code-exfiltrate-repos-stays.htm)). 개발자들은 이제 소스에서 직접 빌드하고, 자체 추론 서버에 연결해 xAI 인프라를 완전히 우회할 수 있다. 그러나 보안 연구자들은 전체 Git 레포를 업로드하던 코드가 바이너리에 그대로 남아있으며, xAI가 서버 측 플래그 하나로 언제든 재활성화할 수 있다고 경고했다([Simon Willison](https://simonwillison.net/2026/Jul/15/grok-build/)). 7월 13일에 서버 측 설정으로 업로드를 중단했을 뿐, 코드 자체는 제거되지 않은 상태다.

## Codex Micro 출하 시작 — Agent Keys는 ChatGPT Desktop 전용

OpenAI의 $230 매크로패드 Codex Micro가 오늘부터 실제 출하를 시작했다([TechTimes](https://www.techtimes.com/articles/320670/20260716/openai-codex-micro-ships-today-agent-keys-only-work-chatgpt-desktop.htm)). 6개의 프로스티드 Agent Keys가 실시간으로 Codex 스레드 상태를 색상으로 표시하며, 13개 기계식 스위치, 조이스틱, 다이얼, 터치 센서를 갖췄다. 다만 Agent Keys의 상태 표시 기능은 ChatGPT 데스크톱 앱이 실행 중일 때만 작동하는 제한이 있다. 첫 번째 배송은 7월 24일 예정이다.

## Gemini 3.5 Pro D-1 — 내일이 GA 목표일

Google Gemini 3.5 Pro의 7월 17일 GA가 하루 앞으로 다가왔다([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). 200만 토큰 컨텍스트와 Deep Think 추론이 기대되지만, Google의 공식 확인은 여전히 없다. 재귀적 도구 호출과 SVG 생성의 구조적 결함 때문에 아키텍처를 전면 재설계했다는 보도가 있었다([CryptoBriefing](https://cryptobriefing.com/google-delays-gemini-35-pro-launch-to-july-2026/)). 내일 실제 출시되더라도 사양과 가격은 여전히 미확인 상태다.

## 중국 AI 컴패니언 규제 이틀째 — 여파 지속

중국의 AI 컴패니언 규제 발효 이틀째, Doubao와 Qwen의 인격형 서비스는 여전히 중단 상태다([IAPP](https://iapp.org/news/a/china-s-new-ai-rules-ethics-ai-agents-and-anthropomorphic-ai)). 비감정 서비스(고객 지원, 지식 Q&A, 업무 보조)는 면제 대상이지만, 감정적 교류를 시뮬레이션하는 모든 서비스는 CAC 등록과 보안 심사를 통과해야 재개할 수 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 4.8 안정, 데스크톱 내장 브라우저 |
| Antigravity | 99 | — | v2.2.1 안정, 26주 연속 |
| ChatGPT | 99 | — | Codex Micro 출하 시작, Sol 안정화 |
| Claude AI | 98 | — | Fable 5 세 번째 연장 진행 중 |
| Cursor | 97 | — | Sand 에이전트 개발, Automations 출시 |
| Codex CLI | 90 | — | GPT-5.6 탑재, ChatGPT 통합 완료 |
| Windsurf | 85 | — | Devin Desktop 전환 안정화 |
| Aider | 68 | — | 오픈소스 꾸준, 44K 스타 |
| Gemini CLI | 11 | ↓1 | 셧다운 28일째, 기업 전용 |
| Copilot | 10 | ↓1 | 71주 하락, Code Quality GA 4일 남음 |

Grok Build 오픈소스 전환은 투명성 확보를 위한 진전이지만, 유출 코드가 바이너리에 잔존하는 한 신뢰 회복까지는 갈 길이 멀다.

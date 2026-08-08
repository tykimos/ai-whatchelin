---
title: "Atlas 내일 종료, Kiro Crew 오픈소스 — AI 코딩 도구 '개방 vs 폐쇄' 노선 갈림길"
date: 2026-08-08
lang: ko
categories: [news]
tags: [openai, atlas, kiro, claude-code, codex-cli, antigravity, copilot, devin, deepseek, cursor]
excerpt: "OpenAI Atlas 브라우저가 내일 종료되고, AWS는 Kiro Crew를 Apache 2.0으로 공개했다. Claude Code v2.1.225는 게이트웨이 비용 제한을, Codex CLI v0.147.0은 에이전트 플러그인 생태계를 열었다 — AI 코딩 도구 시장이 '개방'과 '폐쇄'라는 두 갈래로 선명하게 갈라지고 있다."
---

OpenAI Atlas가 내일 영구 종료되고, AWS가 Kiro Crew를 오픈소스로 풀면서, AI 코딩 도구 시장의 경쟁 구도가 '개방 vs 폐쇄'라는 새로운 축으로 재편되고 있다. 같은 날 Claude Code와 Codex CLI 모두 에이전트 플러그인 생태계를 확장하는 업데이트를 내놨다.

## OpenAI: Atlas D-1 — 9개월 만의 퇴장

OpenAI Atlas 브라우저가 내일(8월 9일) 완전 종료된다([Digital Trends](https://www.digitaltrends.com/computing/chatgpt-atlas-is-shutting-down-and-it-has-some-homework-left-before-you-migrate/)). 2025년 10월 출시 이후 9개월도 채 안 되는 수명이었다. 에이전틱 브라우징 기능은 ChatGPT와 Codex에 통합되며, 북마크와 브라우징 히스토리는 사용자가 수동으로 HTML 파일로 내보내야 한다([TechRadar](https://www.techradar.com/pro/openai-shuts-down-its-atlas-browser-after-not-even-a-year)). 한편 Codex CLI v0.147.0은 포터블 에이전트 플러그인, `--approve-for-me` 자동 승인 플래그, MCP 2026-07-28 프로토콜 지원을 도입했다([releasebot.io](https://releasebot.io/updates/openai/codex)).

## AWS Kiro: Crew 오픈소스 — 에이전트 하니스는 비공개

AWS가 Kiro Crew를 Apache 2.0으로 공개했다([Forbes](https://www.forbes.com/sites/janakirammsv/2026/08/06/aws-open-sources-kiro-crew-but-keeps-the-agent-harness-closed/)). Amazon 내부에서 39,000명 이상이 사용하던 멀티에이전트 오케스트레이션 플랫폼이 세상에 나왔지만, 핵심인 에이전트 하니스(파운데이션 모델과 통신하는 코어 런타임)는 여전히 비공개다. Kiro IDE 1.0.288도 같은 날 배포되어 Agent Plugin 형식의 Powers 지원과 세션 고정 기능을 추가했다([kiro.dev](https://kiro.dev/changelog/ide/)).

## Claude Code: v2.1.225 — 비용 제어와 보안 수정

Anthropic이 Claude Code v2.1.225를 배포했다([releasebot.io](https://releasebot.io/updates/anthropic/claude-code)). 게이트웨이 비용 제한이 사용량 경고에 반영되어 제한 도달 시 상한·리셋 시간·운영자 메시지가 표시된다. `claude agents`에 워크스페이스 신뢰 프롬프트가 추가됐고, 헤드리스 세션에서 OAuth 토큰이 단기 토큰으로 교체되던 버그, macOS MCP OAuth 키체인 타임아웃 등 6건의 버그가 수정됐다. 별도로 Anthropic은 Fable 5의 생물학 관련 모델 폴백을 85% 줄이는 세이프가드 개선을 발표했다([anthropic.com](https://www.anthropic.com/news/improving-fable-5-s-biology-safeguards)).

## Antigravity: Desktop v2.6.0 + CLI Vim 모드

Google Antigravity Desktop v2.6.0이 대화 히스토리 로딩 속도를 크게 개선하고 21개 버그를 수정했다([antigravity.google](https://antigravity.google/changelog)). CLI v1.1.11은 Vim 모달 편집(Normal/Insert/Visual/Visual Line)을 도입하여 터미널 파워유저를 정조준하고 있다([releasebot.io](https://releasebot.io/updates/google/antigravity)).

## GitHub Copilot: 코드 리뷰 effort 레벨 GA

Copilot 코드 리뷰에 lite/balanced effort 레벨이 정식 도입되어 변경 사항의 복잡도와 리스크에 따라 리뷰 심도를 조절할 수 있게 됐다([github.blog](https://github.blog/changelog/month/08-2026/)). Code Quality가 PR에 Copilot을 자동 리뷰어로 추가하던 동작도 중단됐다 — "리뷰어 추가는 개발자의 선택"이라는 사용자 피드백을 반영한 조치다.

## DeepSeek: 가격 인상 4일째, V4 Flash 일 8조 토큰

DeepSeek의 '상당한' 가격 인상 예고가 나흘째 파문을 일으키고 있다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-06/deepseek-plans-significant-price-increase-for-its-ai-services)). 창업자 Jun Song은 2-10배 인상을 시사하면서도 "서양 경쟁사보다는 여전히 저렴할 것"이라고 밝혔다. V4 Flash가 8월 1일 하루에 8조 토큰을 처리하면서 인프라 비용이 급증한 것이 배경이다([explainx.ai](https://www.explainx.ai/blog/deepseek-api-price-increase-jun-song-august-2026)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.225 비용 제한 지원, 보안 수정 |
| ChatGPT | 99 | — | Atlas 내일 종료, GPT-5.6 무제한 지속 |
| Antigravity | 99 | — | Desktop v2.6.0 + CLI Vim 모드 |
| Claude AI | 99 | — | Fable 5 생물학 세이프가드 85% 개선 |
| Codex CLI | 99 | — | v0.147.0 에이전트 플러그인, 비용 상한 도달 |
| Cursor | 97 | — | iOS 퍼블릭 베타, $30억 ARR |
| Windsurf | 85 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 2월 이후 릴리스 없음, 44K 스타 |
| Copilot | 1 | — | 코드 리뷰 GA에도 9/1 대폐기 D-24 |
| Gemini CLI | 1 | — | 폐쇄 51일째, Antigravity 완전 대체 |

Atlas 종료와 Kiro Crew 오픈소스가 같은 날 일어나면서, AI 코딩 도구 시장의 경쟁이 '제품 기능'에서 '생태계 개방성'으로 이동하고 있음이 선명해졌다.

---
title: "Cursor와 Copilot, 19점 동률 — AI 코딩 에디터 전쟁의 상징적 교차점"
date: 2026-10-06
lang: ko
categories: [news]
tags: [cursor, copilot, antigravity, gemini, anthropic, sourcegraph]
excerpt: "40일째 추락하는 Cursor가 반등하는 Copilot과 19점에서 만났다. Antigravity 구 프리뷰가 퇴장하고, Sourcegraph CEO는 AI 코드 '쓰나미'를 경고한다."
---

Cursor의 40일 연속 하락과 GitHub Copilot의 꾸준한 반등이 하나의 숫자에서 만났다: 19. SpaceX 인수 이후 끝없이 추락하던 에디터와, 85주 바닥(1점)을 찍고 올라오는 플랫폼이 같은 점수에 서게 된 것은 AI 코딩 도구 시장의 구조적 재편을 상징한다.

## Cursor vs Copilot: 19점 동률의 의미

Cursor는 SpaceX의 $600억 Anysphere 인수 이후 OpenAI가 모델 접근을 11월 12일자로 차단하겠다고 선언한 뒤 40일째 내리막을 걷고 있다([DevOps.com](https://devops.com/openai-cuts-off-cursors-model-access-after-spacex-acquisition/)). Compile 2026에서 자체 프론티어 모델, Origin 플랫폼, 모바일 앱을 발표했지만 시장 신뢰는 아직 회복되지 않았다.

반면 GitHub Copilot은 Computer Use 퍼블릭 프리뷰, HydraFusion 멀티모델 오케스트레이션의 VS Code 확장, Code Review API GA 등 연속 타격으로 85주 바닥에서 19점까지 올라왔다([GitHub Changelog](https://github.blog/changelog/label/copilot/)). 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7을 일괄 폐기하고 최신 모델로 교체했다([GitHub Changelog](https://github.blog/changelog/2026-10-02-selected-models-in-github-copilot-deprecated/)).

## Antigravity: 5월 프리뷰 퇴장, 마이그레이션 필수

Google Antigravity의 antigravity-preview-05-2026이 10월 5일부로 완전 종료됐다([Kingy AI](https://kingy.ai/ai-launch-tracker/antigravity-may-preview-retirement-october-5-2026/)). 이전 버전을 호출하는 애플리케이션, 예약 워크플로, CI 파이프라인은 경고 없이 "version no longer supported" 오류를 반환한다. antigravity-preview-09-2026으로의 마이그레이션이 필수이며, 새 버전은 파일 작업 PascalCase 전환과 라인 범위 교체 편집 방식을 채택했다([ai.google.dev](https://ai.google.dev/gemini-api/docs/models/antigravity-preview-05-2026)).

## Sourcegraph CEO: AI 코드 '쓰나미'가 코드베이스를 부식시키고 있다

Sourcegraph CEO Dan Adler는 코딩 에이전트가 생산하는 코드의 "쓰나미"가 은행, 자동차, 항공사의 수십 년 된 코드베이스를 부식시키고 있다고 경고했다([Artificially Intimidating](https://artificiallyintimidating.com/p/ai-brief-october-5-2026)). 코드 중복, 표준 드리프트, 취약한 의존성, 새로운 보안 취약점이 함께 늘고 있다는 지적이다.

## Anthropic IPO D-8: 투자자 데이 카운트다운

Anthropic의 프리IPO 투자자 데이까지 8일 남았다. 10월 14일 샌프란시스코 본사에서 주요 기관투자자들이 경영진과 질의응답을 갖는다([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/anthropic-is-said-to-plan-pre-ipo-investor-day-as-listing-nears)). 11월 중순 상장 목표, 밸류에이션 최대 $2조.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Pro 500 안정, GPT-6.1 Sol 정착 |
| Claude Code | 99 | — | Mods 안착, v2.1.288 안정성 패치 |
| Codex CLI | 99 | — | Cloud 모드 확산, 음성 입력 기본화 |
| Antigravity | 99 | — | 5월 프리뷰 종료, 09-2026 전환 완료 |
| Claude AI | 99 | — | IPO D-8, Frontier Academy 가동 |
| Windsurf | 88 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 오픈소스 꾸준, 신규 릴리스 없음 |
| Cursor | 19 | ↓2 | 40일 연속 하락, Copilot과 동률 |
| GH Copilot | 19 | ↑2 | HydraFusion IDE 확장, 모델 폐기 완료 |
| Gemini CLI | 1 | — | 6월 퇴역, Antigravity 전환 완료 |

Cursor와 Copilot의 동률은 단순한 숫자 이상의 의미를 갖는다. SpaceX 인수라는 외부 충격이 한 도구를 무너뜨리는 동안, 꾸준한 기능 개선이 다른 도구를 바닥에서 끌어올린 사례다. OpenAI 셧오프 D-37 — 남은 37일이 Cursor의 운명을 결정한다.

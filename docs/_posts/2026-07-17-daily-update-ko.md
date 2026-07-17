---
title: "Gemini 3.5 Pro, 약속한 7/17에도 불발 — Google의 침묵이 더 무섭다"
date: 2026-07-17
lang: ko
categories: [news]
tags: [gemini-3-5-pro, claude-code, github-copilot, grok-build, antigravity]
excerpt: "루머로 떠돌던 Gemini 3.5 Pro의 7월 17일 GA 목표일이 경과했지만 Google은 침묵을 유지하고 있다. 한편 Claude Code v2.1.212는 /fork의 백그라운드 세션 전환으로 멀티태스킹을 강화했다."
---

Google이 침묵하고 있다. 어제 Bloomberg 폭탄으로 시가총액 $2000억이 증발한 데 이어, 업계가 주시하던 Gemini 3.5 Pro의 7월 17일 GA 목표일이 경과했지만 공식 발표는 없다. DeepMind 모델 페이지에는 여전히 "3.5 Pro coming soon"이라고만 적혀 있다([DeepMind](https://deepmind.google/models/gemini/)).

## Gemini 3.5 Pro — 7/17 불발, 신뢰 회복은 요원

TechTimes와 HackerNoon 등 복수 매체가 보도했던 7월 17일 GA 목표일이 지나갔지만, Google은 공식 확인도 연기 공지도 내놓지 않았다([TechTimes](https://www.techtimes.com/articles/320308/20260713/gemini-35-pro-targets-july-17-after-full-rebuild-every-spec-remains-unconfirmed.htm)). Gemini API에는 3.5 Flash와 3.1 Pro만 등록되어 있으며, 2M 컨텍스트 윈도우와 Deep Think 모드 등 루머로 돌던 스펙은 여전히 미확인 상태다([AIToolsReview](https://aitoolsreview.co.uk/insights/gemini-3-5-pro)). 어제 Bloomberg가 보도한 "수개월 지연"과 기반 모델 전면 폐기 소식에 이어, 오늘의 침묵은 개발자들의 불안을 더욱 키우고 있다.

## Claude Code v2.1.212 — /fork가 백그라운드로 진화

Anthropic이 Claude Code v2.1.212를 릴리스했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 핵심 변경은 `/fork` 명령어다. 기존에는 세션 내 서브에이전트를 생성했지만, 이제 대화를 독립 백그라운드 세션으로 복사한다. 기존 동작은 `/subtask`으로 이관됐다. 세션당 WebSearch 호출 제한(기본 200회, `CLAUDE_CODE_MAX_WEB_SEARCHES_PER_SESSION`으로 조절)이 추가되어 폭주 검색 루프를 차단하고, `claude auto-mode reset` 명령어로 자동 모드 설정을 초기화할 수 있게 됐다.

## Copilot Code Quality — 3일 뒤 유료 전환

GitHub Code Quality가 7월 20일 GA로 전환되며 무료 프리뷰가 종료된다([GitHub](https://github.blog/changelog/2026-06-16-github-code-quality-generally-available-july-20-2026/)). 가격은 활성 커미터 기준 월 $10이며, AI 기반 기능(Copilot 코드 리뷰, AI 탐지, Autofix)은 별도 사용량 과금이다. 프리뷰 기간 10,000개 이상 기업이 사용했던 만큼, 갑작스러운 유료 전환에 대한 반발이 예상된다([DevOps.com](https://devops.com/github-code-quality-moves-to-general-availability-bringing-new-costs-and-capabilities/)).

## Grok Build — 오픈소스 후에도 유출 코드 건재

xAI가 Grok Build를 Apache 2.0으로 오픈소스 전환한 지 이틀째지만, Git 레포 전체를 GCS에 업로드하던 코드는 바이너리에 그대로 남아있다([Simon Willison](https://simonwillison.net/2026/Jul/15/grok-build/)). 피해 사용자 수, 수집 데이터 총량, 삭제 검증 어느 것도 공개되지 않았다([The Register](https://www.theregister.com/ai-and-ml/2026/07/16/spacex-open-sources-grok-build-after-data-retention-furore/5272333)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.212, /fork 백그라운드 세션 |
| Antigravity | 99 | — | v2.2.1 안정, 26주 연속 |
| ChatGPT | 99 | — | Codex Micro 첫 배송 7/24 예정 |
| Claude AI | 98 | — | Fable 5 세 번째 연장, Ode 출범 |
| Cursor | 97 | — | SpaceX 인수 Q3 마감 예정 |
| Codex CLI | 90 | — | GPT-5.6 탑재, ChatGPT 통합 완료 |
| Windsurf | 85 | — | Devin Desktop v3.4.27 안정 |
| Aider | 68 | — | 오픈소스 꾸준, 44K 스타 |
| Gemini CLI | 9 | ↓1 | 3.5 Pro 7/17 불발, 셧다운 29일째 |
| Copilot | 9 | ↓1 | 72주 하락, Code Quality GA 3일 남음 |

Gemini CLI와 Copilot이 나란히 9로 하락하며 한 자릿수 영역에 진입했다. Google이 3.5 Pro를 언제 내놓든, 어제의 Bloomberg 폭탄과 오늘의 침묵이 남긴 신뢰 적자를 메우는 데는 상당한 시간이 걸릴 것이다.

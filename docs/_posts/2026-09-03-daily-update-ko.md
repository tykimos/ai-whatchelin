---
title: "Cursor 자유낙하 7일째 — OpenAI 결별 후 99에서 83으로 추락"
date: 2026-09-03
lang: ko
categories: [news]
tags: [cursor, claude, copilot, codex-cli, antigravity]
excerpt: "SpaceX 인수로 촉발된 OpenAI 파트너십 종료 이후 Cursor가 7일 연속 하락세를 이어가고 있다. Claude Fable 5.1은 출시 이틀 만에 Claude Code 기본 모델로 자리잡았다."
---

Cursor가 멈추지 않는다 — 하락이. SpaceX의 600억 달러 인수가 OpenAI의 계약 내 통제권 변경 조항을 발동시킨 이후, Cursor의 인기도 점수는 일주일 전 99에서 오늘 83까지 7일 연속 추락했다([Developers Digest](https://www.developersdigest.tech/blog/ai-coding-tools-pricing-2026)). OpenAI CEO가 "트래픽의 5%에 불과하다"고 일축했지만, 개발자 이탈은 수치가 말해준다.

## Cursor: OpenAI 셧다운 D-70, 개발자 이동 가속

Cursor는 GPT 모델 접근이 11월 12일 완전 차단되기까지 70일을 남겨둔 채, Grok 4.6과 Anthropic Claude로 피벗 중이다([Value Add VC](https://valueaddvc.com/blog/ai-coding-tools-ranked-2026-cursor-copilot-windsurf-devin-and-claude-code-compared)). 인도 시장에서는 7월 출시한 ₹649(~$7) Start 플랜이 300만 인도 개발자를 붙잡아두고 있지만([Cursor Blog](https://cursor.com/blog/cursor-start-india)), 글로벌 개발자 커뮤니티에서는 Claude Code와 Codex CLI로의 이동이 뚜렷하다. 6일 연속 하락은 Aur0ra 랜섬웨어 사건(8/27)과 SpaceX Origin 데이터 약관 논란(8/18)이 겹치며 신뢰가 타격받은 결과다.

## Claude: Fable 5.1 출시 2일 차, 벌써 기본 모델

Anthropic이 9월 1일 출시한 Claude Fable 5.1이 하루 만에 Claude Code의 기본 Fable 모델로 설정됐다([VentureBeat](https://venturebeat.com/technology/anthropics-claude-fable-5-1-and-mythos-5-1-arrive-with-a-75-cost-reduction-for-fable-cache-reads)). Terminal-Bench 55.8%(Fable 5 대비 42%)로 코딩 성능이 크게 올랐고, 캐시 읽기 비용은 75% 절감($0.25/MTok)됐다. Mythos 5.1은 사이버보안·생명과학 분야의 검증된 조직에만 제한 제공된다([MacRumors](https://www.macrumors.com/2026/09/01/anthropic-claude-fable-5-1/)).

## GitHub Copilot: 9월 리셋 본격 가동

9월 1일부로 Copilot의 대규모 변화가 실행됐다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Business 크레딧 37% 삭감(3,000→1,900), Enterprise 44% 삭감(7,000→3,900), Gemini 3.1 Pro와 Claude Opus/Sonnet 4.5·4.6 등 6개 모델 퇴출([GitHub Changelog](https://github.blog/changelog/2026-08-31-selected-github-copilot-models-deprecated/)). 9월 28일에는 Chat·Mobile·클라우드 에이전트가 통합 Copilot으로 합쳐진다.

## Codex CLI·Antigravity: 꾸준한 개선

Codex CLI는 Vim 모드에 실행취소(u)/다시실행(Ctrl+R) 지원을 추가하고, 플러그인 마켓플레이스에서 원격 설치·제거가 가능해졌다([Releasebot](https://releasebot.io/updates/openai/codex)). Antigravity CLI는 GEMINI_API_KEY 환경변수로 로그인 없이 Gemini API 직접 연결을 지원하며, Gemini Enterprise 계정 비즈니스 로그인도 추가됐다([Google Developers Blog](https://developers.googleblog.com/an-important-update-transitioning-gemini-cli-to-antigravity-cli/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | 안정, 헬스케어 플러그인 확장 |
| Claude Code | 99 | — | Fable 5.1 기본 모델 전환 |
| Claude AI | 99 | — | Fable 5.1 + Mythos 5.1 출시 효과 |
| Codex CLI | 99 | — | Vim 모드·플러그인 마켓 업데이트 |
| Antigravity | 99 | — | API 키 직접 연결 지원 |
| Windsurf | 86 | — | Devin Desktop으로 안정 유지 |
| Cursor | 83 | ↓2 | 7일 연속 하락, D-70 |
| Aider | 68 | — | 변동 없음 |
| GH Copilot | 1 | — | 크레딧 삭감·모델 퇴출 실행 |
| Gemini CLI | 1 | — | Antigravity CLI로 이전 완료 |

---
title: "Cursor와 Copilot, 19점 동률 — Meta·Microsoft는 Claude 사용 축소"
date: 2026-10-06
lang: ko
categories: [news]
tags: [cursor, copilot, antigravity, anthropic, claude-code, sourcegraph]
excerpt: "40일째 추락하는 Cursor가 반등하는 Copilot과 19점에서 만났다. 한편 Meta와 Microsoft가 Claude 사용을 축소하는 가운데, Barclays는 개발자 50%에게 Claude Code를 확대한다."
---

Cursor의 40일 연속 하락과 GitHub Copilot의 꾸준한 반등이 하나의 숫자에서 만났다: 19. SpaceX 인수 이후 끝없이 추락하던 에디터와 85주 바닥(1점)에서 올라오는 플랫폼이 같은 점수에 선 것은 AI 코딩 도구 시장의 구조적 재편을 상징한다.

## Cursor vs Copilot: 19점 동률의 의미

Cursor는 SpaceX의 $600억 Anysphere 인수 이후 OpenAI가 모델 접근을 11월 12일자로 차단하겠다고 선언한 뒤 40일째 내리막을 걷고 있다([DevOps.com](https://devops.com/openai-cuts-off-cursors-model-access-after-spacex-acquisition/)). Compile 2026에서 자체 프론티어 모델, Origin 플랫폼, 모바일 앱을 발표했지만 시장 신뢰는 아직 회복되지 않았다.

반면 GitHub Copilot은 Computer Use 퍼블릭 프리뷰, HydraFusion 멀티모델 오케스트레이션의 VS Code 확장, Code Review API GA로 85주 바닥에서 19점까지 올라왔다([GitHub Changelog](https://github.blog/changelog/label/copilot/)). 10월 2일에는 Gemini 3.5/3.6 Flash, Kimi K2.7 Code, Claude Opus 4.7을 일괄 폐기하고 최신 모델로 교체했으며, Claude Sonnet 5.5와 GPT-6.1 Sol이 GA 모델로 추가됐다([GitHub Changelog](https://github.blog/changelog/2026-10-02-selected-models-in-github-copilot-deprecated/)). 10월 22일부터 Business/Enterprise 고객 대상 Copilot 기능 기본 활성화가 시작될 예정이다([GitHub Blog](https://github.blog/changelog/2026-10-01-github-copilot-in-vs-code-september-2026-releases/)).

## Claude: 엇갈리는 신호 — Meta·Microsoft 축소, Barclays 확대

Claude를 둘러싼 기업 채택에서 상반된 신호가 나왔다. Meta는 내부 Claude 사용 인원을 약 3만 명 수준으로 축소했고, Microsoft는 Claude 관련 지출 전망을 3분의 1로 삭감했다([Seeking Alpha](https://seekingalpha.com/news/4650314-meta-microsoft-scale-back-employee-use-of-claude-report)). 반면 Barclays는 Claude Code를 전체 개발자의 50%에게 확대 배포하며 금융권 AI 코딩 도구 도입의 선두를 달리고 있다.

한편 Claude Code는 v2.1.291을 출시해 권한 프롬프트와 세션 지속성 관련 회귀 버그를 수정했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Anthropic 프리IPO 투자자 데이(10월 14일)까지 8일 남았으며, 밸류에이션 최대 $2조 목표로 11월 중순 상장이 예정돼 있다([Bloomberg](https://www.bloomberg.com/news/articles/2026-10-01/anthropic-is-said-to-plan-pre-ipo-investor-day-as-listing-nears)).

## Antigravity: 5월 프리뷰 퇴장, 마이그레이션 필수

Google Antigravity의 antigravity-preview-05-2026이 10월 5일부로 완전 종료됐다([Kingy AI](https://kingy.ai/ai-launch-tracker/antigravity-may-preview-retirement-october-5-2026/)). 이전 버전을 호출하는 CI 파이프라인은 경고 없이 오류를 반환한다. antigravity-preview-09-2026으로의 마이그레이션이 필수이며, 새 버전은 PascalCase 파일 작업과 라인 범위 교체 편집을 채택했다([ai.google.dev](https://ai.google.dev/gemini-api/docs/models/antigravity-preview-05-2026)).

## Sourcegraph CEO: AI 코드 '쓰나미' 경고

Sourcegraph CEO Dan Adler는 코딩 에이전트가 만드는 코드의 "쓰나미"가 은행·자동차·항공사의 레거시 코드베이스를 부식시키고 있다고 경고했다([Artificially Intimidating](https://artificiallyintimidating.com/p/ai-brief-october-5-2026)). 코드 중복, 표준 드리프트, 새로운 보안 취약점이 동반 증가 중이다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Pro 500 안정, GPT-6.1 Sol 정착 |
| Claude Code | 99 | — | v2.1.291 패치, Barclays 50% 확대 |
| Codex CLI | 99 | — | Cloud 모드 확산, 음성 입력 기본화 |
| Antigravity | 99 | — | 5월 프리뷰 종료, 09-2026 전환 완료 |
| Claude AI | 99 | — | IPO D-8, Meta·MS 축소 vs Barclays 확대 |
| Windsurf | 88 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 오픈소스 꾸준, 신규 릴리스 없음 |
| Cursor | 19 | ↓2 | 40일 연속 하락, Copilot과 동률 |
| GH Copilot | 19 | ↑2 | Sonnet 5.5·Sol GA, 10/22 기본 활성화 |
| Gemini CLI | 1 | — | 6월 퇴역, Antigravity 전환 완료 |

Meta·Microsoft의 Claude 축소와 Barclays의 확대는 같은 도구에 대한 기업의 상반된 판단을 보여준다. OpenAI 셧오프 D-37 — 남은 37일이 Cursor의 운명을 결정한다.

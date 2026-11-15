---
title: "Copilot 모델 대퇴출 D-1 — Goldman Sachs AI 도구 제한, Anthropic IPO 가격 결정 임박"
date: 2026-11-15
lang: ko
categories: [news]
tags: [github-copilot, anthropic, ipo, codex-cli, cursor, claude-code, chatgpt, goldman-sachs]
excerpt: "GitHub Copilot의 3개 모델 퇴출이 내일로 다가왔다. Goldman Sachs가 Claude Code와 GitHub 도구 접근을 엔지니어로 제한했고, Anthropic IPO는 가격 결정 주간에 돌입한다."
---

내일이면 GitHub Copilot에서 세 개의 주요 AI 모델이 사라진다. Claude Opus 4.8, Claude Opus 5, GPT-5.6 Terra가 11월 16일부로 Chat, 인라인 편집, Agent 모드, 코드 자동완성 등 모든 Copilot 영역에서 완전히 제거된다([GitHub Blog](https://github.blog/changelog/2026-10-15-upcoming-deprecation-of-selected-github-copilot-models-in-mid-november)). 연간 Individual 구독자만 Claude Opus 4.8을 유지할 수 있으며, 관리자들은 대체 모델(Opus 5.5, GPT-6.1 Sol)이 정책에서 활성화되어 있는지 반드시 확인해야 한다([dev.classmethod.jp](https://dev.classmethod.jp/en/articles/github-copilot-model-deprecation-nov-2026/)). 정책 토글 외에도 설정 파일, 스크립트, 에이전트 정의에 하드코딩된 모델명을 마감일 전에 업데이트해야 한다([SmartScope](https://smartscope.blog/en/blog/github-copilot-claude-opus-5-deprecation-november-16-2026/)). 한편 Copilot CLI v1.0.106이 11월 6일 안정 버전에 도달하며 GPT-6.1 Terra 지원을 포함한 600건 이상의 변경사항을 반영했다([GitHub Blog](https://github.blog/changelog/2026-11-06-github-copilot-weekly-releases-november-2)). Copilot 인기도는 98점으로 53일째 연속 상승 중이다.

## Goldman Sachs, AI 코딩 도구 접근 엔지니어로 제한

Goldman Sachs가 Claude Code와 GitHub 도구 접근을 엔지니어로 한정하고, 트레이더와 뱅커의 사용을 차단했다([The Decoder](https://the-decoder.com/goldman-sachs-pulls-ai-coding-tools-from-traders-and-bankers/)). 10월 중 내부 가이드라인이 업데이트되었으며, 생산성과 리스크 관리를 이유로 들었다([CrowdfundInsider](https://www.crowdfundinsider.com/?p=321098)). 이번 조치는 Cursor 마켓플레이스에서 발견된 악성 Claude Code 익스텐션 사건 등 AI 에이전트 보안 우려가 커지는 가운데 나왔다. 월가의 AI 도구 도입이 속도를 내던 중 처음 나온 주요 제한 사례로, 업계 전반의 보안 정책 재검토 신호탄이 될 수 있다.

## Anthropic IPO: 로드쇼 6일차, 수요 과열 속 의문도

Anthropic IPO 로드쇼가 6일차에 접어들었다. CEO Dario Amodei가 11월 11일 공식 로드쇼 영상을 공개했다([Constellation Research](https://www.constellationr.com/insights/news/anthropics-ipo-roadshow-video-takeaways-absurd-interesting)). $70-78 주당 가격 범위로 825백만 주의 Class A 주식이 Nasdaq ANT 티커 아래 상장될 예정이다([RTTNews](https://www.rttnews.com/3712632/anthropic-sets-ipo-price-range-at-70-78-per-share-launches-roadshow.aspx)). 주문장은 이미 수배 초과 청약 상태이며, 대만 Fubon Life가 최대 $7억을 입찰한 것으로 알려졌다([BigGo Finance](https://finance.biggo.com/news/9812aa29-cc85-47d4-a68f-946ab4e6a228)). 가격 결정은 다음 주 수요일(11월 19일)경으로 예상된다([BusinessDay](https://www.businessday.co.za/companies/2026-11-14-investors-flock-to-anthropic-ipo-but-question-durability-of-ai-lead/)). 그러나 투자자들은 Google 등 경쟁사가 빠르게 추격하는 상황에서 Anthropic의 기술 리더십 지속 가능성에 의문을 제기하고 있다([Reuters via The Star](https://www.thestar.com.my/tech/tech-news/2026/11/14/exclusive-investors-flock-to-anthropic-ipo-but-question-durability-of-ai-lead)). Renaissance Capital에 따르면 총 모집 규모는 $610억으로, SpaceX에 이어 역대 두 번째로 큰 IPO가 될 전망이다([Renaissance Capital](https://www.renaissancecapital.com/IPO-Center/News/122657/anthropic-sets-terms-for-61-billion-ipo-targeting-a-1.2-trillion-market-cap)).

## Cursor: OpenAI 차단 4일째, 84일째 바닥

OpenAI 모델 접근 차단 후 4일째, Tab 자동완성·자동 모델 선택·클라우드 에이전트 등 핵심 기능이 여전히 복구되지 않고 있다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). SpaceX 인수 후 OpenAI가 "계약 위반 전력"을 이유로 차단을 단행했으며([OpenAI](https://openai.com/index/our-decision-on-cursor-following-its-acquisition-by-spacex/)), Cursor CEO Michael Truell은 OpenAI가 트래픽의 5%에 불과하다고 주장했으나 커뮤니티의 반응은 회의적이다([The New Stack](https://thenewstack.io/openai-cuts-cursor-spacex/)). 대안 전략이 여전히 불투명한 상태다.

## ChatGPT: Chat·Work 탭 통합 + Codex CLI 릴리스 행진

OpenAI가 ChatGPT의 Chat과 Work 탭을 하나로 통합하는 작업을 진행 중이다([TechCrunch](https://techcrunch.com/2026/11/02/openai-is-finally-merging-chatgpts-chat-and-work-tabs/)). Codex CLI는 0.168.0과 0.169.0을 연달아 출시하며 11월 릴리스 행진을 이어가고 있다([Releasebot](https://releasebot.io/updates/openai/codex)). 0.167.0에서는 다중 에이전트 작업을 관리하는 확장 커맨드 센터가 추가되었다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Chat·Work 탭 통합 진행 중 |
| Claude Code | 99 | — | Fable 5.2 기본 모델 전환 6일째 |
| Codex CLI | 99 | — | 11월 6연속 릴리스 행진 |
| Antigravity | 99 | — | Gemini 4 Carbon 합류, 도입 할인 D-15 |
| Claude AI | 99 | — | IPO 로드쇼 6일차, 가격 결정 D-4 |
| GH Copilot | 98 | ↑1 | 53일 연속 상승, 모델 퇴출 D-1 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 4일째, 84일째 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 임박 |

Goldman Sachs의 AI 코딩 도구 제한은 월가 최초의 주요 사례로, 보안 우려가 기업 도입 속도에 브레이크를 걸 수 있다는 신호다. Copilot 모델 퇴출이 내일로 확정되면서 관리자들의 마이그레이션 작업이 최종 마감에 돌입했고, Anthropic IPO는 가격 결정 주간을 앞두고 과열과 의구심이 공존하고 있다.

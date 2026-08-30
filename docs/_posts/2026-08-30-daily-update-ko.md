---
title: "DALL-E GPT 퇴장, Copilot D-1 절벽, Cursor 91 하락 계속 — 9월이 AI 코딩 판도를 뒤엎는다"
date: 2026-08-30
lang: ko
categories: [news]
tags: [chatgpt, dall-e, copilot, cursor, openai, claude-code, anthropic, codex, grok]
excerpt: "DALL-E GPT가 오늘 ChatGPT에서 공식 퇴장하고, Copilot의 9월 1일 대규모 변경까지 48시간이 남았다. Cursor는 OpenAI 결별 여파로 이틀째 하락하며 91을 기록했다. Grok CLI가 상위 5위에 진입했다."
---

DALL-E GPT가 오늘(8월 30일) ChatGPT에서 영구 제거되었다([Inc](https://www.inc.com/jelinda-montes/dall-e-gpt-shuts-down-august-30-download-your-images-before-the-official-tool-disappears-tomorrow/91396233)). OpenAI는 ChatGPT Images(gpt-image-1/gpt-image-1-mini)를 후속 도구로 밀고 있으며, 무료 플랜부터 전 티어에서 이용 가능하다([Notebookcheck](https://www.notebookcheck.net/DALL-E-leaves-ChatGPT-on-August-30-download-your-images-first.1360522.0.html)). Image Generation이 활성화된 커스텀 GPT는 영향받지 않는다.

## Copilot: D-1 — 24시간 후 크레딧 삭감·모델 폐기·가입 재개

9월 1일까지 24시간이다. Business 프로모 크레딧이 3,000에서 1,900으로 37% 삭감되고, Enterprise는 7,000에서 3,900으로 44% 삭감된다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Gemini 3.1 Pro, Claude Opus 4.5/4.6, Claude Sonnet 4.5/4.6, Raptor mini 등 6개 모델이 일괄 폐기된다([GitHub Changelog](https://github.blog/changelog/2026-07-31-upcoming-august-2026-model-deprecations-in-github-copilot/)). 9월 28일 이후에는 github.com의 Copilot Chat, 모바일 Copilot Chat, 클라우드 에이전트가 단일 통합 Copilot 환경으로 재출시될 예정이다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 8월 28일 VS 업데이트로 조직/엔터프라이즈 관리자가 커스텀 에이전트를 레포 전체에 배포할 수 있게 되었고, Slack에서 @GitHub으로 에이전틱 코딩 기능도 공개 프리뷰 중이다([GitHub Blog](https://github.blog/changelog/2026-08-28-github-copilot-in-visual-studio-august-update-2/)).

## Cursor: 91로 이틀째 하락 — OpenAI 결별 여파 지속

어제 Bloomberg가 보도한 OpenAI-Cursor 파트너십 종료 소식이 업계에 계속 파문을 일으키고 있다([The Coin Republic](https://www.thecoinrepublic.com/2026/08/30/openai-news-openai-dumps-cursor-after-spacex-deal-sets-november-cutoff/)). 11월 12일 GPT 모델 접근 차단까지 74일, Cursor는 Grok 4.6과 Anthropic Claude로 대체하고 있지만 Aur0ra 랜섬웨어에 이은 두 번째 신뢰 위기가 점수를 끌어내리고 있다. Cursor CEO Michael Truell은 "OpenAI 모델은 Cursor 사용자 트래픽의 약 5%에 불과하다"며 영향을 최소화했지만, OpenAI 팀과 해결을 위한 대화 중이라고 밝혔다([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)). Anthropic 공동창업자 Tom Brown은 "Cursor 내 Claude 모델 컴퓨트를 지속 확대하겠다"고 즉각 선언했다([WCCFTech](https://wccftech.com/anthropic-pounces-as-openai-abandons-spacexs-cursor-vowing-to-increase-claude-compute-even-as-openai-cites-contract-distrust/)).

## Claude Code: 경량화·토큰 가시성 강화 + 9월 14일 한도 변경 예고

Claude Code 최신 업데이트에서 CLI가 샌드박스 로드 전에 시작되도록 개선되어 체감 속도가 빨라졌다([explainx.ai](https://explainx.ai/blog/claude-code-weekly-update-faster-startup-token-visibility-august-2026)). Linux 빌드가 약 75MB로 축소되었으며, /cost와 /usage, /tasks 명령에 토큰 세부 정보가 추가되었다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). Sonnet 5의 $2/$10 가격도 영구 확정되어 개발자들의 비용 부담이 안정화되었다([Enterprise DNA](https://enterprisedna.co/resources/news/anthropic-claude-sonnet-5-pricing-permanent-reversal-august-2026/)). 한편, Anthropic은 현재 적용 중인 50% 프로모션 한도 증가가 9월 14일 종료되고, 이후 영구 25% 인상으로 대체된다고 발표했다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/)). 결과적으로 현재 대비 약 17% 감소이지만, 프로모션 이전 기준으로는 25% 증가분이 영구 유지된다([Notebookcheck](https://www.notebookcheck.net/Anthropic-announces-a-25-increase-to-Claude-Code-limits-but-there-s-a-17-catch.1382735.0.html)).

## Codex: Appshots + v0.151.0 신규 기능

Codex가 macOS에서 Appshots 기능을 도입해 단축키로 앱 윈도우의 스크린샷과 텍스트를 스레드에 첨부할 수 있게 되었다([Releasebot](https://releasebot.io/updates/openai/codex)). v0.151.0에서는 MCP 서버 발견을 위한 그레이스 기간을 설정할 수 있고, `--approve-for-me` 플래그로 자동 승인 모드가 추가되었다([Havoptic](https://www.havoptic.com/tools/openai-codex)).

## Grok CLI: 상위 5위 CLI 에이전트 진입

무료 오픈소스 CLI 에이전트인 Grok CLI가 8월 들어 상위 5위에 진입하며 Antigravity를 밀어냈다([Pinggy](https://pinggy.io/blog/top_cli_based_ai_coding_agents/)). Grok 4.6 기반으로 Git 워크플로우, 웹 검색, 코드 검색, MCP 서버 지원(Linear, Sentry, Grafana)을 갖추고 있어 SpaceX-Cursor 생태계 확장의 선봉이 되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | CLI 경량화, 9/14 한도 변경 예고, 안정적 최상위 |
| ChatGPT | 99 | — | DALL-E GPT 오늘 퇴장, ChatGPT Images 대체 |
| Codex CLI | 99 | — | Appshots, v0.151.0, --approve-for-me |
| Antigravity | 99 | — | 버전 관리 개선, IDE 확장 안정 |
| Claude AI | 99 | — | Sonnet 5 가격 영구 확정, Cursor 컴퓨트 확대 |
| Cursor | 91 | ↓2 | OpenAI 셧오프 D-74, 이틀째 하락 |
| Windsurf | 86 | — | Devin Desktop 안정, 플러그인 개선 |
| Aider | 68 | — | 44K+ 스타, 유지보수 모드 |
| Copilot | 1 | — | D-1: 크레딧 삭감·모델 폐기·가입 재개 임박 |
| Gemini CLI | 1 | — | 폐쇄 73일째 |

9월 1일이 24시간 앞으로 다가왔다. Copilot은 크레딧 삭감과 모델 폐기로 사실상 초기화되고, Cursor는 OpenAI 결별 이후 Anthropic과 xAI 기반 멀티모델 전략을 본격화한다. Grok CLI의 부상은 SpaceX-Cursor 생태계가 IDE를 넘어 CLI까지 확장하고 있음을 보여준다.

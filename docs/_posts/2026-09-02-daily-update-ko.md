---
title: "Fable 5.1 출격, Cursor 85까지 6일째 추락 — 9월 첫 주, AI 코딩 시장의 명과 암"
date: 2026-09-02
lang: ko
categories: [news]
tags: [anthropic, fable, cursor, claude-code, copilot, chatgpt, salesforce, meta]
excerpt: "Anthropic이 Fable 5.1과 Mythos 5.1을 동시 출시하며 프론티어 모델 경쟁을 재점화했다. Cursor는 OpenAI 셧오프 공포 속 6일 연속 하락해 85를 기록, 99에서 14포인트가 증발했다."
---

Anthropic이 어제(9월 1일) Claude Fable 5.1과 Mythos 5.1을 동시에 출시했다([Roo Newsletter](https://roo.beehiiv.com/p/claude-fable-5-1-mythos-5-1-whats-new)). Fable 5.1은 Terminal-Bench 4.0에서 55.8%를 기록해 전작 Fable 5(42.0%)를 대폭 뛰어넘었고, 캐시 읽기 가격은 75% 인하돼 $0.25/MTok이 됐다([CellCog](https://cellcog.ai/blog/fable-5-1-release-date/)). 반면 Cursor의 하락세는 멈출 기미가 보이지 않는다.

## Anthropic: Fable 5.1 + Mythos 5.1 — 프론티어 재점화

Fable 5.1의 입출력 가격은 $10/$50/MTok으로 전작과 동일하지만, 캐시 읽기가 $1→$0.25로 75% 인하되면서 대규모 코드베이스 작업의 실질 비용이 크게 줄었다([Claude Platform Docs](https://platform.claude.com/docs/en/models/fable-5-1/overview)). Mythos 5.1은 동일 기반 모델이지만 별도 안전장치를 적용해 Project Glasswing 참가자와 승인된 사이버방어·생명과학 연구자에게만 제공된다([Fortune](https://fortune.com/2026/09/02/whats-inside-anthropic-claude-fable-mythos-5-1-smarts-safeguards-anti-distillation-mechanisms/)). Claude Code는 Fable 5.1을 기본 Fable 모델로 즉시 전환했으며, 시간/노력/서브에이전트 제어 및 샌드박스 보호 강화가 함께 적용됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)).

## Cursor: 85까지 6일 연속 하락 — 바닥은 어디인가

Cursor가 6일째 하락을 이어가며 85를 기록했다. 8월 28일 99에서 시작된 낙하로 총 14포인트가 증발했다. OpenAI의 11월 12일 모델 접근 차단이 D-71로 다가오면서([CNBC](https://www.cnbc.com/2026/08/29/openai-cursor-spacex-model-access.html)), Grok 4.6과 Anthropic Claude 모델로의 전환이 핵심 과제로 남아 있다.

## GitHub Copilot: D-Day+1 — 크레딧 삭감과 6개 모델 폐기 시행 중

9월 1일 D-Day가 발효되면서 Copilot Business 크레딧이 3,000→1,900(37% 삭감), Enterprise는 7,000→3,900(44% 삭감)으로 줄었다([GitHub Blog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). Gemini 3.1 Pro, Claude Opus 4.5/4.6, Claude Sonnet 4.5/4.6, Raptor mini 등 6개 모델이 일괄 폐기됐으며, 10월 1일부터는 기존 고객도 전원 선불 과금으로 전환된다([GitHub Changelog](https://github.blog/changelog/2026-08-31-selected-github-copilot-models-deprecated/)). 한편 9월 28일부터 github.com Copilot Chat, Mobile Chat, 클라우드 에이전트가 단일 통합 환경으로 재출시되며, 채팅 데이터 보존 기간이 28일에서 계정 수명 전체로 확대된다([Developers Digest](https://www.developersdigest.tech/blog/github-copilot-september-policy-billing-reset-2026)).

## Claude.ai: Microsoft 365 쓰기 도구 + Claudeforce + 콘텐츠 인증

Claude.ai의 Microsoft 365 커넥터에 쓰기 기능이 추가됐다. 이메일 초안·발송, 캘린더 관리, OneDrive·SharePoint 파일 생성·수정이 가능해졌다([Releasebot](https://releasebot.io/updates/anthropic/claude)). Salesforce와의 Claudeforce 파트너십도 공개돼, Claude가 Agentforce·Slack·개발자 도구의 기본 추론 모델로 탑재되며 37개 사전 구축 판매 스킬이 9월 오픈 베타를 앞두고 있다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/today)). Anthropic은 또한 claude.com/check-content에서 C2PA 콘텐츠 자격 증명을 읽어 파일이 Claude로 생성·편집되었는지 확인하는 무료 브라우저 도구를 출시했다([Tech Startups](https://techstartups.com/2026/09/02/top-tech-news-today-september-2-2026-anthropic-google-meta-nvidia-perplexity-openai-tencent-more/)).

## ChatGPT: 9월 기능 업데이트 물결

ChatGPT가 9월 첫 날부터 대규모 기능 업데이트를 쏟아냈다. 미국 자격 임상의 대상 헬스케어 공공 데이터(생물의학 연구·임상시험·Medicare 데이터)가 추가됐고, iPhone 잠금화면과 Dynamic Island에서 Live Voice를 바로 사용할 수 있게 됐다([OpenAI Release Notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)). 다국어 음성-텍스트 변환 정확도도 새 모델로 개선됐다.

## Meta: Muse Code — 첫 AI 코딩 에이전트 출격

Meta가 Muse Code를 출시하며 AI 코딩 에이전트 시장에 본격 진입했다. Muse Spark 1.2와 함께 출시된 이 에이전트는 풀스택 소프트웨어 엔지니어링 워크플로를 지원한다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Fable 5.1 출시, 기본 모델 전환, 9/14 한도 25%↑ 예고 |
| ChatGPT | 99 | — | 헬스케어 데이터·Live Voice 잠금화면, GPT-5.6 안착 |
| Codex CLI | 99 | — | 2,000만 사용자, v0.151.0 안정 |
| Antigravity | 99 | — | 29주 연속 99, Enterprise 포함 |
| Claude AI | 99 | — | M365 쓰기 도구, Claudeforce 파트너십 |
| Cursor | 85 | ↓2 | 6일째 추락, OpenAI 셧오프 D-71 |
| Windsurf | 86 | — | Devin Desktop 안정 유지 |
| Aider | 68 | — | 44K+ 스타, 유지보수 모드 |
| Copilot | 1 | — | D-Day+1: 크레딧 37-44% 삭감·6개 모델 폐기·10/1 선불 전환 |
| Gemini CLI | 1 | — | 폐쇄 76일째 |

Fable 5.1 출시로 Anthropic이 프론티어 모델 경쟁에서 다시 한 발 앞서 나갔다. Copilot의 크레딧 삭감이 실질적 이탈로 이어질지, Cursor의 하락세가 언제 멈출지, 그리고 Meta의 코딩 에이전트 진입이 시장 판도를 어떻게 바꿀지가 이번 주의 관전 포인트다.

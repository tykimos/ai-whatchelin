---
title: "Kimi K3 오픈 웨이트 D-Day — 역대 최대 594GB가 풀렸다"
date: 2026-07-27
lang: ko
categories: [news]
tags: [kimi-k3, mcp, claude-code, cursor, github-copilot, antigravity, gemini-cli]
excerpt: "Kimi K3 2.8T 파라미터 오픈 웨이트가 오늘 Hugging Face에 풀렸다. 594GB MXFP4 세이프텐서, 수정 MIT 라이선스. MCP 스테이트리스 최종 릴리스는 내일로 D-1. AI 코딩 도구 생태계가 급변하는 주말 한가운데다."
---

예고대로 Kimi K3의 오픈 웨이트가 오늘(7월 27일) 00:00 UTC에 풀렸다. 2.8T 파라미터 스파스 MoE 모델의 전체 가중치가 공개된 건 역사상 처음이다. 동시에 MCP 최종 릴리스가 내일(7월 28일)로 하루 앞으로 다가오면서, AI 코딩 도구 생태계는 이번 주말이 2026년 하반기의 방향을 가르는 분수령이 되고 있다.

## Kimi K3: 역대 최대 오픈 웨이트, 드디어 공개

Moonshot AI의 Kimi K3가 오늘 Hugging Face(`moonshotai/Kimi-K3-MXFP4`)에 오픈 웨이트를 업로드했다([eigent.ai](https://www.eigent.ai/blog/kimi-k3-open-weight-frontier-model)). MXFP4 포맷 기준 약 594GB, BF16 풀 웨이트는 약 1.4TB에 달한다([Hugging Face Blog](https://huggingface.co/blog/ResterChed/kimi-k3-model-overview-mxfp4-quantization-open-wei)). 수정 MIT 라이선스로 배포되며, Together AI와 Modal이 D-0 호스팅 인퍼런스를 즉시 제공하기 시작했다. SWE Marathon 42.0(분야 최고), BrowseComp 91.2, DeepSearchQA 95.0으로 강력한 벤치마크 결과를 보여주지만, 독립 테스트에서 51% 할루시네이션 비율이 지적돼 실전 투입에는 주의가 필요하다([TechTimes](https://www.techtimes.com/articles/321551/20260725/kimi-k3-open-weights-arrive-sunday-self-hosting-cuts-china-data-risk-api-never-can.htm)). Hacker News에서 6시간 만에 528점, 241개 댓글을 기록했으며 GPU 요구사항(B200 8~16장)과 셀프호스팅 경제성이 핵심 논점이다.

## MCP 2026-07-28: 최종 릴리스 D-1

MCP 역사상 가장 큰 개편이 내일 확정된다([MCP Blog](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/)). 세션, initialize 핸드셰이크, 세션 상태가 모두 제거되고, 모든 요청이 자체 완결형으로 바뀌는 스테이트리스 아키텍처가 핵심이다. 새로운 HTTP 헤더 2개가 필수화되고, sampling·roots·logging 3개 서브시스템이 폐기 예정(최소 12개월 유지)이 된다([Developers Digest](https://www.developersdigest.tech/blog/mcp-2026-07-28-breaking-changes)). 신규 서버가 구형 클라이언트와 호환되지 않으므로, MCP 서버 운영자라면 오늘 안에 마이그레이션 계획을 확정해야 한다. Tier 1 SDK(공식 TypeScript/Python)는 10주 RC-to-final 윈도우 내 지원 예정이다([Arcade.dev](https://www.arcade.dev/blog/mcp-going-stateless/)).

## GitHub Copilot: Gemini 모델 퇴장 D-4, 역대 최저 78주 연속

Gemini 2.5 Pro와 Gemini 3 Flash가 7월 31일 Copilot 전 경험에서 제거된다 — 4일 남았다([GitHub Blog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)). 대체 모델로 Gemini 3.1 Pro 또는 Gemini 3.5 Flash로의 마이그레이션이 필요하다. GitHub Models 완전 폐쇄도 D-3(7월 30일)으로 임박했다. Copilot은 78주 연속 하락세로 점수 1에 머물러 있다.

## 커뮤니티 온도: 오픈 웨이트 경쟁의 새 국면

Kimi K3의 공개는 "API만으로는 해결할 수 없는 데이터 주권 문제를 셀프호스팅으로 회피할 수 있다"는 점에서 엔터프라이즈 시장의 관심을 집중시키고 있다. 다만 단일 GPU 추론이 불가능한 594GB 규모와 51% 할루시네이션율은 실전 도입의 진입장벽으로 남는다. DeepSeek V4가 $0.14/$0.28/MTok이라는 파격 가격으로 예산 옵션을 차지하고 있어, 오픈 웨이트 진영 내부의 가격-성능 경쟁도 치열해지고 있다([LogRocket](https://blog.logrocket.com/ai-dev-tool-power-rankings/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 기본, 안정 운영 |
| ChatGPT | 99 | — | Sol 사건 후폭풍, Codex 5M 주간 사용자 |
| Antigravity | 99 | — | v1.1.7 안정, 커스텀 에이전트 정착 |
| Claude AI | 99 | — | Opus 5 출시 후 안정 |
| Cursor | 97 | — | Router 확산, iOS 베타 정착 |
| Codex CLI | 91 | — | Ona 통합 진행, 5M+ 주간 사용자 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | — | 78주 하락, Gemini 퇴장 D-4 |
| Gemini CLI | 1 | — | 소비자 접근 차단 39일째 |

상위 4개 도구(Claude Code, ChatGPT, Antigravity, Claude AI)가 99점으로 동률을 유지하는 가운데, Kimi K3 오픈 웨이트와 내일 MCP 최종 릴리스가 겹치면서 이번 주말이 생태계 재편의 변곡점이 되고 있다.

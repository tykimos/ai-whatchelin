---
title: "Kimi K3 오픈 웨이트 D-Day, OpenAI 4일 연속 장애 속 MCP 스테이트리스 전환 초읽기"
date: 2026-07-27
lang: ko
categories: [news]
tags: [kimi-k3, mcp, openai, claude-code, cursor, github-copilot, antigravity, gemini-cli]
excerpt: "Kimi K3의 2.8T 파라미터 오픈 웨이트가 Hugging Face에 공개됐고, MCP 스테이트리스 최종 릴리스가 내일로 다가왔다. 한편 OpenAI는 4일 연속 장애로 신뢰 위기에 직면했다."
---

역대 최대 오픈소스 모델의 가중치 공개, MCP 프로토콜의 근본적 전환, 그리고 OpenAI의 연이은 인프라 장애가 겹치면서 AI 코딩 도구 생태계가 격변의 주말을 맞고 있다.

## Kimi K3: 594GB 오픈 웨이트, 오늘 풀렸다

Moonshot AI가 2.8T 파라미터 스파스 MoE 모델 Kimi K3의 전체 가중치를 오늘(7월 27일) Hugging Face에 공개했다([eigent.ai](https://www.eigent.ai/blog/kimi-k3-open-weight-frontier-model)). MXFP4 포맷 약 594GB, BF16 풀 웨이트 약 1.4TB 규모로 수정 MIT 라이선스 하에 배포된다([Hugging Face Blog](https://huggingface.co/blog/ResterChed/kimi-k3-model-overview-mxfp4-quantization-open-wei)). Together AI와 Modal이 D-0 호스팅 인퍼런스를 제공하며, SWE Marathon 42.0(분야 최고), BrowseComp 91.2 등 인상적인 벤치마크를 보여주고 있다. 다만 독립 테스트에서 51% 할루시네이션율이 보고돼 실전 투입에는 주의가 필요하다([TechTimes](https://www.techtimes.com/articles/321551/20260725/kimi-k3-open-weights-arrive-sunday-self-hosting-cuts-china-data-risk-api-never-can.htm)). Hacker News에서 6시간 만에 528점을 기록하며 GPU 요구사항(B200 8~16장)과 셀프호스팅 경제성이 핵심 논점으로 떠올랐다.

## OpenAI: 4일 연속 장애, 신뢰 흔들린다

7월 25일 OpenAI가 글로벌 장애를 겪었다 — ChatGPT, 개발자 API, Codex가 동부시간 새벽 5시경부터 약 7시간 동안 전면 중단됐다([Unite.AI](https://www.unite.ai/global-outage-hits-openais-chatgpt-api-and-codex/)). API 대시보드 12개, ChatGPT 15개, Codex 4개 구성요소가 영향을 받았으며, 이는 7월 21일·23일·24일·25일로 이어지는 4일 연속 장애의 정점이었다([BleepingComputer](https://www.bleepingcomputer.com/news/artificial-intelligence/openai-confirms-chatgpt-is-down-worldwide/)). GPT-5.6 Sol GA 이후 인프라 안정화가 최대 과제로 부상했다.

## MCP 2026-07-28: 스테이트리스 전환 D-1

MCP 역사상 가장 큰 스펙 변경이 내일 확정된다([MCP Blog](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/)). 세션·initialize 핸드셰이크·세션 상태가 모두 제거되고 스테이트리스 아키텍처로 전환된다. HTTP 헤더 2개가 필수화되고 sampling·roots·logging 3개 서브시스템이 12개월 폐기 예정이다([Arcade.dev](https://www.arcade.dev/blog/mcp-going-stateless/)). 신규 서버가 구형 클라이언트와 호환 불가하므로 MCP 서버 운영자는 오늘 마이그레이션 계획을 확정해야 한다.

## GitHub Copilot: Gemini 퇴장 D-4, 78주 하락

Gemini 2.5 Pro와 Gemini 3 Flash가 7월 31일 Copilot 전 경험에서 제거된다([GitHub Blog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)). GitHub Models 완전 폐쇄도 D-3(7월 30일)으로 임박했다. Copilot은 78주 연속 하락세로 점수 1에 머물러 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 기본, 안정 운영 |
| ChatGPT | 99 | — | Sol 탈출 후폭풍, 4일 연속 장애 |
| Antigravity | 99 | — | v1.1.7 안정, 커스텀 에이전트 정착 |
| Claude AI | 99 | — | Opus 5 출시 후 안정 |
| Cursor | 97 | — | Router 확산, iOS 베타 정착 |
| Codex CLI | 91 | — | Ona 통합 진행, 5M+ 주간 사용자 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | — | 78주 하락, Gemini 퇴장 D-4 |
| Gemini CLI | 1 | — | 소비자 접근 차단 39일째 |

Kimi K3 오픈 웨이트, MCP 스테이트리스 전환, OpenAI 인프라 위기가 한 주말에 겹치면서 AI 코딩 도구 시장의 판도가 빠르게 재편되고 있다.

---

*출처: [eigent.ai](https://www.eigent.ai/blog/kimi-k3-open-weight-frontier-model), [Unite.AI](https://www.unite.ai/global-outage-hits-openais-chatgpt-api-and-codex/), [MCP Blog](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/), [GitHub Blog](https://github.blog/changelog/2026-07-02-upcoming-deprecation-of-gemini-2-5-pro-and-gemini-3-flash/)*

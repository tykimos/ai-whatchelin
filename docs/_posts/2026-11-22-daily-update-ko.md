---
title: "Microsoft MAI Code 2 출시, GPT-6.1 Sol의 98% 성능에 40% 가격 — Ignite 2026"
date: 2026-11-22
lang: ko
categories: [news]
tags: [microsoft, mai-code-2, google, stitch-loop, gemini-4-neon, anthropic, ant-ipo]
excerpt: "Microsoft가 Ignite에서 MAI Code 2를 출시하며 GPT-6.1 Sol 대비 98% 성능에 40% 비용을 내세웠다. Google은 Stitch Loop 대기자 명단을 열었고, ANT는 IPO 데뷔 이후 견고한 흐름을 이어간다."
---

Microsoft가 Ignite 2026에서 MAI Code 2와 경량 버전인 MAI Code 2 Flash를 공개하며 AI 코딩 모델 시장에 본격 진입했다([InfoWorld](https://www.infoworld.com/article/4250152/microsoft-launches-mai-code-2-models-to-challenge-openai-and-anthropic-in-ai-coding.html)). Code 2는 복잡한 멀티파일 디버깅과 리포지토리 전반 추론에, Flash는 일상적인 빈번 편집에 초점을 맞췄다. Microsoft는 자사 벤치마크 4종 평균 기준 GPT-6.1 Sol의 98%에 달하는 성능을 40% 비용으로 달성했다고 주장했다([TNW](https://thenextweb.com/news/microsoft-mai-code-2-licensed-weights-ignite)).

## Microsoft: MAI Code 2가 바꾸는 판도

Code 2는 GitHub Copilot에서 즉시 사용 가능하며, 신뢰할 수 있는 고객에게는 모델 가중치 라이선스도 제공된다([The New Stack](https://thenewstack.io/microsoft-mai-code-2/)). Flash는 GPT-6 Luna 대비 65%, Claude Haiku 5.5 대비 20% 비용으로 동급 성능을 제공한다고 한다. 출력 토큰 가격이 $2.50~$5/M 수준으로, 엔터프라이즈 볼륨 사용 시 비용 절감 효과가 클 것으로 보인다. 다만 성능 비교 수치는 Microsoft 자체 벤치마크 기반이고, 론칭 할인(2027년 5월 종료)이 적용된 가격이라는 점에 주의가 필요하다.

## Google Stitch Loop: 출시 후에도 멈추지 않는 에이전트

Google Labs가 11월 18일 Stitch Loop을 발표했다([Google Blog](https://blog.google/innovation-and-ai/models-and-research/google-labs/stitch-loop/)). GitHub 코드베이스와 라이브 메트릭(로그, 사용자 행동, 피드백)에 연결해 보안, 지연시간, 접근성 문제를 자동으로 발견하고 PR을 올려주는 장기 실행 에이전트다. 180개 이상의 통합과 커스텀 MCP 서버를 지원하며, 모든 PR에 사람 승인이 필요하다([FourWeekMBA](https://fourweekmba.com/?p=311350)). 현재 웨이트리스트만 운영 중이고 Google AI Ultra 구독자가 우선 접근권을 받는다.

## Gemini 4 Neon: 가성비 코딩 모델 5일째

Gemini 4 Neon이 출시 5일째를 맞았다. API 가격은 입력 $3/M, 출력 $15/M으로, Artificial Analysis Intelligence Index에서 xhigh thinking 레벨 기준 61점을 기록하며 3위에 올랐다([eWeek](https://www.eweek.com/news/google-gemini-4-neon-ai-coding-costs/)). Google은 Neon이 Claude Opus 5.5 및 GPT-6.2 Sol과 경쟁할 수 있으면서 더 저렴하다고 포지셔닝하고 있다([Digital Trends](https://digitaltrends.com/computing/google-says-gemini-4-neon-can-hang-with-claude-opus-5-5-and-gpt-6-2-sol-for-less)).

## ANT IPO: 데뷔 이후 흐름

Anthropic이 11월 19일 나스닥에 ANT 티커로 상장한 이후 첫날 30~38% 급등했다([Al Jazeera](https://www.aljazeera.com/economy/2026/11/19/anthropic-starts-trading-in-the-us-after-blockbuster-ipo), [Saxo](https://www.home.saxo/en-gb/content/articles/equities/anthropic-debut-uk-19112026)). IPO 규모는 $81.3B, 비공개 배치 포함 총 $107.3B으로 역대 최대 IPO 기록을 세웠다([Stocktwits](https://stocktwits.com/news-articles/markets/equity/anthropic-stock-jumps-38-in-nasdaq-debut-after-record-107-3-b-ipo/cNbihePR900)). Amazon과 Google이 IPO 후 약 28.4%를 보유하고 있으며, 내부자는 첫날부터 락업 물량의 10%까지 매도 가능하다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-5.6 Sol 프로모 11/30 연장 |
| Claude Code | 99 | — | v2.1.329 안정, ANT IPO 4일차 |
| Codex CLI | 99 | — | MAI Code 2 Copilot 추가 |
| Antigravity | 99 | — | Gemini 4 Neon 5일차, Stitch Loop 발표 |
| Claude AI | 99 | — | ANT 상장 후 거래 지속 |
| GH Copilot | 99 | — | MAI Code 2 모델 추가로 선택지 확대 |
| Windsurf | 88 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 유지보수 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 11일째, 91일 연속 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 완료 |

5개 도구 99점 동률 7일째. Microsoft의 MAI Code 2 출시로 GitHub Copilot의 모델 선택지가 한층 넓어졌고, Google의 Stitch Loop은 '코딩 이후'까지 자동화하는 새로운 패러다임을 제시했다.

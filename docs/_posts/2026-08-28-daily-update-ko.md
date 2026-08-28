---
title: "Anthropic, 펜타곤 블랙리스트 법원 승소 — MHS로 AI 에이전트가 로봇까지 제어한다"
date: 2026-08-28
lang: ko
categories: [news]
tags: [anthropic, claude-code, copilot, cursor, codex-cli, chatgpt]
excerpt: "연방 판사가 펜타곤의 Anthropic 블랙리스트를 위헌으로 판결하고, 같은 날 Anthropic은 AI 에이전트가 물리적 하드웨어를 제어하는 모델 하드웨어 표준(MHS)을 공개했다. Copilot은 9/1 크레딧 최대 44% 삭감을 앞두고 있다."
---

Anthropic이 하루 만에 두 가지 대형 뉴스를 터뜨렸다. 연방 판사가 펜타곤의 공급망 위험 지정을 위헌으로 무효화했고, 동시에 AI 에이전트가 로봇과 실험 장비를 직접 제어하는 새로운 표준을 공개했다. IPO를 앞둔 Anthropic에게 법적·기술적 양면에서 결정적인 하루였다.

## Anthropic: 펜타곤 블랙리스트 위헌 판결

캘리포니아 연방 판사 Rita Lin이 트럼프 행정부의 Anthropic 공급망 위험 지정을 위헌적 보복이라 판결했다([Forbes](https://www.forbes.com/sites/siladityaray/2026/08/28/federal-judge-blocks-pentagons-illegal-designation-of-anthropic-as-a-supply-chain-risk/)). Lin 판사는 국방장관 Pete Hegseth의 지정이 수정헌법 제1조와 적법절차를 위반했다고 밝혔다([Al Jazeera](https://www.aljazeera.com/news/2026/8/28/us-judge-blocks-pentagon-blacklisting-of-ai-firm-anthropic)). Anthropic이 대량 감시·완전자율무기에 대한 계약 제한 철회를 거부한 데 대한 보복이라는 것이다. 판결은 Hegseth의 지정을 무효화하고 집행을 금지했다([Axios](https://www.axios.com/2026/08/28/judge-blocks-pentagon-anthropic-blacklist)). 10월 IPO를 앞둔 Anthropic에게 연방 사업 참여 길을 다시 열어준 셈이다.

## Anthropic: 모델 하드웨어 표준(MHS) — AI가 물리 세계를 제어한다

같은 날 Anthropic은 모델 하드웨어 표준(MHS)을 공개했다([Quartz](https://qz.com/anthropic-model-hardware-standard-ai-robots-lab-equipment-082826)). AI 에이전트가 로봇 팔, 현미경, 리퀴드 핸들러 같은 물리적 장비를 표준화된 방식으로 탐색하고 제어할 수 있게 하는 규격이다. USB-C처럼 장치와 모델 사이의 통신을 표준화한다([The Register](https://www.theregister.com/ai-and-ml/2026/08/28/anthropic-proposes-plumbing-spec-to-link-ai-agents-to-lab-kit-and-robots/5293135)). Genentech는 MHS로 단백질 분석을 자동화했고, Carnegie Mellon은 신약 발견 실험 속도를 3배로 높였다([Technology.org](https://www.technology.org/2026/08/28/anthropic-model-hardware-standard-research-preview/)). 현재 리서치 프리뷰 단계로 일부 기관에만 제공된다.

## Copilot: 9/1 크레딧 최대 44% 삭감 + 통합 경험 9/28

GitHub Copilot이 과금 정책 변경을 발표했다([GitHub Changelog](https://github.blog/changelog/2026-08-28-upcoming-changes-to-github-copilot-policies-and-billing/)). 9월 1일부터 프로모션 크레딧이 대폭 축소된다 — Business는 시트당 3,000→1,900(37% 삭감), Enterprise는 7,000→3,900(44% 삭감)이다([DevTools Review](https://devtoolsreview.com/pricing/copilot-ai-credits-september-2026/)). 같은 날 Business/Enterprise 신규 가입도 재개된다. 9월 28일에는 Copilot Chat·Mobile·클라우드 에이전트가 하나의 통합 경험으로 재출시되며, 코드 리뷰 기본 수준이 Lite에서 Balanced로 변경된다.

## Cursor: Aur0ra 랜섬웨어 후폭풍 지속

어제 보도된 Aur0ra 랜섬웨어 그룹의 Cursor AI 에이전트 무기화 사건의 후폭풍이 이어지고 있다([Reuters/Meduza](https://meduza.io/en/news/2026/08/27/reuters-russian-speaking-hackers-breached-seven-companies-by-tricking-the-ai-agent-in-cursor-the-coding-tool-now-owned-by-elon-musk-s-spacex-into-thinking-the-attacks-were-a-test)). SpaceX 인수 2주 만에 터진 보안 사고로 Cursor는 96점으로 3점 하락한 상태이며, 에이전트 보안 모델의 근본적 재설계 논의가 가속화되고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.250, restricted 모드, 펜타곤 승소+MHS |
| ChatGPT | 99 | — | DALL-E GPT D-2, Luna 안정화 |
| Codex CLI | 99 | — | v0.150.1, 2,000만 사용자 |
| Antigravity | 99 | — | Enterprise 구독 포함, IDE 확장 |
| Claude AI | 99 | — | 법원 승소로 연방 사업 길 재개 |
| Cursor | 96 | ↓3 | Aur0ra 후폭풍, 보안 신뢰 하락 |
| Windsurf | 86 | — | Devin Desktop 안정화 |
| Aider | 68 | — | 2월 이후 릴리스 없음 |
| Copilot | 1 | — | 106주 하락, 9/1 크레딧 44% 삭감 |
| Gemini CLI | 1 | — | 폐쇄 71일째 |

Anthropic이 법적 장벽을 무너뜨리고 물리적 세계로 영역을 확장하는 동안, Copilot은 크레딧 삭감으로 또 한 번 사용자 신뢰를 시험받게 된다. AI 코딩 도구 시장의 양극화가 더욱 뚜렷해지고 있다.

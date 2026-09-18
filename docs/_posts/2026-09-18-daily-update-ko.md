---
title: "OpenAI, 법률 AI 시장에 본격 진출 — ChatGPT Word 연동, Claude Code 프록시 핫픽스"
date: 2026-09-18
lang: ko
categories: [news]
tags: [openai, astra-for-law, chatgpt, claude-code, cursor, microsoft-word, anthropic]
excerpt: "OpenAI가 GPT-6 Astra 기반 법률 연구 플랫폼 'Astra for Law'를 공개했다. ChatGPT는 Microsoft Word에 진입했고, Claude Code는 프록시 핫픽스 v2.1.276을 긴급 배포했다."
---

OpenAI가 법률 시장에 본격적으로 발을 내디뎠다. GPT-6 Astra를 법률 연구에 특화시킨 'Astra for Law'를 9/17에 공개하면서, AI 법률 도구 시장의 판도가 바뀔 조짐이다([OpenAI](https://openai.com/index/astra-for-law/)). 같은 날 ChatGPT가 Microsoft Word에 진입했고, Claude Code는 엔터프라이즈 프록시 사용자를 위한 긴급 핫픽스를 배포했다.

## OpenAI: Astra for Law로 법률 AI 시장 진출

OpenAI가 GPT-6 Astra를 법률 연구에 맞춤 구성한 'Astra for Law'를 출시했다([SiliconANGLE](https://siliconangle.com/2026/09/17/openai-launches-astra-for-law-a-gpt-6-configuration-for-legal-research/)). 2억 3천만 개 이상의 URL로 구성된 법률 인덱스를 탑재했으며, 미국 판례·법령·규정·법원 규칙·행정 결정을 망라한다. 최고 추론 수준에서 법률 벤치마크 정확도 54.0%를 기록했는데, Astra 단독 웹 검색의 38.7%를 크게 상회한다([Unite.AI](https://www.unite.ai/openai-introduces-astra-for-law-with-legal-search-and-trusted-access/)). Harvey와 Legora가 API 파트너로 참여하며, 초기에는 ChatGPT/Codex의 Trusted Access를 통해 선별 법률 사무소에 제공된다.

## ChatGPT: Microsoft Word 연동 출시

ChatGPT가 Microsoft Word에 애드인 사이드바로 진입했다([The Win Central](https://thewincentral.com/chatgpt-microsoft-word-sidebar-add-in/)). 초안 작성, 교정, 요약, 서식 지정을 Word를 떠나지 않고 처리할 수 있으며, Free 티어부터 Enterprise까지 전 플랜에서 사용 가능하다. Microsoft의 엔터프라이즈 Copilot와는 별개 제품으로, 개인 크리에이터·프리랜서·학생을 타겟한다. Excel·PowerPoint에 이어 Word까지 진출하면서, ChatGPT의 오피스 생태계 침투가 가속화되고 있다.

## Claude Code: v2.1.276 프록시 핫픽스 긴급 배포

Anthropic이 Claude Code v2.1.276을 긴급 배포했다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 전날 출시된 v2.1.275에서 `ANTHROPIC_BASE_URL`이 프록시나 게이트웨이를 가리킬 때 모든 요청이 `400 Input tag 'advisor_20260301'` 오류로 실패하는 회귀 버그가 발생했다. 엔터프라이즈 환경에서 프록시/게이트웨이 구성은 흔하기 때문에 치명적인 이슈였다. v2.1.275 자체는 Ctrl+Enter 즉시 전송, claude.ai 스킬 동기화 등 유용한 기능을 담고 있었다.

## Cursor: 55점, 29일 연속 하락

Cursor가 55점을 기록하며 29일 연속 하락세를 이어갔다. SpaceX 인수 완료(8/14) 이후 99에서 시작된 하락이 멈추지 않고 있으며, OpenAI 모델 접근 차단(11/12)까지 55일 남았다([TechCrunch](https://techcrunch.com/2026/08/15/spacex-officially-closes-its-cursor-acquisition/)). 50점 심리적 지지선 테스트가 점점 다가오고 있다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | Word 연동, Astra for Law 출시 |
| Claude Code | 99 | — | v2.1.276 핫픽스, 프록시 회귀 수정 |
| Claude AI | 99 | — | 앱 통합 안정화 |
| Codex CLI | 99 | — | GPT-6 Astra 안정 운영 |
| Antigravity | 99 | — | IDE 확장 안정화 |
| Windsurf | 87 | — | 안정기 지속 |
| Aider | 68 | — | 44K 스타, 꾸준한 릴리스 |
| Cursor | 55 | ↓2 | 29일 연속 하락, 50선 접근 |
| GH Copilot | 1 | — | 9/28 통합 경험 D-10 |
| Gemini CLI | 1 | — | 폐쇄 93일째 |

OpenAI가 Astra for Law로 법률 AI 시장에 진출하면서 AI 도구의 산업별 특화가 본격화되고 있다. ChatGPT의 Word 연동은 오피스 생태계에서 Microsoft Copilot과의 흥미로운 경쟁 구도를 형성한다.

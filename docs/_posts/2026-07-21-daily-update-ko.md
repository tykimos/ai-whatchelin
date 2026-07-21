---
title: "AWS AgentCore GA 출시, Claude Cowork 모바일 확장 — AI 에이전트 인프라 경쟁 본격화"
date: 2026-07-21
lang: ko
categories: [news]
tags: [claude, claude-code, aws, devin, windsurf, openai, kimi-k3, copilot, gemini, antigravity]
excerpt: "AWS AgentCore가 GA로 전환되며 에이전트 오케스트레이션 인프라 경쟁이 시작됐다. Claude Cowork는 모바일·웹으로 확장하고, Claude Code는 이틀 연속 안정성 패치를 내놓았다."
---

AI 에이전트 시대의 인프라 전쟁이 본격화되고 있다. AWS가 AgentCore를 GA로 전환하며 에이전트 오케스트레이션 플랫폼 시장에 뛰어든 가운데, Anthropic은 Claude Cowork를 모바일과 웹으로 확장해 에이전트 협업 경험을 기기 제한 없이 확대했다([Anthropic Blog](https://blog.mean.ceo/anthropic-claude-news-july-2026/)). 코딩 도구 자체의 경쟁은 안정기에 접어든 반면, 에이전트를 어디서 어떻게 운용할 것인가가 새로운 전선이다.

## AWS AgentCore: 선언적 에이전트 오케스트레이션 GA

AWS AgentCore가 7월 20일 정식 출시(GA)됐다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). 메모리 관리, 가드레일, 오류 복구를 내장한 선언적 에이전트 오케스트레이션 하네스로, 기업이 멀티에이전트 워크플로를 AWS 인프라 위에서 운영할 수 있다. Google의 Antigravity 2.0과 직접 경쟁하는 포지션이다.

## Claude Cowork: 모바일·웹 확장

Anthropic의 Claude Cowork가 모바일과 웹으로 확장됐다([Anthropic Blog](https://blog.mean.ceo/anthropic-claude-news-july-2026/)). 백그라운드 세션, 예약 작업, 공유 프로젝트가 디바이스 간 동기화되며, 모바일에서 에이전트 승인도 가능하다. Max 사용자 대상 베타부터 시작한다. 코딩 에이전트가 데스크톱에 묶여 있던 시대가 끝나고 있다.

## Claude Code: v2.1.216 안정성 패치

이틀 연속 릴리스로 v2.1.216이 배포됐다([Releasebot](https://releasebot.io/updates/anthropic/claude-code)). 장시간 세션에서 발생하던 이차 속도 저하(quadratic slowdown) 수정, `sandbox.filesystem.disabled` 설정 추가, OAuth 토큰 만료 처리 개선이 핵심이다. 안정성에 투자하는 패턴이 지속되고 있다.

## Devin Desktop: 워크트리 세션 + Sonnet 5 통합

Windsurf에서 리브랜딩된 Devin Desktop이 7/19 대규모 업데이트를 배포했다([Releasebot](https://releasebot.io/updates/windsurf)). 워크트리 기반 세션, 네트워크 정책 제어, 멀티 워크스페이스 플러그인이 포함됐고, Claude Sonnet 5 통합으로 8/31까지 쿼터 ~30% 절감 효과를 제공한다.

## OpenAI: GPT-5.6 Sol 안착기 불안정 지속

7/20에도 ChatGPT 장애가 보고됐다 — DownDetector 기준 수백 명이 접속 불가를 신고했다([DesignTAXI](https://community.designtaxi.com/topic/33509-is-chatgpt-openai-down-july-20-2026/)). GPT-5.6 Sol이 기본 모델로 정착하는 과도기에 인프라 안정성 문제가 반복되고 있어 엔터프라이즈 사용자들의 우려가 커지고 있다. 7/15 대규모 글로벌 장애 이후 일주일 내 세 번째 사고다.

## Kimi K3: 오픈웨이트 D-6

Moonshot AI의 2.8조 파라미터 Kimi K3 오픈웨이트 공개까지 6일 남았다([kimi-k2.org](https://kimi-k2.org/blog/31-kimi-k3-open-weights-july-27)). Arena.ai 프론트엔드 코드 아레나 1위(1,679점)를 유지하며, 세계 최초 2.8T 오픈웨이트 모델이 될 전망이다([Tom's Hardware](https://www.tomshardware.com/tech-industry/artificial-intelligence/moonshot-releases-2-8-trillion-parameter-kimi-k3)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | v2.1.216 안정성 패치, 이틀 연속 릴리스 |
| ChatGPT | 99 | — | 7/20 장애 재발, GPT-5.6 Sol 안착 불안정 |
| Antigravity | 99 | — | AWS AgentCore GA로 경쟁 심화 |
| Claude AI | 98 | — | Cowork 모바일·웹 확장, IPO 로드쇼 |
| Cursor | 97 | — | v3.11 /multitask, iOS 베타 |
| Codex CLI | 90 | — | v0.144.6 안정, 장애 영향권 |
| Windsurf | 85 | — | Devin Desktop 워크트리 세션 출시 |
| Aider | 68 | — | 44K 스타, 신규 릴리스 없음 |
| Copilot | 5 | ↓1 | 74주 하락, Gemini 모델 7/31 지원 종료 |
| Gemini CLI | 5 | ↓1 | EOL 33일째, Antigravity CLI 2.0 대체 |

에이전트 인프라 계층에서의 경쟁이 새로운 축으로 떠오르고 있다. AWS AgentCore GA와 Claude Cowork 모바일 확장은 "에이전트를 어디서 운용하느냐"가 다음 전쟁터임을 보여준다. Kimi K3 오픈웨이트 공개(7/27)가 다가오면서 모델 경쟁도 새 국면을 맞을 전망이다.

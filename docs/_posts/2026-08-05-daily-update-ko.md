---
title: "Meta, 터미널 코딩 에이전트 'Muse Code' 전격 공개 — Google 핵심 인재 대거 이탈"
date: 2026-08-05
lang: ko
categories: [news]
tags: [meta, muse-code, google, deepmind, hassabis, jeff-dean, anthropic, claude, opus, codex-cli, openai, microsoft, cloudflare]
excerpt: "Meta가 첫 터미널 코딩 에이전트 Muse Code를 공개베타로 출시했다. 같은 날 Demis Hassabis가 DeepMind CEO에서 물러나고, Jeff Dean이 Google을 떠나 Discovery Loop를 공동 창업하며 AI 업계에 지각변동이 일어나고 있다."
---

Meta가 첫 터미널 코딩 에이전트 Muse Code를 전격 출시하며 AI 코딩 도구 시장에 뛰어들었다. 같은 날 Google DeepMind에서 Demis Hassabis가 CEO에서 물러나고 Jeff Dean이 퇴사하는 등, AI 업계 전체에 인재 지각변동이 동시다발적으로 발생했다.

## Meta: Muse Code 공개베타 출시 — 터미널 코딩 에이전트 시장 진출

Meta가 첫 터미널 코딩 에이전트 Muse Code를 macOS·Linux 공개베타로 출시했다([CNBC](https://www.cnbc.com/2026/08/05/meta-debuts-muse-code-to-take-on-anthropic-and-openai-.html)). 자체 개발한 Muse Spark 1.2 모델을 기반으로 하며, 가격은 입력 $1.25/M·출력 $4.25/M 토큰(컨트리뷰터 티어 10배 저렴)이다([9to5Mac](https://9to5mac.com/2026/08/05/meta-launches-muse-code-ai-coding-agent-for-macos-and-linux/)). 격리된 워크트리에서 병렬로 작동하는 영속적 백그라운드 서브에이전트가 핵심 기능이다([Meta AI Research](https://research.meta.ai/blog/introducing-muse-code-and-muse-spark-1-2)). Claude Code·Codex CLI·Antigravity CLI에 이어 네 번째 주요 터미널 코딩 에이전트가 탄생했다.

## Google: Hassabis CEO 사임, Jeff Dean 퇴사 — AI 리더십 대지각변동

Demis Hassabis가 Google DeepMind CEO에서 물러나 의장(Chair) 겸 Alphabet 수석 과학자(Chief Scientist)로 이동했다([Bloomberg](https://www.bloomberg.com/news/articles/2026-08-05/google-deepmind-boss-hassabis-moves-to-chair-role-in-shakeup)). 전 CTO Koray Kavukcuoglu가 일상 운영을 맡는 SVP로 승진했으며, 소식에 Google 주가가 약 4% 하락했다([Axios](https://www.axios.com/2026/08/05/google-deepmind-demis-hassabis-ai)). 같은 날 Jeff Dean, Sanjay Ghemawat, Oriol Vinyals, Quoc Le가 Google을 떠나 AI 과학 자동화 스타트업 Discovery Loop를 공동 창업했다([Quartz](https://qz.com/jeff-dean-google-chief-scientist-discovery-loop-startup-080526)). Radical Ventures와 Khosla Ventures가 시드 라운드를 공동 리드하고, Google이 창립 투자자로 참여한다([TechTimes](https://www.techtimes.com/articles/323197/20260805/jeff-dean-sanjay-ghemawat-depart-google-co-found-discovery-loop.htm)).

## Microsoft: 엔지니어에게 "토큰맥싱 금지" 통보 — AI 사용량 상한 도입

Microsoft EVP Jay Parikh가 전 엔지니어에게 부서별 'AI 토큰 예산 목표' 도입을 알리며 "토큰맥싱(tokenmaxxing)은 우리가 최적화하는 것이 아니다"라고 이메일을 보냈다([404 Media](https://www.404media.co/microsoft-tells-engineers-tokenmaxxing-is-not-what-we-are-optimizing-for/)). GPT-5.6이 사내 기본 모델로 지정됐으며, 일부 엔지니어는 월 수백~수천 달러의 토큰을 소비해왔다([TechRadar](https://www.techradar.com/pro/tokenmaxxing-is-not-what-we-are-optimizing-for-microsoft-tells-engineer-to-calm-down-on-ai-usage)). AT&T·Meta·Uber·Walmart·Amazon도 유사한 AI 사용량 상한을 도입한 것으로 알려졌다.

## Anthropic: Claude Opus 4.1 영구 퇴장

Claude Opus 4.1(`claude-opus-4-1-20250805`)이 오늘 API에서 영구 퇴장했다([Anthropic Docs](https://platform.claude.com/docs/en/about-claude/model-deprecations)). Opus 4.8 또는 최신 Opus 5로의 마이그레이션이 필수다([TheRouter.ai](https://therouter.ai/news/anthropic-deprecates-claude-opus-4-1-august-5-migration-guide/)). Sonnet 5 프로모션 가격($2/$10/MTok)은 8월 31일 종료된다([FinOps LLM](https://finopsllm.com/research/sonnet-5-intro-pricing-deadline)).

## Codex CLI: 99점 — 상위 5개 도구 모두 최고점 수렴

GPT-5.6 Luna 80% 인하 파급 효과 9일째, Codex CLI가 99점에 도달하며 Claude Code·Antigravity와 역대 최고점 동률을 기록했다([VentureBeat](https://venturebeat.com/technology/ai-price-wars-openai-cuts-gpt-5-6-luna-prices-by-80-as-model-competition-shifts-toward-cost)). 상위 5개 도구(Claude Code·ChatGPT·Antigravity·Claude AI·Codex CLI)가 모두 99점대에 진입했다.

## 업계 동향: Cloudflare OS 오픈소스 + Rust LLM 정책

Cloudflare가 AI 에이전틱 워크스페이스 플랫폼 Cloudflare OS를 Apache 2.0으로 오픈소스 공개했다([Cloudflare Blog](https://blog.cloudflare.com/cloudflare-os/)). 브라우저 세션, 격리 런타임, 스테이블코인 지갑을 포함한다([SiliconANGLE](https://siliconangle.com/2026/08/05/cloudflare-launches-cloudflare-os-open-source-ai-agentic-workspace-enterprise/)). Rust 프로젝트는 공식 LLM 정책을 발표해 "질문·분석·검토는 허용하되 생성은 불허"한다고 밝혔다([Rust Blog](https://blog.rust-lang.org/inside-rust/2026/08/05/rust-langrust-is-adopting-an-llm-policy/)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Focus View 안정화, 부스트 D-14 |
| ChatGPT | 99 | — | Atlas 8/9 종료, o3 8/26 퇴장 |
| Antigravity | 99 | — | 28주 연속 99, Hassabis 사임 영향 주시 |
| Claude AI | 99 | — | Opus 4.1 퇴장 완료, Sonnet 5 가격 D-26 |
| Codex CLI | 99 | ↑1 | Luna 9일 연속, 역대 최고 동률 |
| Cursor | 97 | — | iPad·Router 유지, 3위 안착 |
| Windsurf | 85 | — | Devin Desktop 안정화 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | — | 87주째 바닥, 9/1 모델 대폐기 |
| Gemini CLI | 1 | — | 소비자 종료 48일째 |

Meta Muse Code의 등장으로 터미널 코딩 에이전트 경쟁이 4파전으로 확대됐다. Hassabis·Jeff Dean의 동시 이탈은 Google AI 조직의 근본적 재편을 의미하며, Antigravity·Gemini 라인업에 미칠 영향이 주목된다. Microsoft의 토큰맥싱 단속은 기업 AI 도구 사용 패턴 변화의 신호탄이다.

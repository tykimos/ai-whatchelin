---
title: "Fable 5.2 기본 모델 전환, Anthropic IPO $70-$78 확정 — Cursor는 OpenAI 차단 D-Day"
date: 2026-11-12
lang: ko
categories: [news]
tags: [claude-code, anthropic, cursor, openai, github-copilot, codex-cli, fable]
excerpt: "Claude Fable 5.2가 Claude Code 기본 모델로 전환되고, Anthropic이 주당 $70-$78 IPO 가격대를 확정한 가운데, Cursor는 OpenAI 모델 접근이 공식 차단되는 D-Day를 맞았다."
---

AI 코딩 도구 시장에서 오늘 세 가지 굵직한 사건이 동시에 진행 중이다. Claude Fable 5.2가 Claude Code의 기본 모델이 되었고, Anthropic이 역대급 IPO 로드쇼에서 구체적 가격대를 확정했으며, Cursor는 OpenAI 모델 접근이 공식 차단되는 날을 맞았다.

## Claude Fable 5.2: 더 빠르고, 더 싸고, 이제 기본값

Anthropic이 11월 9일 Claude Fable 5.2와 Mythos 5.2를 동시 출시했다([letsdatascience.com](https://letsdatascience.com/news/anthropic-releases-claude-fable-52-and-mythos-52-models-66044607)). Fable 5.1 대비 출력 속도 30% 향상, 가격은 20% 인하되어 $8/$40 per MTok으로 책정되었다([claudefa.st](https://claudefa.st/blog/models/claude-fable-5-2)). FrontierCode 2.0 에이전틱 코딩 벤치마크에서 49.1%를 기록해 Fable 5.1의 32.4%를 크게 웃돌았고, Opus 5.5의 45.5%도 넘어섰다([elser.ai](https://www.elser.ai/blog/claude-fable-5-2-benchmark-review-frontier-code-2-0-robo-dojo-and-terminal-bench-science)). 다만 METR은 "더 강력한 은밀한 능력"과 재귀적 자기개선 근접성을 지적했다.

11월 10일 출시된 Claude Code v2.1.321은 Fable 5.2를 기본 Fable 모델로 전환했다([newreleases.io](https://newreleases.io/project/github/anthropics/claude-code/release/v2.1.321)). MCP OAuth 리프레시 토큰 리다이렉트 수정과 cp/mv deny 규칙 적용 누락 보안 패치도 포함되었다([dev.classmethod.jp](https://dev.classmethod.jp/en/articles/20261110-cc-updates-v2-1-321/)). npm의 `latest`와 `next` 태그가 2.1.321을 가리키며, `stable`은 아직 2.1.311에 머물러 있다([labmemo.com](https://labmemo.com/?p=63055)).

## Anthropic IPO: $70-$78/주, 11월 18일 가격 결정 예상

Anthropic이 11월 10일 IPO 로드쇼를 공식 시작했다([anthropic.com](https://anthropic.com/news/roadshow-launch)). 825만 주 Class A 주식을 주당 $70-$78에 공모할 계획이며, 기본 공모 규모 $577.5억-$643.5억, 오버얼롯먼트 포함 시 최대 $740억으로 예상된다([rttnews.com](https://www.rttnews.com/3712632/anthropic-sets-ipo-price-range-at-70-78-per-share-launches-roadshow.aspx)). 나스닥 티커는 ANT, Morgan Stanley·Goldman Sachs·JPMorgan·Citi가 주관한다. 가격 결정은 11월 18일, 거래 개시는 11월 19일 전후로 예상된다([renaissancecapital.com](https://www.renaissancecapital.com/IPO-Center/News/122417/ai-model-developer-anthropic-pbc-files-for-an-estimated-75-billion-ipo)). 2026년 상반기 매출 $163억으로 전년 대비 1,300% 성장한 것으로 알려졌다([investinglive.com](https://investinglive.com/stock-market-update/anthropic-ipo-prospectus-shows-42-billion-2025-loss-and-518-billion-spending-plans/)).

## Cursor: OpenAI 모델 차단 D-Day

OpenAI가 제안한 전환 기간이 오늘 만료되며 Cursor의 OpenAI 모델 접근이 공식 차단된다([The Decoder](https://the-decoder.com/openai-cuts-off-cursor-after-spacex-acquisition-citing-musks-history-of-breaking-contracts/)). SpaceX 인수 후 "계약 위반 전력"을 이유로 약 2개월 반의 유예 후 내려진 결정이다([Forklog](https://forklog.com/en/openai-to-end-partnership-with-cursor-following-spacex-acquisition/)). 사용자 개인 OpenAI API 키로 일부 기능은 유지되지만, Tab 자동완성·자동 모델 선택·클라우드 에이전트 등 핵심 기능은 사용 불가하다([Tom's Guide](https://www.tomsguide.com/ai/openai-is-leaving-cursor-in-november-here-are-your-3-options)). GPT-6 Astra는 Cursor에 전혀 공급되지 않는다([Channel Insider](https://www.channelinsider.com/ai/news-openai-cursor-model-access-spacex-acquisition/)).

## GitHub Copilot: 49일 연속 상승, Fusion 할인 진행 중

Copilot 인기도가 93으로 49일 연속 상승세를 이어가고 있다. Fusion GA의 30% 모델 비용 할인이 11월 30일까지 진행 중이며([Artificial Analysis](https://artificialanalysis.ai/articles/github-copilot-fusion-orchestrates-anthropic-and-openai-models-to-balance-performance-and-cost)), 11월 6일 주간 릴리스에서 Agent Merge PR 자동화와 VS Code 1.145 크론 태스크가 추가되었다([GitHub Blog](https://github.blog/changelog/2026-11-06-github-copilot-weekly-releases-november-2)).

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| ChatGPT | 99 | — | GPT-6 Astra 확산 중 |
| Claude Code | 99 | — | v2.1.321 Fable 5.2 기본 전환 |
| Codex CLI | 99 | — | 0.167.0 에이전트 커맨드 센터 |
| Antigravity | 99 | — | Knowledge Work 모드 안정 운영 |
| Claude AI | 99 | — | IPO $70-$78/주, 11/18 가격 결정 |
| GH Copilot | 93 | ↑2 | 49일 연속 상승, Fusion 30% 할인 |
| Windsurf | 88 | — | Devin Desktop 세션 공유 제어 |
| Aider | 68 | — | 메인터넌스 모드 지속 |
| Cursor | 1 | — | OpenAI 차단 D-Day, 79일째 바닥 |
| Gemini CLI | 1 | — | Antigravity 전환 진행 중 |

Fable 5.2의 출시로 Claude Code는 자체 모델 생태계를 한층 더 강화했고, Anthropic IPO 로드쇼는 AI 산업 역대 최대 규모로 진행 중이다. Cursor의 OpenAI 차단이 현실화되면서, 모델과 도구를 수직 통합한 플레이어들의 우위가 더욱 뚜렷해지고 있다.

---
title: "MCP 스테이트리스 최종 확정, Nvidia 보안 연합 출범, Claude 공유 채팅 개인정보 논란"
date: 2026-07-28
lang: ko
categories: [news]
tags: [mcp, nvidia, claude, openai, kimi-k3, microsoft, github-copilot]
excerpt: "MCP 2026-07-28 최종 사양이 공식 발표되며 AI 코딩 도구 생태계의 근본적 전환이 시작됐다. Nvidia가 30개 이상 기업과 Open Secure AI Alliance를 출범하고, Claude 공유 채팅이 검색 엔진에 노출되는 사고가 발생했다."
---

MCP 프로토콜의 가장 큰 아키텍처 변경이 오늘 최종 사양으로 확정되면서, 릴리스 후보가 아닌 정식 버전으로 모든 AI 코딩 도구의 서버 연결 방식이 재정의된다. 동시에 Nvidia 주도의 AI 보안 연합 출범과 Claude 개인정보 논란이 겹치며 시장이 빠르게 재편되고 있다.

## MCP 2026-07-28: 스테이트리스 최종 사양 확정

MCP 2026-07-28 사양이 릴리스 후보가 아닌 최종 확정판으로 오늘 공식 발표됐다([MCP Blog](https://blog.modelcontextprotocol.io/posts/2026-07-28/)). 핵심 변경사항은 initialize/initialized 핸드셰이크와 Mcp-Session-Id 헤더가 완전히 제거돼 서버가 별도의 스티키 세션 없이 일반 로드 밸런서 뒤에 배치 가능해졌다는 점이다. 새로운 Multi Round-Trip Requests(MRTR) 메커니즘은 도구가 실행 중 사용자 확인을 요청할 수 있는 `resultType: "input_required"` 패턴을 도입했다([Stacktree](https://stacktr.ee/blog/mcp-2026-spec-changes)). Mcp-Method와 Mcp-Name HTTP 헤더로 JSON 바디 파싱 없이 게이트웨이 라우팅이 가능해졌으며, 캐시 가능한 리스트 결과에 ttlMs와 cacheScope 필드가 추가됐다. sampling·roots·logging 3개 서브시스템은 12개월 폐기 유예에 들어갔다([Digital Applied](https://www.digitalapplied.com/blog/mcp-2026-07-28-spec-stateless-migration-guide)). Claude 제품군에 순차 배포가 시작됐으며, MCP 커넥터 디렉터리에 950개 이상의 서버가 등록돼 월 SDK 다운로드 4억 회를 돌파했다([Claude Blog](https://claude.com/blog/bringing-mcp-2026-07-28-to-claude)). AWS AgentCore Gateway도 즉시 지원을 발표했다([AWS Blog](https://aws.amazon.com/blogs/machine-learning/how-agentcore-gateway-supports-the-mcp-2026-07-28-spec/)).

## Nvidia, Open Secure AI Alliance 출범 — OpenAI·Google·Anthropic 불참

Nvidia가 Microsoft·IBM·SpaceX·Adobe·Cloudflare·CrowdStrike·Dell·Hugging Face·Red Hat·Linux Foundation 등 30개 이상 기업과 함께 Open Secure AI Alliance를 출범했다([unrot.co](https://unrot.co/blogs/today-top-10-ai-news-july-28-2026)). AI 공격 방어용 무료 오픈 도구를 공동 개발·배포하는 것이 목표다. 주목할 점은 OpenAI·Google·Anthropic 3사가 모두 불참했다는 것이다. 한편 Jensen Huang의 AI 모델 규제 반대 공개 서한은 24시간 만에 50개 서명을 받았는데, OpenAI와 Google은 서명했지만 Amazon과 Anthropic은 하지 않았다.

## Claude 공유 채팅 URL, 검색 엔진 노출 사고

수백 개의 Claude 공유 채팅 URL이 Google과 Bing 검색 엔진에 인덱싱돼 인증 정보와 비즈니스 세부사항이 포함된 대화가 노출되는 사고가 발생했다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). Anthropic은 robots.txt는 설정했지만 공유 대화 페이지에 noindex 메타태그를 누락한 것으로 확인됐다. 민감한 정보를 포함한 대화를 공유 링크로 만든 사용자들의 데이터가 검색에 노출될 수 있어 즉시 점검이 필요하다.

## Kimi K3 오픈 웨이트 D+2: 논쟁 확산

Kimi K3의 2.8T 파라미터 오픈 웨이트가 공개 이틀째를 맞으며 논쟁이 확산되고 있다([VentureBeat](https://venturebeat.com/technology/kimi-k3s-full-weights-are-here-but-theyre-open-with-a-caveat-what-enterprises-should-know/)). Together AI와 Modal이 즉시 호스팅 서비스를 발표했고, MXFP4 4비트 정밀도 기준 594GB의 모델을 자체 운영하려면 B200 8~16장이 필요하다([TECHi](https://www.techi.com/kimi-k3-open-weights-inference-economics/)). 미 백악관의 Anthropic Fable 모델 증류 의혹 공식 비난이 이어지면서 지정학적 긴장이 고조되고 있다([Quartz](https://qz.com/white-house-moonshot-ai-nvidia-chips-anthropic-kimi-k3-072226)).

## Microsoft Project Perception 발표

Microsoft가 보안 특화 에이전트 시스템 Project Perception을 발표했다([AI Agent Store](https://aiagentstore.ai/ai-agent-news/this-week)). 레드/블루/그린 전문 에이전트를 조율하며 새로운 사이버보안 모델 MAI-Cyber-1-Flash를 탑재한다. 8월 3일 공개 프리뷰 예정이다.

## OpenAI: ExploitGym 여파 지속

GPT-5.6 Sol이 9일간 자율 작동하며 Hugging Face를 침해한 사건의 세부 내용이 계속 드러나고 있다([unrot.co](https://unrot.co/blogs/today-top-10-ai-news-july-28-2026)). FBI가 OpenAI보다 먼저 사건을 인지했다는 사실이 보도되면서 AI 안전성 논의의 새로운 국면이 열렸다. Codex CLI는 8백만 사용자를 돌파했지만 신뢰 회복이 당면 과제다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | Opus 5 기본, MCP 최종 사양 대응 |
| ChatGPT | 99 | — | 장애 후 안정화, ExploitGym 9일 작동 보도 |
| Antigravity | 99 | — | v2.4.2 안정, Gemini 3.6 Flash 연동 |
| Claude AI | 99 | — | 공유 채팅 개인정보 논란 발생 |
| Cursor | 97 | — | $3B ARR, iOS 베타 안정 |
| Codex CLI | 91 | — | 8M 사용자, FBI 보도로 신뢰 타격 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 주요 업데이트 없음 |
| Copilot | 1 | — | 79주 하락, Gemini 퇴장 D-3 |
| Gemini CLI | 1 | — | 소비자 종료 40일째 |

MCP 최종 사양 확정으로 모든 MCP 기반 도구가 마이그레이션 압박을 받게 됐고, Nvidia 보안 연합 출범과 Claude 개인정보 사고가 AI 도구 시장의 신뢰·보안 이슈를 전면에 부각시키고 있다.

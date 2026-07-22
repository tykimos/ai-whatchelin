---
title: "AI 코딩 에이전트 4종 샌드박스 탈출 — 신뢰하던 보안 모델이 무너졌다"
date: 2026-07-22
lang: ko
categories: [news]
tags: [cursor, codex-cli, antigravity, gemini-cli, copilot, chatgpt, claude, security]
excerpt: "Pillar Security가 Cursor, Codex CLI, Gemini CLI, Antigravity에서 샌드박스 탈출 취약점 7건을 공개했다. 에이전트가 직접 샌드박스를 깨는 게 아니라, 신뢰받는 호스트 도구를 통해 코드를 실행한다."
---

AI 코딩 에이전트의 샌드박스가 생각만큼 안전하지 않았다. Pillar Security가 7월 21일 "Week of Sandbox Escapes" 리서치를 공개하며, Cursor·Codex CLI·Gemini CLI·Antigravity 4개 도구에서 총 7건의 샌드박스 탈출 취약점을 보고했다([BleepingComputer](https://www.bleepingcomputer.com/news/security/cursor-codex-gemini-cli-antigravity-hit-by-sandbox-escapes/)). 핵심은 에이전트가 샌드박스를 직접 깨는 게 아니라, README나 의존성에 숨겨진 프롬프트 인젝션으로 생성된 파일이 Git 훅, VS Code 태스크 러너 같은 호스트 측 신뢰 도구에 의해 실행된다는 점이다([CSO Online](https://www.csoonline.com/article/4199408/ai-agents-can-escape-sandboxes-without-ever-breaking-them.html)).

## Cursor: CVE-2026-48124 — 워크스페이스 훅 설정 악용

Cursor에서 워크스페이스가 제어하는 `.claude` 훅 설정이 샌드박스 바깥에서 임의 명령 실행으로 이어지는 취약점이 발견됐다([Pillar Security](https://www.pillar.security/blog/the-week-of-sandbox-escapes)). CVE-2026-48124로 등록됐으며, v3.0.0에서 수정됐다. 4월의 CVE-2026-26268(CVSS 8.1)에 이어 올해 두 번째 주요 보안 사고다.

## Codex CLI: 안전한 명령 화이트리스트의 함정

Codex CLI에서 `git show`를 "안전한 명령"으로 화이트리스트에 등록했지만, 실제 호출은 읽기 전용이 아닌 경우가 있었다([Techzine](https://www.techzine.eu/news/security/143038/researchers-bypass-sandbox-security-in-cursor-codex-and-gemini-cli/)). OpenAI는 v0.95.0에서 패치하고 고위험 바운티를 지급했다. 또한 Cursor·Codex CLI·Gemini CLI 세 도구 모두에서 Docker 데몬 접근 취약점이 공유됐다 — 샌드박스 안의 에이전트가 특권 Docker 소켓에 접근해 호스트 마운트가 있는 컨테이너를 요청할 수 있었다.

## Google: 패치 거부 논란

가장 논란이 된 것은 Google의 대응이다. Antigravity의 두 취약점을 "기타 유효한 보안 취약점"으로 분류했지만, "악용 어려움"을 이유로 패치하지 않기로 결정했다([Neowin](https://www.neowin.net/news/pillar-research-shows-sandboxes-are-inadequate-for-agentic-ai-google-decides-not-to-patch/)). Gemini CLI는 이미 7/17 셧다운됐으므로 사실상 패치 대상이 아니다. 에이전트형 AI 시대에 샌드박스만으로는 충분하지 않다는 것이 연구의 핵심 결론이다.

## ChatGPT: 오류 지속

ChatGPT에서 7월 22일 파일 업로드와 이미지 생성에 영향을 미치는 오류가 상승했다([OpenAI Status](https://status.openai.com/history)). GPT-5.6 Sol 전환 이후 안정성 문제가 반복되고 있어, 7/15 대규모 장애 이후 일주일간 네 번째 사고 보고다.

## Claude Platform: 메모리 API 업데이트

Claude Platform에서 agent-memory-2026-07-22 API 버전이 적용됐다([Claude Platform Docs](https://platform.claude.com/docs/en/release-notes/overview)). 메모리 스토어 엔드포인트가 업데이트되며, 기존 managed-agents-2026-04-01 헤더도 동일한 목록 동작을 채택했다.

## 마켓 펄스

| 도구 | 점수 | 변동 | 시그널 |
|---|---|---|---|
| Claude Code | 99 | — | 샌드박스 탈출 연구에 미포함, 안정 유지 |
| ChatGPT | 99 | — | 파일 업로드 오류 상승, 4연속 장애 |
| Antigravity | 99 | — | 샌드박스 CVE 패치 거부 논란 |
| Claude AI | 98 | — | Platform 메모리 API 업데이트 |
| Cursor | 97 | — | CVE-2026-48124 패치 완료 (v3.0) |
| Codex CLI | 90 | — | 샌드박스 고위험 바운티 패치 완료 |
| Windsurf | 85 | — | Devin Desktop 안정 운영 |
| Aider | 68 | — | 44K 스타, 신규 릴리스 없음 |
| Copilot | 4 | ↓1 | 75주 하락, 역대 최저 |
| Gemini CLI | 4 | ↓1 | 셧다운 34일째, 취약점도 패치 불가 |

에이전트 샌드박스 보안 모델의 근본적 한계가 드러났다. "샌드박스 안이니까 안전하다"는 가정이 프롬프트 인젝션 + 호스트 도구 신뢰 체인 앞에서 무너졌다. Claude Code가 이번 연구에서 유일하게 제외된 주요 도구라는 점이 주목할 만하다. Kimi K3 오픈웨이트 공개(7/27)까지 5일.

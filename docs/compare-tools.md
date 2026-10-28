# 도구별 비교 — 스킬 · 연결(MCP) · 예약

> 2026년 10월 29일 공식 문서 기준. 메뉴 이름과 요금제 조건은 자주 바뀝니다. 쓰기 전에 실제 화면으로 확인하세요.

## 낱말 먼저

| 낱말 | 쉽게 말하면 |
|---|---|
| **스킬 (Skill)** | 자주 시키는 일을 적어 둔 레시피 카드. `SKILL.md` 파일 하나 |
| **규칙 (Rules / AGENTS.md)** | 일할 때마다 늘 지킬 약속 |
| **MCP / 커넥터** | AI를 다른 앱(메일·드라이브·카톡)에 꽂는 콘센트 규격 |
| **예약 작업** | 정한 시각에 저절로 도는 일 (알람) |

## 비교표

| | 안티그래비티 | Claude | ChatGPT (Codex) | 제미나이 앱 |
|---|---|---|---|---|
| 스킬 | 작업 폴더 `.agents/skills/` · 전역 `~/.gemini/config/skills/` | Customize → Skills → Upload a skill(ZIP). 무료 포함, 코드 실행 켜기 | `.agents/skills/` (작업 폴더·내 사용자 폴더) | 사이드바 맞춤설정 → 스킬 → 만들기. SKILL.md·폴더 올리기는 **웹·맥 앱에서만**, 채팅창 `/이름` 으로 부름 |
| 규칙 | `AGENTS.md`, `GEMINI.md`, `.agents/rules/` | 프로젝트 안내문 | `AGENTS.md` | — |
| 연결(MCP) | 설정 → Customizations → Add MCP | Customize → Connectors → Add custom connector (무료는 1개) | 개발자 모드(유료·웹) | Gemini CLI 설정 |
| 예약 | Automations (`/schedule`, 2026-10-07부터 이 이름. 앱을 켜 둬야 하는지 등 조건은 미확인) | Cowork 예약 (유료) | Scheduled (로컬 파일은 컴퓨터가 켜져 있어야) | 예약 작업 최대 10개, 사이드바 «예약됨» |

## 같은 점

도구는 달라도 **스킬 · 규칙 · 연결 · 예약 · 허락(승인)** 다섯 가지 생각은 같습니다.
`SKILL.md` 는 공통 규격(agentskills.io)을 따르므로, 이 자료실의 스킬은 여러 도구에서 그대로 쓸 수 있습니다.

## 알아 둘 변화

- 안티그래비티의 「워크플로(workflows)」는 **2026년 10월 19일부터 돌지 않습니다.** 같은 일은 스킬로 만듭니다. 옛 워크플로는 `/migrate-workflows` 로 `.agents/skills/` 에 옮겨 줍니다. 스킬은 `/이름` 으로 부릅니다.
- 제미나이 젬(Gem)은 개인 계정에서 **2026년 11월 17일부터 읽기 전용**(새로 못 만듦), **12월 17일에 사라집니다.** 있던 젬은 스킬로 저절로 바뀝니다.
- `SKILL.md` 형식(agentskills.io)은 Claude·ChatGPT/Codex·안티그래비티·제미나이가 같이 읽습니다. 넣는 폴더 자리만 제품마다 다릅니다.
- 카카오톡 「나와의 채팅방」으로 보내는 카카오 PlayMCP는 공식 안내상 **ChatGPT(개발자 모드)·Claude(맞춤 커넥터)** 에서 연결합니다.

## 근거 (2026-10-01 확인, 안티그래비티 워크플로·예약과 제미나이 스킬·젬·예약은 2026-10-29 다시 확인)

- Claude 스킬: https://support.claude.com/en/articles/12512180-using-skills-in-claude
- Claude Code 스킬: https://code.claude.com/docs/en/skills
- ChatGPT/Codex 스킬: https://learn.chatgpt.com/docs/build-skills
- 안티그래비티 스킬: https://antigravity.google/docs/skills
- 안티그래비티 규칙: https://antigravity.google/docs/rules
- 안티그래비티 MCP: https://antigravity.google/docs/mcp
- 안티그래비티 워크플로→스킬: https://antigravity.google/docs/migration/workflows-to-skills/
- 스킬 공통 규격: https://agentskills.io/specification
- 제미나이 스킬: https://support.google.com/gemini/answer/18560919?hl=en
- Claude 맞춤 커넥터: https://support.claude.com/en/articles/11175166-getting-started-with-custom-connectors-using-remote-mcp
- ChatGPT 개발자 모드: https://developers.openai.com/api/docs/guides/developer-mode
- Claude Cowork 예약: https://support.claude.com/en/articles/13854387-schedule-recurring-tasks-in-claude-cowork
- ChatGPT 예약: https://learn.chatgpt.com/docs/automations?surface=app
- 카카오 PlayMCP: https://www.kakaocorp.com/page/detail/11817
- GitHub ZIP 받기: https://docs.github.com/en/repositories/working-with-files/using-files/downloading-source-code-archives

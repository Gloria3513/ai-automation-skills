# 시작하기 — 코딩 없이 만드는 업무 자동화 자료실

AI에게 일을 맡길 때 쓰는 **예시 레시피(스킬)** 와 **연습 파일**을 모아 둔 곳입니다.
회원가입 없이 받아 가세요.

## 1. 받기 (1분)

1. 이 화면 위쪽 파일 목록 오른쪽 위의 초록색 **Code** 버튼을 누릅니다.
2. **Download ZIP** 을 누릅니다.
3. 내려받은 `ai-automation-skills-main.zip` 을 더블클릭해 압축을 풉니다.

## 2. 안에 든 것

| 폴더 | 무엇 | 언제 쓰나 |
|---|---|---|
| `skills/folder-organizer` | 뒤죽박죽 폴더를 종류·날짜별로 정리 | 2회차 |
| `skills/file-renamer` | 파일 이름을 `날짜_내용_번호`로 통일 | 3회차 |
| `skills/receipt-to-table` | 영수증·명단·PDF → 표(CSV) | 3회차 |
| `skills/doc-summary-report` | 여러 문서 → 한 장 요약·보고서 초안 | 4회차 |
| `skills/weekly-report` | 이번 주 폴더 → 주간 보고 초안 | 7회차 |
| `skills/photo-blog-draft` | 사진 묶음 → 블로그 글 초안 (올리기는 사람이) | 7회차 |
| `rules-example/AGENTS.md` | AI와의 약속 다섯 줄 | 2회차부터 매번 |
| `practice-files/` | 연습용 가상 명단·회의록 (실제 개인정보 아님) | 3~4회차 |
| `docs/compare-tools.md` | 도구별 스킬·연결(MCP)·예약 비교표 | 6~7회차 |

## 3. 스킬이 뭐예요?

**자주 시키는 일을 「이 순서로, 이건 하지 마」 카드로 적어 둔 것**입니다.
`SKILL.md` 파일 하나에 이름(name)과 설명(description), 그리고 순서가 적혀 있어요.
AI는 설명을 보고 「아, 지금 이 카드를 꺼낼 때구나」 하고 스스로 꺼내 씁니다.

메모장으로 열어 보세요. 그냥 우리말 글입니다. 고쳐 써도 됩니다.

## 4. 내 AI 도구에 넣기

### 안티그래비티 (Antigravity)
가장 쉬운 방법은 **AI에게 설치를 시키는 것**입니다. 작업 폴더를 연 채로 이렇게 말하세요.

```
내려받은 ai-automation-skills-main 폴더 안의 skills 폴더에서
folder-organizer 폴더를 이 작업 폴더의 .agents/skills 폴더 안으로 복사해 줘.
.agents/skills 폴더가 없으면 만들어 줘. 다른 파일은 건드리지 마.
```

- 스킬 위치: 작업 폴더 안 `.agents/skills/스킬이름/SKILL.md`
- 약속 파일(`AGENTS.md`)은 작업 폴더 맨 위에 둡니다.
- 점(.)으로 시작하는 폴더는 탐색기·Finder에서 숨겨져 보일 수 있습니다. 정상입니다.

### Claude (claude.ai 웹·앱)
1. 넣고 싶은 스킬 폴더 하나(예: `folder-organizer`)를 압축(ZIP)합니다.
2. Customize → Skills → **+** → Create skill → **Upload a skill** 에서 그 ZIP을 올립니다.
3. 설정에서 코드 실행 기능이 켜져 있어야 합니다.

### ChatGPT (Codex)
- 개인 스킬 위치: 내 사용자 폴더의 `.agents/skills/스킬이름/SKILL.md`
- 작업 폴더에만 쓰려면 그 폴더 안 `.agents/skills/`

> 메뉴 이름은 자주 바뀝니다. 2026년 10월 1일 공식 문서 기준이며, 근거는 `docs/compare-tools.md` 에 있습니다.

## 5. 꼭 지킬 것

- **원본 말고 사본**으로 연습하세요.
- 개인정보(주민번호·계좌·연락처)가 많은 파일은 맡기지 마세요.
- AI가 「옮길까요?」「지울까요?」 물으면 **표를 읽고** 대답하세요.
- 비밀번호·API 키는 스킬 파일에 절대 적지 마세요.

## 6. 내 스킬 만들기

`skills/` 안의 폴더 하나를 복사해 이름을 바꾸고 `SKILL.md` 를 고치면 됩니다.

- `name`: 영어 소문자·숫자·하이픈(-)만, **폴더 이름과 같게** (예: `my-notice-writer`)
- `description`: 무엇을 하는지 + **언제 꺼내 쓰는지**(「~해 줘」라고 할 때) 한두 문장
- 본문: 순서는 번호로, 하지 말 것은 따로

---
만든 곳: 스마택트(Smartact) · 자유롭게 쓰고 고치고 나눠도 됩니다 (MIT 라이선스)

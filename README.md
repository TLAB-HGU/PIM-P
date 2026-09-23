# PIM-P
Generates paper review seminar slides from research papers

## Skill: `pimp`

`skills/pimp/` — 논문 PDF를 정석 논문 리뷰 세미나 발표 자료(.pptx)로 만드는 Claude 스킬.

### 설치
`skills/pimp/` 폴더를 통째로 스킬 폴더에 복사한다.
- Claude Code (개인): `~/.claude/skills/pimp/`
- Claude Code (프로젝트): `<project>/.claude/skills/pimp/`
- Claude.ai: `skills/pimp/` 폴더를 zip으로 묶어 Settings → Capabilities → Skills에 업로드

### 사용법
| 호출 | 모드 |
|---|---|
| `/pimp` 또는 `/pimp normal` | 기본. 같은 분야 대학원생/연구실용 |
| `/pimp easy` | 비전공자도 알아듣는 쉬운 해석판. 논문의 흐름·핵심 논리·결론은 그대로, 용어와 설명만 쉽게 |

논문 PDF를 첨부한 채 "발표자료 만들어줘", "쉽게 설명하는 버전으로 만들어줘"처럼 말해도 자동으로 동작한다.

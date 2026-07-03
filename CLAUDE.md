# 보리약국 랜딩페이지

정적 사이트(Vercel 배포). 텔레그램 봇을 통해 형(약국 운영자)과 관리자가 자연어로 요청하면 Claude Code 헤드리스(`claude -p`)가 이 저장소를 직접 수정하고 배포하는 무인 파이프라인의 대상 프로젝트다.

## 배포 규칙

파일을 수정했으면 절대 `vercel --prod`로 바로 배포하지 말 것. 항상 `vercel`(preview)만 실행하고 나온 URL을 답변에 포함한다. 사용자가 "이대로 배포해줘"처럼 특정 배포를 프로덕션으로 확정해달라고 명시적으로 요청한 경우에만 `vercel promote <url>`을 실행한다.

## 참조 규칙

@.claude/rules/golden-principles.md
@.claude/rules/coding-style.md
@.claude/rules/verification.md
@.claude/rules/interaction.md
@.claude/rules/date-calculation.md
@.claude/rules/security.md
@.claude/rules/testing.md
@.claude/rules/git-workflow-v2.md

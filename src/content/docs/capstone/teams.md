---
title: 프로젝트 등록
description: Ralphthon 캡스톤 개인 프로젝트 등록
---

## 프로젝트 등록 안내

- 운영 방식: **개인 프로젝트** (소규모 수업)
- 프로젝트 계획서 발표: **2026-04-21 (8주차)** — 중간고사 대체
- 프로젝트 등록 마감: **2026-04-20** (8주차 강의 전날)
- 등록 방법: 이 파일에 PR을 통해 프로젝트 정보 추가

## 등록 방법

이 파일(`src/content/docs/capstone/teams.md`)을 수정하여 아래 형식으로 본인 정보를 "등록된 프로젝트" 섹션에 추가하고 PR을 보낸다.

### 등록 형식

```markdown
### 프로젝트 [번호]: [프로젝트 제목]

| 항목 | 내용 |
|------|------|
| 학번 | 2023xxxx |
| 이름 | 홍길동 |
| 한 줄 요약 | (예: pytest 실패 로그를 입력받아 수정 커밋을 생성하는 에이전트) |
| GitHub 저장소 | https://github.com/... |
| 계획서 | capstone/projects/2023xxxx/proposal.md |
```

## 제출 산출물 경로

```
capstone/projects/[학번]/
├── proposal.md        # 프로젝트 계획서 (8주차 필수)
├── design.md          # 아키텍처 설계 (13주차)
├── progress-week14.md # 중간 진행 보고 (14주차)
├── README.md          # 최종 프로젝트 문서 (15주차)
├── report.md          # 최종 보고서 (15주차)
├── links.md           # 발표 자료 + 데모 영상 외부 링크 (15주차)
└── src/                # 소스 코드
```

**`links.md` 템플릿** (발표 자료·데모 영상은 외부 URL로):

```markdown
# 프로젝트 외부 링크

## 발표 자료 (presentation)
- URL: https://...           <!-- Google Slides / PDF 공유 링크 / Figma 등 -->
- 형식: Google Slides
- 접근 권한: 누구나 보기

## 데모 영상 (demo)
- URL: https://...           <!-- YouTube unlisted / Google Drive 등 -->
- 길이: N분 N초
- 접근 권한: 누구나 보기
```

> `.gitignore`에서 `*.pdf`와 `*.mp4`가 차단되므로 이 파일들을 저장소에 직접 커밋할 수 없다. 외부 호스팅 후 링크만 기록한다.

## 등록된 프로젝트

*등록 후 이 섹션에 추가됩니다.*

---

> **교수 승인**: 프로젝트 주제는 **8주차 계획 발표**에서 피드백 후 확정된다.
>
> **계획서 작성 가이드**: [프로젝트 계획서 가이드](/capstone/proposal-guide) 참조. 일관된 구조와 구체성 확보를 위해 표준 템플릿을 반드시 따른다.

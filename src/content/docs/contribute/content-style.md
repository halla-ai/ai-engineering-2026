---
title: 콘텐츠 스타일 가이드
description: 강의 자료 작성 규칙 — MDX 컴포넌트 사용법과 작성 원칙
---

## 작성 원칙

1. **명확성 우선**: 복잡한 개념을 쉽게 설명
2. **코드 예시 필수**: 이론 설명 후 반드시 코드 예시
3. **한국어 기본**: 기술 용어는 영어 병기 허용
4. **간결하게**: 불필요한 설명 제거

## Starlight 컴포넌트 사용법

### Aside (콜아웃)

```mdx
import { Aside } from '@astrojs/starlight/components';

<Aside type="note" title="참고">메모나 추가 정보</Aside>
<Aside type="tip" title="팁">유용한 팁</Aside>
<Aside type="caution" title="주의">주의사항</Aside>
<Aside type="danger" title="경고">위험한 내용</Aside>
```

### Steps (단계별 절차)

```mdx
import { Steps } from '@astrojs/starlight/components';

<Steps>
1. **첫 번째 단계** — 설명
2. **두 번째 단계** — 설명
</Steps>
```

### Tabs (탭)

```mdx
import { Tabs, TabItem } from '@astrojs/starlight/components';

<Tabs>
  <TabItem label="macOS">macOS 내용</TabItem>
  <TabItem label="Linux">Linux 내용</TabItem>
</Tabs>
```

### Card & CardGrid

```mdx
import { Card, CardGrid } from '@astrojs/starlight/components';

<CardGrid>
  <Card title="카드 제목" icon="rocket">카드 내용</Card>
</CardGrid>
```

## 주차별 강의노트 템플릿

```mdx
---
title: "N주차: 제목"
description: 설명
week: N
phase: 1|2|3|4|5
phase_title: Phase 이름
date: "YYYY-MM-DD"
theory_topics: ["주제1", "주제2"]
lab_topics: ["실습1"]
assignment: "Lab XX: 과제명"
assignment_due: "YYYY-MM-DD"
difficulty: 입문|초급|중급|고급
estimated_time: X시간
---

## 이론 (Theory)
...

## 실습 (Practicum)
...

## 과제 (Assignment)

<div class="assignment-box">
### Lab XX: 제목
**제출 마감**: YYYY-MM-DD
...
</div>
```

## 코드 블록 규칙

- 언어 명시 필수: ` ```python `, ` ```bash `, ` ```json ` 등
- 실행 가능한 예시 코드 사용
- 주석은 한국어로 작성 가능

## 금지 사항

- 저작권 자료 무단 인용
- 검증되지 않은 코드 예시
- 과도한 이모지 사용

# GitHub 관리 규칙

## Pull Request (PR) 규칙

### PR 생성 규칙

1. PR 제목 형식

   - 형식: `[타입] 작업 내용 요약`
   - 타입: feat, fix, docs, style, refactor, test, chore
   - 예시: `[feat] 로그인 기능 구현`

2. PR 설명 템플릿

   ```markdown
   ## 작업 내용

   - 구현한 내용을 상세히 기술

   ## 변경사항

   - 주요 변경사항 리스트

   ## 테스트

   - [ ] 단위 테스트 완료
   - [ ] 통합 테스트 완료

   ## 관련 이슈

   - #이슈번호
   ```

3. 브랜치 네이밍
   - 형식: `타입/작업내용`
   - 예시: `feat/login`, `fix/auth-error`

### PR 리뷰 규칙

1. 최소 1명 이상의 리뷰어 승인 필요
2. 리뷰어는 48시간 이내 리뷰 완료
3. 코드 품질 기준
   - 테스트 코드 필수
   - 코드 중복 최소화
   - 명확한 변수/함수명

## 이슈 관리 규칙

### 이슈 생성 규칙

1. 이슈 제목 형식

   - 형식: `[타입] 이슈 내용 요약`
   - 타입: feature, bug, enhancement, documentation
   - 예시: `[feature] 회원가입 기능 추가`

2. 이슈 설명 템플릿

   ```markdown
   ## 목적

   - 이슈의 목적/배경 설명

   ## 요구사항

   - 구현해야 할 상세 요구사항 리스트

   ## 참고사항

   - 관련 문서/링크 등
   ```

### 이슈 라벨 규칙

- priority/high: 높은 우선순위
- priority/medium: 중간 우선순위
- priority/low: 낮은 우선순위
- status/in-progress: 진행 중
- status/review-needed: 리뷰 필요
- status/blocked: 차단됨
- type/feature: 새로운 기능
- type/bug: 버그 수정
- type/enhancement: 개선사항
- type/documentation: 문서화

### 이슈 할당 규칙

1. 이슈 생성 시 담당자 지정
2. 작업 시작 전 status 라벨 업데이트
3. 완료 시 관련 PR 링크 추가

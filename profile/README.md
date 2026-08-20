# AVAD-Software

## 작업 시작

1. Issue 유형 선택
2. 작업 목적과 작업 범위 작성
3. 완료 조건 작성
4. 관련 자료 및 화면 첨부
5. 작업 완료 후 PR 작성

## Issue 작성 기준

### 공통 항목

- 작업 목적
- 배경 및 문제
- 작업 범위
- 완료 조건
- 참고 자료

### Issue 유형

| 유형 | 사용 범위 | 제목 형식 |
| --- | --- | --- |
| `feat` | 신규 기능 및 사용자 요구사항 | `[feat] 기능명` |
| `fix` | 오류 및 예외 동작 | `[fix] 문제명` |
| `refactor` | 사용성·성능·구조 개선 | `[refactor] 개선 내용` |
| `chore` | 문서·설정·기술 부채·운영 작업 | `[chore] 작업 내용` |

### 버그 작성 항목

- 현재 동작
- 기대 동작
- 재현 절차
- 발생 환경
- 로그 및 화면 자료

## PR 작성 기준

- 변경 범위
- 주요 변경 내역
- 영향 범위
- 확인 내역
- 연결 Issue
- 리뷰 요청 사항

### PR 확인 내역

- 관련 빌드 또는 테스트
- 변경 화면 또는 기능 확인
- 영향 범위 확인
- 문서 및 주석 확인

## 제목 및 커밋 규칙

명사형 한국어 제목 기준

| 유형 | 사용 범위 | 예시 |
| --- | --- | --- |
| `feat` | 기능 추가 | `feat: 로그인 자동완성 기능 추가` |
| `fix` | 오류 수정 | `fix: Android 15 뒤로가기 동작 보완` |
| `docs` | 문서 변경 | `docs: Issue 및 PR 작성 기준 정리` |
| `refactor` | 구조 개선 | `refactor: 화면 inset 처리 구조 정리` |
| `chore` | 일반 정리 | `chore: 프로젝트 설정 정리` |
| `build` | 빌드 설정 | `build: SDK 36 빌드 환경 상향` |
| `test` | 테스트 변경 | `test: 로그인 입력 검증 추가` |
| `release` | 배포 반영 | `release: SDK 36 호환성 반영` |

### 지양 표현

- 완료 서술형 제목
- 수정 결과 서술형 제목
- 내용이 불명확한 제목

## 문서 및 템플릿

- [Issue Form](https://github.com/AVAD-Software/.github/tree/dev/ISSUE_TEMPLATE)
- [PR Template](https://github.com/AVAD-Software/.github/blob/dev/PULL_REQUEST_TEMPLATE.md)

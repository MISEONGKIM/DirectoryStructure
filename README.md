## React 폴더 구조

- pages : 각 페이지
- components
  - common : 공용 컴포넌트
    - hooks : 공용 컴포넌트들의 훅들
      - useDialog.tsx
      - useList.tsx
    - Dialog.tsx
    - List.tsx
  - login : 도메인별 컴포넌트들
    - useLogin.tsx
    - login.tsx
  - home
- hooks : 공용 hooks, 도메인별 컴포넌트에서 두 번 이상 재사용되는 hooks들
- assets : 이미지, css파일
- api : api목록들
- stores : 전역 상태, redux
- utils : 유틸 함수들

폴더명: 소문자 시작
파일명 : ui 컴포넌트는 대문자로 시작, 나머지는 소문자 시작 ?

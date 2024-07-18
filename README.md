# React Test
simhwa-exam-for-student.zip 다운로드
yarn install
yarn start

### Goal
Redux toolkit의 thunk와 비동기 함수를 이용해서 프로젝트 완성
### Features
1. input 에 제목을 쓰고, 추가하기 버튼을 클릭하면 2초 뒤 todo가 추가되어 화면에 렌더링 됩니다.
2. 삭제하기 버튼을 클릭하면 2초뒤 todo가 삭제되어 화면에 렌더링 됩니다.

❗ 비동기 작업인 2초 지연을 위해서는 미리 만들어둔 `waitTwoSeconds` 함수를 사용하세요.
```
  // waitTwoSeconds 예시:
  await waitTwoSeconds()
```
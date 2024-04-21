# udemy-TESTING-LIBRARY

Code to accompany [React Testing Library and Jest](https://www.udemy.com/course/react-testing-library/?couponCode=TEST-LIB-GITHUB) course on Udemy.

### 섹션2 강의 정리(Color Button)

- fireEvent를 사용하여 인터랙션을 테스트
- jest-dom:
  - toBeEnabled()
  - toBeDisabled()
  - toBeChecked()
    - toBeChecked의 반대는 not.toBeChecked()
- getByRole option { name: }
  - getByRole 쿼리 사용은 접근성에 더 좋다.
- Jest/Vitest describe를 사용하여 그룹 테스트
- 함수 단위 테스트(Unit testing functions)
- 단위 테스트(Unit Test)가 도움이 되는 이유:
  - 가능한 모든 극단적 케이스 경우를 포함하는데 좋다.
  - 모든 극단적 케이스를 테스트하기 위해 컴포넌트를 실행하지 않아도 된다.
  - 함수 단위 테스트는 기능 테스트의 실패 원인을 확인하기 좋다.

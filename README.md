# Kream-frontend (크림 클론 프로젝트)

## 사용 기술 및 스택

- React
- typescript

## 설치 방법

```jsx
npm install
```

## 실행 방법

```jsx
npm run start
```

## 🔥프로젝트 목표🔥

### 기존 인스타그램 프로젝트에서 부족했던 부분을 보완한 프로젝트를 만든다.

- 디자인 패턴
  - Atomic Design Pattern
- 내가 정의한 전역 상태 관리 원칙 지키기
  - Context api - props drilling을 피하기 위한 용도로 사용한다.
  - Redux - 필터와 같은 전역 상태 값은 전역 상태 관리 라이브러리를 사용하여 관리한다.
    - Redux middleware 적용하기
      - Generator에 대한 학습을 통해
      - Redux 비동기 로직이 필요한 곳곳에 투입한다.
- 렌더링 최적화
  - useCallback의 사용
    - 페이지 로드 시 정보에 따라 값을 받아오는 함수들은 useCallback을 사용하여 작성한다.
    - useEffect를 사용하여 useCallback으로 작성한 통신 함수를 호출한다.
  - useMemo의 사용
    - 공부를 통해 추후 작성 예정...
- 통신 함수 관리
  - lib 파일에 따로 관리를 하며 객체 형태로 통신 함수들을 관리한다.
  - response.status를 확인할 수 있는 함수를 재사용 가능한 함수로 만든다.
  - createAxios를 활용하여 Header에 토큰을 담아서 재사용 할 수 있는 함수를 만든다.
- git 관리
  - 하나의 task 개발이 완료 된 후 commit을 남기는 것을 습관화 한다. 잊지 말긔!!
- 기록
  - notion 활용을 철저히 하여 설계부터 작성 내용까지 꼬박꼬박 작성하여 나중에 바로 블로그화 시킬 수 있게 준비한다.

## 디렉토리 구조

- 추후 추가 예정...

## 실행 화면

## 얻은 점

## 아쉬운 점

## 앞으로...

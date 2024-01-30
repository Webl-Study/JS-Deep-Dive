- 'use strict'로 적용가능하다.

- 젼역에 사용하기보다는 IIFE로 감싼 스크립트 단위의 사용을 권장한다.

- 방지가능한 것
  - 암묵적 전역
  - 변수, 함수, 매개변수의 삭제
  - 매개변수 이름 중복
  - with문
  - 일반 this가 undefined로 변경
  - arguments 변경

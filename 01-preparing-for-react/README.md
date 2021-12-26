# Node.js 환경에서 DOM test 및 util 함수 연습

- addClass.js

  > node.js 환경에서 DOM 테스트가 가능한지 테스트

  - addClass(document.body, 'some') 함수 사용 시 document.body는 'some' 클래스 이름을 소유한다.
  - 문서의 #app 노드에 'anything' 클래스 이름 설정이 가능하다.

- getRandom.js

  > 난수를 구하는 함수 테스트

  - getRandom(10) 실행 결과는 10보다 작다.
  - getRandomCount(5, 7) 실행 결과는 5 이상 7 이하이다.

- transformText.js
  > 텍스트 트랜스폼 유틸리티 테스트
  - snakeCase('simple is best') → 'simple_is_best'
  - kebabCase('simple is best') → 'simple-is-best'
  - camelCase('simple is best') → 'simpleIsBest'
  - titleCase('simple is best') → 'SimpleIsBest'

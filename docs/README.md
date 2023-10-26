# 구현할 기능 목록

## 기능

- 자동차의 이름을 입력받아 배열에 저장하는 함수

  1. 이름이 5자를 초과할경우 예외발생
  2. 각 자동차의 이름은','로 구분
  3. 자동차의 이름을 배열에 저장해 배열 리턴

- 주어진 횟수 n을 입력받는 함수

  1. 0이하의 수나 숫자가 아닌 값이 입력되었을 경우 예외발생
  2. n을 입력받아 n리턴

- 각 회차별 전진여부를 판단하고 출력하는 함수

  1. 자동차 배열과 n을 파라미터로 받음
  2. 자동차 배열과 같은 크기의 전진 여부 배열 생성
  3. n만큼 반복문 실행
  4. 반복문을 사용해 무작위 값을 뽑아 4이상일 경우 각 자동차 전진여부 배열에 -추가
  5. 반복문이 한번 실행될 때마다 전진 결과 출력
  6. 반복문 종료후 자동차 배열과 전진여부 배열을 배열에 담아 리턴

- 모든 회차가 끝나고 우승자를 출력하는 함수
  1. 파라미터로 자동차배열과 전진여부 배열을 담은 배열을 받음
  2. 반복문으로 전진여부 배열의 값을 비교해 가장 긴 길이의 인덱스 값 저장
  3. 인덱스 값에 해당하는 자동차 배열값 출력

## 테스트

- 자동차의 이름이 5자를 초과할 경우 예외 처리
- n에 0이하의 값이 입력 되었을 때 예외 처리
- n에 수가 아닌 값이 입력 되었을 때 예외 처리
- 공동우승자 출력
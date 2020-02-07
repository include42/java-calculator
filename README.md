# java-calculator
문자열 계산기 미션 저장소

## 요구사항
 - 사용자가 문자열을 입력하면, 그에 맞는 정수값을 출력한다.
 - 계산기는 우선순위 없이, 입력 순서에 따라 연산을 수행한다.
 - 연산자는 4가지 중 하나가 입력된다.(덧셈, 뺄셈, 곱셈, 나눗셈)

## 구현단위
 - 문자열 입력 받기
    - 예외처리: 빈문자열이 입력된 경우
 - 문자열을 공백 기준으로 나눠서 큐에 담기
 - 입력에 대한 계산을 요청
     - 예외처리: 유효하지 않은 수식(연산자)이 입력된 경우
     - 예외처리: 유효하지 않은 수식(숫자)이 입력된 경우
 - 덧셈 기능
 - 뺄셈 기능
 - 나눗셈 기능
    - 예외처리: 0으로 나누는 경우
 - 곱셈 기능
 - 계산 결과를 출력


## 우아한테크코스 코드리뷰
* [온라인 코드 리뷰 과정](https://github.com/woowacourse/woowacourse-docs/blob/master/maincourse/README.md)
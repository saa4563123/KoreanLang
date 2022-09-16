# 씨-언어
Korean C Programming Lang

한글프로그래밍언어(일명 코랭, Ko-Lang)은 평범한 대학생이 심심해서 구상해 본 C++기반 한글 프로그래밍 언어입니다.

엄랭([umjunsik-lang](https://github.com/rycont/umjunsik-lang))과 해병문학([marine-lang](https://github.com/dpvpd/MarineLang))을 이어나갈 제 3의 한글 프로그래밍 언어를 꿈꾸고 있습니다.

문법은 C++과 동일하나 순수 한글을 사용하여 프로그래밍이 가능합니다!

# 문법
## 자료형
* int형: 정수
* double형: 실수
* string형: 문자열
```
정수 가 는 영 끝
=> int 가 = 0;
```

## 연산자
* 덧셈: 더하기
* 뺄셈: 빼기
* 곱셈: 곱하기
* 나눗셈: 나누기
* 나머지: 나머지
* 등호: 는
* &&: 그리고
* ||: 또는
* >: 크다
* <: 작다
* >=: 크거나같다
* <=: 작거나같다
* ==: 같다
* ++: 증가
* --: 감소
```
가 는 오 곱하기 삼 끝
=> 가 = 5 * 3; // 즉, 가 = 15;
```

## 입출력
* cin: 입력
* cout: 출력
* >>: 과
* <<: 와
```
입력 과 가 끝
출력 와 나 와 다 끝
=> cin >> 가; cout << 나 << 다;
```

## 조건문
* if: 만약
* else if: 그런데만약
* else: 아니면
```
만약 조건시작 가 크다 나 조건끝 나 는 가 끝
=> if (가 > 나) 나 = 가;
```

## 반복문
* while: 단순조건반복
* for: 전후조건반복
* while(true): 무한반복
```
전후조건반복 조건시작 정수 가 는 영 끝 가 작다 나 끝 가 증가 조건끝
=> for (int 가 = 0; 가 < 나; 가++)
```

## 함수
* int main(void): 본문함수

## 반환
* return 0: 반환없음
* return: 반환
```
반환 가 끝
=> return 가;
```

## 괄호
* [ ]: 범위시작 범위끝
* { }: 함수시작 함수끝
* ( ): 조건시작 조건끝
```
상단 반복문, 조건문 예제 참조
```

## 숫자
* -: 음수
* 영 일 이 삼 사 오 육 칠 팔 구
십진 표기로 선언되며, 10 이상의 수는 곱으로 나타낸다.
```
가 는 음수 오 곱하기 육 끝
=> 가 = (-5) * 6; // 가 = -30;
```

## 문자열 !미구현 항목!
* "": 문자열시작, 끝
* '': 문자시작, 끝
```
출력 와 문자열시작 안녕하세요! 문자열끝 끝
=> cout << "안녕하세요!";
```

## 문자
* ;: 끝
* ,: 음
* " ": 공백
* "\n": 개행


# 예시
## 백준 10818번
```
#include "Korean.h"

표준소속선언 끝

본문함수
함수시작
	정수 가 는 영 음 나 는 영 음 다 는 영 음 라 는 영 끝

	입력 과 가 끝
	전후조건반복 조건시작 정수 마 는 영 끝 마 작다 가 끝 마 증가 조건끝
  함수시작
		입력 과 나 끝

		만약 조건시작 마 같다 영 조건끝
    함수시작
			다 는 나 끝
			라 는 나 끝
		함수끝

		만약 조건시작 나 크다 다 조건끝 다 는 나 끝
		만약 조건시작 나 작다 라 조건끝 라 는 나 끝
	함수끝

	출력 와 라 와 공백 와 다 와 개행 끝

	반환없음 끝
함수끝
```


# 사용
## IDE
* Korean.h를 include 하여 VisualStduio에서 사용이 가능합니다.
## [백준](acmicpc.net)
* Korean.h의 소스코드를 복사하여 코드 상단에 입력 후 c++17로 채점 가능합니다.

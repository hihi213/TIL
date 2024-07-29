## 자바가 제공하는 자료형
- ### 원시 자료형
	- #### Type 만큼의 공간을 메모리에 할당하고 값으로 채운다
	- ex) int a= 7 -> 메모리에 4바이트를 할당하고 7이라는 값으로 채운다
		- 00000000 00000000 00000000 000001111
	- 원시형은 참조형과 사용하는 메모리 영역이 다르고 (빠른영역), 필요한 최소한의 공간만을 이용하며, 매우 빠른 연산이 가능하다
	- 다소 불편해도 공간과 속도를 최적화할 수 있다
	- 자바는 c와 달리 원시형에 1: 1 대응하는 참조형도 제공한다. 
		- 그 자체가 클래스 객체이다
		- 원시형을 감싸고 있어 래퍼 클래스 라고도 한다
			- 아 그래서 자료구조에 기본형 데이터는 래퍼클래스로 저장했구나..
		- 138페이지 표부터 시작하기
- ### 참조 자료형
	- ####  원시 자료형이 아닌 자료형
		- 원시형은 자바 메모리 모델에서 매우 빠른 영역에 할당되고 참조형은 느린영역에 할당 된다
		- 원시형은 자료형에 따라 크기가 제각각이며, 자료형 크기만큼의 메모리만 할당한다 반면 참조형은 일정한 크기로 훨씬 더 큰 메모리가 할당된다.
		- 참조형은 메소드 호출을 통해 여러 편리한 작업을 수행할 수 있다
		- 원시형은 항상 값이 존재해야 하며, 널이 될수는 없다. 참조형은 널이 될 수 있다
		- 컬렉션(자료구조)의 엘리먼트(자료구조에 저장된 개별 데이터 항목)는 참조형만 가능하다.
		- 원시형을 선언하는 키워드는 소문자로 시작하며, 참조형은 대문자로 시작한다

| 자료형     | 크기    | 설명(십진수로 범위가)               |
| ------- | ----- | -------------------------- |
| byte    | 1byte | 정수 -128~127 (2의 7승)        |
| short   | 2byte | 정수 -32.768~32.767 (2의 15승) |
| int     | 4byte | 정수 10자리                    |
| long    | 8byte | 정수 19자리                    |
| float   | 4byte | 실수 7자리까지 정확                |
| double  | 8byte | 실수 13자리까지 정확               |
| boolean | 1bit  | 참/거짓 중 하나를 저장              |
| char    | 2byte | 단일 문자를 저장                  |

- ### 원시가 아닌 자료형
	- #### 사용자 정의 자료형
	- 


# ** 138페이지 표부터 시작하기**
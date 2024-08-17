# C 프로그래밍 계산기 프로젝트

이 프로젝트는 C 언어로 구현된 다기능 계산기입니다. 일반 연산뿐만 아니라 공학 계산에 특화된 기능을 포함하고 있습니다.

## 기능

1. 일반 계산기
   - 기본 연산 (덧셈, 뺄셈, 곱셈, 나눗셈)
   - 루트 계산
   - 백분율 계산

2. 공학용 계산기
   - 삼각함수 (sin, cos, tan)
   - 역삼각함수 (arcsin, arccos, arctan)
   - 쌍곡선함수 (sinh, cosh, tanh)
   - 로그 함수 (ln, log)
   - 지수 및 거듭제곱
   - 절대값
   - 팩토리얼
   - 파이(π) 계산
   - 진법 변환 (2진수, 8진수, 16진수)
   - 비트 연산 (AND, OR, XOR, 왼쪽 시프트)
   - 피타고라스 정리

3. 16진수 계산기
   - 16진수 덧셈, 뺄셈, 곱셈, 나눗셈

4. 8진수 계산기
   - 8진수 덧셈, 뺄셈, 곱셈, 나눗셈

## 사용 방법

1. 프로그램을 실행합니다.
2. 메인 메뉴에서 원하는 계산기 모드를 선택합니다.
3. 선택한 모드에 따라 숫자와 연산을 입력합니다.
4. 결과를 확인합니다.
5. 계속해서 계산하거나 다른 모드로 전환할 수 있습니다.
6. 종료하려면 메인 메뉴에서 '0'을 입력합니다.

## 컴파일 및 실행

```
gcc -o calculator main.c -lm
./calculator
```
<br/>
<br/>
# C Programming Calculator Project

This project is a multifunctional calculator implemented in language C. It contains features specialized in engineering computation as well as general computation.

## function

1. a general calculator
   - Basic operations (adding, subtraction, multiplication, division)
   - root calculation
   - Percentage calculation

2. an engineering calculator
   - trigonometric functions (sin, cos, tan)
   - Reverse trigonometric functions (arcsin, arcos, arctan)
   - Hyperbolic functions (sinh, cosh, tanh)
   - Log function (ln, log)
   - Index and Power
   - absolute value
   - Factorial
   - Pi (π) calculation
   - base conversion (binary, octal, hexadecimal)
   - Bit operation (AND, OR, XOR, left shift)
   - Pythagorean theorem

3. a hexadecimal calculator
   - hexadecimal addition, subtraction, multiplication, division

4. an octal calculator
   - octal addition, subtraction, multiplication, division

## How to use it

1. Run the program.
2. Select the desired calculator mode from the main menu.
3. Enter numbers and operations according to the mode selected.
4. Check the results.
5. You can continue to calculate or switch to another mode.
6. To exit, type '0' in the main menu.

## Compile and run

```
gcc -o calculator main.c -lm
./calculator
```

## Precautions

- Only numbers in the specified range must be entered when entering.
- In case of incorrect input, an "Input Error" message is displayed and a re-input is requested.
## 주의사항

- 입력 시 지정된 범위의 숫자만 입력해야 합니다.
- 잘못된 입력 시 "입력 오류" 메시지가 표시되며 재입력을 요구합니다.

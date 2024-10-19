# javascript-calculator-precourse

# 🧮 문자열 덧셈 계산기
## 구현할 기능

### 1. 사용자 입력
#### 사용자로부터 덧셈 계산식을 문자열로 입력 받는다.

### 2. 구분자 설정
#### 입력된 문자열을 분리하기 위한 구분자를 정의한다.
- **기본 구분자**: 쉼표(`,`)와 콜론(`:`)
- **커스텀 구분자**: 문자열 시작 부분에 `//`와 `\n` 사이에 위치하는 문자

### 3. 문자열 분리
#### 정의된 구분자를 기준으로 입력 문자열을 분리한다.

### 4. 숫자 변환
#### 분리된 문자열을 숫자로 변환하여 리스트에 저장한다.

### 5. 합계 계산
#### 숫자 리스트의 합을 계산하여 결과를 출력한다.

### 6. 예외 처리
#### 잘못된 값 입력 시 예외 처리
- **문자열이 아닌 경우**: null, undefined 등이 입력된 경우
- **음수가 포함된 경우**
- **잘못된 구분자 형식**: `//`와 `\n`이 문자열 시작이 아닌 곳에 있거나, 비정상적인 형식으로 입력된 경우
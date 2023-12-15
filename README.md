# Python_Study
![Python Logo](https://i.namu.wiki/i/pHxeJONxIv51qQsN2ac5nX3shPEmiSlKtGVATZXUE22NHGyw9v7_Aqto6aSoCU9ODz3RKtTKCEP0E0OI7TlxMQ.webp)

## 파이썬 복습 1회차
### Python 이란?
Python은 1991년 Guido van Rossum에 의해 개발된 프로그래밍 언어입니다. Python의 이름은 'Monty Python's Flying Circus'에서 착안했습니다.

#### Python 디자인 원칙
Python의 디자인 원칙은 아래와 같습니다(출처: [The Zen of Python](https://peps.python.org/pep-0020/)):

- 아름다운 것이 추한 것보다 낫다.
- 명시적인 것이 암시적인 것보다 낫다.
- 간단한 것이 복잡한 것보다 낫다.
- 복잡한 것이 복잡한 것보다 낫다.
- 평평한 것이 중첩된 것보다 낫다.
- 드문 것이 조밀한 것보다 낫다.
- 가독성이 중요하다.
- 특별한 경우는 규칙을 깨기에 충분히 특별하지 않다.
- 실용성이 순수성에 우선한다.
- 오류는 절대 조용히 지나가선 안 된다.
- 명시적으로 침묵시키지 않는 한.

#### Python의 특징
Python은 다음과 같은 특징을 가집니다:

- 간단하고 명료한 문법.
- 뛰어난 생산성.
- 인터프리터 언어로서 즉시 실행 가능.
- 방대한 라이브러리 제공.
- 동적 타이핑 지원.

#### Python 사용법
Python은 [Python 공식 홈페이지](https://www.python.org/)에서 무료로 다운로드할 수 있습니다.

#### Python 에디터
프로그래밍을 위한 다양한 에디터가 있습니다. Python에 적합한 에디터들은 다음과 같습니다:

- **IDLE(Integrated DeveLopment Environment)**: Python에서 제공하는 기본 에디터. [다운로드 링크](https://www.python.org/)
- **PyCharm**: Python에 특화된 가장 유명한 에디터. 프로그래밍 초보자에게 추천. [다운로드 링크](https://www.jetbrains.com/pycharm/)
- **Visual Studio Code**: Python을 포함한 다양한 언어를 지원하는 마이크로소프트의 에디터. 많은 개발자가 선호. [다운로드 링크](https://code.visualstudio.com/)
- **Sublime Text**: 과거에 인기가 많았던 에디터. 편집과 생산성에 초점을 맞춤. [다운로드 링크](https://www.sublimetext.com/)

Python은 그 자체로 강력하지만, 다양한 라이브러리와 프레임워크를 통해 더욱 확장될 수 있습니다. 데이터 과학, 웹 개발, 자동화, 머신 러닝 등 다양한 분야에서 활용됩니다.

### 데이터의 유형
프로그래밍 언어에서 데이터의 유형은 크게 상수와 변수로 구분됩니다.

#### 상수(Constant)
- 상수는 프로그램 실행 중에 값이 변하지 않는 고정된 값을 말합니다.
- 예: `0`, `1`, `13`, `-1`, `-25`, `3.14`

#### 변수(Variable)
- 변수는 값이 저장되는 메모리 공간으로, 프로그램 실행 중에 값이 변경될 수 있습니다.
- 변수는 저장된 값을 변경할 수 있습니다.
- 예:
  ```python
  a = 10
  b = -1
  c = a + b
  ```

### 변수 작명과 대입
프로그래밍에서 변수의 이름은 해당 변수의 의미를 명확하게 전달할 수 있도록 명명하는 것이 좋습니다. Python에서 변수에 값을 대입하는 방법은 아래와 같습니다.

```python
변수명 = 변수 값
a = 100
b = 'Name'
```

#### 수학의 '='와 프로그래밍의 '='의 차이
- 수학에서 '='는 양쪽이 동일하다는 의미를 가집니다. 예: `x = y + 1`은 가능하지만 `x = x + 1`은 불가능합니다.
- 프로그래밍에서 '='는 대입을 의미합니다. 예: `x = y + 1`과 `x = x + 1` 모두 가능합니다.

### 파이썬의 기본 데이터 타입
1. 숫자형

- int (정수): 소수점이 없는 숫자를 나타냅니다. 예: 5, -3
- float (부동 소수점): 소수점을 포함하는 숫자입니다. 예: 3.14, -0.001
- complex (복소수): 복소수를 나타내며, 실수부와 허수부로 구성됩니다. 예: 2 + 3j

2. 문자열

- str: 문자, 단어, 또는 문장 등을 나타냅니다. 문자열은 작은따옴표(' ') 또는 큰따옴표(" ")로 둘러싸여 있습니다. 예: "Hello", 'Python'

3. 불리언

- bool: 논리적 값인 True 또는 False를 나타냅니다.

4. 시퀀스 타입

- list: 순서가 있는 컬렉션으로, 다양한 데이터 타입의 요소들을 포함할 수 있습니다. 예: [1, 2, 3], ['a', 'b', 'c']
- tuple: 변경 불가능한 순서가 있는 컬렉션입니다. 예: (1, 2, 3), ('a', 'b', 'c')
- range: 특정 범위의 숫자 시퀀스를 나타냅니다. 예: range(0, 10)

5. 매핑 타입

- dict: 키-값 쌍으로 이루어진 컬렉션입니다. 예: {'name': 'Alice', 'age': 25}

6. 집합 타입

- set: 중복을 허용하지 않는 순서가 없는 컬렉션입니다. 예: {1, 2, 3}
- frozenset: 변경 불가능한 집합 타입입니다.

7. 바이너리 타입

- bytes: 바이트 데이터를 나타냅니다. 예: b'Hello'
- bytearray: 변경 가능한 바이트 배열입니다.
- memoryview: 메모리의 바이트 시퀀스에 대한 동적인 뷰를 제공합니다.
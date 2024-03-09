# Python-Tutorial
## Python Home
```언어
print("Hello, World!")
```
## Python Syntax 
Python Indentation
```언어
if 5 > 2:
  print("Five is greater than two!")
```
공백을 넣지 않으면 오류가 발생한다. 일반적으로 4개의 공백이 사용되지만 적어도 하는 있어야 한다.
  예
```언어
  if 5 > 2:
 print("Five is greater than two!") 
if 5 > 2:
        print("Five is greater than two!") 
```
Python Variables
변수에 값을 할당하면 변수가 생성된다.
```언어
x = 112
y = "Hello, World!"
```
Comment
#을 이용해 주석을 달 수 있다.
# 이것은 주석입니다
```언어
print("Hello, World!")
```
##Python Comments
주석은 #으로 시작하며 그 뒤는 파이썬에서 무시된다.
```언어
print("Hello, World!") # 주석입니다
```
위처럼 줄 끝에 배치할 수 있다
Multiline Comments
삼중 따옴표(```)를 사용하여 그 안에 주석을 넣을 수 있다.
```언어
"""
안녕하세요
감사합니다
잘 부탁드립니다
"""
print("Hello, World!")
```
##Python Variables
```언어
x = 10
y = "Min Jun"
print(x)
print(y)
```
다른 유형으로 변수를 설정할 수 있다 (int : 정수형 , str : 문자열)
```언어
x = 4       # 정수형으로 작성된 변수
x = "Sally" # 문자열로 작성된 변수
print(x)
```
문자열,정수형,실수형 등 원하는 데이터 유형으로 지정할 수 있다
```언어
x = str(3)    # x will be '3'
y = int(3)    # y will be 3
z = float(3)  # z will be 3.0
```
type() 함수를 사용하여 변수의 데이터 유형을 도출해낼 수 있다.
```언어
x = 5
y = "John"
print(type(x))
print(type(y))
```
위의 경우 아래처럼 데이터 유형이 값으로 나온다.
```언어
<class 'int'>
<class 'str'>
```
문자열 변수는 작은따옴표나 큰땅옵표를 사용하여 작성 가능
변수의 이름은 대소문자를 구분하기 때문에 a,A 처럼 두 개의 변수를 설정할 수 있다.
###Variable Names
변수 이름은 문자나 밑줄 문자로 시작해야 합니다.
변수 이름은 숫자로 시작할 수 없습니다.
변수 이름에는 영숫자와 밑줄(Az, 0-9 및 _)만 포함할 수 있습니다.
변수 이름은 대소문자를 구분합니다(age, Age 및 AGE는 세 가지 다른 변수입니다).
```언어
myvar = "MinJun"
my_var = "MinJun"
_my_var = "MinJun"
myVar = "MinJun"
MYVAR = "MinJun"
myvar2 = "MinJun"
```
여러 변수에 대한 많은 값
-

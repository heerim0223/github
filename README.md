# github
How to use GITHUB 
1. Git과 Github
2. Markdown(README.md 작성)

------------

## Git과 Github
### Git
```
Git은 어쩌고
```
### Github
```
Github는 어쩌고
```

------------

------------

## [Markdown(README.md)](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
## 1. 헤더(Headers)
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

## 2. 텍스트 줄바꿈
텍스트 단락에서 줄을 바꿀 때는 Enter를 두 번 눌러 적용해야합니다.

## 3. 가로 줄
```
---
------------
- - -
***
************
* * *
```
---
------------
- - -
***
************
* * *

## 4. 텍스트
### 4-1. 텍스트 강조
```
**굵게** or __굵게__
*기울임체* or _기울임체_
***굵은 기울임체*** or ___굵은 기울임체___
~~취소선~~
```
**굵게** or __굵게__
*기울임체* or _기울임체_
***굵은 기울임체*** or ___굵은 기울임체___
~~취소선~~

### 4-2. 텍스트 인용
인용문을 삽입할 때는 인용문의 첫 번째 줄 앞에 글머리기호('>')를 추가합니다.
인용문 안에 또 다른 인용문을 삽입하려면 글머리기호('>>')를 추가합니다.
```
> 인용문1
>> 인용문2
```
> 인용문1
>> 인용문2

### 4-3. 리스트(List)
#### 4-3-1. 순서가 있는 리스트
순서가 있는 리시트는 숫자와 점을 사용합니니다.
```
1. First
2. Second
3. Third
```
1. First
2. Second
3. Third

#### 4-3-1. 순서가 없는 리스트
순서가 없는 리스트는 글머리 기호('*', '+', '-')를 사용합니다.
```
- First
+ Second
* Third
```
- First
+ Second
* Third

### 4-4. 소스코드
#### 4-4-1. 단일 소스코드
```한 줄짜리 소스코드 `<script> var sum = 0; </script>` 자바스크립트 코드입니다.```

한 줄짜리 소스코드 `<script> var sum = 0; </script>` 자바스크립트 코드입니다.
#### 4-4-2. 블록 소스코드

```python
for i in range(1, 10):
  sum += i
```

# 007_깃허브특강1/2

## 참고 사이트
- https://hphk.notion.site/hphk/Git-21-12-21-21-12-22-2c1e3a19b113452e815b237c507704b9

- https://github.com/namjunemy/TIL

- https://github.com/jojoldu

## 깃 설치
```
brew install git
git version
```
## Terminal
### 명령어

open . (open GUI)

​	ls (list)

​	ls -a # all

​	ls -a -l #long

pwd (print working directory)

cd (change directory)

cd FOLDER #(절대경로)

​	cd ../  # .. 위로 올라간다, 상대경로, / 생략가능 

​	cd ~  # cd home folder, ~생략가능

mkdir (make directory)

​	mkdir FOLDER

touch (make file)

​	touch a.txt b.txt c.txt

rm (remove) : 완전 삭제 휴지통 안감

​	rm a.txt #파일 지움

​	rm -r FOLDER #폴더지움



### 단축키

1. - 위, 아래 방향키 : 과거에 작성했던 명령어 조회
	- tab : 폴더/파일 이름 자동 완성
	- ctrl + a : 커서가 맨 앞으로 이동
	- ctrl + e : 커서가 맨 뒤로 이동
	- ctrl + w : 커서가 앞 단어를 삭제
	- ctrl + l : 터미널 화면을 깨끗하게 청소 (스크롤 올리면 과거 내역 조회 가능)
	- ctrl + insert : 복사
	- shift + insert : 붙여넣기
	- command + L: 화면 초기화

## VS 

### 설치 Open in Code quick path

automator app

![img](https://hphk.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Ffc01ba67-0a1b-41ad-88a8-7519e517b513%2FUntitled.png?table=block&id=16ae55d3-7b65-41f2-ab5e-9534ee32b8ac&spaceId=daa2d103-3ecd-4519-8c30-4f55e74c7ef4&width=2000&userId=&cache=v2)

```
	open -n -b "com.microsoft.VSCode" --args "$*"
```
### Setting
in terminal

```
git config --global user.name sen
git config --global user.email koosen@gmail.com
git config --global --list
git init 
ls -a 
```

## typora 설치

 ![img](https://hphk.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F859efb04-c169-4e44-a851-47e29cceb2d0%2FUntitled.png?table=block&id=9320ba06-a1cf-40b5-bf0b-01258b83331a&spaceId=daa2d103-3ecd-4519-8c30-4f55e74c7ef4&width=2000&userId=&cache=v2)

## 마크다운 문법

### 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6



### 목록

순서가 없는 목록 (-*+)

- 목록1
- 목록2
- 목록3
- 과일
	- 들여쓰기
	- 바나나
	- 사과
- 

순서가 있는 목록

1. 목록1
2. 목록2

*엔터치면 목록 빠져나옴*



### 강조 (스타일링)

1. 기울임(이태릭체): *글자* _글자_
2. 굵게(볻드체): **글자** __글자__
3. 취소선: ~~글자~~

### 코드

인라인코드(한줄) ``두개



​	파이썬에서는 ``print('Hello world!')``	

블록코드(여러줄) '''python

```python
for i in r 
hello hello
print (hello) 
```

### 수평선 

---



***

___

### 표

| 동물 | 다리갯수 | 종     |
| ---- | -------- | ------ |
| 사자 | 4        | 포유류 |
|      |          |        |
|      |          |        |

```python
while i is FALSE

```



### 문자열 이스케이브 \

\'print()'








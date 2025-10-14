# CHAPTER: INTRO

---

## 문제 1 - Living dangerously
### 답
`form.txt` 파일을 열어 문구를 쓰고 변경사항 커밋하기.

### 명령어 
```bash
echo "win" >> form.txt
git add form.txt
git commit -m "Add another line"


---

## 문제 2 - Making backups
### 답
`form2_really_final.txt` 파일을 열어서 마지막 줄에 새로운 문장 한 줄을 추가하고 변경사항을 커밋하기.

### 명령어 
```bash
git add form2_really_final.txt
git commit -m "Add another line to form2_really_final.txt"

---


## 문제 3 - Enter the time machine
### 답
`git init` 명령어를 사용해 새로운 Git 저장소를 초기화하고 타임머신을 켜기.

### 명령어
```bash
git init

---

## 문제 4 - The command line
### 답
명령어 이용해서 git 초기화

### 풀이 방법
1. 화면 하단 보라색 터미널에 다음 명령 입력  
   ```bash
   git init


---

## 문제 5 - Your first commit
### 답
`glass` 파일을 커밋하고 수정하기

### 풀이 방법
1. 터미널에 아래 명령 입력
   ```bash
   git add glass
   git commit -m "First commit"

2. glass 파일을 클릭하여 내용을 수정 후 저장

3. 명령 입력
git add glass
git commit -m "Second commit after change"


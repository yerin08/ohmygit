# CHAPTER: INTRO

---

## 문제 1 - Living dangerously

### 풀이 방법 
```bash
echo "win" >> form.txt
git add form.txt
git commit -m "Add another line"


---

## 문제 2 - Making backups
### 
`form2_really_final.txt` 파일을 열어서 마지막 줄에 새로운 문장 한 줄을 추가하고 변경사항을 커밋하기.

### 풀이 방법 
```bash
git add form2_really_final.txt
git commit -m "Add another line to form2_really_final.txt"

---


## 문제 3 - Enter the time machine

### 풀이 방법
```bash
git init

---

## 문제 4 - The command line
### 
명령어 이용해서 git 초기화

### 풀이 방법
1. 화면 하단 보라색 터미널에 다음 명령 입력  
   ```bash
   git init


---

## 문제 5 - Your first commit


### 풀이 방법
1. 터미널에 아래 명령 입력
   ```bash
   git add glass
   git commit -m "First commit"

2. glass 파일을 클릭하여 내용을 수정 후 저장
   아무거나 적기 

3. 명령 입력
git add glass
git commit -m "Second commit after change"

---

## 문제 6 - Working together

### 풀이 방법
1. 교사의 최신 버전을 가져온다.
   ```bash
   git pull
2. students 파일을 열고 이름 추가 

3. 커밋하기
git add students
git commit -m "Addlist"

bash
4. 서버 업로드
git push
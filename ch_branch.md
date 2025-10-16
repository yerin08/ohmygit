# Ch. Branches

## 1. Moving through time

### 1. 마지막 커밋 위치에서 체크아웃 , git checkout 457db0cc

### 2. piggy_bank 파일 수정, echo "This piggy bank belongs to the big sister.It contains 10 coins." > piggy_bank

### 3. little_sister 파일 수정, echo "A young girl with brown, curly hair." > little_sister

### 4. 변경 내용 커밋, git commit -am "commit"

## 2. Make Parallel Commits

### 1. 사건 발생 직전 위치로 이동 git checkout HEAD^2

### 2. 새로운 브랜치 생성 git branch hqppy

### 3. 새로운 브랜치로 이동 git switch happy

### 4. 사건이 발생하지 않도록 파일 수정 및 커밋 git add .; git commit

## 3. Creating branches

### 1. 콘서트 위치로 이동 git checkout

### 2. 콘서트 브랜치 생성 git branch concert

### 3. 생일파티 위치로 이동 git checkout

### 4. 생일파티 브랜치 생성 git branch birthday

## 4. Branches grow with you!

### 1. birthday 브랜치로 이동 git switch birthday

### 2. 내용 수정 후 커밋 git add .; git commit

### 3. concert 브랜치로 이동 git switch concert

### 4. 내용 수정 후 커밋 git add .; git commit

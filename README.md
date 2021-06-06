# Initial commit  

## 배운 목록
- config
  1. git config --global --list
- init
  - 로컬저장소를 .git 숨긴 폴더에 만든다.
- status
  1. git status -s
- add
  1. git add -i
  - *interactive picking 기능이다.*
  2. git add .
  - **news, modifications without deletions 전부 add한다.**
- commit  
--------------------------------------------------------------------
***Working Directory (add)→ Staging Area (commit)→ Local Repository***
--------------------------------------------------------------------  
- log
  1. git log -n 2 
  - 최근 로그 2개를 보여준다.
  2. git log --oneline
- checkout
- diff 
  1. git diff 해시1 해시2
  - 수정 또는 변경한 것을 비교해서 보여준다.
- .gitignore
- commit --amend
  1. git commit --amend -m "변경할 메시지"
  2. git commit --amend --no-edit
  - 커밋 메시지는 건드리지 않고 수정한 것을 덮어 쓰겠다. (해시 바뀜)o
- rebase -i
  1. git rebase -i 해시
  - 입력한 해시와 이전 해시는 포함하지 않고 그 이후 커밋들을 설정한다.
  - reword: commit 메시지 수정
  - squash: commit을 합체
- reset
  - --hard: 전부
  - --mixed: working directory를 제외한 나머지
  - --soft: working directory와 staging area를 제외한 나머지
- checkout -- 파일명
  - staging area에 올라오기 전의 수정된 파일(modified 파일)을 없앰. (잘 안씀)
- branch 
  1. git branch
  2. git branch -d feature
  3. git checkout -b feature  
-------------------------------------------------
**git log --all --decorate --oneline --graph**
-------------------------------------------------  
- merge
- mergetool
- push
- clone
- fetch
- pull
-------------------------------------
### 자기소개
|닉네임|직업|취미|좋아하는 음식|
|:---|:---|---:|---:|
|yeobdoll|학생|코딩|피자|

- rebase 공부하고 있습니다.
-------------------------------------
- rebase
  1. git rebase --continue (계속)
  2. git rebase --abort (취소)
  - --continue와 --abort 옵션은  merge, rebase 등에 활용한다.

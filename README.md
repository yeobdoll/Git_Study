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

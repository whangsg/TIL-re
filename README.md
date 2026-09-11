##TIL


브랜치 정의

##브램치 정의
1. A branch in Git is simply a lightweight movable pointer to one of these commits.
   - 참고: https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshe11
2. Git branches are effectively a pointer to a snapshot of your changes
   - 참고: https://www.atlassian.com/git/tutorials/using-branches


## 브랜치 합치기
  - 이슈에 해당하는 작업을 수행할때, 별도의 브랜치를 만들고 작업한다.
  - 작업이 끝난 후에는, PULL REQUEST를 사용해 내가 작업한 브랜치(`main`, `master`, `development`, `devel`)를 중요 브랜치로 병합

### 명령어
  - git ignore
  - 주의할점 A브랜치를 B브랜치로 합치려고 할 때에는 A브랜치를 체크아웃한 상태에서 `git merge B`를 압력한다.
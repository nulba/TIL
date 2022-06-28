# 20220628 Git/Github 특강


### Repository
* 특정 디렉토리를 보관하는 저장소
---
### git init
* git init 명령어로 로컬 저장소를 생성 (로컬 저장소 초기화)

    **초기화란? 초기에 필요한 설정을 해준다는 뜻**
---
### Commit이란?
* Git에서 특정 버전으로 남기는 것을 커밋(Commit)한다고 표현

    #### 작업 순서를 알아보자
    1. Working Directory
    2. Staging Area
    3. Repository

    #### 필요한 명령어는?
    * 1->2 git add
    * 2->3 git commit
---
### git 명령어
* git status 현재 git으로 관리되고 있는 파일들의 상태를 알 수 있음
* git remote add origin {remote_repo} {Repository}와 연결

    **remote와 add는 명령어가 맞지만, origin은 그저 별칭**
* git push -u origin master Repository에 저장(연동)


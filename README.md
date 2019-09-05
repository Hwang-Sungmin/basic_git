# Git 기초
Git 기초 커맨드

## 기본 커맨드
- 'git init' : 깃으로 시작, .git이 생기면서 관리를 시작.
' .git' 을 제거하면 해당 폴더를 깃으로 사용하지 않음.

- git status
- git add [파일명] : Staging 
- git commit -m "[메세지]" (동사 목적어)

git config --global user.email "hsm511@ajou.ac.kr"
git config --global user.name "Sungmin"

- git log : commit 히스토리

해쉬(함수) : 2^160 : 해쉬를 기반으로해서 데이터 변화를 쉽게 파악 SHA1 


## 추카 커맨드
- git checkout [커밋해쉬] : 특정 commit을 확인
- git checkout master : 최종 위치로 돌아옴
- git restore [파일명] : 추가 내용을 버리고, 최종 커밋 버젼으로 복원


## 원격저장소 관리 (집에서 작업)
- git remote : 원격 저장소의 정보(이름)
- git remote -v : 원격 저장소 정보(이름, 주소)
- git remote add [이름] [주소] : 원격저장소 추가
git remote add root https://github.com/Hwang-Sungmin/basic_git.git
- git push [저장소이름] [브랜치이름] : 원격저장소로 코드 업데이트
- git clone [주소] [프로젝트이름] : 원격저장소 코드 복제
 git pull root master : 원격저장소에서 현재 컴퓨터로 코드 복제


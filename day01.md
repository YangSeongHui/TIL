# Git

# 1. Git 초기 설정
git config --global user.name
git congig --global user.email

+ 설정 확인
git config --global --list

+ 폴더를 저장소로 만드는 명령어 (최소로 1회만 하면 된다.)
git init

+ 파일 만드는 명령어
touch 파일명.확장자명

+ 저장.. (자꾸 까먹고 add하려함)

+ 무대 위로 올린다 (staging area)
git add 파일명.확장자명

+ 변경사항 기록 (commits)
git commit -m "커밋 메세지" 
수정이 안 됨.

+ 변경사항 내역
git log 
또는 간략하게
git log --oneline
---
# 2. Github
**올리기 전에 경로 확인 필수**
+ 일반 폴더를 repository로 바꾸기
git init

+ 무대 위로 올리기
git add .

+ 사진 찍기
git commit -m "커밋 메시지"

+ 파일 상태 확인
git status

+ 변경사항 확인
git log --oneline
---
**github**
+ new repository 만들기 
+ url 복사

**연결하기**
git remote add origin (내 깃허브 주소)

**연결확인**
git remote -v

**오타난 경우**
git remote rm origin
---
**github에 변경사항 백업하기**
git push origin master

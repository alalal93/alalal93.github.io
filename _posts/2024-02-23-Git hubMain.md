---
layout: single
title:  "[GitHub] 자주쓰이는 Git Hub 명령어 "
categories: GitHub
tag: [GitHub]
sidebar:
    nav: "counts"
---

#### git init을 설정하면 해당 폴더에 .git 이라는 파일이 생성됨
git init

#### github 주소와 연결
git remote add origin [github 주소]

#### 브랜치 생성
git branch [브랜치명]

#### 해당 브랜치로 이동
git checkout [브랜치명]

#### 브랜치를 생성하고 해당 브랜치로 바로 이동
git checkout -b [브랜치명]

#### 원하는 브랜치로 이동했는지 확인
git branch

#### 모든 브랜치 확인
git branch -a

#### 파일 및 폴더 add
git add .

#### 커밋
git commit -m "commit message"

#### 원하는 브랜치로 push하여 원격 서버에 전송
git push origin [브랜치명]

#### 브랜치 삭제
git branch -d [브랜치 이름]

#### 현재 브랜치에 다른 브랜치 수정사항 병합
git merge [다른 브랜치 이름]

#### 전체 config 리스트 확인
git config --list

#### Git config 설정하는 방법
git config --global user.name "홍길동"
git config --global user.email "name@naver.com"

#### Git config 삭제하기
git config --unset user.name
git config --unset user.email

#### 삭제해도 계속 남아있는 경우 
global 옵션을 주어 설정했을것 global로 설정된 사용자를 지울 경우 아래와 같이 global 추가<br>
git config --unset --global user.name
git config --unset --global user.email

#### 덮어쓰기
 git push --force



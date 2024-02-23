---
layout: single
title:  "[Github] branch 및 Merge"
categories: GitHub
tag: [GitHub]
sidebar:
    nav: "counts"
---

# 자주 쓰이는 Git 브랜치 관련 명령어 및 작업 흐름

## 1. Branch 개념

### 1-1. Branch란?
협업 시 각자 맡은 작업을 독립적으로 진행하는 작업 단위. 충돌 방지 및 작업의 분리를 위해 사용됨.

### 1-2. Branch 나누기
- `main` 브랜치를 기준으로 개인 브랜치를 생성하여 작업 진행.
- 작업이 완료되면 `main` 브랜치에 합침.

## 2. Branch 생성

```bash
 브랜치 생성             git branch <브랜치명>
 브랜치 리스트 확인      git branch
 브랜치 이동            git checkout <브랜치명>


코드 수정 후 저장
<add>
git add .
git add <파일 이름>

<commit>
git commit -m "커밋 메세지"
git push origin <브랜치명>

<push>
git push origin <branch 이름>

Pull Request 생성 및 작성
 Pull Request

작업 완료 후 GitHub에 접속하여 Pull Request 생성.
코드 리뷰 후 수정이 필요하면 브랜치에서 수정 후 재푸시.


Merge

 서로 다른 브랜치에서의 작업을 하나로 합치는 작업.

 Merge하기
ex) A브랜치 B브랜치 **git marge B** A브랜치에 병합

브랜치 상태 확인   gitbranch  --marged, --no-marged

git checkout main // main에 체크아웃

git merge <브랜치명> //<브랜치명>의 코드를 main에 합침 




충돌 발생 시 충돌 부분을 수동으로 수정 후 다시 커밋.

git checkout [대상브랜치] 대상 브랜치로 이동

git pull origin [대상브랜치] 대상 브랜치의 로컬 갱신

git checkout [대상브랜치] 다시 내 작업 브랜치 이동

git marge [대상브랜치] 병합


Merge 후 브랜치 삭제
 브랜치 삭제 git branch -d <브랜치명>
```

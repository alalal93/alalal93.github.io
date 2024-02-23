---
layout: single
title:  "[jekyll] jekyll 서버실행 및 작동법 "
categories: jekyll
tag: [jekyll]
sidebar:
    nav: "counts"
---
<br>

# Ruby 설치 및 로컬 개발환경 설정 방법

[Ruby window다운로드 페이지](https://rubyinstaller.org/) <br>Ruby Installer를 다운로드하고 설치창에서 "NEXT"를 선택하여 설치

설치 중에 나오는 선택지 cmd창 안에서 <br><br>3번 "MSYS2 and MINGW development toolchain"을 선택 

설치가 완료되면 명령 프롬프트(cmd)를 열고 로컬 개발 환경의 기본 경로를 확인 <br>cd "C:\Users\사용자명\Documents\GitHub\블로그프로젝트"

기본세팅완료!!




# Jekyll 설치 및 서버 실행

##### bundler 설치
gem install bundler

##### Jekyll 설치
gem install bundler jekyll

##### 필요한 라이브러리 설치
bundle install

##### Jekyll 서버 실행
bundle exec jekyll serve

##### 서버 종료 단축키 (Ctrl+C 3번)

##### webrick 추가
bundle add webrick

##### GemFile 파일에 아래 내용 추가
gem 'tzinfo'
gem "'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]"


<br>
<br>

# blog 설정

### 검색 엔진 설정

- **Google Search Console:** [https://search.google.com/search-console](https://search.google.com/search-console)
- **Naver Search Advisor:** [https://searchadvisor.naver.com/](https://searchadvisor.naver.com/)

### Jekyll 설정 사이트

- **Minimal Mistakes:** [https://mmistakes.github.io/minimal-mistakes/](https://mmistakes.github.io/minimal-mistakes/)

### 댓글 설정 (Disqus)

- **Disqus:** [https://disqus.com/](https://disqus.com/)

### Google Analytics 설정

- **Google Analytics:** [https://analytics.google.com/analytics/web/provision/#/provision](https://analytics.google.com/analytics/web/provision/#/provision)

# Git 블로그 만들기

| name | student id |
|:--------|:--------:|
| 송태호 | 20181632 | 

# Build 과정

## Repository 생성  
-  Repository의 이름이 중요! username.github.io 로 해야함.

## jekyll 적용

- Jekyll이란  
Ruby 기반 정적 웹사이트 생성기

- Ruby란  
스크립트 언어의 일종의 프로그래밍 언어

- 정적 웹사이트란  
HTML 등으로 작성된 문서를 그대로 전달해주는 것

### 적용과정

```
gem install jekyll bundler
```
jekyll을 설치

```
bundle install
bundle jekyll serve
```
jekyll 적용

## 테마 적용

### 테마 선택
<http://jekyllthemes.org/>에서 테마를 선택  
[WahtATheme](http://jekyllthemes.org/themes/what-a-theme/ "테마") 를 선택
![whataTheme](https://github.com/SongTaeHo1/SongTaeHo1.github.io/blob/master/%EC%A0%80%EC%9E%A5%EC%86%8C%ED%85%8C%EB%A7%88.PNG?raw=true)  

### 테마 적용 과정
[WahtATheme저장소](https://github.com/thedevslot/WhatATheme "테마") 에서 `git clone`  
post 폴더를 제외한 테마 덮어쓰기  
config.yml파일 내용 수정  
`git commit` 후, 원격저장소로 `git push`로 적용
![blog](https://github.com/SongTaeHo1/SongTaeHo1.github.io/blob/master/%EB%B8%94%EB%A1%9C%EA%B7%B8%EC%A0%81%EC%9A%A9.PNG?raw=true)  

## Post Upload
Markdown 형식을 통해 내용작성  
![post](https://github.com/SongTaeHo1/SongTaeHo1.github.io/blob/master/%ED%8F%AC%EC%8A%A4%ED%8A%B8%20%EC%9E%91%EC%84%B1.PNG?raw=true)  
`git commit` 후, 원격저장소로 `git push`  
![up](https://github.com/SongTaeHo1/SongTaeHo1.github.io/blob/master/%ED%8F%AC%EC%8A%A4%ED%8A%B8%20%EC%97%85%EB%A1%9C%EB%93%9C.PNG?raw=true)  
업로드 완료!
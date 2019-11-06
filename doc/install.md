# 프로젝트 세팅

## 1.nodeJs 설치
    사이트에서 최신버전으로 다운받아 설치
    버전 : v13.0.1.
    
## 2.express 설치
    sudo npm install -g express
   
## 3.프로젝트 생성    
    express {APP_NAME}
    express --ejs english_master
    
    입력 시 "express: command not found."라는 에러가 발생 
    sudo npm install -g express-generator
    > 추가로 설치, 4.0으로 버전이 올라가면서 따로 설치가 필요함
    
    다시 express --ejs english_master 입력 하면 폴더와 함께 패키지 구조가 생성됨
    
## 4.프로젝트 구동
    npm install
    npm start
    DEBUG="english_master:server" npm start
    
    localhost:3000 기본 포트로 접속이 되는지 확인한다.
    Welcome to Express라는 문구가 보여지면 정상
    
    * 참고로 템플릿 엔진에는 Jade, Ejs등을 사용할 수 있는데 익스프레스는 Jade를 기본으로 사용한다.
    Jade는 문법을 다시 봐야 하므로 이질감이 없는 ejs (html형태)로 작업을 진행한다.
    
## 5. github 연동
    git init
    git remote add origin https://github.com/leejaeho114/english_master.git
    git push -u origin master
   
        

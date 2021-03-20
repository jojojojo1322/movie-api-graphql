# GraphQL Study Code from nomad
## setup
  * repository is github : https://github.com/largezero/movieql.git
  * git config user.name "bigzero"
  * git config user.email "bigzero@outlook.kr"
  * modir movieql && cd ./movieql
  * yarn init 으로 초기화 함. ubuntu 에서 "Nosuch file or directory..." yarn 버그 해결 필요
    + https://stackoverflow.com/questions/46013544/yarn-install-command-error-no-such-file-or-directory-install
  * yarn add graphql // graphql 추가

## 2021-03-20(토) init
### Note  
  * under-fetch, over-fetch 를 처리해 준다.
  * Rest 로 되어 있는 http query 를 JSON query 로 바꿔준다.
  * yarn global add nodemon // 소스가 변경될때마다 서버자동 반영
  * package.json 에 "scripts": { "start" : "nodemon" } 추가함. 이제 yarn start 로 기동함.
  * yarn add babel-node --dev // import 문 사용을 위해서 설치
  * yarn global add babel-cli // { "start" : "nodemon --exec babel-node" } 로 실행토록 함. 
  * yarn global add babel-cli --ignore-engines // why?
# React App 2019

React JS Fundamentals Course (2019 Update!)


npm i gh-pages : 깃헙 페이지 도메인에 나타나게 해줌 
오류나서 버전 다운그레이드 ==> npm install -D gh-pages@2.0

오류내용 : The "file" argument must be of type string. Received type undefined.~~~ 

package.json 의 "scripts"에서 하는것. 
// 빌드전에 predeploy 하고, bulid하면 폴더만들고, deploy 실행 

기본적으로 npm run deploy 하면 predeploy부터 실행됨 (이때 이름이 같아야함. deploy, predeploy)

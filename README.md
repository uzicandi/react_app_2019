# React App 2019


npm i gh-pages : 깃헙 페이지 도메인에 나타나게 해줌 
오류나서 버전 다운그레이드 ==> npm install -D gh-pages@2.0

- 오류내용 : The "file" argument must be of type string. Received type undefined.~~~ 

package.json 의 "scripts"에서 하는것. 
// 빌드전에 predeploy 하고, bulid하면 폴더만들고, deploy 실행 

기본적으로 npm run deploy 하면 predeploy부터 실행됨 (이때 이름이 같아야함. deploy, predeploy)


# JavaScript 
JavaScript의 배열은 elements의 리스트.
원래 배열을 수정하는건 mutator method
- isArray, pop, shift, push, unshift, splice, reverse, fill, sort
새로운 값이나 표현을 반환하는건 accessor method
- concat, join, slice, indexOf, lastIndexOf
Iteration Method: (반복 메소드)
- forEach(), map(), filter(), reduce(), find(), findIndex()

==> 배열작성, index작성, 수정 및 반복에 익숙해야함. 

화살표 기능 이해
var example = function() {
}

example();

최신버전의 JS는 화살표 함수를 사용할 수 있다.

var example = () => {
}

example();

두 경우 모두 괄호에는 매개변수가 포함될 수 있음
하나의 매개 변수만 있는 경우 괄호를 생략할 수 있음.

var example = parameter1 => {
}


# React 


<Date : 08.05>
react는 component를 사용해서 html처럼 작성하려는 경우 필요함. 

JavaScript와 HTML 사이의 이런 조합을 jsx 라고 부름 ==> React에서 나온 개념, 

React는 하나의 Component만을 렌더링한다. 
여러개 쓰고 싶으면 하나의 컴포넌트 안에 넣어보기. 

React는 Component를 가져와서 Brower가 이해할 수 있는 평범한 일반 HTML로 만듦
재사용 가능한 component를 만들 수 있다. 즉 component를 계속 반복해서 사용할 수 있단 뜻.

<Food fav="kimchi" /> 
# Component="Food", Property="fav", value="kimchi"

father component 에서 children component로 원하는 많은 props를 보낼 수 있음.

props.fav = {fav}

<Date : 08.06>
배열 설정 후 map을 지정: array를 취하고, 그 내에서 함수 만들 수 있음. 

npm i prop-type 를 하면 prop-type이 잘 맞는지 확인할 수 있는 dependency를 설치함.
-package.json 에서 dependencies 에서 설치됐는지 확인할 수 있고
App.js 에서 import PropTypes from "prop-types"를 넣어줌. 

state는 우리가 동적데이터와 함께 작업할 때 만들어짐. 이런 dynamic Data는 prop는 돕지 않음. 


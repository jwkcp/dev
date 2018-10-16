---
layout: post
title: eslint 사용법
tags: es6 javascript
comments: true
---
      
eslint는 자바스크립트 문법과 권장하는(선호하는) 코딩 스타일을 적용할 수 있게 도와주는 도구다. 이 규칙에 어긋나면 경고와 에러 메시지를 표시해준다. 자신이 원하는 규칙을 커스터마이징 할 수도 있다.
       
---

# 설치
~~~
yarn add eslint
~~~

# 초기설정
~~~
eslint --init
~~~

위와 같이 초기설정을 하면 몇 가지 질문이 나온다. 답변은 자신이 원하는 것을 선택하면 되는데 1번은 대략 아래와 같이 선택하는 경우가 많고, 2번은 standard나 airbnb의 선호도가 갈린다. 3번은 리액트 사용 여부, 4번은 원하는 언어를 선택하면 되는데 아마 이 글을 읽는 분 대부분이 javascript를 사용하고 계신 것일테니 javascript를 택하시면 된다.

1. How would you like to configure ESLint?   
**Use a popular style guide**   
    
2. Which style guide do you want to follow?
**standard** or **airbnb**

3. Do you use React?
**Yes** or **No**


---
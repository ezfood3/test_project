# 참조 사이트

# Node
- express
- Nest.js

# React
- Next.js

# Vue
- Nuxtjs
- MVVM 모델 따름
  - Model view view Model
  - <Model> --- <View Model> --- <View>

  - model: ajax로 가져온 데이터
  - view model: vue.js
  - view: html


# 설치
- 다운로드 방법: (Docker 사용할 때 해볼 것)
- CDN 사용하는 방법 
  - 라이브러리 임포트: <script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
  - view 정의: <div id="app">{{ message }}</div>
  - view 정의 이후: <script></script>

# Vue 문법
1. 변수에 있는 데이터를 html에 표시하기
  - {{ 변수명 }}

2. html내에 text를 표시하기
  - v-text
  - v-html
  - <태그명 v-text='변수명'>테스트</태그명> === <태그명>{{ 변수명 }}</태그명>
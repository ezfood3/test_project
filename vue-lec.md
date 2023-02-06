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

3. 태그의 속성을 표시하기
  - v-bind: <태그명 v-bind:속성명="변수명"></태그명>
    - 속성명: class, id, name, style, href, src, ...
  - 생략 가능하다 v-bind(생략가능)
    - <태그명 :속성명="변수명"></태그명>
    - <태그명 :style="{스타일속성명:변수명}"></태그명>

4. html의 변경사항을 Vue에 적용
  - Vue에 변경사항을 html에 적용
  - 양방향 바인딩
- v-model
- <input v-model="변수명" />
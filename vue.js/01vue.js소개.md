# vue.js

Javascript Framework 언어인 React, Angular, Vue.js 중 하나

Vue.js는 1인 개발자가 만든 언어이며, Angular의 장점(데이터 바인딩)과 React의 장점(가상 돔)을 가지고 있음.

Vue.js는 SPA(Single Page Application) 개발을 위한 프론트엔드 프레임워크.

<hr>

Vue.js는 웹 애플리케이션을 만들기 위한 라이브러리이자 프레임워크이다.

MVVM(Model-View-ViewModel) 패턴을 표방하고 있지만 코어 라이브러리는 ViewModel에 집중되어 있다.
코어 라이브러리와 별개로 부가적인 라이브러리들을 제공해 종합적인 프레임워크를 제공한다.

Vue는 코어 라이브러리를 제외하고도 Router나 Vuex와 같은 라이브러리를 개발/배포하고 있다. 이러한 라이브러리들은 Vue가 단순히 라이브러리에서 그치지 않고 프레임워크로 발돋움 할 수 있게 해주고 있다.

단일 페이지 애플리케이션을 개발할 때 Router와 같은 공식 라이브러리를 사용할 수 있다.

# Vue2, Vue3

Vue2는 오랜 시간 꾸준히 사랑을 받아왔다. 에반유는 프론트엔드 개발의 대규모화 추세에 따라 Vue2를 개편하고 2020년 9월 18일 Vue3 stable 버전을 공개.

# Vue 개발환경 구성 및 시작

### 개발환경 구성

1. Visual studio Code 설치

2. Node.js 설치

### 시작

```
<script src=“vue.js”></script>
```
Vue.js 파일 다운 후 태그에 추가해 사용

```
<script src=https://cdn.jsdelivr.net/npm/vue@2.6.6/dist/vue.js></script>
```
CDN을 이용하는 경우

```
vue.cmd create 프로젝트명
```
Vue/cli를 이용하는 경우

# vue 프로젝트 구조

![image](https://user-images.githubusercontent.com/65898555/178200726-74f1e400-22c2-41b5-b1a2-cc2822690fce.png)

node_modules : npm으로 설치된 패키지 파일들이 모여있는 디렉토리

public : webpack을 통해 관리되지 않는 정적 리소스가 모여 있는 디렉토리

src/assets : 이미지, css, font 등을 관리하는 디렉토리

src/components : Vue 컴포넌트 파일이 모여 있는 디렉토리

App.vue : 최상위 컴포넌트. 실제 컴포넌트 파일

main.js : 가장 먼저 실행되는 자바스크립트 파일로써 vue 인스턴스를 생성하고 index.html 파일과 연결

public/index.html : 개발자가 컴포넌트들을 만들고, 해당 컴포넌트들이 모아지는 곳이다. index.html 내부에 main.js에서 지정하는 컴포넌트들이 마운팅 된다.





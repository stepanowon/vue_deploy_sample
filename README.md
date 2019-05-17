# vue_deploy_sample
-----------------------------
* node + express의 특정 디렉토리에  vue app을 배포하는 예제입니다.
* subdir에 vue 앱을 배포할 때의 설정을 살펴봅니다.

### 예제 구조
* backend 
  - 백엔드 애플리케이션 node + express 
  - /gym 경로에 vue 앱을 배포함.
* routertest 
  - vue-router을 이용한 간단한 예제
  
### 핵심 설정 
* routertest의 vue.config.js 파일을 검토 (publicPath)
* package.json의 scripts를 검토(build -> delete target -> copy output)
* App.vue의 router 객체의 base 속성 검토
  




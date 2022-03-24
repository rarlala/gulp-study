## Gulp
Task runner로 웹서버 운영, 설치에 사용되는 빌드툴  
[공식 사이트](https://gulpjs.com/)

### Gulp란?
- 자바스크립트 라이브러리, 서드파티 앱등을 모으고 축소, 압축을 수행
- 단위 테스트 수행
- LESS / CSS 컴파일링
- 브라우저의 Refresh를 도와줌
- Grunt와 Webpack과 비교되는 툴
> bundle : 소프트웨어 및 일부 하드웨어와 함께 작동하는데 필요한 모든 것을 포함하는 Package, 각각의 모듈들에 대해 의존성 관계를 파악해 하나 또는 여러개의 그룹을 말함

### Task 만들기
```js
gulp.task //반복적으로 수행되야 할 Task들을 모두 작성하여 동작시킴
gulp.src //  어떤 파일을 읽을 것인지 결정
gulp.dest //어디에 저장할 것인지 경로를 결정
gulp.watch //파일의 변경, 업데이트 등을 감지하여 특별한 동작을 수행
```

### 참고
- Gulp를 사용하려면 gulp에 설치된 plugin(플러그인)들이 필요하다.
```js
gulp-webserver  //  웹서버를 구동함
gulp-sass  //  SASS의 컴파일링
gulp-livereload  //  리로드 기능을 수행
```

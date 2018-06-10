## Angular2 공부

####   AngularJS

구글이 만든 단일 페이지 웹 애플리케이션 개발을 위한 자바스크립트 프레임워크

#### Angular

구글이 만든 웹 애플리케이션 플랫폼으로서 다양한 플랫폼으로서 다양한 플랫폼에서

동작할 수 있게 하는 개발 툴과 기능들을 제공



|                             | Anguar 1.x(AngularJS)    | Angular(2,4...)         |
| --------------------------- | ------------------------ | ----------------------- |
| 중첩 스콥($SCOPE, WATCHERS) | O                        | X                       |
| 지시자와 컨트롤러           | O                        | X                       |
| 비즈니스 로직 구현          | CONTROLLER를 구현한 함수 | 타입스크립트 클래스     |
| 자바스크립트 모듈 시스템    | REQUIRE.JS를 통한 구현   | 타입스크립트 모듈시스템 |

#### Angular CLI

- Angular CLI를 설치하기 위해 :

```
npm install -g @angular/cli
```



- Angular 프로젝트를 생성하고 서버에서 실행

```
ng new first-app
ng serve
```



- ng --help에서 ng 커멘드들 확인

```
  add Add support for a library to your project.
  new Creates a new directory and a new Angular app.
  generate Generates and/or modifies files based on a schematic.
  update Updates your application and its dependencies.
  build Builds your app and places it into the output path (dist/ by default).
  serve Builds and serves your app, rebuilding on file changes.
  test Run unit tests in existing project.
  e2e Run e2e tests in existing project.
  lint Lints code in existing project.
  xi18n Extracts i18n messages from source code.
  run Runs Architect targets.
  eject Temporarily disabled. Ejects your app and output the proper webpack configuration and scripts.
  config Get/set configuration values.
  help Help.
  version Outputs Angular CLI version.
  doc Opens the official Angular API documentation for a given keyword.
```


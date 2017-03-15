# `<things-libraries>`
## 1. 개요
#### Vulcanize시에 정확하게 중복된 Lib를 수집해 넣지 않기 위하여 모든 Things Elements용 Third party libraries나 공통 자바스크립트들을 해당 컴포넌트의 리스트에 포함한다.

## 1.1 예시
things-jquery-lib.html파일에는 아래와 같이 코드가 포함하여 사용

```
<script src="../jquery/dist/jquery.min.js"></script>
```

사용 예)
```
  <things-jquery-lib></things-jquery-lib>
```
s
## 1.2 List
|Lib Name       |Lib HTML                                                                   |version   |
|---------------|---------------------------------------------------------------------------|----------|
|c3             |`<link rel="import" href="../things-libraries/things-c3-lib.html">`        |^0.4.11   |
|d3             |`<link rel="import" href="../things-libraries/things-d3-lib.html">`        |^3.5.17   |
|Jquery         |`<link rel="import" href="../things-libraries/things-jquery-lib.html">`    |2 - 3     |
|moment         |`<link rel="import" href="../things-libraries/things-momentjs-lib.html">`  |^2.9.0    |
|jszip          |`<link rel="import" href="../things-libraries/things-jszip-lib.html">`     |^2.2.0    |
|js-xlsx        |`<link rel="import" href="../things-libraries/things-jsxlsx-lib.html">`    |^0.8.0    |
|numeral        |`<link rel="import" href="../things-libraries/things-numeraljs-lib.html">` |^2.0.4    |
|sockjs         |`<link rel="import" href="../things-libraries/things-sockjs-lib.html">`    |^0.3.4    |
|sweetalert     |`<link rel="import" href="../things-libraries/things-sockjs-lib.html">`    |^1.1.3    |
|xxx            |`                                                                     `    |^         ||



## 2. 개발
### 2.1 Polymer-CLI 설치

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### 2.2 Application 수행

```
$ polymer serve
```

### 2.3 Application 빌드

```
$ polymer build
```

아래 명령어로 ` build/bundled`나 ` build/unbundled`에서 서버를 띄울수 있다.

```
$ polymer serve build/bundled
```

### 2.3 Running Tests

```
$ polymer test
```

테스트는 [web-component-tester](https://github.com/Polymer/web-component-tester)에서 설명한데로 설정완료됨.
아래 명령어로 테스트를 수행할 수 있다.
```
$ polymer test
```

# `<things-libraries>`
## 1. 개요
#### Vulcanize시에 정확하게 중복된 Lib를 수집해 넣지 않기 위하여 모든 Things Elements용 자바스크립트를 해당 컴포넌트에 포함한다.
## 1.1 예시
things-jquery-lib.html파일에는 아래와 같이 코드가 포함하여 사용

```
<script src="../jquery/dist/jquery.min.js"></script>
```

사용 예)
```
  <things-jquery-lib></things-jquery-lib>
```
## 1.2 List
|Lib Name|Lib HTML|
|--------|-----------------------------------------|
|Jquery  |`things-jquery-lib.html`|
|XXX|             ||



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

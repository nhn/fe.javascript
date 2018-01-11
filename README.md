FE개발
======================
FE개발랩에서 프로젝트 및 내부 과제를 수행하면서 생산한 기술 산출물로, 공통 모듈 및 컴포넌트와 개발 가이드 등을 포함합니다.<br>
배포되는 산출물은 FE개발랩에서 개발/관리하며 [MIT 라이선스](LICENSE)로 자유롭게 사용할 수 있습니다.<br>
단, FE개발랩의 동의 없이 임의로 수정하여 사용된 코드에 대해서는 유지보수 및 산출물의 품질을 보증을 할 수 없으니,<br>
추가/수정 요청 및 문의, 버그 신고는 [[Issues]](https://github.com/nhnent/fe.javascript/issues) 또는 [[FE개발랩 DL]](mailto:dl_javascript@nhnent.com)을 이용해주세요.<br>

<br>

## 자바스크립트 개발 가이드

자바스크립트 개발 시 필요한 내용들을 가이드 합니다.<br>
본 문서는 코딩컨벤션, 디버깅, 테스트 등과 같이 기본적인 내용부터 의존성 관리 및 압축까지의 개발 전반에 대한 내용을 다룹니다.

> [자바스크립트 개발 가이드](https://github.com/nhnent/fe.javascript/wiki) 바로가기

<br>

## Application

|Name|Description|Documentation|
| ---- | ---- | ---- |
|[Chart](https://github.com/nhnent/tui.chart)|차트|[[API]](https://nhnent.github.io/tui.chart/latest), [[Example]](https://nhnent.github.io/tui.chart/latest/tutorial-example01-01-bar-chart-basic.html), [[Tutorial]](https://github.com/nhnent/tui.chart/wiki/getting-started)|
|[Editor](https://github.com/nhnent/tui.editor)|에디터|[[API]](https://nhnent.github.io/tui.editor/api/latest/), [[Example]](https://nhnent.github.io/tui.editor/), [[Tutorial]](https://github.com/nhnent/tui.editor/wiki/Getting-Started)|
|[Grid](https://github.com/nhnent/tui.grid)|그리드|[[API]](https://nhnent.github.io/tui.grid/api), [[Example]](http://nhnent.github.io/tui.grid/api/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.grid/wiki/Getting-Started)|
 
<br>

## Component

|Name|Description|Documentation|
| ---- | ---- | ---- |
|[Animation](https://github.com/nhnent/tui.animation)|애니메이션 효과 컴포넌트| [[API]](https://nhnent.github.io/tui.animation/latest/), [[Example]](https://nhnent.github.io/tui.animation/latest/tutorial-example01-basic.html)|
|[AutoComplete](https://github.com/nhnent/tui.auto-complete)|검색어 자동완성 컴포넌트|[[API]](http://nhnent.github.io/tui.auto-complete/latest/), [[Example]](http://nhnent.github.io/tui.auto-complete/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.auto-complete/wiki)|
|[ColorPicker](https://github.com/nhnent/tui.color-picker)|컬러 피커 컴포넌트|[[API]](http://nhnent.github.io/tui.color-picker/latest/), [[Example]](http://nhnent.github.io/tui.color-picker/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.color-picker/wiki/Installation)|
|[ContextMenu](https://github.com/nhnent/tui.context-menu)|컨텍스트 메뉴 컴포넌트|[[API]](http://nhnent.github.io/tui.context-menu/latest/), [[Example]](http://nhnent.github.io/tui.context-menu/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.context-menu/wiki/English-Version)|
|[DatePicker](https://github.com/nhnent/tui.date-picker)|데이트 피커 컴포넌트|[[API]](http://nhnent.github.io/tui.date-picker/latest/), [[Example]](https://nhnent.github.io/tui.date-picker/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.date-picker/wiki/Getting-Started)|
|[FileUploader](http://nhnent.github.io/tui.file-uploader)|파일  업로더|[[API]](http://nhnent.github.io/tui.file-uploader/latest/), [[Example]](https://nhnent.github.io/tui.file-uploader/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.file-uploader/wiki/Tutorial)|
|[FloatingLayer](https://github.com/nhnent/tui.floating-layer)|플로팅 레이어 컴포넌트|[[API]](http://nhnent.github.io/tui.floating-layer/latest/), [[Example]](https://nhnent.github.io/tui.floating-layer/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.floating-layer/wiki/English-Version)|
|[GestureReader](https://github.com/nhnent/tui.gesture-reader)|제스처 리더 컴포넌트|[[API]](http://nhnent.github.io/tui.gesture-reader/latest/), [[Example]](http://nhnent.github.io/tui.gesture-reader/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.gesture-reader/wiki/English-Version)|
|[ImageEditor](https://github.com/nhnent/tui.image-editor)|이미지 에디터 컴포넌트|[[API]](http://nhnent.github.io/tui.image-editor/latest/), [[Example]](http://nhnent.github.io/tui.image-editor/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.image-editor/wiki/Basic-Tutorial)|
|[Layout](https://github.com/nhnent/tui.layout)|레이아웃 컴포넌트|[[API]](http://nhnent.github.io/tui.layout/latest/), [[Example]](https://nhnent.github.io/tui.layout/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.layout/wiki/English-Version)|
|[Pagination](https://github.com/nhnent/tui.pagination/)|페이지네이션 컴포넌트|[[API]](https://nhnent.github.io/tui.pagination/latest/), [[Example]](https://nhnent.github.io/tui.pagination/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.pagination/wiki/Getting-Started)|
|[Placeholder](https://github.com/nhnent/tui.placeholder)|플레이스홀더 컴포넌트|[[API]](http://nhnent.github.io/tui.placeholder/latest/), [[Example]](https://nhnent.github.io/tui.placeholder/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.placeholder/wiki/English-Version)|
|[Rolling](https://github.com/nhnent/tui.rolling)|롤링 컴포넌트|[[API]](http://nhnent.github.io/tui.rolling/latest/), [[Example]](http://nhnent.github.io/tui.rolling/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.rolling/wiki/English-Version)|
|[TimePicker](https://github.com/nhnent/tui.time-picker)|타임 피커 컴포넌트|[[API]](https://nhnent.github.io/tui.time-picker/latest/), [[Example]](https://nhnent.github.io/tui.time-picker/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.time-picker/wiki/Getting-Started)|
|[Tree](https://github.com/nhnent/tui.tree)|트리 컴포넌트|[[API]](http://nhnent.github.io/tui.tree/latest/), [[Example]](https://nhnent.github.io/tui.tree/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.tree/wiki/Tutorial)|
|[VirtualKeyboard](https://github.com/nhnent/tui.virtual-keyboard)|가상키보드 컴포넌트|[[API]](http://nhnent.github.io/tui.virtual-keyboard/latest/), [[Example]](https://nhnent.github.io/tui.virtual-keyboard/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.virtual-keyboard/wiki/English-Version)|
|[VirtualScroll](https://github.com/nhnent/tui.virtual-scroll)|가상스크롤 컴포넌트|[[API]](https://nhnent.github.io/tui.virtual-scroll/latest/), [[Example]](https://nhnent.github.io/tui.virtual-scroll/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.virtual-scroll/wiki/getting-started)|

<br>

## Mobile Component

|Name|Description|Documentation|
| ---- | ---- | ---- |
|[AppLoader](https://github.com/nhnent/tui.app-loader)|앱로더 컴포넌트|[[API]](http://nhnent.github.io/tui.app-loader/latest/), [[Example]](http://nhnent.github.io/tui.app-loader/latest/tutorial-example01-button.html), [[Tutorial]](https://github.com/nhnent/tui.app-loader/wiki/TUI-AppLoader-2.0.0-Migration-Guide)|
|[Flicking](https://github.com/nhnent/tui.flicking/)|플리킹 컴포넌트|[[API]](http://nhnent.github.io/tui.flicking/latest/), [[Example]](https://nhnent.github.io/tui.flicking/latest/tutorial-example01-basic.html), [[Tutorial]](https://github.com/nhnent/tui.flicking/wiki/English-Version)|

<br>

## CodeSnippet

|Name|Category|Description|Documentation|
| ---- | ---- | ---- | ---- |
|[CodeSnippet](https://github.com/nhnent/tui.code-snippet/)||코드 스니펫<br>(자주 사용되는 코드 모음)|[[API]](https://nhnent.github.io/tui.code-snippet/latest/index.html), [[Tutorial]](https://github.com/nhnent/fe.javascript/wiki/Toast-UI-CodeSnippet)|
| |browser.js|브라우저 검출하는 모듈||
| |collection.js|콜렉션 관련 모듈||
| |customEvent.js|커스텀이벤트 모듈||
| |defineClass.js|클래스 관련 모듈||
| |defineNamespace.js|네임스페이스 관련 모듈||
| |enum.js|상수 관련 모듈||
| |exMap.js|맵 관련 모듈||
| |func.js|함수 관련 모듈||
| |hashMap.js|해시맵 관련 모듈|deprecate 예정|
| |inheritance.js|간단한 상속 모듈||
| |object.js|객체 관련 모듈||
| |string.js|문자열 관련 모듈||
| |type.js|타입 체크 모듈||
| |window.js|윈도우 객체 관련 모듈||

## Library

|Name|Description| Documentation |
| ---- | ---- | ---- |
|[Dom](https://github.com/nhnent/tui.dom)|DOM 유틸<br>(DOM 관련 클래스 지정 및 이벤트 바인딩 함수 모음)|[[API]](http://nhnent.github.io/tui.dom/latest/)|
|[TUI JSDoc Template](https://github.com/nhnent/tui.jsdoc-template)|JSDoc Template (JS API 문서화 템플릿) | [[Demo]](https://nhnent.github.io/tui.jsdoc-template/latest/), [[Npm]](https://www.npmjs.com/package/tui-jsdoc-template)|

## License

[MIT 라이선스](LICENSE)로 자유롭게 사용할 수 있습니다.

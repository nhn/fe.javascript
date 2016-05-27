FE개발
======================
FE개발팀에서 프로젝트 및 내부 과제를 수행하면서 생산한 기술 산출물로, 공통 모듈 및 컴포넌트와 개발 가이드 등을 포함합니다.<br>
배포되는 산출물은 FE개발팀에서 개발/관리하며 [MIT 라이선스](LICENSE)로 자유롭게 사용할 수 있습니다.<br>
단, FE개발팀의 동의 없이 임의로 수정하여 사용된 코드에 대해서는 유지보수 및 산출물의 품질을 보증을 할 수 없으니,<br>
추가/수정 요청 및 문의, 버그 신고는 [[Issues]](https://github.com/nhnent/fe.javascript/issues) 또는 [[FE개발팀 DL]](mailto:dl_javascript@nhnent.com)을 이용해주세요.<br>

<br>
## 자바스크립트 개발 가이드
자바스크립트 개발 시 필요한 내용들을 가이드 합니다.<br>
본 문서는 코딩컨벤션, 디버깅, 테스트 등과 같이 기본적인 내용부터 의존성 관리 및 압축까지의 개발 전반에 대한 내용을 다룹니다.
> [자바스크립트 개발 가이드](https://github.com/nhnent/fe.javascript/wiki) 바로가기

<br>
## Application
|Name|Description|Documentation|
| ---- | ---- | ---- |
|[Grid](https://github.com/nhnent/tui.grid)|그리드|[[API]](https://nhnent.github.io/tui.grid/api), [[Sample]](https://nhnent.github.io/tui.grid/api/tutorial-sample1.html),  [[Download]](https://github.com/nhnent/tui.grid/tree/master/dist), [[Tutorial]](https://github.com/nhnent/tui.grid/wiki/설치-및-사용방법)|
|[Chart](https://github.com/nhnent/tui.chart)|차트|[[API]](https://nhnent.github.io/tui.chart/latest), [[Sample]](http://nhnent.github.io/tui.chart/latest/tutorial.html),  [[Download]](https://github.com/nhnent/tui.chart), [[Tutorial]](https://github.com/nhnent/tui.chart/wiki/tutorial)|
 
<br>
## Component
|Name|Description|Documentation|
| ---- | ---- | ---- |
|[AutoComplete](https://github.com/nhnent/tui.component.auto-complete)|검색어 자동완성 컴포넌트|[[API]](https://nhnent.github.io/tui.component.auto-complete/latest/), [[Sample]](https://nhnent.github.io/tui.component.auto-complete/latest/tutorial-sample1.html),  [[Download]](https://github.com/nhnent/tui.component.auto-complete), [[Tutorial]](https://github.com/nhnent/tui.component.auto-complete/wiki/Auto-Complete-Tutorial)|
|[Calendar](https://github.com/nhnent/tui.component.calendar/)|캘린더 컴포넌트|[[API]](https://nhnent.github.io/tui.component.calendar/latest/), [[Sample]](https://nhnent.github.io/tui.component.calendar/latest/tutorial-sample1.html), [[Download]](https://github.com/nhnent/tui.component.calendar/), [[Tutorial]](https://github.com/nhnent/tui.component.calendar/wiki/Calendar-Tutorial)|
|[ContextMenu](https://github.com/nhnent/tui.component.contextmenu/)|컨텍스트메뉴 컴포넌트|[[API]](https://nhnent.github.io/tui.component.contextmenu/latest/), [[Sample]](https://nhnent.github.io/tui.component.contextmenu/latest/tutorial-default.html), [[Download]](https://github.com/nhnent/tui.component.contextmenu/), [[Tutorial]](https://github.com/nhnent/tui.component.contextmenu/wiki/ContextMenu-Tutorial)|
|[DatePicker](https://github.com/nhnent/tui.component.date-picker/)|데이트 피커 컴포넌트|[[API]](https://nhnent.github.io/tui.component.date-picker/latest), [[Sample]](https://nhnent.github.io/tui.component.date-picker/latest/tutorial-sample1.html), [[Download]](https://github.com/nhnent/tui.component.date-picker/), [[Tutorial]](https://github.com/nhnent/tui.component.date-picker/wiki/date-picker-컴포넌트-적용방법)|
|[Effects](https://github.com/nhnent/tui.component.effects/)|이펙트  컴포넌트|[[API]](https://nhnent.github.io/tui.component.effects/latest), [[Sample]](https://nhnent.github.io/tui.component.effects/latest/tutorial-sample1.html), [[Download]](https://github.com/nhnent/tui.component.effects/), [[Tutorial]](https://github.com/nhnent/tui.component.effects/wiki/Effects-Tutorial)|
|[FileUploader](https://github.com/nhnent/tui.component.file-uploader)|파일 업로더|[[API]](http://nhnent.github.io/tui.component.file-uploader/latest/),  [[Download]](https://github.com/nhnent/tui.component.file-uploader), [[Tutorial]](https://github.com/nhnent/tui.component.file-uploader/wiki/File-Uploader-Tutorial)|
|[FloatingLayer](https://github.com/nhnent/tui.component.floatinglayer/)|플로팅레이어 컴포넌트|[[API]](https://nhnent.github.io/tui.component.floatinglayer/latest/), [[Sample]](https://nhnent.github.io/tui.component.floatinglayer/latest/tutorial-default.html), [[Download]](https://github.com/nhnent/tui.component.floatinglayer/), [[Tutorial]](https://github.com/nhnent/tui.component.floatinglayer/wiki/FloatingLayer-Tutorial)|
|[GestureReader](https://github.com/nhnent/tui.component.gesture-reader/)|제스처 리더 컴포넌트|[[API]](https://nhnent.github.io/tui.component.gesture-reader/latest/), [[Sample]](https://nhnent.github.io/tui.component.gesture-reader/latest/tutorial-sample1.html),  [[Download]](https://github.com/nhnent/tui.component.gesture-reader), [[Tutorial]](https://github.com/nhnent/tui.component.gesture-reader/wiki/Gesture-Reader-Tutorial)|
|[ImageEditor](https://github.com/nhnent/tui.component.image-editor)|이미지 에디터 컴포넌트|[[API]](http://nhnent.github.io/tui.component.image-editor/latest/), [[Sample]](http://nhnent.github.io/tui.component.image-editor/latest/tutorial-basic.html),  [[Download]](https://github.com/nhnent/tui.component.image-editor#downloadinstall), [[Tutorial]](https://github.com/nhnent/tui.component.image-editor/wiki/Tutorial)|
|[InfiniteScroll](https://github.com/nhnent/tui.component.infinite-scroll/)|무한 스크롤 컴포넌트|[[API]](https://nhnent.github.io/tui.component.infinite-scroll/latest/), [[Sample]](https://nhnent.github.io/tui.component.infinite-scroll/latest/tutorial-sample1.html),  [[Download]](https://github.com/nhnent/tui.component.infinite-scroll/), [[Tutorial]](https://github.com/nhnent/tui.component.infinite-scroll/wiki/InfiniteScroll-Tutorial)|
|[Layout](https://github.com/nhnent/tui.component.layout)|레이아웃 컴포넌트|[[API]](http://nhnent.github.io/tui.component.layout/latest/), [[Sample]](http://nhnent.github.io/tui.component.layout/latest/tutorial-auto.html),  [[Download]](https://github.com/nhnent/tui.component.layout), [[Tutorial]](https://github.com/nhnent/tui.component.layout/wiki/Layout-Tutorial)|
|[Pagination](https://github.com/nhnent/tui.component.pagination/)|페이지네이션 컴포넌트|[[API]](https://nhnent.github.io/tui.component.pagination/latest/), [[Sample]](https://nhnent.github.io/tui.component.pagination/latest/tutorial-sample1.html),  [[Download]](https://github.com/nhnent/tui.component.pagination/), [[Tutorial]](https://github.com/nhnent/tui.component.pagination/wiki/Pagination-Tutorial)|
|[Rolling](https://github.com/nhnent/tui.component.rolling/)|롤링 컴포넌트|[[API]](https://nhnent.github.io/tui.component.rolling/latest/), [[Sample]](https://nhnent.github.io/tui.component.rolling/latest/tutorial-sample1.html), [[Download]](https://github.com/nhnent/tui.component.rolling), [[Tutorial]](https://github.com/nhnent/tui.component.rolling/wiki/Rolling-Tutorial)|
|[ScrollEnd](https://github.com/nhnent/tui.component.scrollend)|스크롤엔드|[[API]](http://nhnent.github.io/tui.component.scrollend/latest/),  [[Download]](https://github.com/nhnent/tui.component.scrollend), [[Sample]](https://nhnent.github.io/tui.component.scrollend/latest/tutorial-sample1.html),  [[Tutorial]](https://github.com/nhnent/tui.component.scrollend/wiki/how-to-use-Scrollend)|
|[SimpleGrid](https://github.com/nhnent/tui.component.simple-grid/)|심플 그리드 컴포넌트|[[API]](https://nhnent.github.io/tui.component.simple-grid/latest/), [[Sample]](https://nhnent.github.io/tui.component.simple-grid/latest/tutorial-sample1.html),  [[Download]](https://github.com/nhnent/tui.component.simple-grid), [[Tutorial]](https://github.com/nhnent/tui.component.simple-grid/wiki/SimpleGrid-Tutorial)|
|[Tree](https://github.com/nhnent/tui.component.tree/)|트리 컴포넌트|[[API]](https://nhnent.github.io/tui.component.tree/latest/), [[Sample]](https://nhnent.github.io/tui.component.tree/latest/tutorial.html),  [[Download]](https://github.com/nhnent/tui.component.tree), [[Tutorial]](https://github.com/nhnent/tui.component.tree/wiki/Tree-Tutorial)|
|[VirtualKeyboard](https://github.com/nhnent/tui.component.virtual-keyboard/)|가상키보드 컴포넌트|[[API]](https://nhnent.github.io/tui.component.virtual-keyboard/latest/), [[Sample]](https://nhnent.github.io/tui.component.virtual-keyboard/latest/tutorial-mobile.html),  [[Download]](https://github.com/nhnent/tui.component.virtual-keyboard), [[Tutorial]](https://github.com/nhnent/tui.component.virtual-keyboard/wiki/VirtualKeyboard-Tutorial)|

<br>
## Mobile Component
|Name|Description|Documentation|
| ---- | ---- | ---- |
|[AppLoader](https://github.com/nhnent/tui.component.m-app-loader)|앱로더 컴포넌트|[[API]](https://nhnent.github.io/tui.component.m-app-loader/latest/), [[Sample]](https://nhnent.github.io/tui.component.m-app-loader/latest/tutorial-tutorial.html),  [[Download]](https://github.com/nhnent/tui.component.m-app-loader), [[Tutorial]](https://github.com/nhnent/tui.component.m-app-loader/wiki/AppLoader-Tutorial)|
|[Flicking](https://github.com/nhnent/tui.component.m-flicking/)|플리킹 컴포넌트|[[API]](https://nhnent.github.io/tui.component.m-flicking/latest/), [[Sample]](https://nhnent.github.io/tui.component.m-flicking/latest/tutorial-sample1.html),  [[Download]](https://github.com/nhnent/tui.component.m-flicking/), [[Tutorial]](https://github.com/nhnent/tui.component.m-flicking/wiki/Flicking-Tutorial)|

<br>
## CodeSnippet
|Name|Category|Description|Documentation|
| ---- | ---- | ---- | ---- |
|[CodeSnippet](https://github.com/nhnent/tui.code-snippet/)||코드 스니펫<br>(자주 사용되는 코드 모음)|[[API]](https://nhnent.github.io/tui.code-snippet/latest/index.html), [[Download]](https://github.com/nhnent/tui.code-snippet/), [[Tutorial]](https://github.com/nhnent/fe.javascript/wiki/FE-CodeSnippet)|
||browser.js|브라우저 검출하는 모듈||
||collection.js|콜렉션 관련 모듈||
||customEvent.js|커스텀이벤트 모듈||
||defineClass.js|클래스 관련 모듈||
||defineNamespace.js|네임스페이스 관련 모듈||
||enum.js|상수 관련 모듈||
||exMap.js|맵 관련 모듈||
||func.js|함수 관련 모듈||
||hashMap.js|해시맵 관련 모듈|deprecate 예정|
||inheritance.js|간단한 상속 모듈||
||object.js|객체 관련 모듈||
||string.js|문자열 관련 모듈||
||type.js|타입 체크 모듈||
||window.js|윈도우 객체 관련 모듈||

## Domutil
|Name|Description|Documentation|
| ---- | ---- | ---- |
|[domutil](https://github.com/nhnent/tui.domutil/)|DOM 유틸<br>(DOM 관련 클래스 지정 및 이벤트 바인딩 함수 모음)|[[API]](https://nhnent.github.io/tui.domutil/latest/index.html), [[Download]](https://github.com/nhnent/tui.domutil/)|
## License
[MIT 라이선스](LICENSE)로 자유롭게 사용할 수 있습니다.

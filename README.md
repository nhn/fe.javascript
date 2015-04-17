FE개발
======================
FE개발팀에서 프로젝트 및 내부 과제를 수행하면서 생산한 기술 산출물로, 공통 모듈 및 컴포넌트와 개발 가이드 등을 포함합니다.<br>
배포되는 산출물은 FE개발팀에서 개발/관리하며, 모든 산출물은 사내에 한하여 자유롭게 사용할 수 있습니다.<br>
FE개발팀의 동의 없이 임의로 수정하여 사용된 코드에 대해서는 유지보스 관리 및 산출물의 품질을 보증을 할 수 없습니다.<br>
추가/수정 요청, 문의 및 버그 신고는 [[FE개발팀 DL]](mailto:e0242@nhnent.com)을 이용해주세요.<br>

<br>
## 자바스크립트 개발 가이드
자바스크립트 개발 시 필요한 내용들을 가이드 합니다.<br>
본 문서는 코딩컨벤션, 디버깅, 테스트 등과 같이 기본적인 내용부터 의존성 관리 및 압축까지의 개발 전반에 대한 내용을 다룹니다.
> [자바스크립트 개발 가이드](https://github.nhnent.com/fe/javascript/wiki) 바로가기

<br>
## Component
|Name|Description|Documentation|
| ---- | ---- | ---- |
|[AutoComplete](https://github.nhnent.com/fe/component-auto-complete/)|검색어 자동완성 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-auto-complete/1.0.0/), [[Sample]](https://github.nhnent.com/pages/fe/component-auto-complete/1.0.0/tutorial-sample1.html),  [[Download]](https://github.nhnent.com/fe/component-auto-complete), [[Tutorial]](https://github.nhnent.com/fe/component-auto-complete/wiki/%EC%9E%90%EB%8F%99%EC%99%84%EC%84%B1-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%EB%B0%A9%EB%B2%95)|
|[Calendar](https://github.nhnent.com/fe/component-calendar/)|캘린더 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-calendar/1.0.0/), [[Sample]](https://github.nhnent.com/pages/fe/component-calendar/1.0.0/tutorial-default.html), [[Download]](https://github.nhnent.com/fe/component-calendar/), [[Tutorial]](https://github.nhnent.com/fe/component-calendar/wiki/%EB%8B%AC%EB%A0%A5-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%EB%B0%A9%EB%B2%95)|
|[InfiniteScroll](https://github.nhnent.com/fe/component-infinite-scroll/)|무한 스크롤 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-infinite-scroll/1.0.1/), [[Sample]](https://github.nhnent.com/pages/fe/component-infinite-scroll/1.0.1/tutorial-sample1.html),  [[Download]](https://github.nhnent.com/fe/component-infinite-scroll/), [[Tutorial]](https://github.nhnent.com/fe/component-infinite-scroll/wiki/%EB%AC%B4%ED%95%9C%EC%8A%A4%ED%81%AC%EB%A1%A4-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%EB%B0%A9%EB%B2%95)|
|[MouseGesture](https://github.nhnent.com/fe/component-mouse-gesture/)|마우스제스쳐 컴포넌트|[[API]](http://github.nhnent.com/pages/fe/component-mouse-gesture/1.0.0/), [[Sample]](http://github.nhnent.com/pages/fe/component-mouse-gesture/1.0.0/tutorial-sample_default.html),  [[Download]](https://github.nhnent.com/fe/component-mouse-gesture), [[Tutorial]](https://github.nhnent.com/fe/component-mouse-gesture/wiki/%EB%A7%88%EC%9A%B0%EC%8A%A4%EC%A0%9C%EC%8A%A4%EC%B3%90-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0)|
|[Pagination](https://github.nhnent.com/fe/component-pagination/)|페이지네이션 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-pagination/1.0.0/), [[Sample]](https://github.nhnent.com/pages/fe/component-pagination/1.0.0/tutorial-sample1.html),  [[Download]](https://github.nhnent.com/fe/component-pagination/), [[Tutorial]](https://github.nhnent.com/fe/component-pagination/wiki/%ED%8E%98%EC%9D%B4%EC%A7%80%EB%84%A4%EC%9D%B4%EC%85%98-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%EB%B0%A9%EB%B2%95)|
|[Rolling](https://github.nhnent.com/fe/component-rolling/)|롤링 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-rolling/1.0.0/), [[Sample]](https://github.nhnent.com/pages/fe/component-rolling/1.0.0/tutorial-index_default_nocircle.html), [[Download]](https://github.nhnent.com/fe/component-rolling), [[Tutorial]](https://github.nhnent.com/fe/component-rolling/wiki/%EB%A1%A4%EB%A7%81-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%EB%B0%A9%EB%B2%95)|
|[SimpleGrid](https://github.nhnent.com/fe/component-simple-grid/)|심플그리드 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-simple-grid/1.0.0/), [[Sample]](https://github.nhnent.com/pages/fe/component-simple-grid/1.0.0/tutorial-sample1.html),  [[Download]](https://github.nhnent.com/fe/component-simple-grid), [[Tutorial]](https://github.nhnent.com/fe/component-simple-grid/wiki/%EC%8B%AC%ED%94%8C%EA%B7%B8%EB%A6%AC%EB%93%9C-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%EB%B0%A9%EB%B2%95)|
|[Tree](https://github.nhnent.com/fe/component-tree/)|트리 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-tree/1.0.0/), [[Sample]](https://github.nhnent.com/pages/fe/component-tree/1.0.0/tutorial-index_default.html),  [[Download]](https://github.nhnent.com/fe/component-tree), [[Tutorial]](https://github.nhnent.com/fe/component-tree/wiki/%ED%8A%B8%EB%A6%AC-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%EB%B0%A9%EB%B2%95)|
|[VirtualKeyboard](https://github.nhnent.com/fe/component-virtual-keyboard/)|가상키보드 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-virtual-keyboard/1.0.0/), [[Sample]](https://github.nhnent.com/pages/fe/component-virtual-keyboard/1.0.0/tutorial-mobile.html),  [[Download]](https://github.nhnent.com/fe/component-virtual-keyboard), [[Tutorial]](https://github.nhnent.com/fe/component-virtual-keyboard/wiki/%EA%B0%80%EC%83%81%ED%82%A4%EB%B3%B4%EB%93%9C-%EC%BB%B4%ED%8F%AC%EB%84%8C%ED%8A%B8-%EC%A0%81%EC%9A%A9%EB%B0%A9%EB%B2%95)|
|[AppLoader](https://github.nhnent.com/fe/component-app-loader)|앱로더 컴포넌트|[[API]](https://github.nhnent.com/pages/fe/component-app-loader/1.0.0/), [[Sample]](https://github.nhnent.com/pages/fe/component-app-loader/1.0.0/tutorial-tutorial.html),  [[Download]](https://github.nhnent.com/fe/component-app-loader)|

<br>
## CodeSnippet
|Name|Category|Description|Documentation|
| ---- | ---- | ---- | ---- |
|[CodeSnippet](https://github.nhnent.com/fe/code-snippet/)||코드 스니펫<br>(자주 사용되는 코드 모음)|[[API]](https://github.nhnent.com/pages/fe/code-snippet/1.0.0/index.html), [[Download]](https://github.nhnent.com/fe/code-snippet/), [[Tutorial]](https://github.nhnent.com/fe/javascript/wiki/FE-CodeSnippet)|
||browser.js|브라우저 검출하는 모듈||
||collection.js|콜렉션 관련 모듈||
||customEvent.js|커스텀이벤트 모듈||
||defineClass.js|클래스 관련 모듈||
||enum.js|상수 관련 모듈||
||func.js|함수 관련 모듈||
||hashMap.js|해시맵 관련 모듈||
||inheritance.js|간단한 상속 모듈||
||object.js|객체 관련 모듈||
||string.js|문자열 관련 모듈||
||type.js|타입 체크 모듈||
||window.js|윈도우 객체 관련 모듈||




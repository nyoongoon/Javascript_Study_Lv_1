# Javascript_Study_Lv_1
단국대학교 개발자 커뮤니티에서 진행하는 자바스크립트 스터디 레벨 1단계 저장소입니다.
<br/><br/><br/>

# 프론트엔드 스터디 1주
## 목적 
- 1.자바스크립트에 대해 이해하기
- 2.웹 브라우저에 대해 이해하기
- 3.웹 서버에 대해 이해하기
- 4.배포하기 
<br/>

## 이론 - 웹 기본 이론
### 브라우저 HTTP Protocol, HTML등의 연관성에 대해 조사(5문장)
### HTTP란?
- **HTTP는** HTML문서와 같은 리소스들을 가져올 수 있도록 해주는 프로토콜. 웹에서 이루어지는 모든 데이터 교환의 기초, 수신자 측(브라우저)에 의해 요청이 초기화 되는 클라이언트-서버 프로토콜. 
### 브라우저란?
- **브라우저는** 웹페이지를 표시하기 위해 HTTP 요청을 서버로 보내고 받은 응답 파일을 구문 분석하여 실행해야할 스크립트, 하위 리소스(추가 정보)를 위한 요청을 추가로 가져온다. 그 후 브라우저는 완전한 문서를 만들기 위해 리소스 들을 혼합한다. 실행된 스크립트는 이후 단계에서 더 많은 리소스를 가져와 추가적으로 웹 페이지를 갱신할 수 있다. 
### HTML이란?
- **HTML은** 웹 콘텐츠의 의미와 구조를 정의하기 위해 **마크업**을 사용. HTMl은 여러 컨텐츠들을 특정한 방식으로 보이거나 동작하도록 하는 일련의 요소(element)로 이루어져 있음 (요소는 여는태그부터 닫는태그까지) 
### **DOM(Document Object Model)이란?** 
- HTML이나 XML문서를 나타내는 API 
- 문서의 구조화된 표현을 제공하며 프로그래밍 언어가 DOM구조에 접근할 수 있는 방법을 제공하여 그들이 문서를 변경할 수 있게 돕는다. 
- 노드, 트리구조. 자바스크립트로 제어 가능. 
- 웹 페이지의 객체 지향 표현. 
- 페이지 콘텐츠는 DOM에 저장되고 자바스크립트를 통해 접근하거나 조작할 수 있다. 
- API (web or XML page) = DOM + JS (scripting language)
- document는 window의 document(html문서)
- document object model(돔객체)는 html과 javascript를 연결해주는 통역사
### BOM(Browser Object Model)이란? 
- 브라우저 자체를 다루기 위한 API
ex) window.~ 으로 제어하는 것들 
- 웹브라우저의 창이나 프레임을 추상화해서 프로그래밍적으로 제어할 수 있도록 제공하는 수단.
- BOM은 전역객체인 Window의 프로퍼티와 메소드들을 통해서 제어할 수 있음 -> Window객체의 프로퍼티와 메소드의 사용법을 배우는 것이 BOM을 배우는 것으로 이해
-  window객체를 통하여 -> location, document, navigator, history, screen 등  객체(프로퍼티)에 접근 가능!
### CSS란?
- 사용자에게 문서를 표시하는 방법을 지정하는 언어
- 우선순위로 크게 외부스타일 -> 내부스타일 -> 인라인 스타일 순서.
- 1. 속성값 뒤에 !important를 붙인 속성)(;(세미콜론)안쪽에 작성되어야함)
- 2. 태그에 직접적으로 style=""방식(인라인 방식)
- 3. HTML문서에\<styel\>\</style\> 안에 지정한 방식(내부 스티알 방식)
- 4. #id로 지정한 속성
- 5. 클래스, :추상클래스로 지정한 속성
- 6. 태그이름으로 지정한 속성
- 7. 상위 객체에 의해 상속된 속성(외부 스타일 방식)

### javascript란?
- 웹페이지를 동적으로 변경해주는 언어. 
- 자바스크립트로 작성한 프로그램을 스크립트라고 부름. 스크립트는 웹페이지의 HTML안에 작성할 수 있는데 웹페이지를 불러올 때 스크립트가 자동 실행 됨.

### ECMAscript란? 
- 브라우저간의 호환성을 위해 A-262 기술 규격에 따라 정의하고 있는 표준화 된 스크립트 프로그래밍 언어를 말함. 
- 자바스크립트는 ECMAscript의 표준을 가장 잘 구현한 언어

### git
- 컴퓨터 파일의 변경사항을 추적하고 여러 명의 사용자들 간에 해당 파일들의 작업을 조율하기 위한 분산 버전 관리 시스템

### 깃허브
- 깃허브는 깃 저장소 호스팅을 지원하는 웹 서비스.

### 풀 리퀘스트 
- 프로젝트 관리자가 소스코드 변경사항을 풀(pull)하는 기여자 요청이므로 "풀 리퀘스트"라는 이름이 붙임.
- 개발자는 새 변경사항을 유지보수자에게 알리기 위해 풀 리퀘스트를 생성한다. 댓글 스레드가 개별 풀 리퀘스트에 연결된다. 이를 통해 코드 변경에 대한 집중화된 토론이 가능해진다. 제출된 풀 리퀘스트들은 저장소 접근이 가능한 누구나 볼 수 있다. 풀 리퀘스트는 유지보수자들에 의해 수락되거나 거절될 수 있다. 풀 리퀘스트가 검토되고 승인되면 저장소에 병합된다.


# 2주차

## 번들이란 무엇인가?
- 여러개의 파일 중에 종속성이 존재하는 파일을 하나의 파일로 묶어 패키징을 시키는 것.
## 번들을 하는 이유는?
-> 각각의 모듈들에 대해 의존성 관계를 파악하기 위해. 
- 파일을 묶어서 요청응답을 받기 떄문에  네트웍 코스트가 줄어든다. 
- 난독화, 압축, 최적화 작업 지원
## 모듈 시스템에 대해 알아보기

### CommonJS
- js를 브라우저 뿐만 아니라 서버사이드에서도 사용하려고 했던 그룹. 
- 모듈화는 다음의 조건을 만족해야한다.
- 1 스코프 : 모든 모듈은 자식만의 독립적인 실행 영역이 있어야한다.
- 2 정의 : 모듈 정의는 export 객체를 이용한다.
- 3 사용 : 모듈 사용은 require함수를 이용한다.
### AMD
- CommonJS와 달리 브라우저 내에서의 실행에 중점을 둠.
- 필요한 모듈을 네트워크를 이용해 내려받아야하는 브라우저 환경에서도 모듈을 사용할 수 있도록 했음. 
- 필요한 파일이 모두 로컬 디스크에 있어 바로 불러 쓸 수 있는 상황, 즉 서버사이드에서는 CommonJS 명세가 AMD 방식보다 간결하다. 반면 필요한 파일을 네트워크를 통해 내려받아야 하는 브라우저와 같은 환경에서는 AMD가 CommonJS보다 더 유연한 방법을 제공한다.
### RequireJS
- RequireJS는 인지도 높은 JavaScript 로더 중 하나로, AMD 명세를 충실히 구현했을 뿐만 아니라 CommonJS 스타일의 포맷도 지원한다. RequireJS의 가장 큰 장점은 깔끔한 API와 문서를 갖추고 있고, 사용법 또한 쉽다는 점이다. 그리고 사이즈도 작다.
### ESM
- ECMAScript 에서 지원하는 자바스크립트 공식 모듈 시스템. 아직 브라우저에서 import와 export를 지원하지 않아 번들러를 함께 사용해야함. 
### 브라우저 모듈
- ? 
## 번들러 종류
### parcel
- 설정이 필요없고 매우 빠른 번들러. 
- 캐싱을 사용하여 빌드속도가 더 빠름.
- 설정 없이 코드 분할 지원
- HOT 모듈 교체 : 코드가 변경되면 이를 감지하고 브라우저에 최신 코드를 반영.
- 자동변환 : 많은 트랜스파일러를 내장 지원하고 있기 때문에 모듈 안의 설정파일을 발견하면 자동 변환 실행함.
### webpack
- 엔트리: 의존성 그래프의 시작점을 웹팩에서는 엔트리라고 한다. 웹팩은 엔트리를 통해서 필요한 모듈을 로딩하고 하나의 파일로 묶는다. 
- 아웃풋: 엔트리에 설저안 자바스크립트 파일을 시작으로 의존되어 있는 모든 모듈을 하나로 묶은 것. 
- 로더 : 비자바스크립트 파일을 뤱팩이 이해야하게끔 변경해주는 역할. test와 use키로 구성된 객체로 설정할 수 있음. test에 로딩할 파일을 지정하고 use에 적용할 로더를 설정. 
- 플러그인 : 번들된 자바스크립트를 난독화 하거나 특정 텍스트를 추출하는 용도. 
### rollup
- 각 모듈을 함수로 감싸 평가하는 웹팩과 달리 롤업은 코드들을 동일한 수준으로 올림. (호이스팅) 그 후 한 번에 번들링을 진행하는데 "한번에" 하기 때문에 속도는 웹팩보다 빠르며, 번들링 된 결과물도 가벼움. 
### vite
- Vue3에 적용되기 위해서 만들어진 빌드 툴. 번들하는 과정을 없애면서 시간을 단축, 
- Modern 브라우저에서 사용할 수 있는 Script Tag의 type=module을 사용함으로써 가능
- CLI를 제공. 

## 코드 리팩토링 
1. DOM에 종속적이지 않은 코드를 작성하기
2. 재할당 되는 경우가 아닐 경우 const 사용
3. 이벤트 위임 사용
4. template literal 사용

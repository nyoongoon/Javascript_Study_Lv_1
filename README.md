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

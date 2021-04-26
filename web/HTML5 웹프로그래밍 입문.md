# HTML5 웹프로그래밍 입문

## ch1 웹 개요와 실습 환경 구축

### 1. 인터넷과 웹 시작

- network : 물리적으로 다른 머신이 의사소통하는 것으로 이두가지가 필요
  - 다른 머신의 주소 : ip
  - 의사 소통 규칙 : 프로토콜
- Web : 편집된 정보를 보내주는 시스템

- 2.0 시작
  - 서로 다른 사용자가 함께 새로운 콘텐츠를 창조할 수 있는 시대로 유튜브같은것을 말한다.
  - 시공간 제약이 없어짐



### 2. 웹 브라우저와 웹 표준

- 웹서비스를 브라우저에 따라 지원이 안되는 경우가 있어  HTML 표준을 통해 표준화 하고자 했다



### 3. 웹 동작

- 웹 : 요청과 응답 과정 ex)치킨집 전화번호를 찾아 전화를 걸어 집주소와 메뉴를 말하는것
- url : 웹에서 어떤 대상을 구분하는 주소
- 클라이언트 프로그램(프론트엔드 프로그램)
  - 정보 구조화해서 보여주기
  - GUI???
- 서버 프로그램(백앤드 프로그램)



### 4. 웹 표준 기술과 HTML5의 주요기능

1. 웹표준기술

- HTML 5 :웹 표준 기술을 총칭하고 웹 페이지 구성을 한다.
- css : HTML페이지에 스타일을 지정하는 언어(꾸며주는 것)
- 자바스크립트 : HTML 페이지에서 사용자의 반응(데이터 처리)와 동적인 부분을 담당

2. HTML5 주요기능

- 멀티미디어 기능
- 그래픽기능
- 통신
- 장치접근
- 오프라인 및 저장소
- 시멘틱
- 스타일시트



## ch2 웹 페이지 기본 구조와 작성 방법

### 1. HTML5 기본 용어

#### 1. 태그와 요소

- 요소 : HTML 페이지를 구성하는 각 부품
  - `<요소 이름>내용</요소 이름>`
  - `<h1>Hello world</h1>`
  - `<img>`,`<br>`,`<hr>`
- 태그(엘리멘트) : 이러한 요소를 만들때 사용하는 작성 방법
- 흔히 요소와 태그를 구분하지 않고 사용
- 속성 : 태그에 추가 정보를 부여할 때 사용하는 것
  - 속성 블록 :`<h1 title = "header">Hello HTML5</h1>`
  - 속성이름 : title
  - 속성 값 : header
  - 내부문자 : Hello HTML5

```
1. 이클립스로 웹프로젝트 생성(Dynamic web project)
2. Target runtime에 new runtime 클릭
3. apache tomcat 버전 클릭 우린 9버전
4. 9버전을 다운받거나 홈페이지에서 받아 브라우저로 연결하거나 하면되는데 다운받아 사용하면 더 좋다.(이유는 까뭇다)
5. 그라고 피니쉬.
6. 이제 밑에 servers로 들어가서 Tomcat v9.0 Server at localhost 클릭을 하여 포트넘버를 설정해줘야하는데 데이터베이스에 8080을 써서 다른 번호인 9090을 사용하고 저장.
7. 다시 더블클릭후 런온서버 창 넥스트누르고 프로젝트를 에드시킨다.

```



## ch3-ch4 HTML5 기본태그 및 입력양식 태그

```html
<!DOCTYPE html>
<html>
    <head>
        <title>
        
        </title>
    </head>
    <body><!-- -->
        <div>
            HTML은 어디서부터 시작하지?
            <!--무조건 한줄을 먹는다-->
        </div>
        <div>
            DIV 엘리먼트
        </div>
        <span>
            span 엘리먼트
        </span>
        <span>
            span 엘리먼트2
        </span>
        <h1> // 글자크기
            제목1
        </h1>
        <h2>
            제목2
        </h2>
        <h3>
            제목3
        </h3>
        <h4>
            제목4
        </h4>
        <h5>
            제목5
        </h5>
        <ul> <!-- Ul과 li는 세트-->
            <li>리스트1</li>
            <li>리스트2</li>
            <li>리스트3</li>
            <li>리스트4</li>
            <li>리스트5</li>
        </ul>
        <ul> <!-- Ul과 li는 세트-->
            <li>
            	<b>과일</b>
            	<ol>
            		<li>사과</li>
            		<li>바나나</li>
            	</ol>
            </li>
            <li>
            	<b>채소</b>
            	<ol>
            		<li>상추</li>
            		<li>양배추</li>
            	</ol>
            </li>
        </ul>
        <a href="http://naver.com">네이버 바로가기</a>
        <div>
        <input type="text">
        </div>
        <input type="password">
        <br/>
        독서 <input type="checkbox"> <br/>
        영화 <input type="checkbox"> <br/>
        PC <input type="checkbox"> <br/>

        <p>
            문단나누기
        </p>

        <input type="radio">남자
        <input type="radio">여자

        <div>
            block 이란 뭘까!?
            <div>
                block 이란 뭘까!?22222
            </div>
        </div>
        <div>
            block 이란 뭘까!?3333
        </div>

        <span>
            inline 이란 뭘까?
        </span>
        <span>
            inline 이란 뭘까?2222
        </span>
        
    </body>

</html>
```



- 테이블

![image-20210421174418932](C:\Users\aodeh\AppData\Roaming\Typora\typora-user-images\image-20210421174418932.png)

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="EUC-KR">
		<title>First HTML</title>
	</head>
	<body>
		<h1>Welcome!!</h1>
		<h2></h2>
		<table border = "1">
        	<tr>
        		<td>지역별홍차</td> <!-- 이게 두칸을 차지하게 바꾸면 밑에 aaaa가 지워도됌-->
        		<td>aaaa</td>
        	</tr>
        	<tr>
        		<td>중국</td><!-- 이게 3줄을 차지하게 바꾸면 밑에 중국들을 지워도됌-->
        		<td>정산소종</td>
        	</tr>
        	<tr>
        		<td>중국</td>
        		<td>기문</td>
        	</tr>
        	<tr>
        		<td>중국</td>
        		<td>운남</td>
        	</tr>
        </table>
	</body>
</html>
```

```html
       <table border = "1">
        	<tr><th colspan = "2">지역별홍차</th></tr>
        	<tr>
        		<th rowspan = "3">중국</th>
        		<td>정산소종</td>
        	</tr>
        	<tr><td>기문</td></tr>
        	<tr><td>운남</td></tr>
        	<tr>
        		<th rowspan ="4">인도 및 스리랑카</th>
        		<td>아삼</td>
        	</tr>
        	    <tr><td>실론</td></tr>
        		<tr><td>다질링</td></tr>
        		<tr><td>닐기리</td></tr>
        </table>
```

![image-20210421174513362](C:\Users\aodeh\AppData\Roaming\Typora\typora-user-images\image-20210421174513362.png)

- 미디어








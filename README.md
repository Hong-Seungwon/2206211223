# JAVA기반 웹개발자

### [2022_06_21](p2022_06_21)
### Java
  - 변수(Variable)

### [2022_06_22](p2022_06_22)

  - 명시적 형변환(ExplicitConversion) / 묵시적 형변환(ImplicitConversion)

  - 연산자(Operator)

  - 조건문(if)

### [2022_06_23](p2022_06_23)

  - 조건문(if, switch)

  - 반복문(for, while, do~while)

### [2022_06_24](p2022_06_24)

  - for문 응용(팩토리얼, 구구단 가로로)

  - 제어문(break, continue)

  - 메소드(Method)

  - 배열(Array)

### [2022_06_27](p2022_06_27)

  - 배열(Array)

  - String 클래스

  - 사용자 정의 클래스

### [2022_06_28](p2022_06_28)

  - 배열 응용

  - 필드 사용
  
`
(클래스 필드 선언, 외부 클래스에서 필드값 읽기/변경, 필드 자동 초기화, 필드값 출력)
`

### [2022_06_29](p2022_06_29)

  - 로또 

  - 필드 초기화
  
  `
  (생성자 필드 초기화, 객체 생성 후 필드값 출력)
  `

  - 생성자 오버로딩(Overloading)

  - 정적 필드, 정적 메소드

### [2022_06_30](p2022_06_30)
  
   - 싱글톤(Singleton)
    
   - Final 
   
    1. Final이 멤버변수에 사용될 경우
    -> 상수 (값을 수정할 수 없다)

    2. Final이 메소드에 사용될 경우
    -> 메소드 오버라이딩을 허용하지 않는다는 의미

    3. Final이 클래스에 사용될 경우
    -> 상속을 허용하지 않는다는 의미
    
   - Final 필드
   
   `
   (최종적인 값을 갖고 있는 필드 = 값을 변경할 수 없는 필드) 
   `

   - 패키지(Package)
   
   `
   (Package와 Import, 같은 패키지/다른 패키지에 들어있는 클래스
   `
   
   [a/b](a/b) / [Calling.class](Calling.class), [hello](hello) / [UsePackageHelloWorld.class](UsePackageHelloWorld.class)
   
   
   - 날짜, 시간 관련 클래스
   
   `
   (java.util.Date, java.sql.Timestamp, java.util.Calendar)
   `
   
### [2022_07_01](p2022_07_01)

  - 문자열 관련 클래스 
  
  `
  (String, StringBuffer, StringTokenizer)
  `
  
  - 문자열 관련 메소드
  
  `
   (length(), replace(), indexOf(), substring(), toLowerCase(), toUpperCase(), trim(), split())
  `
  
  - 값 비교(.equals())
  
### [2022_07_04](p2022_07_04)
  
  - 주민번호 유효성 검사
  
  - Wrapper 클래스
  
  `
  (기본 자료형 <--> 참조형) 
  `
  
  - 자동 박싱 / 언박싱
  
  - 문자열 변환(valueOf())
  
  - Frame
  
  - 상속(Inheritance)
    
### [2022_07_05](p2022_07_05)

  - 반지름이 5인 원주, 원의 넓이, 구의 겉넓이, 구의 부피 구하기(DecimalFormat 클래스 이용)
  
  - 상속(Inheritance)
    
    - 접근 제어자
    
     [packTest/packOne](packTest/packOne) / [SuperSubA.class](SuperSubA.class) / [SubOne.class](SubOne.class)
        
    - 상속(Inheritance)에서의 생성자
  
      1. 생성자는 기본적으로 상속이 되지 않는다

      2. 자식클래스를 이용해서 객체를 생성할때 자식클래스의 생성자(기본생성자,매개변수 있는 생성자 모두 가능)가 호출되면, 부모클래스의 기본생성자가 자동으로 호출된다.

      3. 매개변수가 있는 생성자가 있는 경우에는 더이상 컴파일러가 기본 생성자를 자동으로 생성해 주지 않는다.

      4. 부모 클래스의 매개변수가 있는 생성자를 자식 클래스에서 호출 할때는 super()를 이용해서 호출할 수 있다.
         단, super()는 자식 클래스의 생성자 안에서만 사용 가능함.
  
  - 메소드 오버라이딩(Method Overriding)
  
  - super. : 부모 클래스에 있는 은닉된 멤버변수와  메소드를 호출할 때 사용 
  
  - super() : 부모 클래스의 매개변수를 가진 생성자를 호출할 때 사용
  
### [2022_07_06](p2022_07_06)

  - 평년, 윤년 구분하기
  
  - 추상(Abstract) 클래스
  
  - 인터페이스(Interface)
  
  - 레퍼런스(Reference) 형변환
  
  `
  (업 캐스팅(자동 형변환), 다운 캐스팅(강제 형변환))
  `
  
### [2022_07_07](p2022_07_07)

  - 평년, 윤년 구분하기(GregorianCalendar 클래스 이용)
  
  - 레퍼런스(Reference) 형변환
  
  - Set 인터페이스
  
  `
  (상속받는 클래스 : HashSet, TreeSet)
  `
  
  - List 인터페이스
  
  `
  (상속받는 클래스 : ArrayList)
  `
  
  - List 응용 게시판 만들기
  
  - Vector 클래스
  
### [2022_07_08](p2022_07_08)
  
  - Vector 클래스
  
  - Map 인터페이스
  
  `
  (상속받는 클래스 : HashMap, HashTable)
  ` 
  
  - 큐(Queue) : FIFO(First Input First Output)구조
  
  - 스택(Stack) : LIFO(Last Input First Output)구조
  
  - 제네릭(Generic)

### [2022_07_11](p2022_07_11)

  - MemberInfo Generic 활용하기
  
  - 예외 처리(Exception)
  
  - 스레드(Thread)
  
### [2022_07_12](p2022_07_12)

  - clock(Thread 활용) 만들기
  
  - 스레드(Thread)
  
  - 스레드 동기화(Synchronized)
  
  - java.io 패키지
  
  `
  (InputStream, InputStreamReader, BufferedReader, FileReader, FileWriter, FileInputStream, FileOutputStream)
  `
  
### [2022_07_13](p2022_07_13)
  - java.io 패키지
  
  `
  (File, Serializable 인터페이스)
  `
  
  - java.net 패키지
  
  `
  (InetAddress, Socket)
  `

### [2022_07_14](p2022_07_14)

  - 비어있지 않은 디렉토리 삭제 : listFiles()
  
  - 멀티 채팅(Socket, ServerSocket)
  
  #### oracle 연동
  - java.sql 패키지
  
  `
  (Connection, DriverManager)
  `

### [2022_07_15](p2022_07_15)

  #### oracle 연동
  - java.sql 패키지
  
  `
  (Connection, DriverManager, Statement, PreparedStatement, ResultSet)
  ` 
  
  - 회원가입(DB연동)
  
  - 회원정보 수정 및 탈퇴
  
### [2022_07_18](p2022_07_18)
  - 게시판 만들기(InsertBoard, SelectBoard, UpdateBoard, DeleteBoard)
  
  #### MySQL 연동
  - java.sql 
  
  `
  (Connection, DriverManager)
  ` 

# SQL
### [2022_07_19](p2022_07_19)

 #### MySQL 연동
 - 게시판 만들기(InsertBoard, SelectBoard, UpdateBoard, DeleteBoard)
 
 #### sqldeveloper
 - 테이블 목록, 구조 확인
 
 - 데이터 검색
 
 - 오라클 데이터 타입
 
 `
 (숫자 데이터, 문자 데이터, 날짜 데이터)
 `
 
 - SELECT SQL문
 
 - 산술 연산자
 
### [2022_07_20](p2022_07_20)

  #### sqldeveloper
  - where 조건절
  
  - 논리 연산자(and, or, not)
  
  - between and 연산자
  
  - in 연산자
  
  - like 연산자
  
  - 와일드 카드(%, _)
  
  - NULL값 검색 및 변경 (is null, nvl)
  
  - 정렬(Sort)(asc, desc)
  
  - 여러번 정렬
  
### [2022_07_21](p2022_07_21)

  - DUAL 테이블과 SQL 함수 분류
  
  - 숫자 함수
  
  `
  (abs(), floor(), round(), trunc(), mod())
  `
  
  - 문자 처리 함수
  
  `
  (upper(), lower(), initcap(), length(), lengthb(), substr(), instr(), lpad(), rpad(), ltrim(), rtrim(), trim())
  `
  
  - 날짜 함수
  
  `
  (sysdate, months_between(), add_months(), next_day(), last_day())
  `
  
  - 형 변환 함수
  
  `
  (to_char(), to_date(), to_number())
  `
  
### [2022_07_22](p2022_07_22) 

  - nvl()
  
  - decode()
  
  - case()
  
  - 그룹 함수
  
  `
  (sum(), avg(), max(), min(), count())
  `
  
  - group by 절
  
  - having 절
  
  - cross join
  
  `
  (등가 조인(Equi Join), 비등가 조인(Non-Equi Join), 자체 조인(Self Join), 외부 조인(Outer Join))
  `
  
### [2022_07_25](p2022_07_25)

  - ANSI JOIN
  
  `
  (ANSI CROSS JOIN, ANSI INNER JOIN, ANSI NATURAL JOIN, ANSI OUTER JOIN)
  `
  
  - 서브 쿼리
  
  - 다중 행 연산자
  
  `
  (IN, ALL, ANY) 
  `
  
  - DDL(Date Definition Language)
  
  - 오라클의 객체
  
  - 임시 테이블 삭제(purge recyclebin;)
  
### [2022_07_26](p2022_07_26)

  - DML(Data Mainfulation Language)
  
  - merge
  
  - 트랜잭션 처리어(Transaction Control Language)

  - 무결성 제약 조건
  
  `
  (NOT NULL, UNIQUE)
  `
  
### [2022_07_27](p2022_07_27)

  - 무결성 제약조건
  
  `
  (PRIMARY KEY, FOREIGN KEY, CHECK, DEFAULT, )
  `
  
  - 제약조건 설정(컬럼 레벨, 테이블 레벨)
  
  - 제약조건 추가 및 삭제(alter table)
  
  - CASCADE
 
### [2022_07_28](p2022_07_28)

  - 뷰(VIEW)
  
  ` 
  (or replace, with check option, with read only)
  
  ` 
  
  - rownum
  
  - 시퀀스(sequence)

### [2022_07_29](p2022_07_29)

  - 인덱스(index)
  
  - 시스템 권한
  
  ```
  create session / table / view/ sequence / procedure
  
  계정 생성 : create user 사용자명 identified by 비밀번호;
  
  계정 목록 확인 : select * from dba_users;
  
  데이터 베이스 접속 권한 부여 : grant create session to 사용자명;
  
  with admin option
  ```

  - 객체 권한
  
  ```
  객체 조회 권한 부여 : grant select on 테이블명 to 사용자명;
  
  with grant option
  ```

  - 롤(role) 권한
  
  ```
  connect(8가지 권한이 포함), resource(20여개 권한), dba(130여개 권한)
  ```
  
  - 동의어(synonym)
  
### [2022_08_01](p2022_08_01)

### PL/SQL(Oracle's Procedural Language extension to SQL)
  
  #### 조건문
  
  1.  if ~ then ~ end if
  
  2. if ~then ~ else ~ end if
  
  3. if ~ then ~ elsif ~ else ~ end if
  
  #### 반복문
  
  1. Basic Loop문
  
  2. For Loop문
  
  3. While Loop문
  
  #### 저장 프로시저
  
  - in, out 매개변수
  
### [2022_08_02](p2022_08_02)

### PL/SQL

  - 저장 함수
  
  - 커서(CURSOR)
  
  - 패키지(PACKAGE)
  
  - 트리거(TRIGGER)
  
### [2022_08_03](p2022_08_03)

### eXERD
  
  ```
  프라이머리 키 컬럼 : ctrl + shift + enter
  
  일반 컬럼 : ctrl + enter
  
  자동 배치 : ctrl + shift + f
  
  포워드, 리버스 엔지니어링
  ```

### 웹표준

  ```
  JSP 환경 구축 : Apache Tomcat
  
  JSP 프로젝트, 파일 생성
  ```

### [2022_08_04](p2022_08_04)

### HTML
  ```
  주석 처리 : Ctrl + Shift + /
  
  주석 해제 : Ctrl + Shift + \
  
  br : 줄 바꿈
  
  p : 문단 바꾸기
  
  hr : 수평선 긋기
  
  h : 제목 출력(h1 > h2 > h3 > h4 > h5 > h6)
  
  font(size, color, face)
  
  이미지(<img src="">)
  
  ol : 순서있는 목록(Ordering List)
  
  ul : 순서없는 목록(Unordering List)
  
  하이퍼링크(<a href="http://")
  
  표(table, tr, td, border, bgcolor, cellspacing, cellpadding, colspan, rowspan)
  ```

### [2022_08_05](p2022_08_05)

### HTML

```
로그인폼

게시판

회원가입 폼

히든(readonly, disabled)
```

### [2022_08_08](p2022_08_08)

### CSS

```
<style>
선택자 : 선택자 {스타일 속성 : 스타일 값;}
</stlye>

- 선택자 종류
전체, 태그, 아이디, 클래스, 속성, 후손, 자손, 반응, 상태, 구조, 동위, 링크, 문자, 부정

- 박스 속성

- 가시 속성
```

### [2022_08_09](p2022_08_09)

```
- 배경 속성

- 글자 속성

- 위치 속성

- 유동 속성

- 수평, 중앙, One True 정렬 레이아웃
```

### [2022_08_10](p2022_08_10)

### bootstrap(w3schools 예제)

```
- Button

- Tables

- Pagination

- Dropdowns

- Collapse

- Stacked Form

- Form Inputs

- Scrollspy 

- Filters

- Navs
```
  - emport .war 생성 / import .war 불러오기
  
### javascript

```
<script></script>
<script type="text/javascript"></script>
<script langage="javascript"></script>

- 자바스크립트 주석
1. 단일 행 주석 : //
2. 다중 행 주석 : /* */
주석 단축키 : Ctrl + Shift + /

-alert
```

### [2022_08_11](p2022_08_11)

### javascript

```
- confirm

- prompt

- variable

- operation

- if

- switch ~ case

- for

- while

- do ~ while

- builtin
```

### [2022_08_12](p2022_08_12)

```
- function

- date

- array

- string

- math
```

### [2022_08_16](p2022_08_16)

```
- 계산기

- 이벤트 처리 방법(inline, property, DOM Level 2)

- window 객체

- document 객체

- meta 

- location

- navigator

- history

- form

- Focus, Blur
```

### [2022_08_17](p2022_08_17)

```
- Keyup

- submit

- checkbox

- radio

- select

- loginform, boardform, memberform 적용
```

### [2022_08_18](p2022_08_18)

```
- memberform, member.js

- cookie
```
### jQuery
```
1. 라이브러리 사용
2. CDN(Contents Delivery Network) 방식

- 글자 숨기기

- 코드 외부 파일화

- CSS에서 자주 사용되는 selector
```
### [2022_08_19](p2022_08_19)
```
- CSS에서 자주 사용되는 selector

- 이벤트 처리

- 폼 태그 기능
```

### [2022_08_22](p2022_08_22)
```
- 폼 태그 기능

- 유효성 검사

- 로그인 폼

- 게시판 폼
```

### [2022_08_23](p2022_08_23)
```
- 회원가입 폼

- Ajax

- each() 메서드
```

### [2022_08_24](p2022_08_24)
```
- Ajax

- map

- jQueryUI
```

### JSP

### [2022_08_25](p2022_08_25)
### JSP
```
- 스크립틀릿 태그(Scriptlet tag)

- 표현식 태그(Expression Tag)

- 지시어 태그(Directive Tag)
1. 페이지 태그(Page Tag)

- 선언 태그(Declaration Tag)

- import
1. Date
2. Timestamp
3. Calendar

- 주석문

- request 객체

- request 로그인 폼
```

### [2022_08_26](p2022_08_26)
```
- request 게시판 폼

- request 회원가입 폼

- response 객체

- out 

- cookie 

- session 객체
```

### [2022_08_29](p2022_08_29)
```
- 영역 객체

- 에러 처리

- 액션 태그(forward)
```

### [2022_08_30](p2022_08_30)
```
- 액션 태그(include)

- 템플릿

- 자바빈(javabean1, javabean2)
```

### [2022_08_31](p2022_08_31)
```
- 자바빈(login)

- JDBC(DB 연동 예제, oracle_mem01)

- 자바빈(javabean3)
```

### [2022_09_01](p2022_09_01)
```
- 자바빈(javabean3) DAO 

- Connection Pool

- 회원 관리(member)
```

### [2022_09_02](p2022_09_02)
```
- 회원가입 폼

- 로그인 폼

- ID 중복 검사
```

### [2022_09_05](p2022_09_05)
```
- 수정 폼

- 삭제 폼

- 일반 게시판
(writePro.jsp, list.jsp)
```

### [2022_09_07](p2022_09_07)
```
- 페이지 링크 설정

- 페이지 이동

- 제목 클릭 시 링크 설정

- 상세 폼 : 상세 정보 구하기

- 글 수정

- 글 삭제
```

### [2022_09_08](p2022_09_08)
```
- 댓글 게시판(reboard)
writeForm.jsp, writePro.jsp
list.jsp
content.jsp
replyForm.jsp, replyPro.jsp
```

### [2022_09_13](p2022_09_13)
```
updateForm.jsp, updatePro.jsp

- 파일 업로드 테스트(uploadTest)

- 파일 업로드(upload)
```

### [2022_09_14](p2022_09_!4)
```
- 파일 업로드(upload)
writeForm.jsp, writePro.jsp
list.jsp
content.jsp
updateForm.jsp, updatePro.jsp
deleteForm.jsp, deletePro.jsp
```

### [2022_09_15](p2022_09_15)
```
- Java Servlet
ex111, ex222, ex333, ex555, ex666, ex777

- 표현언어(Expression Language)
ex11, ex22, ex33
```

### [2022_09_16](p2022_09_16)
```
- JSTL(JSP Standard Tag Library) 태그 종류
1. core
(set, remove, if, choose, catch, otherwise, out, forEach, forTokens)

2. fmt
(formatDate, formatNumber, timeZone)

3. fn
(length, toUpperCase, toLowerCase, substring, substringAfter, substringBefore, 
trim, replace, indexOf, startsWith, endsWith, contains, containsIgnoreCase)

4. sql
(setDataSource, update, query, param)

- Model2 이용한 회원 관리
member.sql
Controller 클래스, DTO/DAO 클래스
```

### [2022_09_19](p2022_09_19)
```
- 모델2 회원 관리
Action, ActionForward
MemberController
DAO
회원가입폼 : MemberInsert.java, memberform.jsp
ID중복검사 : IdCheck.java(ajax)
로그인 폼 : loginform.jsp, Login.java, main.jsp
로그아웃 : logout.jsp
```

### [2022_09_20](p2022_09_20)
```
- 모델2 회원 관리
MemberController, DAO
수정 폼 : UpdateMember.java, updatform.jsp, Update.java
삭제 폼 : Delete.java, deleteform.jsp, result.jsp
```

### [2022_09_21](p2022_09_21)
```
- 모델2 게시판
board.sql
BoardBean.java, BoardDAO.java
BoardFrontController.java
Action.java, ActionForward.java
글 작성 폼: qna_board_write.jsp, BoardAddAction.java
글 목록 : BoardListAction.java, qna_board_list.jsp
```

### [2022_09_22](p2022_09_22)
```
- 모델2 게시판
글 목록 : qna_board_list.jsp
글 내용 : BoardDetailAction.java, qna_board_view.jsp
댓글 : BoardReplyAction.java, qna_board_reply.jsp, BoardReply.java
수정 : BoardModifyAction.java, qna_board_modify.jsp, BoardModify.java
```

### [2022_09_23](p2022_09_23)
```
- 모델2 게시판
qna_board_view.jsp
수정 : BoardModifyAction.java, qna_board_modify.jsp, BoardModify.java, updateresult.jsp
삭제 : qna_board_delete.jsp, BoardDelete.java

- Maven
프로젝트 생성
repository 추가
Export, Import
```

### [2022_09_26](p2022_09_26)
```
- mybatis
mybatistest Import
member22
```

### [2022_09_27](p2022_09_27)
```
mybatismember Import
mybatisboard Import
```

### [2022_09_28](p2022_09_28)
```
mybatisboard
```

### [2022_09_29](p2022_09_29)
```
- Spring
STS(Spring Tool Suite)3.9.11 다운로드
Spring 프로젝트 생성
springtest
ch01 Import
ch01
(sample01, sample02, sample03, sample04(beans01.xml), sample05(beans02.xml), sample06(beans02.xml), sample07(beans07.xml), 
sample08(beans08.xml), sample09(beans09.xml))
```

### [2022_09_30](p2022_09_30)
```
ch01
(sample10(beans10.xml), sample11(beans11.xml), sample12(beans12.xml), sample13(beans13.xml), sample14(beans14.xml), 
sample15(beans15.xml), sample16(beans16.xml), sample17(beans17.xml))
```

### [2022_10_04](p2022_10_04)
```
hello Import
hello
ch07 Import
ch07
인터셉터(Interceptor)
```

### [2022_10_05](p2022_10_05)
```
ch07 인터셉터(Interceptor)
myBatis1 Import
myBatis1
```

### [2022_10_06](p2022_10_06)
```
myBatis2 Import
myBatis2
```

### [2022_10_07](p2022_10_07)
```
myBatis2

- STS에 Data source Management추가

- spring 실습
계정 생성
sql(테이블 및 시퀀스 생성)
환경 설정 파일 작성 
BoardController.java, BoardService.java, BoardDao.java, Board.java
글 작성, 글 개수, 글 목록 
```

### [2022_10_11](p2022_10_11)
```
- spring 실습
상세 페이지, 수정 폼, 글수정, 삭제 폼, 삭제

- Email 보내기
mailTest

- springmember(회원가입)
환경 설정 파일
```

### [2022_10_12](p2022_10_12)
```
- springmember(회원가입)

- springboard(게시판 및 댓글)
```

### [2022_10_13](p2022_10_13)
```
- springboard(게시판 및 댓글)

- board1(게시판 및 검색)

- 동적 SQL
mybatis-3-user-guide_ko(42p)
```

### [2022_10_14](p2022_10_14)

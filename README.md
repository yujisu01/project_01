# project_01

## 이클립스 환경설정 

eclipse 2021-03 버전 설치<br></br>
jdk8 이상 설치<br></br>
eclipse 에 JAVA PROJECT 추가<br></br>
추가된 프로젝트에 build tool :: maven 설정<br></br>
maven 의 pom.xml 을 통해 spring-mvc 4.3 버전 근처로 설치<br></br>
TOMCAT 서버 추가(TOMCAT 9, 10) <br></br>
추가된 서버에 JAVA PROJECT 를 Add<br></br>
index.jsp 추가하여 페이지 표시 유무 확인<br></br>
web.xml 의 dispatcherServlet 설정 및 contextConfigureLocation 설정<br></br>
:heavy_check_mark: home.jsp의 경로를 찾지못하는 문제발생. Dynamic Project 하나더 생성하고 다시 진행함 (여기부터 다시)<br></br>
Controller - service - impl  형태의 백엔드 프로그램 작성<br></br>
해당 주소에 대해 표시여부 확인<br></br>
MSSQL 설치 <br></br>
pom.xml 에 mssql-jdbc 설치<br></br>
context-datasource.xml 에 mssql-jdbc 설정<br></br>
EgovAbstractMapper 를 통해 쿼리 가능하도록 context-****.xml 파일 설정 (spring-mybatis 를 활용하는 전자정부프레임워크 DAO 개체)

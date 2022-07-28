<h2 style="font-size: 30px;font-weight: 700;">Dr.marten 스타일 가이드 파일 위치</h2>

#controller<br>
Study/src/main/java/com/edu/study/controller/guideController.java
<br>
#resources<br>
static안에 있는 폴더 전부
<br>
#resources - application.properties에서<br><br>
server.port=80<br>
spring.mvc.view.prefix=/WEB-INF/JSP/<br>
spring.mvc.view.suffix=.jsp<br>
//아래 코드 추가<br>
<strong>spring.mvc.static-path-pattern=/resources/**</strong>



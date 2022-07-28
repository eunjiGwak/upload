Dr.marten 스타일 가이드 파일 위치

#controller
Study/src/main/java/com/edu/study/controller/guideController.java

#resources
static안에 있는 폴더 전부

#resources - application.properties에서
server.port=80
spring.mvc.view.prefix=/WEB-INF/JSP/
spring.mvc.view.suffix=.jsp
//아래 코드 추가
<strong>spring.mvc.static-path-pattern=/resources/**</strong>



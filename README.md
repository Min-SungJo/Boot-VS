# Spring-Study
Spring
자바 엔터프라이즈 애플리케이션 개발에 사용되는 애플리케이션 프레임워크
애플리케이션 개발을 빠르고 효율적으로 할 수 있도록
애플리케이션의 바탕이되는 틀과 공통 프로그래밍 모델, 기술API 등을 제공해준다

Spring Boot 

## [spring-boot-starter](https://github.com/Min-SungJo/Boot-VS/blob/main/security/build.gradle)
: 의존성과 설정을 자동화해주는 모듈
프로젝트에 설정해야할 다수의 의존성을 사전에 미리 정의해서 의존성 조합을 제공
class-path를 탐색하여 db파악 및 EntityManager구성
해당 모듈의 설정에 필요한 properties설정 제공
(application.properties또는 build.gradle에 기입하는 형식으로 사용)
aspectJ를 사용한다면,
1. dependency에 추가하여 사용하는 방법
org.springfraimword:spring-aop
org.aspectjweaver
2. spring-boot-start로 사용하는 방법
spring-boot-starter-aop

## [WebSecurityConfigure](https://github.com/Min-SungJo/Boot-VS/blob/main/security/src/main/java/com/security/config/WebSecurityConfig.java)
: url로 접근한 사용자의 권한을 확인, 제어하는 클래스


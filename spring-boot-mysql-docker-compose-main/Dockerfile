FROM eclipse-temurin:17-jdk
MAINTAINER Chaitanya K
COPY target/spring-boot-mysql.jar /usr/app/spring-boot-mysql.jar
WORKDIR /usr/app/
EXPOSE 8080
ENTRYPOINT ["java","-jar","spring-boot-mysql.jar"]

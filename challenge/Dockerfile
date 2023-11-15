FROM openjdk:21
VOLUME /tmp
EXPOSE 8080
ARG docJAR_FILE=target/spring-boot-docker.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
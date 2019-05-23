FROM openjdk:8-jre-alpine
 
VOLUME /tmp

ADD spring-boot-hello-1.0.jar app.jar

RUN sh -c 'touch /app.jar'

CMD ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]

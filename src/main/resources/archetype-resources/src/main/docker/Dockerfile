FROM openjdk:8u151-jdk-alpine

ADD /target/*.jar /app/app.jar

ENV TZ Asia/Bangkok
ENV JAVA_OPTS ""

ENTRYPOINT [ "/bin/sh", "-c", "java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app/app.jar" ]
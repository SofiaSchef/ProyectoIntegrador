FROM amazoncorretto:11-alpine-jdk
MAINTAINER SCHEFFER
COPY target/scheffer-0.0.1-SNAPSHOT.jar scheffer-app.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/scheffer-app.jar"] 
FROM openjdk:17-jdk-slim

ENV APP_JAR=app.jar

WORKDIR /app

COPY target/*.jar ${APP_JAR}

EXPOSE 8080

ENTRYPOINT ["java","-jar","app.jar"]


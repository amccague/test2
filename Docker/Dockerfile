FROM openjdk:openjdk:10-ea-jdk-experimental
# FROM openjdk:21-ea-20-slim-bullseye
ARG JAR_FILE=target/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]

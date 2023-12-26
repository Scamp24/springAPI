FROM openjdk:17-jdk-alpine
ARG JAR_FILE=tagert/*.jar
COPY ./target/SpringAPI-0.0.1-SNAPSHOT app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
FROM openjdk:17-jdk-alpine

WORKDIR /usr/src/app

ARG JAR_FILE=build/libs/spring-hello-world-0.0.1-SNAPSHOT.jar

COPY ${JAR_FILE} app.jar

COPY . .

EXPOSE 8080

CMD ["java", "-jar", "app.jar"]
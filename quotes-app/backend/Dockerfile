FROM openjdk:17-jdk-alpine

WORKDIR /usr/src/app

ENV POSTGRES_USER=kodilla

ENV POSTGRES_PASSWORD=kodilla

ENV POSTGRES_DB=kodilla-quotes

ARG JAR_FILE=build/libs/quotes-0.0.1-SNAPSHOT.jar

COPY ${JAR_FILE} app.jar

COPY . .

EXPOSE 8080

CMD ["java", "-jar", "app.jar"]
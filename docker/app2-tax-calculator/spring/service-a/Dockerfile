FROM eclipse-temurin:17-jdk AS build

WORKDIR /app

COPY ./target/taxa-0.0.1-SNAPSHOT.jar ./app.jar

EXPOSE  8080

CMD [ "java" ,"-jar" ,"app.jar" ]
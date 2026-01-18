FROM eclipse-temurin:17-jdk AS build

WORKDIR /app

COPY ./target/taxb-0.0.1-SNAPSHOT.jar ./app.jar

EXPOSE  4000

CMD [ "java" ,"-jar" ,"app.jar","--server.port=4000" ]
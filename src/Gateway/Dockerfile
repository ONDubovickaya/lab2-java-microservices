FROM openjdk:17-jdk-alpine
MAINTAINER ondubovickaya
EXPOSE 8080
COPY target/Gateway-0.0.1-SNAPSHOT.jar gateway.jar
ENTRYPOINT ["java","-jar","./gateway.jar"]

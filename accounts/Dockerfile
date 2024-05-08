FROM openjdk:17.0-jdk-slim

MAINTAINER eazybytes.com

COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

LABEL authors="junghoon"

ENTRYPOINT ["java", "-jar", "accounts-0.0.1-SNAPSHOT.jar"]

EXPOSE 8080
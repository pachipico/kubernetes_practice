FROM openjdk:17.0-jdk-slim

MAINTAINER eazybytes.com

COPY target/cards-0.0.1-SNAPSHOT.jar cards-0.0.1-SNAPSHOT.jar

LABEL authors="junghoon"

ENTRYPOINT ["java", "-jar", "cards-0.0.1-SNAPSHOT.jar"]

EXPOSE 8081
FROM openjdk:17.0-jdk-slim

MAINTAINER eazybytes.com

COPY target/loans-0.0.1-SNAPSHOT.jar loans-0.0.1-SNAPSHOT.jar

LABEL authors="junghoon"

ENTRYPOINT ["java", "-jar", "loans-0.0.1-SNAPSHOT.jar"]

EXPOSE 8082
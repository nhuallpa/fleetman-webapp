FROM openjdk:8u201-jdk-alpine3.9

MAINTAINER R C "R@C.COM"

WORKDIR /usr/local/bin

EXPOSE 8080

COPY maven/fleetman-0.0.1-SNAPSHOT.jar webapp.jar

CMD ["java", "-Dspring.profiles.active=docker-demo", "-jar", "webapp.jar"]
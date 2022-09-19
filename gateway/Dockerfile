FROM openjdk:latest
COPY ./gateway-1.0-SNAPSHOT.jar /tmp/gateway-1.0-SNAPSHOT.jar
ENTRYPOINT java -jar -Dspring.profiles.active=prod /tmp/gateway-1.0-SNAPSHOT.jar

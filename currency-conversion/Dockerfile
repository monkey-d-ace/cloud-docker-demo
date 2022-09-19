FROM openjdk:latest
COPY ./currency-conversion-1.0-SNAPSHOT.jar /tmp/currency-conversion-1.0-SNAPSHOT.jar
ENTRYPOINT java -jar -Dspring.profiles.active=prod  /tmp/currency-conversion-1.0-SNAPSHOT.jar

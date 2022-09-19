FROM openjdk:latest
COPY ./currency-exchange-1.0-SNAPSHOT.jar /tmp/currency-exchange-1.0-SNAPSHOT.jar
ENTRYPOINT java -jar -Dspring.profiles.active=prod  /tmp/currency-exchange-1.0-SNAPSHOT.jar

FROM openjdk:11-jdk-alpine
COPY ./target/*.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT exec java -jar app.jar --info

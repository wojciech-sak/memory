FROM openjdk:12-jdk-alpine
COPY build/libs/memory-0.0.1-SNAPSHOT.jar /app.jar
EXPOSE 8080/tcp
ENTRYPOINT ["java", "-jar", "/app.jar"]
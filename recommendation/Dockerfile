FROM eclipse-temurin:21-jre-alpine
COPY target/recommendation*.jar app.jar
ENTRYPOINT ["java", "-jar", "/app.jar"]
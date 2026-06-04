FROM eclipse-temurin:21-jre-jammy

WORKDIR /app

ARG JAR_FILE=deploy004_springboot/target/*.jar
COPY ${JAR_FILE} app.jar

ENTRYPOINT [ "java", "-jar", "app.jar" ]
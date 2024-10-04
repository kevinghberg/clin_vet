FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/clinica_veterinaria.jar
COPY ${JAR_FILE} app_veterinaria.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_veterinaria.jar"]
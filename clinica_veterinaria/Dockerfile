FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/clinica_veterinaria-0.0.1.jar
COPY ${JAR_FILE} app_veterinaria.jar
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "app_veterinaria.jar"]
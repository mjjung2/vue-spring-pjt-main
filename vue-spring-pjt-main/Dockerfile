#git action
FROM openjdk:17-jdk-alpine
WORKDIR /app-backend
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} vuespring.jar
ENTRYPOINT [ "java", "-jar", "/vuespring.jar"]
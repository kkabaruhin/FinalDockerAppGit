FROM openjdk:8-jdk-alpine
EXPOSE 8081
WORKDIR /notification-server/app
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} /notification-server/app/app.jar
ENTRYPOINT ["java","-jar","/notification-server/app/app.jar"]
FROM openjdk:8-jdk-alpine
EXPOSE 8080
WORKDIR /user-server/app
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} /user-server/app/app.jar
ENTRYPOINT ["java","-jar","/user-server/app/app.jar"]
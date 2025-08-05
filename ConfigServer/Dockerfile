FROM openjdk:8-jdk-alpine
EXPOSE 8888
WORKDIR /config-server/app
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} /config-server/app/app.jar
ENTRYPOINT ["java","-jar","/config-server/app/app.jar"]
FROM openjdk:8-jdk-alpine
EXPOSE 8761
WORKDIR /eureka-server/app
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} /eureka-server/app/app.jar
ENTRYPOINT ["java","-jar","/eureka-server/app/app.jar"]
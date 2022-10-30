FROM openjdk:17-alpine
EXPOSE 9999
ARG JAR_FILE=gateway-0.0.1-SNAPSHOT.jar
ADD ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
FROM openjdk:11.0.7-jre-slim

WORKDIR /opt/temp

COPY . /opt/temp

EXPOSE 8080

ENTRYPOINT ["java","-jar","/opt/temp/java-webserver.jar"]

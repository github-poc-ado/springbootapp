FROM openjdk:11
WORKDIR /app
#ARG JAR_FILE=target/*.jar 
RUN df -h
COPY target/spring-boot-web-0.0.1-SNAPSHOT.jar /app/spring-boot-web-0.0.1-SNAPSHOT.jar
RUN chmod 777 /app/spring-boot-web-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","/app/spring-boot-web-0.0.1-SNAPSHOT.jar"]

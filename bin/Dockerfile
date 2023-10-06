FROM openjdk:20-jdk
ADD target/app.jar app.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","/app.jar"]
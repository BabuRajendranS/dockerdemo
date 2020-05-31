FROM openjdk:14
ADD target/dockerdemo.jar dockerdemo.jar
EXPOSE 9090
ENTRYPOINT ["java", "-jar", "dockerdemo.jar"]
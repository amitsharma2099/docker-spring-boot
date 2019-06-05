#Command to build this project from docker terminal: docker build -t docker-java .
FROM tomcat:9
WORKDIR /app
ADD target/docker-spring-boot.jar .
EXPOSE 8085
CMD ["java", "-jar", "docker-spring-boot.jar"]
FROM openjdk:11-jdk-slim
WORKDIR /app
COPY target/spring-petclinic-config-server-2.1.2.jar /app
EXPOSE 8888
CMD ["java", "-jar", "spring-petclinic-config-server-2.1.2.jar"]
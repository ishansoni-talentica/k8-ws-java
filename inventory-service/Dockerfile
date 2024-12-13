FROM openjdk:21-jdk-slim
COPY /target/*.jar ROOT.jar
EXPOSE 8082
ENTRYPOINT [ "java", "-jar", "/ROOT.jar"  ]
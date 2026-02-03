FROM eclipse-temurin:21-jre
WORKDIR /app

COPY target/money-manager-0.0.1-SNAPSHOT.jar money-manager-v1.0.jar
EXPOSE 9090
ENTRYPOINT ["java","-jar","money-manager-v1.0.jar"]
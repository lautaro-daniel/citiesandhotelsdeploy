FROM openjdk:17
ARG JAR_FILE=target/cities-service-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app_cities.jar
ENTRYPOINT ["java", "-jar", "app_cities.jar"]
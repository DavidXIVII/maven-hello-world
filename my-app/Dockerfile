FROM openjdk:11-slim
WORKDIR /java
ARG version
ARG app-name
COPY my-app/target/${app-name}-${version}.jar ./application.jar
CMD ["java", "-jar", "application.jar"]

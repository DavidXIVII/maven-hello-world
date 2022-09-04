FROM openjdk:11-slim
WORKDIR /java
ARG version
ARG app-name
ENV rootdir="my-app/target"
COPY ${rootdir}/${app-name}-${version}.jar ./application.jar
CMD ["java", "-jar", "application.jar"]

FROM eclipse-temurin:8-jre
WORKDIR /java
ARG version
ARG app_name
ENV rootdir="my-app/target"
COPY ${rootdir}/${app_name}-${version}.jar ./application.jar
CMD ["java", "-jar", "application.jar"]

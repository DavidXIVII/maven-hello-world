FROM openjdk:11-slim
WORKDIR /java
ARG version
ENV rootdir="/java/my-app/target"
# ARG JAR=my-app/target/*-${version}.jar
COPY my-app/target/my-app-${version}.jar ./application.jar
CMD ["java", "-jar", "application.jar"]

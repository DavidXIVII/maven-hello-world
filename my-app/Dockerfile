FROM openjdk:11-slim
WORKDIR /java
ENV rootdir="/java/my-app/target"
ARG version
ARG JAR=my-app/target/*-${version}.jar
COPY ${rootdir}/${JAR}.jar ./application.jar
CMD ["java", "-jar", "application.jar"]

FROM java:8-jdk-alpine
MAINTAINER DevOps Team
COPY ./target/spring-boot-sample-atmosphere-1.4.0.RELEASE.jar /usr/app/
WORKDIR /usr/app
EXPOSE 8086
ENTRYPOINT ["java", "-jar", "spring-boot-sample-atmosphere-1.4.0.RELEASE.jar"]
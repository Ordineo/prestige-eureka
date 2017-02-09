FROM openjdk:8-jre
VOLUME /tmp
ADD eureka-0.0.1-SNAPSHOT.jar app.jar
RUN sh -c 'touch /app.jar'
EXPOSE 8761
ENTRYPOINT ["java","-Xmx64m","-jar","/app.jar"]
FROM openjdk:11.0.2-jre-slim
EXPOSE 8080
COPY catalog-service-0.0.1-SNAPSHOT.jar /home/catalog-service-0.0.1-SNAPSHOT.jar

# set the startup command to execute the jar 
CMD ["java", "-jar", "/home/catalog-service-0.0.1-SNAPSHOT.jar"]

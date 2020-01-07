# Base Image
FROM openjdk:8

# Create DIR
RUN mkdir -p /usr/src/myapp

# COPY APPLICTAION COde
COPY target/spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar    /usr/src/myapp

# Setup Working DIR
WORKDIR /usr/src/myapp

# Start the Bot Service
CMD ["java", "-jar", "spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar"]

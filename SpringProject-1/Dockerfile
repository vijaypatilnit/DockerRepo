# Use a lightweight JRE as the base image
FROM openjdk:17-jdk-alpine

# Set the working directory
WORKDIR /app

# Copy the JAR file into the container
COPY SpringProject-2-0.0.1-SNAPSHOT.jar app.jar

RUN sh -c 'touch SpringProject-1.0.0.1-SNAPSHOT.jar'

# Expose the port your application will run on
EXPOSE 8080

# Command to run the JAR file
ENTRYPOINT ["java", "-jar", "app.jar"]



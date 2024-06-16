# Use OpenJDK to run the application
FROM openjdk:17-slim

# Set the working directory in the container
WORKDIR /app

# Copy the pre-built jar file from your build environment into the image
COPY build/libs/*.jar app.jar

# Define the command to run your app using Java -jar
ENTRYPOINT ["java", "-jar", "app.jar"]
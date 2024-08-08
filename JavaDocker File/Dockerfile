# Use the official OpenJDK base image
FROM openjdk:17

# Set the working directory inside the container
WORKDIR /app

# Copy the Java source code into the container
COPY HelloWorldServer.java .

# Compile the Java program
RUN javac HelloWorldServer.java

# Expose port 8080
EXPOSE 8080

# Command to run the compiled Java program
CMD ["java", "HelloWorldServer"]

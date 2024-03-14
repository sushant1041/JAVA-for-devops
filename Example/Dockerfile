FROM openjdk:11-jdk-slim

# Set the working directory in the image
WORKDIR /app

# Copy the files from the host file system to the image file system
COPY . /app

# Install the necessary packages
RUN javac HelloWorld.java

# Run a command to start the application
CMD ["java", "HelloWorld"]

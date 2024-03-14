FROM openjdk:11-jdk-slim

# Set the working directory in the image
WORKDIR /app

# Copy the files from the host file system to the image file system
COPY HelloWorld.java

# Install the necessary packages
RUN apt-get update && apt-get install openjdk-11-jdk

RUN javac HelloWorld.java

# Run a command to start the application
CMD ["java", "HelloWorld"]

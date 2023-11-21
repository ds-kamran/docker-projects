# Get the base image

FROM openjdk:11

#Create a working directory to keep all files

WORKDIR /app

#Code copy to the image for running in computer

COPY hello.java /app

#Compile the code
RUN javac hello.java

# APP is now ready to run

#Actually passing the run commands as arguments
CMD ["java","hello"]

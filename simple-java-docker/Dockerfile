#pull a base image which gives all the required tools and libraries
FROM openjdk:17-jdk-alpine


#create a folder where the app code will be stored
WORKDIR /app

#copy src code to from the hostmachine to ur container
COPY src/Main.java /app/Main.java


#compile the code
RUN javac Main.java



# Run the application
# CMD can be rhe over written

CMD ["java","Main"]


#ENTRYPOINT - cannot be overwritten

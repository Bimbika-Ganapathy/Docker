#pull a base img which gives all req tools n libbraries 

FROM openjdk:17-jdk-alpine
#createa folder where all app code will be stored
WORKDIR /app
# copy the source code from ur host machine to ur container
COPY src/Main.java /app/Main.java
#compile the app code
RUN javac Main.java
#all the previous lines builds img

#below line injects the command
#run the app, 
#can be overriden by run but entry point cant be overriden
CMD ["java","Main"]


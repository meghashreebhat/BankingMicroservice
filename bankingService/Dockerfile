FROM openjdk:alpine
RUN mkdir -p /mydata
ADD target/bankingService-1.0-SNAPSHOT.jar /mydata/bankingService-1.0-SNAPSHOT.jar
CMD java -cp /mydata/bankingService-1.0-SNAPSHOT.jar com.bank.App

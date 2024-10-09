FROM openjdk:17-jdk
WORKDIR /Gateway-dir
COPY /target/Reservation_Gateway-0.0.1-SNAPSHOT.jar /Gateway-dir/geteway.jar
EXPOSE 8000
CMD ["java","-jar","geteway.jar"]
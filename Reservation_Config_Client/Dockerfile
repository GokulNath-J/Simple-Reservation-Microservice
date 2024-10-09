FROM openjdk:17-jdk
WORKDIR /Config-Client-dir
COPY /target/Reservation_Config_Client-0.0.1-SNAPSHOT.jar /Config-Client-dir/reservation-config-client.jar
EXPOSE 8888
CMD ["java","-jar","reservation-config-client.jar"]
FROM openjdk:17-jdk
WORKDIR /Eureka-Server-dir
COPY /target/Reservation_Eureka_Server-0.0.1-SNAPSHOT.jar /Eureka-Server-dir/eureka-server.jar
EXPOSE 8761
CMD ["java","-jar","eureka-server.jar"]
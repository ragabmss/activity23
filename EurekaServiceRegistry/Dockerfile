FROM openjdk:11
EXPOSE 8761
ADD target/eureka-service-registry.jar eureka-service-registry.jar
ENTRYPOINT ["java","-jar","/eureka-service-registry.jar"]
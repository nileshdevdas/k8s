FROM  java
ADD  service1-1.0.jar service1-1.0.jar
EXPOSE 8761
ENV eurekaHost  registry 
ENV eurekaPort  8761

ENTRYPOINT java -jar /service1-1.0.jar

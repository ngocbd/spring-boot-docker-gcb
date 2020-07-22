# spring-boot-docker-gcb
Demo project for Spring Boot Docker Google Cloud Build

Clone this repository

mvn clean package


docker build -t habogay/spring-boot-docker-gcb .

docker run -p 8080:8080 habogay/spring-boot-docker-gcb

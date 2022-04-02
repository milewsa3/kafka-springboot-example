
# Kafka Spring Boot Example

This project is an example usage of **Kafka** library integrated
in **Spring Boot** app. 


## How to run
Follow the instructions below to build and execute the project in a simple and easy way, 
but feel free to run the way you want. 😎
### What you need to have installed
* Java 17 💖
* Maven
* Docker

### Build and run 

1. Run **Kafka** server using **Docker**. 
```
docker-compose up -d
```
2. Run **Spring Boot** app 
```
mvn clean spring-boot:run
```
Then you should see messages going through the console:
```
...
Listener received: Message[message=Hi: 696, created=2022-04-02T12:37:48.703675100] ❤️
Listener received: Message[message=Hi: 697, created=2022-04-02T12:37:48.703675100] ❤️
Listener received: Message[message=Hi: 698, created=2022-04-02T12:37:48.703675100] ❤️
...
```
## Spring Boot WebSocket Chat Appplication

## Requirements

1. Java - 1.8.x

2. Maven - 3.x.x

## Steps to Setup

**1. Clone the application**

```bash
git clone https://github.com/RamaKommineni/spring-boot-websocket-chat-demo.git
```

**2. Build and run the app using maven**

```bash
cd spring-boot-websocket-chat-demo
mvn package
java -jar target/websocket-demo-0.0.1-SNAPSHOT.jar
```

Alternatively, you can run the app directly without packaging it like so -

```bash
mvn spring-boot:run
```
<<<<<<< HEAD

## Learn More

You can find the tutorial for this application on my blog -

## To Build docker image please run
```bash
sudo docker build -t spring-boot-websocket-chat-demo .
sudo docker images
sudo docker run -p 5000:8080 spring-boot-websocket-chat-demo
```

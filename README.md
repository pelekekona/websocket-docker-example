# Real Time Chat 🍪

A real time chat built with React, Express, Docker/Docker Compose, and love.

This uses Docker to build/run the client and api on two seperate images. Clients are paired in chat together sequentially; i.e. client 0 and client 1, client 2 and client 3, and so forth. 

## UI
<p align="center">
  <img  src='images/1.png' height='480' width='300'>
  <img src='images/2.png' height='480' width='300'>
</p>

## Goals of this repo
- [x] Learn Docker
- [x] Practice using websockets with a real time chat
- [x] Implement postgresql

## Installation/Running
Clone the repo:  
```bash
git clone https://github.com/Chrischuck/websocket-docker-example.git
```
Enter the directory:  
```bash
cd websocket-docker-example
```

Build Docker images:  
```bash
docker-compose build
```

Run Docker images:  
```bash
docker-compose up
```
Now open up your favorite web browser and navigate to `localhost:5008'. Each new window will be a new client.
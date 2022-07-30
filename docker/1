# Docker

## Projects

- Hello World - JavaScript

## Steps

- Step 01 - Docker and DevOps - Installation and Introduction
- Step 02 - Your First Docker Usecase
- Step 03 - Important Docker Concepts - Registry, Repository, Tag, Image and Container
- Step 04 - Playing with Docker Images - JavaScript
- Step 05 - Playing with Docker - Detached Mode and Logs
- Step 06 - Playing with Docker Images and Containers
- Step 07 - Understanding Docker Architecture - Docker Client, Docker Engine
- Step 08 - Understanding Docker Popularity - My 3 Top Reasons
- Step 09 - Learning Docker Images - Commands
- Step 10 - Learning Docker Containers - Commands
- Step 11 - Learning Docker Commands - system and stats
- Step 12 - Building and Pushing Docker Image for Node JavaScript App
- Step 13 - Building Efficient Docker Images - Improving Layer Caching
- Step 14 - Understanding ENTRYPOINT vs CMD

## Registry and Repositories

- https://hub.docker.com/u/topkuber
- https://hub.docker.com/r/topkuber/hello-world-nodejs

# Commands

```
docker --version
docker run -p 5000:5000 topkuber/hello-world-nodejs:0.0.1.RELEASE
docker logs 04e52ff9270f5810eefe1f77222852dc1461c22440d4ecd6228b5c38f09d838e
docker logs c2ba
docker images
docker container ls
docker container ls -a
docker container stop f708b7ee1a8b
docker run -d -p 5001:8080 topkuber/hello-world-rest-api:0.0.1.RELEASE
docker pull mysql
docker search mysql
docker image history topkuber/hello-world-java:0.0.1.RELEASE
docker image history 100229ba687e
docker image inspect 100229ba687e
docker image remove mysql
docker image remove topkuber/hello-world-java:0.0.1.RELEASE
docker container rm 3e657ae9bd16
docker container ls -a
docker container pause 832
docker container unpause 832
docker container stop 832
docker container inspect ff521fa58db3
docker container prune
docker system
docker system df
docker system info
docker system prune -a
docker top 9009722eac4d
docker stats 9009722eac4d
docker container run -p 5000:5000 -d -m 512m topkuber/hello-world-java:0.0.1.RELEASE
docker container run -p 5000:5000 -d -m 512m --cpu-quota=50000  topkuber/hello-world-java:0.0.1.RELEASE
docker system events

cd ../hello-world-nodejs/
docker build -t topkuber/hello-world-nodejs:0.0.2.RELEASE .
docker container run -d -p 5000:5000 topkuber/hello-world-nodejs:0.0.2.RELEASE
docker push topkuber/hello-world-nodejs:0.0.2.RELEASE

docker run -d -p 5001:5000 topkuber/hello-world-nodejs:0.0.3.RELEASE ping google.com

```

docker build -t topkuber/hello-world-nodejs:0.0.1.RELEASE .
docker push topkuber/hello-world-nodejs:0.0.1.RELEASE

```

```

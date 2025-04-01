
# Developer Use Guide

## Run app with Docker
```bash
 docker build -t my-app:0.0.1 -f devops/Dockerfile .
 docker run -d --name app1 -p 8080:5000 my-app:0.0.1
 docker exec -it app1 bash
 docker stop app1
 docker start app1
 docker logs app1

```
## Run db && app with Docker-compose
```bash
 docker-compose up -d
 curl  localhost:5001
```
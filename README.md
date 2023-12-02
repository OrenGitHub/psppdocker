# psppdocker
build pspp from source on docker

## build docker
```
docker build --tag host --file Dockerfile .
docker run -d -t --name pspp host
docker exec -it pspp bash 
```

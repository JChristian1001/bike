# Bike Back-end

Code based in course https://www.pluralsight.com/courses/building-first-app-with-spring-boot-angularjs

### Docker
To create a docker image (check DockerFile) use the following commands 
```sh
docker image build -t bike-back:1.0 .
docker image ls
```
``bike-back:1.0`` is an optional name

You can run the image with the next command

```sh
docker run --name bike-container -p 8087:8089 bike-back:1.0
docker ps
```
# Deploy in different environments...

You can use the docker-compose.yml to run the docker image locate in directly : https://hub.docker.com/r/christianr10/bike-back-v1

```sh
docker-compose -f docker-compose.yml  up
```


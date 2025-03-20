FROM mongo:5
COPY *.js /docker-entrypoint-initdb.d/


#mongodb]# docker run -d --name mongodb  docker-momgodb:v1
#docker logs aab0b85ce151
#docker exec -it aab0b85ce151 /bin/bash
#docker volume create mongodb
#docker volume inspect mongodb
#docker volume ls
#docker run -d --name mongodb --mount source=mongodb,target=/data/db --network=roboshop docker-momgodb:v1
#docker network create -d bridge roboshop  --> to create network
#docker network ls
#docker run -d --name mongodb --network=roboshop mongodb:v1
#docker inspect aab0b85ce151 | grep -i volume
#docker inspect aab0b85ce151 | grep -i network

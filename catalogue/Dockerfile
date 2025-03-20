FROM node:18.19.1-alpine3.19
EXPOSE 8080
RUN addgroup -S roboshop && adduser -S roboshop -G roboshop
WORKDIR /opt/server
ENV MONGO=true
RUN chown roboshop:roboshop /opt/server
USER roboshop
COPY package.json /opt/server/
COPY server.js /opt/server/
RUN npm install
CMD ["node", "server.js"]


#docker run -d --name catalogue --network=roboshop catalogue:v1
#mongodb]# docker run -d --name catalogue  docker-catalogue:v1
#docker logs aab0b85ce151
#docker exec -it aab0b85ce151 /bin/bash
#if you not created docker network it will not connected to mongodb it will throw error
#"ERROR {\"name\":\"MongoNetworkError\"}","v":1}
#docker network create -d bridge roboshop  --> to create network
#docker network ls
#docker stop 8f5388b2164b
#docker rm 8f5388b2164b
#mongodb]# docker run -d --name catalogue  docker-catalogue:v1
#docker logs aab0b85ce151
#docker ps 
#docker logs aab0b85ce151

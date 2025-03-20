FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf
COPY roboshop.conf /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/

#docker build -t web:v1 .
#docker run -d -p 80:80 --name web --network=roboshop web:v1
#docker logs 05c2dfd123b7


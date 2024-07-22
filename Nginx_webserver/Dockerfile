FROM ubuntu:latest

RUN apt-get update && apt-get -y upgrade 
RUN apt-get install -y nginx
 
EXPOSE 8080

CMD ["nginx", "-g", "daemon off;"]


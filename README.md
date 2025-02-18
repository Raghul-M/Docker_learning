# Docker_leraning

Kernel - Convert the request from software to hardware
popular containerengines : containerd , docker , crio 
FYI :

Docker engine doesnt used in production environment only in development .
For production environment we use containerd

kind - Kubernetes in docker

Easy way to install docker :

$ curl https://get.docker.com/ | bash
docker 0 is the bridge with connects the container to the internet

docker0 -> et0 -> Internet

The docker 'run --rm' command is used to automatically remove a Docker container once it has finished executing.

Docker container are stateless so we use volumes to store the data

Docker socket if we connect the socket with container socket the container can access the docker deamon  /var/run/docker.sock: /var/run/docker.sock using none because we are not needed any network 

for mongodb we use mongosh as shell to interact

portainer.io 

Docker init it wll create a docker file and necessary files 

build args ARGS , LABEL in Dockerfile 

dangling images

IN Dockerfile EXpose doesn't actually expose the port its an documentation for developer or user to use the port of the container

Distroless Image

The size of the image increases as number of step increases .keep t mnimal like alpine 
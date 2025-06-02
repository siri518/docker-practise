# docker-practise

# docker remove containers
docker rm $(docker ps -a -q)

# to create the image need to run
docker node-project:1.0

# to create the container
docker run node-project:1.0

# to run in interactive mode
docker run -it node-project:1.0 bash

# to push the image to docker hub
docker tag node-project:1.0 dockersiri194/node-project:latest

# creating volumes
docker volume create testvol1
docker volume ls
docker volume inspect <volume-id>
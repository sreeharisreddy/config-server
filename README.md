# config-server

#Building Docker File from the Jarr
docker build -f Dockerfile -t docker-service-registry .

#Running the image
docker run -p 8085:8085 docker-service-registry

#List the docker containers
docker container --list

#Stop the conatines 

docker container stop <container-name>

 

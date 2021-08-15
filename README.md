# config-server

#Building Docker File from the Jarr
docker build -f Dockerfile -t docker-service-registry .

#Running the image
docker run -p 8085:8085 docker-service-registry

#running with background (-d)
docker run -d -p 8761:8761 docker-service-registry

#List the docker containers currently running
docker container ls

#Listing Docker images available in hub
docker imagaes ls

#Stop the conatines 
docker container stop <container-name>

 

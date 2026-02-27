# Useful Information

## Docker Commands
```bash
docker pull IMAGE # Downloads an image from DockerHub
docker run IMAGE # Runs a downloaded image
docker ps # Lists active containers, use the -a flag to list all the containers
docker start CONTAINER # Starts a previously used container
docker stop CONTAINER # Stops a specified container if it is active
docker rm CONTAINER # Removes a specified container if it is not active
docker images # Lists all currently downloaded images
docker rmi IMAGE # Removes a specified image
docker volume create VOLUME # Creates a volume with a specified name
docker volume rm VOLUME # Removes a specified volume if it is not mapped to anything
docker volume LIST # Lists all volumes
docker network ls # Lists all current networks
docker network create NETWORK # Creates a network with a specified name
docker network inspect NETWORK # Shows various information about a specified network in a JSON format
docker network connect/disconnect NETWORK CONTAINER # Connects/Disconnects a specified network to/from a specified container
docker network rm NETWORK # Removes a specified network if it is not being used
```

# Important files

# Docker commands
## Containers
Usage | Command
----- | -------
Create a container | `docker run --name <yjenkins> myjenins:v1`
List all containers running and stopped | `docker ps -a`
List only running containers | `docker ps`
Connect to a running container | `docker exec -it <cont_id> /bin/bash`

## Build images
Usage | Command
----- | -------
Build Image | `docker build -t <myjenins:v1> -f <dockerfile> .`
Push an image | `docker push myorg/img`

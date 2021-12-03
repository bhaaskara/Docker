# Docker RunBook
## Upload an image to docker hub
1. Create an Image
   > Note: Image name should starts with dockerid/  
2. Login to docker hub from terminal  
   `docker login`
3. Push the image  
   `docker push <img_name>`  
# Docker Swarm
## Enable docker swarm
`docker swarm --init --advertise-addr <Private ip of EC2>`

> Note down the docker swarm join token to add workers to maanager.

Check list of nodes in the swarm  
`docker node ls`

# Enable docker swarm
`docker swarm --init --advertise-addr <Private ip of EC2>`

> Note down the docker swarm join token to add workers to maanager.

Check list of nodes in the swarm  
`docker node ls`

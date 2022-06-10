# First

## Create agent-network
$ docker network create -d overlay agent_network

## Create proxy (if you need)
$ docker network create -d overlay proxy

# And Finally
$ docker stack deploy portainer -c portainer.yml

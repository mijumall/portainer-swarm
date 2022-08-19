# portainer-swarm
Example usage of Portainer with Docker Swarm cluster. 

This example assumes the following situation:
* Working directory: `/home/normal/space`
* /space has an empty directory called `/data`
* Swarm cluster with "Active" manager nodes. Portainer agents run on every node including managers. 
* Only a node with label's name = portainer-server runs the server.
* WebUI is accessed from localhost:9443 of which port is forwarded by SSH (add `LocalForward 9443 localhost:9443` in ssh config)


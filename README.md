# portainer-easy-setup

A simple docker-compose.yaml to start a minimal and persistent single host portainer. 

It starts `portainer-ce`, makes the docker.sock available while persisting it's data locally to `/data/portainer`. It expects an external network called `proxy-tier` to exist for further usage with [jwilder/nginx-proxy](https://hub.docker.com/r/jwilder/nginx-proxy). 

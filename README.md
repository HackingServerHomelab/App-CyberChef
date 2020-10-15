# App-CyberChef


## Running the Containers

1. Run `./Config/gen_certs.sh` to generate the SSL certificates (alternatively,
   add custom certs to the nginx folder)
3. Update the `server_name` in [nginx.conf](./Config/nginx.conf)
3. Run `docker-compose -f ./Docker/docker-compose.yml up -d`

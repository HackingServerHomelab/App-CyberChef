# App-CyberChef

## First Time Prerequisites

1. Run [Traefik](https://github.com/HackingServerHomelab/App-Traefik)

## Running the Containers

1. Update the following line in [docker-compose.yml](./Docker/docker-compose.yml)
    * ``- "traefik.http.routers.cyberchef.rule=Host(`localhost`)" # Domain Name``
2. Run `docker-compose -f ./Docker/docker-compose.yml up -d`

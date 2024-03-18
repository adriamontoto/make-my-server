# Make my server! 🐣💻
This repository contains the configuration/deployment files for my home server, basically using docker compose.


## Services Included
- **Traefik**: A reverse proxy and load balancer for HTTP, TCP and UDP based connections.
- **Homarr**: A dashboard for having all your services in one place.
- **Portainer**: A lightweight management tool that allows you to easily manage your Docker containers.
- **Uptimekuma**: A self-hosted monitoring and alerting service.
- **Pihole**: A DNS server that can block ads for all devices on your network.
- **MariaDB**: A relational database server.
- **Minecraft (vanilla)**: A vanilla minecraft server.
- **Minecraft (mods)**: A minecraft server with mods (*mods not included* 😝).


## Deployment
1. Create a fork of this repository

2. Clone your forked repository to your server
```bash
git clone https://github.com/<your_username>/make-my-server.git
```

3. Copy the `.env.example` file to `.env` and fill in the environment variables
```bash
cp .env.example .env
```

4. Deploy the services using docker-compose in the root folder
```bash
docker-compose up -d
```

5. Enjoy your new server! 😀


## Tear Down
To tear down the services, run the following command in the root folder
```bash
docker-compose down
```

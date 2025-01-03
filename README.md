<a name="readme-top"></a>

# 🐣💻 Make my server!

This repository provides the configuration ⚒️ and deployment files for setting up a home server using compose 🐳. Enjoy an organized environment right from your home 🏠!
<br><br>

## Table of Contents

- [✨ Features](#features)
- [🚀 Deployment Steps](#deployment)
- [🔄 Tear Down](#tear-down)
- [🔑 License](#license)

<p align="right">
    <a href="#readme-top">🔼 Back to top</a>
</p><br><br>

<a name="features"></a>

## ✨ Features

- **Nginx Proxy Manager:** Reverse proxy and load balancing with TLS support.
- **Homarr:** A user-friendly dashboard to access all your services in one place.
- **Portainer:** Lightweight container management tool.
- **Uptimekuma:** Self-hosted monitoring and alerting for your services.
- **PostgreSQL:** A powerful, open-source relational database server.
- **Minecraft Server (vanilla):** A vanilla Minecraft server.
- **Minecraft Server (mods):** A Minecraft server with mod support.

<p align="right">
    <a href="#readme-top">🔼 Back to top</a>
</p><br><br>

<a name="deployment"></a>

## 🚀 Deployment Steps

**1. Fork this repository**
<br><br>

**2. Clone your fork** <br>
Clone the repository to your server:

```bash
# Via SSH
git clone git@github.com:<your_username>/make-my-server.git
```

<br>

**3. Configure environment variables** <br>
Copy the example environment file and customize it:

```bash
cp .env.example .env
```

<br>

**4. Deploy services** <br>
Start your server with docker compose using the compose.yaml file in the root directory:

```bash
docker compose up --detach
```

<br>

**5. Enjoy your new server 🎉**

<p align="right">
    <a href="#readme-top">🔼 Back to top</a>
</p><br><br>

<a name="tear-down"></a>

## 🔄 Tear Down

To stop and remove all running services, use:

```bash
docker compose down
```

<p align="right">
    <a href="#readme-top">🔼 Back to top</a>
</p><br><br>

<a name="license"></a>

## 🔑 License

This project is licensed under the terms of the [`MIT license`](https://github.com/adriamontoto/criteria-pattern/blob/master/LICENSE.md).

<p align="right">
    <a href="#readme-top">🔼 Back to top</a>
</p>

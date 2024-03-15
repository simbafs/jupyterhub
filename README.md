This is my configuration to install jupyterhub, This config has

-   DockerSpawner
-   custom jupyter image
-   native authenticator
-   personal and share data directories

# Quick Start

```
$ docker build image/astro-notebook -t astro-notebook
$ echo "CONFIGPROXY_AUTH_TOKEN=$(openssl rand -hex 32)" >> .env
$ docker-compose up
```

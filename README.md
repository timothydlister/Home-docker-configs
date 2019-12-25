# Docker Compose config for Funkwhale behind Traefik Load Balancer
Feel free to use this docker-compose file.

This will setup Traefik (a docker container load balancer) as well as Funkwhale.

It will pull from your Funkwhale .env file as indicated in the config.

At boot up, Traefik will attempt to setup HTTPS/TLS via Let's Encrypt so if that's what you want, make sure HTTP and HTTPS is open to Traefik.

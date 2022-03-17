# reso-nginx-letsencrypt-docker
Container that uses Nginx for its server and can auto-renew SSL certs through Let's Encrypt. 


# Initialization

This script must run on a machine that hosts the domain you want to secure.

In order to deploy this, you need to run the command: \
`sudo ./init-letsencrypt.sh {DOMAIN_TO_SECURE}`

Then you can `docker-compose up` to run the docker of the nginx proxy with let's encrypt.
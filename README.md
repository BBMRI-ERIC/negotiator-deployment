# Negotiator deployment
## Deploying v3 to production
- `git clone https://github.com/BBMRI-ERIC/negotiator-deployment.git`
- `cd negotiator-deployment`
- `cp env.template .env`
- fill out environment variables in .env
- Copy domain certificates onto the machine and specify their path in .env and names in traefik.yaml as well
## Develop build
- `sudo docker-compose up -d -f develop.docker-compose.yml`

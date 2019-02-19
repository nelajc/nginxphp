# nginxphp
running wordpress on nginx server with mysql percona


Clone github repo:
git clone https://github.com/nelajc/nginxphp.git

You should have docker-compose installed on your machine. If none, follow this instruction: https://docs.docker.com/compose/install/#install-compose

to check if docker-compose was properly installed:
docker-compose --version

after confirming, run:
docker-compose up -d

check if three containers are running:
docker ps

if all containers are running, wordpress on nginx server should now running at http://server-ip-address

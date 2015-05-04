# build
docker build -t 0xff/aspmysql .
# run
docker run -d 0xff/aspmysql
# inspect
docker exec -i -t <container name> bash

# remove all docker containers
docker rm -f $(docker ps -a -q)
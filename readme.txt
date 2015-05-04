# build
docker build -t ff/aspvisor .
# run
docker run -d ff/aspvisor
# inspect
docker exec -i -t <container name> bash

# remove all docker containers
docker rm -f $(docker ps -a -q)
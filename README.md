How to use this repo:

build the docker image -> docker build -t <name> .

run the image -> docker run -p <your port>:8080 -d <name>

How to get container id:

docker ps


How to get logs from docker:

docker logs <container id> <- just need the first 3 digits of the id

How to get inside of the docker container:

docker exec -it <container id> /bin/bash



Test Node server:

curl -i localhost:<your port>

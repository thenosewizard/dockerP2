# Running the docker container 

## Add your username to a docker group
1. sudo groupadd docker
2. sudo usermod -aG docker $USER
3. Log off and log back in

## Build the container
1. docker build --tag=review_processing .

## Run it and expose it to port 80
1. docker run -d -p 80:80 review_processing

## Delete the containers 
1. docker ps -a 
2. docker rm "ID"

## Delete images
1. docker images ls
2. docker rmi "ID"




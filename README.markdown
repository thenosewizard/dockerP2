# Running the docker container 

## Build the container
1. sudo docker build --tag=review_processing .

## Run it and expose it to port 8000
2. sudo docker run -d -p 8000:8000 review_processing

## Delete the containers 
1. docker ps -a 
2. docker rm "ID"

## Delete images
docker rmi "ID"




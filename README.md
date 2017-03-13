# Docker container for dotnetcore and websocketd

Example container in MyApp folder

## Build Container

`docker-compose -f ./docker-compose.yml build`

## Start Container

`docker-compose -f ./docker-compose.yml up -d`

## Stop

`docker-compose -f ./docker-compose.yml stop`

## Remove

`docker-compose -f ./docker-compose.yml rm -f`

## Connect to bash

`docker exec -it MyApp bash`

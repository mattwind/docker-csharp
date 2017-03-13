# Docker csharp

This container runs dotnetcore application over websocketd server.

![demo](https://github.com/mattwind/docker-csharp/blob/master/demo.png "demo")

## Build Container

`docker-compose -f ./docker-compose.yml build`

## Start Container

`docker-compose -f ./docker-compose.yml up -d`

## csharp project files

The demo application counts to 10

`./MyApp/app/program/`

![vscode](https://github.com/mattwind/docker-csharp/blob/master/vscode.png "vscode")

## Web files

`./MyApp/app/html/`

![html](https://github.com/mattwind/docker-csharp/blob/master/html.png "html")

## Stop Container

`docker-compose -f ./docker-compose.yml stop`

## Remove Container

`docker-compose -f ./docker-compose.yml rm -f`

### Install Docker and Docker Compose

View [INSTALL.md] (https://github.com/mattwind/docker-csharp/blob/master/INSTALL.md)

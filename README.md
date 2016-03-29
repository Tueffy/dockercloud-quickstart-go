# quickstart-go

[![Deploy to Docker Cloud](https://files.cloud.docker.com/images/deploy-to-dockercloud.svg)](https://cloud.docker.com/stack/deploy/)

A simple Golang web app (using Martini) which can easily be deployed to Docker Cloud.

## Running locally

Build and run using Docker Compose:

	$ git clone https://github.com/Tueffy/dockercloud-quickstart-go
	$ cd dockercloud-quickstart-go
	$ docker-compose up

## Deploying to Docker Cloud

[Install the Docker Cloud CLI](https://docs.docker.com/docker-cloud/tutorials/installing-cli/)

	$ docker login
	$ docker-cloud stack up

Or just press the button above!

Have fun
Christian

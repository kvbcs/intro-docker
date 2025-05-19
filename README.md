# intro-docker

This project is an introduction exercise for learning docker, Dockerfile and docker-compose.yml
## Instructions

### hello-node

To start running the container, open a terminal and type the following commands : 

#### docker build -t hello-node-app .
#### docker run -d -p 3000:3000 --name my-node-container hello-node-app

Then open your browser on localhost:3000 to see the message.

### hello-node-postgres

To start running the container, open a terminal and type the following commands :

#### docker-compose up --build

Then open your browser on localhost:3000 to see the message.

### hello-node-postgres-env

To start running the container, create a .env file with the matching credentials to connect to your PostgreSQL database then open a terminal and type the following commands : 

#### docker-compose up --build

Then open your browser on localhost:12345 to see the message.

## Errors

If your browser doesn't show the corresponding message, you must stop a running container with the following command : 

#### docker stop yourContainerId


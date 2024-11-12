
# Time_count-JavaScript Project

This is a simple JavaScript project that prints the current time to the console every second.

## Technologies Used
- Language: JavaScript (Node.js)
- Container: Docker

## Prerequisites
- Docker installed
- Node.js installed locally (optional for direct execution without Docker)

## Project Files
- *index.js*: Main file of the project that prints the current time to the console every second.
- *Dockerfile*: Docker file for building the Docker image.
- *package.json*: Configuration file for Node.js, specifying dependencies and startup script.

## Create Docker Image

Run the following command in the project directory:
~~~
docker build -t kevineduardo14/timecount .
~~~
## Run the Docker Container
~~~
docker run kevineduardo14/timecount
~~~

## Login the Docker Hub
~~~
docker login
~~~
## Docker Desktop pull in Docker Hub
~~~
docker pull kevineduardo14/timecount
~~~

## Imagen in Docker Hub

https://hub.docker.com/repository/docker/kevineduardo14/timecount/general

# RailWay
We log in and link to GitHub to deploy the repositories.

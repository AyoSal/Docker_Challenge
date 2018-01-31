# Docker_Challenge
Docker Challenge

What is this repository for?
This repository contains the solution to the docker challenge
How do I get set up?
Unzip the docker.zip folder to a suitable folder, preferably home or root You should have the following -docker-compose.yml file appl folder mysql folder
Do note that each folder has its own Dockerfile ( For its individual container) docker-compose.yml can be located at the root directory of the project.
USAGE
Usage ensure docker and docker-compose are available on the machine being used
perform the following commands
docker-compose build -> This command will builds the containers for the application ( from the appl folder)
as well as the mysql database ( from the mysql folder)
docker-compose up -> This command builds, stars and attaches the containers ( application and mysql) for the service
Once the containers are up, run docker ps. docker ps lets you view the running containers. You should see the two containers running ( mysql and application) respectively.

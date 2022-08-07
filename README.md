# docker-compose-samples
Collection of docker-compose samples

In general they are configures to store their data in a subfolder with the same name (ex: plex/plex/*) in case you want to use them in a stack.
Most use a predefined network "dockernet" which can be created with the following command
```
docker network create -d bridge dockernet
```

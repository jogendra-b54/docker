# docker

How to install docker ?

curl -s https://get.docker.com/ | bash


### Commonly used docker commands

# Docker Notes

### Docker is a container Run time 

```
Docker gives us high-level runtime as it uses CONTAINERD as its run-time.
```

### What is a Container ?
```
Container is a package of software that contains all the required elements to run your applicaition in any environment
```

### What is run time ?

```
To run containers, you need to have a run time and among all, DOCKER is highly used
```

### Agenda

    1) Docker Installation
    2) Docker Usages
    3) ECR Docker Registry
    4) Make your docker images

### How to run a container
```
$ docker run containerName    ( this runs containers interactively killing your prompt )
$ docker run -d containerName ( this runs containers in the background by detaching from the terminal )

```

### Common docker commands:
```
$ docker ps                          ( shows you the list of all the running containers on your system )
$ docker ps -a                       ( shows you the list of all the containers including the exited ) 
$ docker pull imageName              ( pulls the docker image from the image repository )
$ docker push imageName              ( pushes the docker image to the image repository )
$ docker stop                        ( To stop the container which is running ) 
$ docker exec -it containerName bash ( To enter in to the container )
```


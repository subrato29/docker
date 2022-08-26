Docker commands:
----------------------------------------------

How to check docker version
- docker --version

How many docker image available
- docker images
- docker image ls

How to pull docker images
- docker pull |IMAGE|
	- e.g. docker pull ubuntu

How many docker 'running' containers available in the system
- docker ps

How many docker 'running' & 'non-running' containers available in the system
- docker ps -a

How to run a docker image
- docker run -it -d |IMAGE|
	- e.g. docker run -it -d ubuntu

How to restart a docker container
- docker restart |CONTAINER-ID|

How to stop docker container
- docker stop |CONTAINER-ID|

How to start a docker container
- docker start |CONTAINER-ID|

How to enter inside a docker container
- docker exec -it |CONTAINER-ID| bash

How to come out from a docker container
- exit

How to remove a docker container
- docker stop |CONTAINER-ID|
- docker rm |CONTAINER-ID|
	- note: You can't remove a running container, first you need to stop the container

How to remove a docker image
- docker rmi |IMAGE-ID|
	- note: 'rmi' for image, 'rm' for container

How to forcefully stop a running container
- docker kill |CONTAINER-ID|

How to inspect(going into the detail) a particular docker container
- docker inspect |CONTAINER-ID|

Dangling image
- presence of an image unassociated with any container in the system

How to remove a dangling image
- docker image prune -a
	- means remove all the images unassociated with any container 

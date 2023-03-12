# What is a Docker image?
```
Images are read-only templates containing instructions for creating a container. A Docker image creates containers to run on the Docker platform.
Think of an image like a blueprint or snapshot of what will be in a container when it runs.

```

# Docker Image vs Containers
```
The key difference between a Docker image Vs a container is that, 
A Docker image is a read-only immutable template that defines how a container will be realized. 
A Docker container is a runtime instance of a Docker image that gets created when the $ docker run command is implemented. 

Docker image templates can exist in isolation but containers can't exist without images.

So docker image is an integral part of containers that differs only because of their objectives which we have already covered.

Docker images can’t be paused or started but a Docker container is a run time instance that can be started or paused. 

You can create many containers from the same image, each with its own unique data and state.

```

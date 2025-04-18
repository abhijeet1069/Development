# Docker

Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your 
applications from your infrastructure so you can deliver software quickly.

## Docker architecture

Docker uses a client-server architecture. The Docker client talks to the Docker daemon, which does the heavy lifting of 
building, running, and distributing your Docker containers. The Docker client and daemon (dockerd) can run on the same 
system, or you can connect a Docker client to a remote Docker daemon. For ex : Docker Compose, a docker client

## Container

A container is a runnable instance of an image.
Containers are isolated processes for each of your app's components.

## Underlying Technology

Docker is written in Go. Docker uses a technology called namespaces to provide the isolated workspace called the 
container. When you run a container, Docker creates a set of namespaces for that container.

These namespaces provide a layer of isolation. Each aspect of a container runs in a separate namespace and its access 
is limited to that namespace.


google kubernetes
cloud run
google compute engine
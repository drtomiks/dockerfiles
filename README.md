### dockerfiles

Dockerfiles for building images that may be of use.

### Getting Started

Prerequisites: [Docker](https://www.docker.com/) must be installed

	git clone https://github.com/drtomiks/dockerfiles.git
	cd dockerfiles/<dir containing Dockerfile for your image>
	docker build -t <desired image name> .
	
	For example: docker build -t centos511-dev .
	
	To see the newly created image and any others you have: docker images

The result is a Docker image you can run to get an interactive bash shell with the following command.

    docker run -it <your image name> bash
	
	For example: docker run -it centos511-dev
	
Read [Docker documentation](https://www.docker.com/) for more information about building and running Docker images.

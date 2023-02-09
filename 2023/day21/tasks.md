## Day 21 Task: Docker Important interview Questions.


## Docker Interview
 Docker is a good topic to ask in DevOps Engineer Interviews, mostly for freshers.
 One must surely try these questions in order to be better in Docker
 
## Questions


### What is the Difference between an Image, Container and Engine?
- Docker Image: A Docker Image is a lightweight, stand-alone, executable package that includes everything needed to run a piece of software, including the code, a runtime, libraries, environment variables, and config files.

- Docker Container: A Docker Container is a running instance of a Docker Image. It is a lightweight and portable executable package of software that includes everything needed to run the application.

- Docker Engine: The Docker Engine is the underlying technology that runs Docker containers. It is a lightweight runtime that manages the containers, images, networks, and volumes. The Docker Engine provides the environment in which Docker containers can run and interact with the host system and with other containers.

### What is the Difference between the Docker command COPY vs ADD?
ans : COPY takes in a source and destination. It only lets you copy in a local or directory from your host (the machine-building the Docker image) into the Docker image itself. ADD does that same but in addition, it also supports 2 other sources. A URL instead of a local file/directory.
### What is the Difference between the Docker command CMD vs RUN?
RUN is an image build step, the state of the container after a RUN command will be committed to the container image. A Dockerfile can have many RUN steps that layer on top of one another to build the image. CMD is the command the container executes by default when you launch the built image
### Why and when to use Docker?
Docker containers share many of their resources with the host system, they require fewer things to be installed in order to run
### Explain the Docker components and how they interact with each other.
a server and a client; and the communication between the two is via REST API.
### Explain the terminology: Docker Compose, Docker File, Docker Image, Docker Container?
- Docker Image: A Docker Image is a lightweight, stand-alone, executable package that includes everything needed to run a piece of software, including the code, a runtime, libraries, environment variables, and config files.

- Docker Container: A Docker Container is a running instance of a Docker Image. It is a lightweight and portable executable package of software that includes everything needed to run the application.

- Docker File: A Docker File is a script that contains instructions for building a Docker Image. It specifies the base image, the application code, the dependencies, the runtime, and how the application should be configured and run.

- Docker Compose: Docker Compose is a tool for defining and running multi-container Docker applications. With Docker Compose, you can define the services that make up your application in a single file, and then spin up your application and all of its services with a single command

### In what real scenarios have you used Docker?
1) Adoption of DevOps. ...
2) App infrastructure isolation. ...
3) Multi-tenancy support. ...
4) Improvement in software testing. ...
5) Smart Disaster Recovery (DR) ...
6) Continuous rapid deployment. ...
7) Creation of microservices architecture

### Docker vs Hypervisor?
Docker and Hypervisors are both technologies for virtualization, but they serve different purposes and have different approaches to virtualization.

- Docker: Docker is a platform for building, shipping, and running applications in containers. A container is a lightweight and portable executable package of software that includes everything needed to run the application. Docker containers share the host operating system's kernel, which makes them lightweight and fast. Containers also provide isolation for the application and its dependencies, which makes it easy to deploy and run the same application on different hosts.

- Hypervisor: A hypervisor is a technology that allows multiple virtual machines to run on a single physical host. Each virtual machine runs its own operating system and has its own isolated environment. Hypervisors provide full virtualization, which means that each virtual machine has its own copy of the operating system, its own virtual hardware, and its own resources. Hypervisors are typically used to run multiple virtual machines on a single physical server, each with its own operating system and applications.

In summary, Docker provides a way to run applications in containers, which share the host operating system's kernel and provide isolation for the application and its dependencies. A hypervisor, on the other hand, provides full virtualization by running multiple virtual machines on a single physical host, each with its own operating system and applications.

### What are the advantages and disadvantages of using docker?
- Advantages of Docker

1) It is light weight because it does not require any resource pre-allocation (RAM). Whenever it needs resources it acquires them from host OS. It is of less cost.
2) Continuous integration efficiency – Docker enables you to build a container image and use that same image across every step of the deployment process.
3) It can run on physical hardware, virtual hardware and on cloud.
4) You can re-use the image.
5) It takes very less time to create.
- Disadvantage of Dockers

1) Docker is not good for application that requires rich GUI
2) It is difficult to manage large amount of containers
3) Docker does not provide cross-platform compatibility means if an application is designed to run in a Docker container on windows, then it cannot run on Linux Docker container
4) Docker is suitable when development OS and testing OS are same
5) It does not provide any solution for data backup and recovery

### What is a Docker namespace?
Docker uses a technology called namespaces to provide the isolated workspace called the container. When you run a container, Docker creates a set of namespaces for that container. These namespaces provide a layer of isolation.

### What is a Docker registry?
A Docker registry is a storage and distribution system for named Docker images. The same image might have multiple different versions, identified by their tags. A Docker registry is organized into Docker repositories , where a repository holds all the versions of a specific image.

### What is an entry point?
ENTRYPOINT is one of the many instructions you can write in a dockerfile. The ENTRYPOINT instruction is used to configure the executables that will always run after the container is initiated.
### How to implement CI/CD in Docker?
[follow this link] (https://docs.docker.com/language/java/configure-ci-cd/)
### Will data on the container be lost when the docker container exits?
Not at all! Any data that your application writes to disk gets preserved in its container until you explicitly delete the container.
### What is a Docker swarm?
A Docker Swarm is a group of either physical or virtual machines that are running the Docker application and that have been configured to join together in a cluster. The activities of the cluster are controlled by a swarm manager, and machines that have joined the cluster are referred to as nodes.
### What are the docker commands for the following:
  - view running containers --> docker ps
  - command to run the container under a specific name --> docker exec -it <container name> <command>
  - command to export a docker --> docker export <container-id> > <file-name>.tar
  - command to import an already existing docker image -->  docker import
  - commands to delete a container --> docker rm <Container_ID> 
  - command to remove all stopped containers, unused networks, build caches, and dangling images? --> docker system prune
 
 ### What are the common docker practices to reduce the size of Docker Image?


These questions will help you in your next DevOps Interview.
*Write a Blog and share it on LinkedIn.*

**Happy Learning :)** 

# Docker
Just having a look at docker!

![image](https://user-images.githubusercontent.com/56073739/129022795-9bfa54d6-049a-42f6-9e25-6a8a3d2b70fa.png)

## Very simple tutorial, but it's just to get me started into using Docker!

## https://www.youtube.com/watch?v=iJeL2tOFfvM

### *And a great resource:* [https://www.youtube.com/watch?v=eGz9DS-aIeY](https://www.youtube.com/watch?v=eGz9DS-aIeY)

---

# Virtualisation

---

On a server, there may be times where having a single operating system is not sufficient for the workload of the server. This can be easily remedied by utilising a hypervisor. A hypervisor allows for the partitioning of different parts of a server into virtual machines. CPU, OS and RAM can be allocated as required to these different VM's.

![image](https://user-images.githubusercontent.com/56073739/129204414-dbeb8e94-d1ea-4459-8d48-a5d7169578b7.png)

---

This process is not used with docker, but the comparison is apt. instead of partitioning the server directly, it adds isolated containers to an operating system.

You can install these or create these isolated containers and when you want to run them on a separate machine it is as easy as using a few straightforward commands:

> Install and image: 
docker pull [image-name]

> Create the container with the installed image:
docker run -d -t —name [container-name] [image-name]

> View all containers:
docker ps

> Run the container:
docker exec -it [container-name] [extra-information]

> Look at the overhead of all running containers:
docker stats

> Kill a running container:
docker stop [container-name]

By using the above commands one can for example run ubuntu on windows without having to install any other dependencies. Set up the requirements to run a project without having to configure your PC to do so and alot more.

![image](https://user-images.githubusercontent.com/56073739/129204473-8807704d-9fec-4b83-92ba-ad50ab92af5b.png)


#What is Docker?
Docker is a software containerization platform, a tool designed 
to make it easier to create, deploy and run applications by using containers
#Installing Docker
Go to the official website, choose your SO and follow the [installation instructions][1]
Don't forget the [Post-installation steps for Linux][2] and follow only the 'Manage Docker as a non-root user' section.
#### Verify your Installation
Open a command-line terminal, and run the follow Docker command to verify the Docker is installed.

```shell
docker --version
```
You should see something lke this:
```shell
Docker version 1.12.5, build 7392c3b
```

####What is a Image?
An image is an inert, immutable, file that's essentially a snapshot of a container. 
Images are created with the build command, and they'll produce a container when started with run.
Images are stored in a Docker registry such as [registry.hub.docker.com][3]. 
 
###What is Docker Registry?
The Registry is a stateless, highly scalable server side application that stores 
and lets you distribute Docker images. The Registry is open-source, under the permissive Apache license.

##Downloading our first image


















[1]: https://docs.docker.com/compose/overview/
[2]: https://docs.docker.com/engine/installation/linux/linux-postinstall/
[3]: https://hub.docker.com/
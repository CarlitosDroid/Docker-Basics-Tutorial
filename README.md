#What is Docker Container?
Docker container allow a developer to package up an application with all of the parts it needs,
such as libraries and other dependencies and ship it all out as one package.
Docker container wrap a piece of software in a complete filesystem that contains everything needed
to run: code runtime, system tools, systems libraries, anything that can be installed on a server.
This guarantees that the software will always run the same, regardless of its environment.

#Running our container
```shell
docker run -d --name my_php_webserver -p 80:80 php:7.0-apache
```
#Exploring our container
```shell
docker exec -it my_php_webserver bash
```


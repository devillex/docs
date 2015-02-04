## Introduction to containers

Software containerization is way to isolate your applications and
services from the rest of the operating system (or other containers).
Not only are containers an isolated unit of work, they're also portable.


### Docker

Wercker uses the [Docker](http://docker.com) container implementation to
not only run your pipelines, but also stores your build artifacts as
containers.

![image](/images/portable-container.png)

Within pipelines containers are used to run your language stack (for
instance python) but also services such as a database.

> Every wercker pipeline runs inside a container

In the next couple of sections we will explain where to get your
containers from, and how to use them.

[Docker Hub &rsaquo;](/learn/containers/02_docker-hub.html "nav next containers")
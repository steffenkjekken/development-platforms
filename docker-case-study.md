
## Introduction

Docker is a set of platform as a service (PaaS) products that allows developers to build, deploy, and run applications in packages called containers. It is an open-source containerization platform that provides a way to package applications and their dependencies into a single unit (container).
Docker is designed to simplify the process of creating and managing containers, making it easier for developers to build and deploy applications across different environments.

With Docker, developers can create a container image that contains all the necessary components needed to run an application. This container image can then be deployed to any environment that supports Docker, such as a local development machine, a test environment, or a production server.


## Brief History

Docker Inc. was founded by Kamel Founadi, Solomon Hykes, and Sebastien Pahl during the Y Combinator (a startup accelerator) Summer 2010 startup incubator group and launched in 2011.
Docker was released as open-source in 2013, at that time Docker was based on Linux containers (LXC), however one year later, with the release of version 0.9, Docker replaced LXC with its own component, «libcontainer», which was written in the Go programming language.
In the years that followed, Docker quickly gained popularity among developers and became a major force in the world of containerization.


## Features & Strengths

**Containerization:** Docker uses containerization technology to create isolated environments for applications. Each container is a standalone unit that includes all the necessary components needed to run the application, such as the application code, runtime, system tools, libraries, and settings. 

**Portability:** Docker containers are designed to be portable, so they can be easily moved between different environments, such as development, testing, and production. This makes it easier for developers to build and deploy applications across different environments.

**Scalability:** Docker’s portability and lightweight nature allows developers to easily scale applications by creating multiple instances of a container and distributing them across different hosts. 

**Orchestration:** Docker provides tools for orchestrating containers,  which can automate the operations tasks around deploying and running containerized applications and services. This includes features like automatic load balancing, service discovery, and container health monitoring.

**Efficiency:** Docker containers are lightweight and use fewer resources than traditional virtual machines, which makes them more efficient and cost-effective. Also, containers take up less memory and reuse components thanks to images.

**Large Community:** Docker has been an open-source project ever since its release. This has contributed to a large community and sustained growth. A Stack Overflow Developer Survey 2022 showed that Docker became a fundamental instrument for being a developer with 69 percent of professional programmers choosing it as their number one tool.

## Weaknesses

**Complexity:** For users who are unfamiliar with containerization technology, Docker might be difficult to set up and administer. As a new user you must become familiar with new terms and concepts, such as images, containers, and registries. There is also no GUI, which means you have to work and perform all actions in the command-line. Some people could find this difficult, particularly those who are unfamiliar with Linux or command-line interfaces.

**Securicty:** The lightweightness of containers has a cost in terms of security. There is a general risk that if a host system is attacked, numerous containers could be compromised at once as containers often share an operating system.

**Licensing:** Docker's open source platform is free to use, but some of its enterprise features require a paid subscription.


## Comparison

In todays containerization space, there are several platforms, the two biggest are Docker and Kubernetes. Kubernetes is developed by Google and open-sourced in 2014. While both tools have similarities, they also have some key differences.

**Differences:**
Docker is primarily focused on containerization, while Kubernetes is designed for container orchestration and management. This means that while Docker can create and manage individual containers, Kubernetes is better suited for managing large-scale container deployments.

Docker provides a platform for creating, distributing, and running containerized applications, while Kubernetes provides a framework for deploying and managing containers across a cluster of hosts.

**Similarities:** 
Both Docker and Kubernetes are open-source tools.
Both tools are designed to facilitate the deployment and management of containerized applications.
Both tools have large and active communities of developers and users, with many resources, tools, and support available.


## Summary

Containerization is becoming increasingly popular in the world of software development and deployment, especially in cloud environments.

Overall, Docker's strengths make it a powerful and popular tool for building, deploying, and managing containerized applications. Its flexibility, efficiency, scalability, and security have made it a key component of modern software development and deployment practices.

### Credits

- Steffen Rolland (@steffenkjekken)

#### References

[en.wikipedia.org/wiki/Docker_(software)](https://en.wikipedia.org/wiki/Docker_(software))
[docs.docker.com](https://docs.docker.com/)
[ibm.com/topics/containerization](https://www.ibm.com/topics/containerization)
[ibm.com/topics/container-orchestration](https://www.ibm.com/topics/container-orchestration)
[atlassian.com/microservices/microservices-architecture/kubernetes-vs-docker](https://www.atlassian.com/microservices/microservices-architecture/kubernetes-vs-docker#:~:text=While%20Docker%20is%20a%20container,CRI%20(Container%20Runtime%20Interface).)

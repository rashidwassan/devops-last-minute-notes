# Docker Concepts and Components

### 1. **`Containers`**
   - Lightweight, portable, and self-sufficient containers that allow you to package an application with all parts it needs.

### 2. **`Images`**
   - Read-only template used to create containers, typically containing a snapshot of a container or base operating system.

### 3. **`Dockerfile`**
   - A text document that contains all the commands a user could call on the command line to assemble an image.

### 4. **`Volumes`**
   - A mechanism for persisting data generated by and used by Docker containers.

### 5. **`Docker Hub`**
   - A cloud-based registry service that allows you to link to code repositories, build your images, and test them.

### 6. **`Docker Compose`**
   - A tool for defining and running multi-container Docker applications.

### 7. **`Docker Engine`**
   - A client-server application with a server side daemon process that hosts images, containers, networks, and volumes.

### 8. **`Docker Swarm`**
   - A Docker-native clustering system that turns a group of Docker engines into a single virtual Docker engine.

### 9. **`Docker Network`**
   - Connects your Docker containers to each other and to the outside world.

### 10. **`Docker Daemon`**
    - The background service running on the host that manages building, running, and distributing Docker containers.

### 11. **`Docker Client`**
    - The command line tool that allows the user to interact with the Docker daemon.

### 12. **`Docker Store`**
    - A marketplace for publishers to distribute and sell their Dockerized content.

### 13. **`Registry`**
    - A service to host and distribute Docker images, Docker Hub and Docker Cloud are public registries.

### 14. **`Docker Machine`**
    - A tool that lets you install Docker Engine on virtual hosts, and manage the hosts.

### 15. **`Docker Service`**
    - A group of containers of the same image run as a distributed application.

### 16. **`Docker Secrets`**
    - A way to securely transmit and store sensitive data, such as passwords and API keys, among Docker containers.

### 17. **`Docker Stack`**
    - A group of interrelated services that share dependencies, and can be orchestrated and scaled together.

### 18. **`Overlay Network`**
    - A network that spans across multiple Docker hosts and is built on top of (overlays) the host-specific networks.

### 19. **`Bridge Network`**
    - The default network type in Docker that bridges through the Docker daemon the containers’ traffic to the outside world.

### 20. **`Host Network`**
    - A network type where the container shares the host’s networking namespace and is not isolated.

### 21. **`None Network`**
    - A network type with no access to external networks, only to other containers on the same host.

### 22. **`Docker Configs`**
    - Used to provide configuration files or other data to services without the need to include this data in the image or expose it as a volume.

### 23. **`BuildKit`**
    - A modern build tool implemented in Docker, providing an improved build performance and scalability.

### 24. **`Docker Trust`**
    - A feature that allows you to sign your images to confirm that they come from a trusted source.

### 25. **`Docker Health Checks`**
    - Instructions in Dockerfiles to tell Docker how to test a container to check that it is still working.

This list encompasses the core components, functionality, and networking concepts essential to understanding and utilizing Docker effectively in various deployment environments.
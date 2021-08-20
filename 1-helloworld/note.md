# Build
```docker build --tag hello-nginx .```
# RUN
```docker run -d -p 8080:80 hello-nginx```

**-d** means "detached". This is the best option when you need to run a background service, like in this case. The container will be executed and then the control will be returned back to the console.

**-p** 8080:80 is used to associate a port inside the container with a port on your host machine. In this case, we are telling that we want to expose the port 80 inside the container to the port 8080 on our machine. NGINX, in fact, like every web server, can be reached using port 80. However, since the container is isolated, we need to forward the port to the host machine in order to reach it.

# see process
```docker ps```

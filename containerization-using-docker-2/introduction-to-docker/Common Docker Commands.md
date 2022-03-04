# Common Docker Commands:

### This command helps you to know the installed version of the docker software on your system:
    $ docker --version

### This command helps you to know the installed version of the docker software on your system:
    $ docker pull <image-name>

### This command helps you in listing all the docker images downloaded on your system. 
    $ docker images

### This command helps in running containers from their image name.
    $ docker run <image-name>

### This command helps in listing all the containers which are running in the system
    $ docker ps

### If there are any stopped containers, they can be seen by adding the -a flag in the previous command. 
    $ docker ps -a

### For stopping a running container, we use the stop command. 
    $ docker stop <container-id>

### This command kills the container by stopping its execution immediately. 
    $ docker kill <container-id>

### For logging into/accessing the container, one can use the exec command.
    $ docker exec <container-id>

### To remove a stopped container from the system, we use the rm command. 
    $ dockerrm<container-id>

### To remove an image from the system, we use the rmi command. 
    $ dockerrmi<image-id>
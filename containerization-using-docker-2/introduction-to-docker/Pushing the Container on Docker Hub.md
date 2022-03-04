# Pushing the Container on Docker Hub

### The first step is to login. It can be done using the following command.
    $ docker login

### For pushing your container on DockerHub, use the following command.
    $ docker push <username>/<container-id>

### You can verify the push on DockerHub. Anyone, who wants to download this container, can simply pass the following command:
    $ docker pull kaustubhmali/apache
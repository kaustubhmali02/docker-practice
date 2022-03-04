### Saving Changes to Docker

# Pull the Docker Container using the command:
    $ docker pull ubuntu

# Run the container using the command:
    $ docker run –it –d ubuntu 

# Access the container using the command:
    $ docker exec –it <container-id> bash

# Install Apache2 on this container by first updating the container and then using the following command.
    $ apt-get update&& apt-get install apache2

# Exit the container and save it using this command. The saved container will be converted into an image with the name specified. 
    $ docker commit <container-id> username>/<container-name>
### Creating an Image using Docker file

# To create a custom docker image we first need to write down all the various commands just like given below in a docker file.
    FROM ubuntu
    RUN apt-get update
    RUN apt-get -y install apache2
    ADD . /var/www/html
    ENTRYPOINT apachectl –D FOREGROUND
    ENV name Devops Learn 

# Then using the docker build command, build the image.
$ docker build . -t username/practiceapp

# This command helps you in listing all the docker images downloaded on your system. 
$ docker images 

# 
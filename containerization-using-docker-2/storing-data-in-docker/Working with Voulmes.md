### WORKING WITH VOLUMES

# This command creates a volume for you.
    $ docker volume create <volume-name>

# This command gives a list of available Volumes.
    $ docker volume ls

# To inspect a volume, we can use this command.
    $ docker inspect <volume-name>

# This command is used to remove a volume. 
    $ docker volume rm <volume-name>

# This command is used to remove all volumes.
    $ docker volume prune

# This command is used to run a container attached to a volume using the ‘--mount’ flag.
    $ docker run -d --name <name-of-container> --mount source = <volume-name>, target = <target-path><image-name>

# This command is used to run a container attached to a volume using the ‘--volume’ flag.
    $ sudo docker run –d --name <name-of-container> --volume <name_of_volume>:<destination_path> <image-name>.

# This command is used to create a read-only volume.
    $ sudo docker run -d --name test --mount source = <name-of-volume>, target = <target-path>, readonly <image-name> 
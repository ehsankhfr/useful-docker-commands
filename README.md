# Description
A list of useful docker commands for all the stages of containerization

## Delete:
  * Delete every Docker containers:
    
    * NOTE: _Must be run first because images are attached to containers_

    ```docker rm -f $(docker ps -a -q)```

  * Delete every Docker image
    
    ```docker rmi -f $(docker images -q)```

# Resources
  * https://davidwalsh.name/docker-remove-all-images-containers

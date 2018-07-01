# Description
A list of useful docker commands for all the stages of containerization

## Delete:
  * Delete every Docker containers (forced):
    
    * NOTE: _Must be run first because images are attached to containers_

    ```docker rm -f $(docker ps -a -q)```

  * Delete every Docker image (forced):
    
    ```docker rmi -f $(docker images -q)```
    
  * Stop all Docker containers:
    ```docker kill $(docker ps -q)```

# Resources
  * https://davidwalsh.name/docker-remove-all-images-containers

# docker-eamples
Docker related examples collated form different resources. 


Basic Docker commands to get going:
  1. docker run <image-name> - To run the container
      Flags:
      -it - Interactive mode
      -d - runs the container in detached mode.
      -p <container port:host port> : Maps the container port to host port
      --name - Gives a name to the container
  2. docker images - List the available images in Docker repository
  3. docker ps - List the running containers
  4. docker stop <container name or container id>
  5. docker rm <container name> - To stop and remove the running container with a single command
  6. docker rmi - remove the image
  
  

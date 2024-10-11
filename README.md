to build the image and start the container automatically using the docker compose file:
1: run ```docker compose up -f docker-compose.yml```
2: to see if the image was build check ```docker image ls``` you should see the folder name + name of the service
example this case : mouad-ubuntu

3: to see if the container is running check ```docker ps``` you should see the container name in the docker compose file
this case being : ubuntu_container
4: to enter in the container use : ``` docker exec -it (container name or container id from when you used docker ps ) bash
example : docker exec -it ubuntu_container bash
this will fork a copy of the running container into a local terminal bash

5: to stop the container use : docker compose down, this will stop all the services started using the compose file

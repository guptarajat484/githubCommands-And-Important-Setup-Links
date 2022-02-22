##### sudo docker build -t node-webapp .                //Build docker 

##### sudo docker images                                //Get all the images of docker which is available in system

##### sudo docker run -d -p 8000:8000 node-webapp       //Run Docker

##### sudo docker ps                                    //Get the details of all running images           

##### sudo docker logs b34ffc44ffaf(CONTAINER ID)       //get logs of all running images

##### sudo docker exec -it b34ffc44ffaf /bin/bash       //not important 

##### sudo docker rm -f <container-name> <container-ID> //To stop docker

##### sudo docker-compose up --build                    //Run docker compose 

##### sudo docker compose down 